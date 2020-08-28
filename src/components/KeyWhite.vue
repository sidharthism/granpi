<template>
  <div class="wrap" @[evtListener[0]]="play" @[evtListener[1]]="end" :keyCode="keyCode" :note="note" > <!-- @mouseout="end" -->
    <div class="label">
      <p class="note" :note="note">{{note | parseNote}}</p>
      <p class="keyCode" :keyCode="keyCode">{{keyCode}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "KeyWhite",
  data(){
    return {
      evtListener: []
    }
  },
  props: {
    note: String,
    keyCode: String
  },
  methods: {
    play: function() {
      this.$emit("play",this.note);
    },
    end: function() {
      this.$emit("end",this.note);
    }
  },
  filters: {
    parseNote: function(note) {
    var b = note.slice(0,note.indexOf(",")); // //C,-2 -> C
    var c = parseInt(note.slice(note.indexOf(",")+1,)) + 4; // -2 + 4 = 2
    return b + c.toString(); // C + 2 -> C2
    }
  },
  beforeMount: function() {
    var isMobile = !!navigator.userAgent.match(/Android|BlackBerry|iPhone|iPad|iPod|Opera Mini|IEMobile/i);
      if (isMobile) {
	      this.evtListener = ["touchstart", "touchend"];
      } else {
        this.evtListener = ["mousedown", "mouseup"];
      }
  }
};
</script>

<style scoped>
.wrap {
  height: 200px;
  width: 40px;
  background-color: #f0efe8;
  box-shadow: 5px 5px 5px #151515, 5px 5px 5px #151515;
  border-radius: 0 0 4px 4px;
  margin-right: 0.05rem;
  cursor: pointer;
  transition: margin 0.05s ease 0s, background-color 0.05s ease 0s, box-shadow 0.05s ease 0s;
}
.wrap:hover {
  background-color: #24b1ca;
}
.label {
  position: relative;
  top: 120px;
}
.label p {
  /* margin-bottom: 15px; */
  margin-top: 17px;
  font-size: 0.91rem;
  font-weight: 400;
}
p.note {
  font-size: 0.82rem;
}
p.keyCode {
  font-weight: 600;
}
</style>