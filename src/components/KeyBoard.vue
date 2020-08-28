<template>
  <div class="piano">
    <div class="keyBoard">
	  <p class="name">GranPi</p>
      <KeyWhite class="keys kw1" note="C,-2" keyCode="~" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb1" note="C#,-2" keyCode="1" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw2" note="D,-2" keyCode="2" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb2" note="D#,-2" keyCode="3" @play="playPiano" @end="pausePiano"/>
      <KeyWhite class="keys kw3" note="E,-2" keyCode="4" @play="playPiano" @end="pausePiano"/>
      <KeyWhite class="keys kw4" note="F,-2" keyCode="5" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb4" note="F#,-2" keyCode="6" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw5" note="G,-2" keyCode="7" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb5" note="G#,-2" keyCode="8" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw6" note="A,-2" keyCode="9" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb6" note="A#,-2" keyCode="0" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw7" note="B,-2" keyCode="-" @play="playPiano" @end="pausePiano"/>
      <KeyWhite class="keys kw8" note="C,-1" keyCode="=" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb8" note="C#,-1" keyCode="Q" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw9" note="D,-1" keyCode="W" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb9" note="D#,-1" keyCode="E" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw10" note="E,-1" keyCode="R" @play="playPiano" @end="pausePiano"/>
      <KeyWhite class="keys kw11" note="F,-1" keyCode="T" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb11" note="F#,-1" keyCode="Y" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw12" note="G,-1" keyCode="U" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb12" note="G#,-1" keyCode="I" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw13" note="A,-1" keyCode="O" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb13" note="A#,-1" keyCode="P" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw14" note="B,-1" keyCode="[" @play="playPiano" @end="pausePiano"/>
      <KeyWhite class="keys kw15" note="C,0" keyCode="]" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb15" note="C#,0" keyCode="A" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw16" note="D,0" keyCode="S" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb16" note="D#,0" keyCode="D" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw17" note="E,0" keyCode="F" @play="playPiano" @end="pausePiano"/>
      <KeyWhite class="keys kw18" note="F,0" keyCode="G" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb18" note="F#,0" keyCode="H" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw19" note="G,0" keyCode="J" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb19" note="G#,0" keyCode="K" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw20" note="A,0" keyCode="L" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb20" note="A#,0" keyCode=";" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw21" note="B,0" keyCode="'" @play="playPiano" @end="pausePiano"/>
	  <KeyWhite class="keys kw22" note="C,1" keyCode="Z" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb22" note="C#,1" keyCode="X" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw23" note="D,1" keyCode="C" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb23" note="D#,1" keyCode="V" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw24" note="E,1" keyCode="B" @play="playPiano" @end="pausePiano"/>
      <KeyWhite class="keys kw25" note="F,1" keyCode="N" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb25" note="F#,1" keyCode="M" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw26" note="G,1" keyCode="," @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb26" note="G#,1" keyCode="." @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw27" note="A,1" keyCode="/" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyBlack class="keys kb kb27" note="A#,1" keyCode="◄" @play="playPiano" @end="pausePiano"/>
      <!-- -->
      <KeyWhite class="keys kw28" note="B,1" keyCode="►" @play="playPiano" @end="pausePiano"/>
    </div>
  </div>
</template>
<script>
import KeyWhite from "./KeyWhite";
import KeyBlack from "./KeyBlack";

