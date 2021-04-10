
<html>
<head>
<title>playing </title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
<style>
.seekStyle{
  -webkit-appearance: none;
  margin: 7.3px 0;
}
.seekStyle:focus {
  outline: none;
}
.seekStyle::-webkit-slider-runnable-track {
  height: 11.4px;
  cursor: pointer;
  box-shadow: 1px 1px 1px #000000, 0px 0px 1px #0d0d0d;
  background: rgba(31, 74, 99, 0.92);
  border-radius: 1.3px;
  border: 0.2px solid #010101;
}
.seekStyle::-webkit-slider-thumb {
  box-shadow: 0.9px 0.9px 1px rgba(0, 56, 49, 0.24), 0px 0px 0.9px rgba(0, 82, 71, 0.24);
  border: 1.8px solid rgba(0, 4, 30, 0.14);
  height: 26px;
  width: 26px;
  border-radius: 15px;
  background: rgba(71, 227, 255, 0.89);
  cursor: pointer;
  -webkit-appearance: none;
  margin-top: -7.5px;
}
.seekStyle:focus::-webkit-slider-runnable-track {
  background: rgba(37, 89, 118, 0.92);
}
.seekStyle::-moz-range-track {
  height: 11.4px;
  cursor: pointer;
  box-shadow: 1px 1px 1px #000000, 0px 0px 1px #0d0d0d;
  background: rgba(31, 74, 99, 0.92);
  border-radius: 1.3px;
  border: 0.2px solid #010101;
}
.seekStyle::-moz-range-thumb {
  box-shadow: 0.9px 0.9px 1px rgba(0, 56, 49, 0.24), 0px 0px 0.9px rgba(0, 82, 71, 0.24);
  border: 1.8px solid rgba(0, 4, 30, 0.14);
  height: 26px;
  width: 26px;
  border-radius: 15px;
  background: rgba(71, 227, 255, 0.89);
  cursor: pointer;
}
.seekStyle::-ms-track {
  width: 100%;
  height: 11.4px;
  cursor: pointer;
  background: transparent;
  border-color: transparent;
  color: transparent;
}
.seekStyle::-ms-fill-lower {
  background: rgba(25, 59, 80, 0.92);
  border: 0.2px solid #010101;
  border-radius: 2.6px;
  box-shadow: 1px 1px 1px #000000, 0px 0px 1px #0d0d0d;
}
.seekStyle::-ms-fill-upper {
  background: rgba(31, 74, 99, 0.92);
  border: 0.2px solid #010101;
  border-radius: 2.6px;
  box-shadow: 1px 1px 1px #000000, 0px 0px 1px #0d0d0d;
}
.seekStyle::-ms-thumb {
  box-shadow: 0.9px 0.9px 1px rgba(0, 56, 49, 0.24), 0px 0px 0.9px rgba(0, 82, 71, 0.24);
  border: 1.8px solid rgba(0, 4, 30, 0.14);
  height: 26px;
  width: 26px;
  border-radius: 15px;
  background: rgba(71, 227, 255, 0.89);
  cursor: pointer;
  height: 11.4px;
}
.seekStyle:focus::-ms-fill-lower {
  background: rgba(31, 74, 99, 0.92);
}
.seekStyle:focus::-ms-fill-upper {
  background: rgba(37, 89, 118, 0.92);
}

.buttonStyle { 
text-align:center;
}

.buttonStyle > div {
margin-left:20px;
margin-right:20px;
}

img[alt*="Free Web Hosting"]{
display:none!important;
opacity:0;
}
img[src*="https://www.freewebhostingarea.com/images/poweredby.png"]{
display:none!important;
opacity:0;
}
</style>
<div>
    <p>Pilih Album</p>
    <select id="listMusic">
        <option>Pilih Album</option>
        <option value="all">Semua album</option>
        <option value="twice">Twice</option>
        <option value="blackpink">Blackpink</option>
        <option value="apink">Apink</option>
        <option value="pribadi">pribadi</option>
    </select>
</div>
<div>
<p>Pilih Lagu</p>
<select id="chooseMusic">
</select>
</div>

