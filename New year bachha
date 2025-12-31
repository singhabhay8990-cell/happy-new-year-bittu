<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<title>Happy New Year 2026 Bittu ❤️</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{
height:100vh;
background: radial-gradient(circle at bottom, #020111 0%, #000000 70%);
font-family:'Segoe UI', sans-serif;
overflow:hidden;
color:white;
}
.star{position:absolute;width:2px;height:2px;background:white;border-radius:50%;}
.firework{position:absolute;width:4px;height:4px;border-radius:50%;animation:explode 1.5s ease-out forwards;}
@keyframes explode{from{transform:scale(1);opacity:1;}to{transform:scale(20);opacity:0;}}
.container{
position:relative;z-index:10;max-width:420px;margin:auto;top:50%;
transform:translateY(-50%);background:rgba(0,0,0,0.55);
border-radius:20px;padding:25px;text-align:center;
box-shadow:0 0 25px rgba(255,255,255,0.2);
}
h1{font-size:2em;}h2{color:#ff9ecd;margin:10px 0;}
.heart{font-size:45px;animation:beat 1s infinite;}
@keyframes beat{0%,100%{transform:scale(1);}50%{transform:scale(1.3);}}
.shayari{margin:15px 0;line-height:1.7;color:#ffd6e8;}
footer{margin-top:15px;font-size:0.9em;}
.music-btn{margin-top:15px;padding:8px 16px;border:none;border-radius:20px;background:#ff5fa2;color:white;}
</style>
</head>
<body>

<audio id="bgMusic" loop>
<source src="song.mp3" type="audio/mpeg">
</audio>

<div class="container" onclick="playMusic()">
<h1>🎆 Happy New Year 2026 🎆</h1>
<h2>मेरी Bittu ❤️</h2>
<div class="heart">💖</div>
<div class="shayari">
नया साल आया है रौशनी लेकर,<br>
हर ख्वाब पूरा हो तेरा खुशियों लेकर ✨<br><br>
तू साथ हो तो हर लम्हा खास लगे,<br>
मेरी हर दुआ में बस तेरा ही नाम लगे 💕
</div>
<footer>हमेशा तुम्हारा 💝<br>— With Love</footer>
<button class="music-btn">🔊 Tap for Music</button>
</div>

<script>
for(let i=0;i<120;i++){
let s=document.createElement("div");
s.className="star";
s.style.left=Math.random()*100+"vw";
s.style.top=Math.random()*100+"vh";
document.body.appendChild(s);
}
function firework(){
let f=document.createElement("div");
f.className="firework";
f.style.left=Math.random()*100+"vw";
f.style.top=Math.random()*70+"vh";
f.style.background=`hsl(${Math.random()*360},100%,70%)`;
document.body.appendChild(f);
setTimeout(()=>f.remove(),1500);
}
setInterval(firework,400);
function playMusic(){
const m=document.getElementById("bgMusic");
if(m.paused){m.volume=0.4;m.play();}
}
</script>

</body>
</html>