const keyNotes = {
  /* ~ */
  192: "C,-2",

  /* 1 */
  49: "C#,-2",

  /* 2 */
  50: "D,-2",

  /* 3 */
  51: "D#,-2",

  /* 4 */
  52: "E,-2",

  /* 5 */
  53: "F,-2",

  /* 6 */
  54: "F#,-2",

  /* 7 */
  55: "G,-2",

  /* 8 */
  56: "G#,-2",

  /* 9 */
  57: "A,-2",

  /* 0 */
  48: "A#,-2",

  /* - */
  189: "B,-2",

  /* = */
  187: "C,-1",

  /* Q */
  81: "C#,-1",

  /* W */
  87: "D,-1",

  /* E */
  69: "D#,-1",

  /* R */
  82: "E,-1",

  /* T */
  84: "F,-1",

  /* Y */
  89: "F#,-1",

  /* U */
  85: "G,-1",

  /* I */
  73: "G#,-1",

  /* O */
  79: "A,-1",

  /* P */
  80: "A#,-1",

  /* [ */
  219: "B,-1",

  /* ] */
  221: "C,0",

  /* A */
  65: "C#,0",

  /* S */
  83: "D,0",

  /* D */
  68: "D#,0",

  /* F */
  70: "E,0",

  /* G */
  71: "F,0",

  /* H */
  72: "F#,0",

  /* J */
  74: "G,0",

  /* K */
  75: "G#,0",

  /* L */
  76: "A,0",

  /* ; */
  186: "A#,0",

  /* " */
  222: "B,0",

  /* Z */
  90: "C,1",

  /* X */
  88: "C#,1",

  /* C */
  67: "D,1",

  /* V */
  86: "D#,1",

  /* B */
  66: "E,1",

  /* N */
  78: "F,1",

  /* M */
  77: "F#,1",

  /* , */
  188: "G,1",

  /* . */
  190: "G#,1",

  /* / */
  191: "A,1",

  /* <- */
  37: "A#,1",

  /* -> */
  39: "B,1"
};

//audioSynth.js start