<div>
    <p>Play Mode</p>
    <input type="radio" name="modeS" value="0" checked="checked"/>NormalSwitch
    <input type="radio" name="modeS" value="1" />RandomSwitch
</div>
<hr>
<h3 id="myStatus"></h3>
<div class="buttonStyle" style="display:flex;">
<div id="myMute"><img src="https://image.flaticon.com/icons/svg/747/747575.svg" width="50" height="50" alt="mute"></div>
<div id="myPlay" ><img src="https://image.flaticon.com/icons/svg/747/747551.svg" width="50" height="50" alt="play" /></div>
<div id="myNext"><img src="https://image.flaticon.com/icons/svg/2284/2284768.svg" width="50" height="50" alt="next" /></div>
<div id="myPrev"><img src="https://image.flaticon.com/icons/svg/2284/2284843.svg" width="50" height="50" alt="prev"/></div>
</div>

<div style="clear:both"></div>
<br>
<div id="timebox">
	<span id="curtimetext">00:00</span> / <span id="durtimetext">00:00</span>
</div>
<div>
<input id="mySeek" class="seekStyle" type="range" min="0" max="100" value="0" step="1"/>
</div>
<div>
<span>Volume:</span>
<input id="myVolume" type="range" min="0" max="100" value="100" step="1"/>
</div>
<br/>
<center>Contact: mrtampan54@gmail.com</center>
<script>
var audio, playbtn, mutebtn, 
seekslider, volumeslider, 
seekto, seeking=false, 
curtimetext, durtimetext,
play_status, dir, playlist,
ext, playlist_index, agent,isMobile, 
listmusic, modeSwitch, playModeValue;

