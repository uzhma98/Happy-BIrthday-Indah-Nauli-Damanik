<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Indah Nauli Damanik</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Dancing+Script:wght@700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
body,html{height:100%;font-family:'Poppins',sans-serif;overflow:hidden}

.bg-image{
background:url('5ea4d25c-04a4-48ae-ab60-e65c001a4e59.JPG') center/cover no-repeat;
position:fixed;width:100%;height:100%;z-index:-2;
filter:blur(2px);transform:scale(1.05);
animation:zoom 20s infinite alternate ease-in-out
}
@keyframes zoom{from{transform:scale(1.05)}to{transform:scale(1.12)}}

.overlay{position:fixed;width:100%;height:100%;background:rgba(0,0,0,.4);z-index:-1}

.content-container{display:flex;flex-direction:column;justify-content:center;align-items:center;height:100vh;text-align:center;color:#fff;padding:20px}

.title{font-size:clamp(2.5rem,8vw,5rem);letter-spacing:3px;text-transform:uppercase;opacity:0;
animation:fadeDown 1s .3s forwards;
text-shadow:0 0 10px #fff,0 0 30px #7c9cff}

@keyframes fadeDown{from{opacity:0;transform:translateY(-30px)}to{opacity:1;transform:translateY(0)}}

.name{
font-size:clamp(3rem,9vw,5.5rem);
font-family:'Dancing Script',cursive;
white-space:nowrap;overflow:hidden;width:0;border-right:3px solid #fff;
background:linear-gradient(90deg,#fff,#a5b4fc,#60a5fa);
-webkit-background-clip:text;-webkit-text-fill-color:transparent;
animation:typing 2.5s steps(25) 1s forwards,blink .7s infinite,glow 2s infinite 4s
}
@keyframes typing{from{width:0}to{width:100%}}
@keyframes blink{50%{border-color:transparent}}
@keyframes glow{0%,100%{filter:drop-shadow(0 0 5px #60a5fa)}50%{filter:drop-shadow(0 0 20px #a5b4fc)}}

.message-title,.message-text{opacity:0;animation:fadeUp 1s forwards}
.message-title{animation-delay:4s;font-size:1.5rem}
.message-text{animation-delay:4.3s;font-weight:300}

@keyframes fadeUp{from{opacity:0;transform:translateY(20px)}to{opacity:1;transform:translateY(0)}}

.cake-container{margin-top:30px;cursor:pointer;animation:float 4s infinite ease-in-out}
@keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-10px)}}

.cake{font-size:5rem;transition:.3s}
.cake:hover{transform:scale(1.15) rotate(-5deg)}

.music-btn{
position:fixed;top:20px;right:20px;width:60px;height:60px;border-radius:50%;
background:rgba(255,255,255,.2);border:1px solid rgba(255,255,255,.3);
backdrop-filter:blur(10px);color:#fff;font-size:1.5rem;cursor:pointer;
display:flex;align-items:center;justify-content:center;z-index:10
}
.music-btn:hover{transform:scale(1.1)}

</style>
</head>
<body>

<div class="bg-image"></div>
<div class="overlay"></div>

<button class="music-btn" id="musicBtn">🎵</button>

<div class="content-container">
<h1 class="title">🎉Happy Birthday🎉</h1>
<div class="name">Indah Nauli Damanik</div>

<div class="message-title">Selamat ulang tahun ya! 🎉</div>
<div class="message-text">
Makasih sudah selalu ada 💖<br>
Semoga kamu bahagia selalu ✨<br>
<b>I'm so lucky to have you</b>
</div>

<div class="cake-container" onclick="celebrate()">
<div class="cake">🎂</div>
</div>
</div>

<audio id="bgMusic" loop>
<source src="mp3.mp3">
</audio>

<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>

<script>
const musicBtn=document.getElementById('musicBtn')
const bgMusic=document.getElementById('bgMusic')
let playing=false

musicBtn.onclick=()=>{
if(playing){bgMusic.pause();musicBtn.innerHTML='🔇'}
else{bgMusic.play().catch(()=>{});musicBtn.innerHTML='🎵'}
playing=!playing
}

function celebrate(){
bgMusic.play().catch(()=>{})
confetti({particleCount:200,spread:120,origin:{y:.6}})
setTimeout(()=>{
confetti({particleCount:150,angle:60,spread:80,origin:{x:0}})
confetti({particleCount:150,angle:120,spread:80,origin:{x:1}})
},400)
}
</script>

</body>
</html>