var Synth, AudioSynth, AudioSynthInstrument;
!function(){

	var URL = window.URL || window.webkitURL;
	var Blob = window.Blob;

	if(!URL || !Blob) {
		throw new Error('This browser does not support AudioSynth');
	}

	var _encapsulated = false;
	var AudioSynthInstance = null;
	var pack = function(c,arg){ return [new Uint8Array([arg, arg >> 8]), new Uint8Array([arg, arg >> 8, arg >> 16, arg >> 24])][c]; };
	var setPrivateVar = function(n,v,w,e){Object.defineProperty(this,n,{value:v,writable:!!w,enumerable:!!e});};
	var setPublicVar = function(n,v,w){setPrivateVar.call(this,n,v,w,true);};
	AudioSynthInstrument = function AudioSynthInstrument(){this.__init__.apply(this,arguments);};
	var setPriv = setPrivateVar.bind(AudioSynthInstrument.prototype);
	var setPub = setPublicVar.bind(AudioSynthInstrument.prototype);
	setPriv('__init__', function(a,b,c) {
		if(!_encapsulated) { throw new Error('AudioSynthInstrument can only be instantiated from the createInstrument method of the AudioSynth object.'); }
		setPrivateVar.call(this, '_parent', a);
		setPublicVar.call(this, 'name', b);
		setPrivateVar.call(this, '_soundID', c);
	});
	setPub('play', function(note, octave, duration) {
		return this._parent.play(this._soundID, note, octave, duration);
	});
	setPub('generate', function(note, octave, duration) {
		return this._parent.generate(this._soundID, note, octave, duration);
	});
	AudioSynth = function AudioSynth(){if(AudioSynthInstance instanceof AudioSynth){return AudioSynthInstance;}else{ this.__init__(); return this; }};
	setPriv = setPrivateVar.bind(AudioSynth.prototype);
	setPub = setPublicVar.bind(AudioSynth.prototype);
	setPriv('_debug',false,true);
	setPriv('_bitsPerSample',16);
	setPriv('_channels',1);
	setPriv('_sampleRate',44100,true);
	setPub('setSampleRate', function(v) {
		this._sampleRate = Math.max(Math.min(v|0,44100), 4000);
		this._clearCache();
		return this._sampleRate;
	});
	setPub('getSampleRate', function() { return this._sampleRate; });
	setPriv('_volume',32768,true);
	setPub('setVolume', function(v) {
		v = parseFloat(v); if(isNaN(v)) { v = 0; }
		v = Math.round(v*32768);
		this._volume = Math.max(Math.min(v|0,32768), 0);
		this._clearCache();
		return this._volume;
	});
	setPub('getVolume', function() { return Math.round(this._volume/32768*10000)/10000; });
	setPriv('_notes',{'C':261.63,'C#':277.18,'D':293.66,'D#':311.13,'E':329.63,'F':349.23,'F#':369.99,'G':392.00,'G#':415.30,'A':440.00,'A#':466.16,'B':493.88});
	setPriv('_fileCache',[],true);
	setPriv('_temp',{},true);
	setPriv('_sounds',[],true);
	setPriv('_mod',[function(i,s,f,x){return Math.sin((2 * Math.PI)*(i/s)*f+x);}]);
	setPriv('_resizeCache', function() {
		var f = this._fileCache;
		var l = this._sounds.length;
		while(f.length<l) {
			var octaveList = [];
			for(var i = 0; i < 8; i++) {
				var noteList = {};
				for(var k in this._notes) {
					noteList[k] = {};
				} 
				octaveList.push(noteList);
			}
			f.push(octaveList);
		}
	});
	setPriv('_clearCache', function() {
		this._fileCache = [];
		this._resizeCache();
	});
	setPub('generate', function(sound, note, octave, duration) {
		var thisSound = this._sounds[sound];
		if(!thisSound) {
			for(var i=0;i<this._sounds.length;i++) {
				if(this._sounds[i].name==sound) {
					thisSound = this._sounds[i];
					sound = i;
					break;
				}
			}
		}
		if(!thisSound) { throw new Error('Invalid sound or sound ID: ' + sound); }
		var t = (new Date).valueOf();
		this._temp = {};
		octave |= 0;
		octave = Math.min(8, Math.max(1, octave));
		var time = !duration?2:parseFloat(duration);
		if(typeof(this._notes[note])=='undefined') { throw new Error(note + ' is not a valid note.'); }
		if(typeof(this._fileCache[sound][octave-1][note][time])!='undefined') {
			if(this._debug) { console.log((new Date).valueOf() - t, 'ms to retrieve (cached)'); }
			return this._fileCache[sound][octave-1][note][time];
		} else {
			var frequency = this._notes[note] * Math.pow(2,octave-4);
			var sampleRate = this._sampleRate;
			var volume = this._volume;
			var channels = this._channels;
			var bitsPerSample = this._bitsPerSample;
			var attack = thisSound.attack(sampleRate, frequency, volume);
			var dampen = thisSound.dampen(sampleRate, frequency, volume);
			var waveFunc = thisSound.wave;
			var waveBind = {modulate: this._mod, vars: this._temp};
			var val = 0;
			var curVol = 0;

			var data = new Uint8Array(new ArrayBuffer(Math.ceil(sampleRate * time * 2)));
			var attackLen = (sampleRate * attack) | 0;
			var decayLen = (sampleRate * time) | 0;

			for (var i = 0 | 0; i !== attackLen; i++) {
		
				val = volume * (i/(sampleRate*attack)) * waveFunc.call(waveBind, i, sampleRate, frequency, volume);

				data[i << 1] = val;
				data[(i << 1) + 1] = val >> 8;

			}

			for (; i !== decayLen; i++) {

				val = volume * Math.pow((1-((i-(sampleRate*attack))/(sampleRate*(time-attack)))),dampen) * waveFunc.call(waveBind, i, sampleRate, frequency, volume);

				data[i << 1] = val;
				data[(i << 1) + 1] = val >> 8;

			}

			var out = [
				'RIFF',
				pack(1, 4 + (8 + 24/* chunk 1 length */) + (8 + 8/* chunk 2 length */)), // Length
				'WAVE',
				// chunk 1
				'fmt ', // Sub-chunk identifier
				pack(1, 16), // Chunk length
				pack(0, 1), // Audio format (1 is linear quantization)
				pack(0, channels),
				pack(1, sampleRate),
				pack(1, sampleRate * channels * bitsPerSample / 8), // Byte rate
				pack(0, channels * bitsPerSample / 8),
				pack(0, bitsPerSample),
				// chunk 2
				'data', // Sub-chunk identifier
				pack(1, data.length * channels * bitsPerSample / 8), // Chunk length
				data
			];
			var blob = new Blob(out, {type: 'audio/wav'});
			var dataURI = URL.createObjectURL(blob);
			this._fileCache[sound][octave-1][note][time] = dataURI;
			if(this._debug) { console.log((new Date).valueOf() - t, 'ms to generate'); }
			return dataURI;
		}
	});
	setPub('play', function(sound, note, octave, duration) {
		var src = this.generate(sound, note, octave, duration);
		var audio = new Audio(src);
		audio.play();
		return true;
	});
	setPub('debug', function() { this._debug = true; });
	setPub('createInstrument', function(sound) {
		var n = 0;
		var found = false;
		if(typeof(sound)=='string') {
			for(var i=0;i<this._sounds.length;i++) {
				if(this._sounds[i].name==sound) {
					found = true;
					n = i;
					break;
				}
			}
		} else {
			if(this._sounds[sound]) {
				n = sound;
				sound = this._sounds[n].name;
				found = true;
			}
		}
		if(!found) { throw new Error('Invalid sound or sound ID: ' + sound); }
		_encapsulated = true;
		var ins = new AudioSynthInstrument(this, sound, n);
		_encapsulated = false;
		return ins;
	});
	setPub('listSounds', function() {
		var r = [];
		for(var i=0;i<this._sounds.length;i++) {
			r.push(this._sounds[i].name);
		}
		return r;
	});
	setPriv('__init__', function(){
		this._resizeCache();
	});
	setPub('loadSoundProfile', function() {
		for(var i=0,len=arguments.length;i<len;i++) {
			var o = arguments[i];
			if(!(o instanceof Object)) { throw new Error('Invalid sound profile.'); }
			this._sounds.push(o);
		}
		this._resizeCache();
		return true;
	});
	setPub('loadModulationFunction', function() {
		for(var i=0,len=arguments.length;i<len;i++) {
			var f = arguments[i];
			if(typeof(f)!='function') { throw new Error('Invalid modulation function.'); }
			this._mod.push(f);
		}
		return true;
	});
	AudioSynthInstance = new AudioSynth();
	Synth = AudioSynthInstance;
}();