function initAudioPlayer() {
	// Set Object references
	playbtn = document.getElementById("myPlay");
	mutebtn = document.getElementById("myMute");
	nextbtn = document.getElementById("myNext");
	prevbtn = document.getElementById("myPrev");
	volumeslider = document.getElementById("myVolume");
	seekslider = document.getElementById("mySeek");
	curtimetext = document.getElementById("curtimetext");
	durtimetext = document.getElementById("durtimetext");
	play_status = document.getElementById("myStatus");
	listmusic = document.getElementById("listMusic");
	modeSwitch = document.getElementsByName("modeS");
	chooseMusic = document.getElementById("chooseMusic");
	
	isMobile = {
    Android: function() {
        return navigator.userAgent.match(/Android/i);
    },
    BlackBerry: function() {
        return navigator.userAgent.match(/BlackBerry/i);
    },
    iOS: function() {
        return navigator.userAgent.match(/iPhone|iPad|iPod/i);
    },
    Opera: function() {
        return navigator.userAgent.match(/Opera Mini/i);
    },
    Windows: function() {
        return navigator.userAgent.match(/IEMobile/i);
    },
    any: function() {
        return (isMobile.Android() || isMobile.BlackBerry() || isMobile.iOS() || isMobile.Opera() || isMobile.Windows());
    }
};

    // Music Object
    izone = [
    {
        music:"1617448131",
        name:"Panorama"        
    },
    {
        music:"1592014747",
        name:"La Vie En Rose"        
    },
    {
        music:"1601323460",
        name:"Fiesta"        
    }
    ];
    secretnumber = [
    {
        music:"1599550782",
        name: "Who Dis"
    }  
    ];
    itzy = [
    {
        music:"1590101600",
        name:"Wannabe"        
    },
    {
        music:"1601369448",
        name:"Not Shy"        
    }
    ];
    redvelvet = [
    {
        music:"1577258121",
        name:"Umpah Umpah"        
    },
    {
        music:"1590094461",
        name:"Psycho"        
    },
    {
        music:"1612381437",
        name:"Power Up"        
    }
    ];
    gfriend = [
    {
        music:"1612346890",
        name:"Mago"
    },
    {
        music:"1612329996",
        name:"Glass Bead"
    },
    {
        music:"1599506245",
        name:"Apple"
    },
    {
        music:"1601371887",
        name:"Sunrise"
    },
    {
        music:"1592024570",
        name:"Rough"
    },
    {
        music:"1590169426",
        name:"Me Gusta"
    },
    {
        music:"1577294347",
        name:"Fever"
    },
    {
        music:"1605106202",
        name:"Love Whisper"
    },
    {
        music:"1605047341",
        name:"Summer Rain"
    },
    {
        music:"1605013558",
        name:"Time For MoonLight"
    },
    {
        music:"1605035464",
        name:"Navilerra"
    }
    ];
    blackpink = [
    {
        music: "1605103693",
        name: "LoveSick Girl"
    },
    {
        music: "1599508881",
        name: "Ice Cream"
    },
    {
        music:"1594592797",
        name: "How You Like That"
    },
    {
        music:"1594596689",
        name: "Kill This Love"
    },
    {
        music:"1570186762",
        name:"As If Its Your Last"
    },
    {
        music: "1570187253",
        name:"Boombayah"
    },
    {
        music: "1570149074",
        name: "DDU-DU"
    },
    {
        music: "1570170030",
        name: "Dont Know What To Do"
    },
    {
        music: "1570169887",
        name: "Forever young"
    },
    {
        music: "1570146803",
        name: "Stay"
    },
    {
        music: "1570152934",
        name: "Playing with fire"
    },
    {
        music: "1590098648",
        name: "Whistle"
    }
    ];
    apink = [
    {
        music:"1592005500",
        name:"Eung Eung"
    },
    {
        music:"1571037228",
        name:"Cause you are myStar"
    },
    {
        music:"1571084363",
        name:"U You"
    },
    {
        music:"1569219977",
        name:"LUV"
    },
    {
        music:"1569177384",
        name:"Mr Chu"
    },
    {
        music:"1569212272",
        name:"Five"
    },
    {
        music:"1569220880",
        name:"I Dont Know"
    },
    {
        music:"1569244477",
        name:"My My"
    },
    {
        music:"1569179000",
        name:"Nonono"
    },
    {
        music:"1569192029",
        name:"orion"
    },
    {
        music:"1570166578",
        name:"Bye Bye"
    }
    ]
    twice = [
    {
        music:"1617437335",
        name:"Cry For Me"
    },
    {
        music:"1612341304",
        name:"Better"
    },
    {
        music:"1605063070",
        name:"I Cant Stop Me"
    },
    {
        music:"1594606414",
        name:"Fanfare"
    },
    {
        music:"1591997967",
        name:"More and More"
    },
    {
        music:"1577264687",
        name:"Fake And True"
    },
    {
        music:"1571051176",
        name:"Feel Special"
    },
    {
        music:"1569174387",
        name:"Happy Happy"
    },
    {
        music:"1569155161",
        name:"Fancy uu"
    },
    {
        music:"1612383150",
        name:"One More Time"
    },
    {
        music:"1612312378",
        name:"Wake Me UP"
    },
    {
        music:"1569225408",
        name:"Signal"
    },
    {
        music:"1569180863",
        name:"Knock Knock"
    },
    {
        music:"1569156686",
        name:"Last Dance The Night Away"
    },
    {
        music:"1569187847",
        name:"Cheer Up"
    },
    {
        music:"1569229531",
        name:"Heart Sheaker"
    },
    {
        music:"1569248802",
        name:"Likey"
    },
    {
        music:"1570219584",
        name:"TT"
    },
    {
        music:"1571033799",
        name:"Like Ooh Aah"
    },
    {
        music:"1569167345",
        name:"What Is Love"
    },
    {
        music:"1570178170",
        name:"Yes Or Yes"
    },
    {
        music:"1569164712",
        name:"CandyPop"
    }
    ];
    pribadi = [
    {
        music:"1587563516",
        name:"Himawari no yakusoku"
    },
    {
        music:"1587490401",
        name:"Orange"
    },
    {
        music:"1587512192",
        name:"Lemon"
    },
    {
        music:"1587915782",
        name:"Kimi Sae Inakerya"
    },
    {
        music:"1587856397",
        name:"Hanabi Mr Children"
    },
    {
        music:"1587596676",
        name:"Meow Meow"
    },
    {
        music:"1590118746",
        name:"Happy End"
    },
    {
        music:"1590130780",
        name:"Dan Dan Dragon ball"
    },
    {
        music:"1590079560",
        name:"Peace Sign"
    },
    {
        music:"1598313103",
        name:"Anotamo"
    },
    {
        music:"1599560613",
        name:"Kimi No Toriko"
    },
    {
        music:"1600439568",
        name:"Number One"
    },
    {
        music:"1600449090",
        name:"Kimi Ga Kureta"
    },
    {
        music:"1599579086",
        name:"Sukima Switch"
    },
    {
        music:"1606281129",
        name:"First Love"
    }
    ];
    // kpop = twice.concat(apink,blackpink,gfriend,redvelvet,itzy,izone);
	
	// Audio Object
	audio = new Audio();
	dir = "http://otupload.orangeoval.net/uploads/";
	playlist = twice.concat(apink,blackpink,gfriend,redvelvet,itzy,izone,secretnumber);
	playModeValue = "0";
	playlist_index = 0;
	ext = ".mp3";
	agent = navigator.userAgent.toLowerCase();
	if(agent.indexOf('firefox') != -1 || agent.indexOf('opera') != -1 ){
		ext = ".ogg";
	}
	audio.src = dir+playlist[0].music+ext;
	audio.loop = false;
	audio.play();
	play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
	document.title = play_status.innerText;
	
	playbtn.addEventListener("click", playPause);
	mutebtn.addEventListener("click", mute);
    nextbtn.addEventListener("click", nextPlay);
    prevbtn.addEventListener("click", prevPlay);
	if(isMobile.Android() || isMobile.any() ) {
	/*seekslider.addEventListener("touchend", function(event){ seeking=true; seek(event); });
	seekslider.addEventListener("touchmove", function(event){ seek(event); });
	seekslider.addEventListener("touchstart", function(){ seeking=false; });*/
	
	seekslider.addEventListener("touchstart", function(event){ seeking=true; seekandro(event); });
	seekslider.addEventListener("touchmove", function(event){ seekandro(event); });
	seekslider.addEventListener("touchend", function(){ seeking=false; });
	volumeslider.addEventListener("touchmove", setvolume);
	} else {
	seekslider.addEventListener("mousedown", function(event){ seeking=true; seek(event); });
	seekslider.addEventListener("mousemove", function(event){ seek(event); });
	seekslider.addEventListener("mouseup", function(){ seeking=false; });
	volumeslider.addEventListener("mousemove", setvolume);
	}
	audio.addEventListener("timeupdate", function() { seektimeupdate(); })
	audio.addEventListener("ended", function(){ switchTrack(); });
	listmusic.addEventListener("change", musicList);
	chooseMusic.addEventListener("change", musicChoose);
	
	for(let i = 0; i < modeSwitch.length ; i++){
	    modeSwitch[i].addEventListener("change", function() {
	        console.log(this.value);
	        if(this == null){
	            playModeValue = 0;
	        }
	        playModeValue = this.value;
	    })
	}
	
	//Functions
	function musicChoose() {
	    audio.pause();
	    audio.currentTime = 0;
	    let checkedMusic = chooseMusic.options[chooseMusic.selectedIndex].value
	    audio.src = dir+checkedMusic+ext;
	    playlist_index = chooseMusic.selectedIndex
	    play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
        document.title = play_status.innerText;
	    playPause(true);
	}
	function switchTrack() {
	    if(playModeValue == "1"){
	       playlist_index = Math.floor(Math.random() * (playlist.length - 1));
	    } else {
    		if(playlist_index == (playlist.length - 1)){
    			playlist_index = 0;
    		} else {
    			playlist_index++;
    		}
	    }
		play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
		document.title = play_status.innerText;
		audio.src = dir+playlist[playlist_index].music+ext;
		audio.play();
	}
	function defineChoose() {
	    chooseMusic.innerHTML = '';
	    var df = '';
    	df = document.createDocumentFragment();
        for(var d=0;d<playlist.length;d++)
        {
        let option = ''
        option = document.createElement('option');
        option.value = playlist[d].music;
        option.appendChild(document.createTextNode(playlist[d].name));
        df.appendChild(option);
        }
    	chooseMusic.appendChild(df);
	}
	
	function musicList(){
	    audio.pause();
	    audio.currentTime = 0;
	    audio.src = "";
	    switch(listmusic.options[listmusic.selectedIndex].value){
	        case "all":
	            playlist = twice.concat(apink,blackpink,gfriend,redvelvet,itzy,izone,secretnumber);
	            play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
	            audio.src = dir+playlist[0].music+ext;
    	        break;
	        case "twice":
	            playlist = twice;
	            play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
	            audio.src = dir+playlist[0].music+ext;
    	        break;
	        case "blackpink":
	            playlist = blackpink;
	            play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
	            audio.src = dir+playlist[0].music+ext;
    	        break;
	        case "apink":
	            playlist = apink;
	            play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
	            audio.src = dir+playlist[0].music+ext;
    	        break;
    	    case "pribadi":
    	        playlist = pribadi;
    	        play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
    	        audio.src = dir+playlist[0].music+ext;
    	        break;
	    }
	    defineChoose();
    }
    
    function playPause(playTrigger){
        this.playTrigger = playTrigger;
        
        if(playTrigger = true){
            audio.play();
            playbtn.children[0].src = "https://image.flaticon.com/icons/svg/747/747553.svg";
        }else{
            audio.pause();
            playbtn.children[0].src = "https://image.flaticon.com/icons/svg/747/747551.svg";
        }
    }
	
	function playPause(){
		if(audio.paused){
			audio.play();
			playbtn.children[0].src = "https://image.flaticon.com/icons/svg/747/747553.svg";
			// playbtn.innerText = "Pause";
		} else {
			audio.pause();
			playbtn.children[0].src = "https://image.flaticon.com/icons/svg/747/747551.svg";
// 			playbtn.innerText = "Play";
		}
	}
	function mute(){
		if(audio.muted){
			audio.muted = false;
		} else {
			audio.muted = true;
		}
	}
	function seek(event){
		if(seeking){
			seekslider.value = event.clientX - seekslider.offsetLeft;
			seekto = audio.duration * (seekslider.value / 100);
			audio.currentTime = seekto;
			
		}
	}
	
	function seekandro(event){
		if(seeking){
			seekslider.value = event.touches[0].clientX - seekslider.offsetLeft;
			seekto = audio.duration * (seekslider.value / 100);
			audio.currentTime = seekto;

		}
	}
	
	
	function setvolume() {
		audio.volume = volumeslider.value / 100;
	}
	function seektimeupdate() {
		var nt = audio.currentTime * (100 / audio.duration);
		seekslider.value = nt;
		var curmins = Math.floor(audio.currentTime / 60);
		var cursecs = Math.floor(audio.currentTime - curmins * 60);
		var durmins = Math.floor(audio.duration / 60);
		var dursecs = Math.floor(audio.duration - curmins * 60);
		if(cursecs < 10) { cursecs = "0"+cursecs;}
		if(dursecs < 10) { dursecs = "0"+dursecs;}
		if(curmins < 10) { curmins = "0"+curmins;}
		if(durmins < 10) { durmins = "0"+durmins;}
		curtimetext.innerHTML = curmins+":"+cursecs;
		durtimetext.innerHTML = durmins+":"+dursecs;
	}
    function nextPlay() {
        if(playlist_index > (playlist.length - 1)){
            playlist_index = 0;
        }
        playlist_index++;
        play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
        document.title = play_status.innerText;
		audio.src = dir+playlist[playlist_index].music+ext;
		playPause(true);
    }
    function prevPlay() {
        if(playlist_index < 1 ) {
         alert("Error Mbah");
        }else {
        playlist_index--;
        play_status.innerHTML = "Track "+(playlist_index+1)+" - "+ playlist[playlist_index].name;
        document.title = play_status.innerText;
		audio.src = dir+playlist[playlist_index].music+ext;
		playPause(true);
        }
    }
	
}
window.addEventListener("load", initAudioPlayer);
</script>

<div style="text-align:right;position:fixed;bottom:3px;right:3px;width:100%;z-index:999999;cursor:pointer;line-height:0;display:block;"><a target="_blank" href="https://www.freewebhostingarea.com" title="Free Web Hosting with PHP5 or PHP7"><img alt="Free Web Hosting" src="https://www.freewebhostingarea.com/images/poweredby.png" style="border-width: 0px;width: 180px; height: 45px; float: right;"></a></div>
</body>
</html>		