Synth.loadModulationFunction(
	function(i, sampleRate, frequency, x) { return 1 * Math.sin(2 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 1 * Math.sin(4 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 1 * Math.sin(8 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 1 * Math.sin(0.5 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 1 * Math.sin(0.25 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 0.5 * Math.sin(2 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 0.5 * Math.sin(4 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 0.5 * Math.sin(8 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 0.5 * Math.sin(0.5 * Math.PI * ((i / sampleRate) * frequency) + x); },
	function(i, sampleRate, frequency, x) { return 0.5 * Math.sin(0.25 * Math.PI * ((i / sampleRate) * frequency) + x); }
);

Synth.loadSoundProfile({
	name: 'piano',
	attack: function() { return 0.002; },
	dampen: function(sampleRate, frequency, volume) {
		return Math.pow(0.5*Math.log((frequency*volume)/sampleRate),2);
	},
	wave: function(i, sampleRate, frequency, volume) {
		var base = this.modulate[0];
		return this.modulate[1](
			i,
			sampleRate,
			frequency,
			Math.pow(base(i, sampleRate, frequency, 0), 2) +
				(0.75 * base(i, sampleRate, frequency, 0.25)) +
				(0.1 * base(i, sampleRate, frequency, 0.5))
		);
	}
},
{
	name: 'organ',
	attack: function() { return 0.3 },
	dampen: function(sampleRate, frequency) { return 1+(frequency * 0.01); },
	wave: function(i, sampleRate, frequency) {
		var base = this.modulate[0];
		return this.modulate[1](
			i,
			sampleRate,
			frequency,
			base(i, sampleRate, frequency, 0) +
				0.5*base(i, sampleRate, frequency, 0.25) +
				0.25*base(i, sampleRate, frequency, 0.5)
		);
	}
},
{
	name: 'acoustic',
	attack:	function() { return 0.002; },
	dampen: function() { return 1; },
	wave: function(i, sampleRate, frequency) {

		var vars = this.vars;
		vars.valueTable = !vars.valueTable?[]:vars.valueTable;
		if(typeof(vars.playVal)=='undefined') { vars.playVal = 0; }
		if(typeof(vars.periodCount)=='undefined') { vars.periodCount = 0; }
	
		var valueTable = vars.valueTable;
		var playVal = vars.playVal;
		var periodCount = vars.periodCount;

		var period = sampleRate/frequency;
		var p_hundredth = Math.floor((period-Math.floor(period))*100);

		var resetPlay = false;

		if(valueTable.length<=Math.ceil(period)) {
	
			valueTable.push(Math.round(Math.random())*2-1);
	
			return valueTable[valueTable.length-1];
	
		} else {
	
			valueTable[playVal] = (valueTable[playVal>=(valueTable.length-1)?0:playVal+1] + valueTable[playVal]) * 0.5;
	
			if(playVal>=Math.floor(period)) {
				if(playVal<Math.ceil(period)) {
					if((periodCount%100)>=p_hundredth) {
						// Reset
						resetPlay = true;
						valueTable[playVal+1] = (valueTable[0] + valueTable[playVal+1]) * 0.5;
						vars.periodCount++;	
					}
				} else {
					resetPlay = true;	
				}
			}
	
			var _return = valueTable[playVal];
			if(resetPlay) { vars.playVal = 0; } else { vars.playVal++; }
	
			return _return;
	
		}
	}
},
{
	name: 'edm',
	attack:	function() { return 0.002; },
	dampen: function() { return 1; },
	wave: function(i, sampleRate, frequency) {
		var base = this.modulate[0];
		var mod = this.modulate.slice(1);
		return mod[0](
			i,
			sampleRate,
			frequency,
			mod[9](
				i,
				sampleRate,
				frequency,
				mod[2](
					i,
					sampleRate,
					frequency,
					Math.pow(base(i, sampleRate, frequency, 0), 3) +
						Math.pow(base(i, sampleRate, frequency, 0.5), 5) +
						Math.pow(base(i, sampleRate, frequency, 1), 7)
				)
			) +
				mod[8](
					i,
					sampleRate,
					frequency,
					base(i, sampleRate, frequency, 1.75)
				)
		);
	}
});

//audioSynth.js end

const audioSynth = new AudioSynth();
var visualKeyboard;
const pressColor = "#e2aa2f";
var keysPressed = [];
var octave = 4; //sets position of middle C, normally the 4th octave

function fnPlayNote(note, octave) {
      var src = audioSynth.generate("0", note, octave, 2);
      var container = new Audio(src);
      container.addEventListener("ended", function () {
        container = null;
      });
      container.addEventListener("loadeddata", function (e) {
        e.target.play();
      });
      container.autoplay = false;
      container.setAttribute("type", "audio/wav");
      container.load();
      return container;
}

function fnRemoveKeyBinding(e) {
	var keyCode = e.keyCode | e; 
    var i = keysPressed.length;
    while (i--) {
      if (keysPressed[i] == keyCode) {
	    if(keyNotes[keyCode]) {
	      var k = keyNotes[keyCode];
          var key = visualKeyboard.querySelector(`div[note = "${k}"]`);
	      key.style.backgroundColor = "";
	      key.style.marginTop = "";
	      key.style.boxShadow = "";    
	    }
	    keysPressed.splice(i, 1);
	  }
    }
  };
  

function fnPlayPiano(e) {
	var keyCode = e.keyCode | e;
	var i = keysPressed.length;
	while (i--) {
		if(keysPressed[i] == keyCode) return false;
	}
	keysPressed.push(keyCode);
	if(keyNotes[keyCode]){
		var k = keyNotes[keyCode];
		var key = visualKeyboard.querySelector(`div[note = "${k}"]`);
	    key.style.backgroundColor = pressColor;
	    key.style.marginTop = "5px";
	    key.style.boxShadow = "none";
	    var arrPlayNote = k.split(",");
        var note = arrPlayNote[0];
        var octaveModifier = arrPlayNote[1] | 0;
	    fnPlayNote(note, octave + octaveModifier);
	}else return false;
}

function getKeyByValue(object, value) {
  return Object.keys(object).find(key => object[key] === value);
}

export default {
  name: "KeyBoard",
  components: {
    KeyWhite,
    KeyBlack
  },
  methods: {
    playPiano: function(note){
      var keyCode = getKeyByValue(keyNotes, note);
	  fnPlayPiano(keyCode);
    },
    pausePiano: function(note){
      var keyCode = getKeyByValue(keyNotes, note);
      fnRemoveKeyBinding(keyCode);
	},
	
  },
  mounted: function(){
    this.$nextTick(function(){
      audioSynth.setVolume(0.5);
	  visualKeyboard = document.querySelector('#keyBoard').firstElementChild;
	  window.addEventListener("keydown", fnPlayPiano);
      window.addEventListener("keyup", fnRemoveKeyBinding);
  })
  }
};
</script>

<style scoped>
.piano {
  display: flex;
  justify-content: center;
  width: 74.1rem;
  background-color: #2c3e50;
  margin: 0 auto;
  box-shadow: 5px 5px 5px silver, 5px 5px 5px silver, -5px -1px 5px silver, 5px 5px 5px silver;
  padding-top: 20px;
  border-radius: 10px;
}
.keyBoard {
  height: 250px;
  min-width: 71.4rem; /* 856.8px */
  position: relative;
  /* transform: scale(1.2); */
}
.keys {
  position: absolute;
}
.kw1 {
	border-top-left-radius: 4px;
}

.kw28 {
	border-top-right-radius: 4px;
}

.kw2 {
  left: 2.55rem;
}
.kw3 {
  left: 5.1rem;
}
.kw4 {
  left: 7.65rem;
}
.kw5 {
  left: 10.2rem;
}
.kw6 {
  left: 12.75rem;
}
.kw7 {
  left: 15.3rem;
}
.kw8 {
  left: 17.85rem;
}
.kw9 {
  left: 20.4rem;
}
.kw10 {
  left: 22.95rem;
}
.kw11 {
  left: 25.5rem;
}
.kw12 {
  left: 28.05rem;
}
.kw13 {
  left: 30.6rem;
}
.kw14 {
  left: 33.15rem;
}
.kw15 {
  left: 35.7rem;
}
.kw16 {
  left: 38.25rem;
}
.kw17 {
  left: 40.8rem;
}
.kw18 {
  left: 43.35rem;
}
.kw19 {
  left: 45.9rem;
}
.kw20 {
  left: 48.45rem;
}
.kw21 {
  left: 51rem;
}
.kw22 {
  left: 53.55rem;
}
.kw23 {
  left: 56.1rem;
}
.kw24 {
  left: 58.65rem;
}
.kw25 {
  left: 61.2rem;
}
.kw26 {
  left: 63.75rem;
}
.kw27 {
  left: 66.3rem;
}
.kw28 {
  left: 68.85rem;
}

.kb {
  z-index: 100;
}
.kb1 {
  left: 1.5875rem;
}
.kb2 {
  left: 4.1375rem;
}
.kb4 {
  left: 9.2375rem; /* 3 * 2.55 + 1.5875 */
}
.kb5 {
  left: 11.7875rem;
}
.kb6 {
  left: 14.3375rem;
}
.kb8 {
  left: 19.4375rem; /* 7 * 2.55 + 1.5875 */
}
.kb9 {
  left: 21.9875rem;
}
.kb11 {
  left: 27.0875rem;
}
.kb12 {
  left: 29.6375rem; /* 11 * 2.55 + 1.5875 */
}
.kb13 {
  left: 32.1875rem;
}
.kb15 {
  left: 37.2875rem;
}
.kb16 {
  left: 39.8375rem;
}
.kb18 {
  left: 44.9375rem;
}
.kb19 {
  left: 47.4875rem;
}
.kb20 {
  left: 50.0375rem;
}
.kb22 {
  left: 55.1375rem;
}
.kb23 {
  left: 57.6875rem;
}
.kb25 {
  left: 62.7875rem;
}
.kb26 {
  left: 65.3375rem;
}
.kb27 {
  left: 67.8875rem;
}

.name {
	position: absolute;
    right: 0;
    top: 198px;
    left: 0;
    z-index: 1000;
    color: cornsilk;
    font-family: 'Sacramento';
    font-weight: bold;
}
</style>