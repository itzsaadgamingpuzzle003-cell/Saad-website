<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Saad Bloxd Website</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
scroll-behavior:smooth;
}

body{

background:linear-gradient(135deg,#1a5f1a,#0b3d16);
color:white;
overflow-x:hidden;

}

/* ===== Header ===== */

header{

background:#0b3d16;
padding:25px;
text-align:center;
font-size:42px;
font-weight:bold;
box-shadow:0 0 25px lime;
animation:glow 2s infinite alternate;
position:sticky;
top:0;
z-index:999;

}

@keyframes glow{

from{
text-shadow:0 0 8px white;
}

to{
text-shadow:0 0 25px lime;
}

}

/* ===== Navigation ===== */

nav{

background:#145a32;
display:flex;
justify-content:center;
gap:35px;
padding:15px;
flex-wrap:wrap;

}

nav a{

color:white;
text-decoration:none;
font-size:18px;
font-weight:bold;
transition:.3s;

}

nav a:hover{

color:gold;
transform:scale(1.08);

}

/* ===== Hero ===== */

.hero{

text-align:center;
padding:70px 20px;

}

.hero h1{

font-size:60px;
margin-bottom:15px;

}

.hero p{

font-size:22px;
margin-bottom:25px;

}

.button{

display:inline-block;
padding:15px 35px;
background:#ff9800;
color:white;
text-decoration:none;
font-size:20px;
border-radius:10px;
transition:.3s;

}

.button:hover{

background:#ffc107;
transform:scale(1.05);

}

/* ===== Main Container ===== */

.container{

width:92%;
max-width:1300px;
margin:auto;

}

/* ===== Cards ===== */

.card{

background:white;
color:black;
margin:30px 0;
padding:25px;
border-radius:15px;
box-shadow:0 0 20px rgba(0,0,0,.4);

}

.card h2{

color:#145a32;
margin-bottom:15px;

}

/* ===== Grid ===== */

.video-grid{

display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;

}

.video{

background:white;
color:black;
border-radius:15px;
overflow:hidden;
transition:.35s;
box-shadow:0 0 20px rgba(0,0,0,.35);

}

.video:hover{

transform:translateY(-8px);
box-shadow:0 0 25px lime;

}

.video img{

width:100%;
display:block;

}

.video h3{

padding:15px;

}

.video p{

padding:0 15px 15px;

}

.video a{

display:block;
padding:14px;
background:#ff0000;
color:white;
text-decoration:none;
text-align:center;
font-weight:bold;

}

.video a:hover{

background:#cc0000;

}

/* ===== Crosshair Cards ===== */

.crosshair-box{

background:black;
padding:35px;
display:flex;
justify-content:center;
align-items:center;

}

.crosshair-box img{

width:120px;
height:120px;
object-fit:contain;

}

.download-btn{

display:block;
background:#00b050;
color:white;
text-decoration:none;
padding:14px;
text-align:center;
font-weight:bold;
transition:.3s;

}

.download-btn:hover{

background:#008f3b;

}

.best{

border:4px solid gold;
box-shadow:0 0 25px gold;

}

.best h3{

color:gold;

}

/* ===== Footer ===== */

footer{

margin-top:40px;
padding:25px;
background:#0b3d16;
text-align:center;
font-size:18px;

}

</style>

</head>

<body>

<header>

🎮 Saad Bloxd Website

</header>

<nav>

<a href="#">🏠 Home</a>

<a href="#videos">🎥 Videos</a>

<a href="#music">🎵 Music</a>

<a href="#crosshair">🎯 Crosshairs</a>

<a href="https://bloxd.io" target="_blank">🎮 Play Bloxd.io</a>

</nav>

<section class="hero">

<h1>Welcome!</h1>

<p>

Everything about Bloxd.io, my YouTube channel, favorite music and crosshairs.

</p>

<a class="button"

href="https://bloxd.io"

target="_blank">

▶ Play Bloxd.io

</a>

</section>

<div class="container">
<!-- ================= ABOUT ================= -->

<div class="card">

<h2>📺 My YouTube Channel</h2>

<p>
Welcome to my Bloxd.io channel where I upload Bedwars, Bridging,
Texture Packs, Crosshairs, ASMR and much more!
</p>

<br>

<a class="button"
href="https://youtube.com/@Saad_Bloxd_YT3"
target="_blank">

🔴 Subscribe Now

</a>

</div>

<!-- ================= DISCORD ================= -->

<div class="card">

<h2>💬 Discord</h2>

<p>

Want to talk with me?

</p>

<br>

<h2 style="color:#5865F2;">

saadisonline_

</h2>

</div>

<!-- ================= HOW TO PLAY ================= -->

<div class="card">

<h2>🎮 How To Play Bloxd.io</h2>

<p>

1️⃣ Open Bloxd.io

<br><br>

2️⃣ Choose your favorite game mode.

<br><br>

3️⃣ Practice Bridging.

<br><br>

4️⃣ Defeat enemies.

<br><br>

5️⃣ Become a Bloxd Legend.

</p>

<br>

<a class="button"

href="https://bloxd.io"

target="_blank">

🎮 Play Now

</a>

</div>

<!-- ================= TOP VIDEOS ================= -->

<div id="videos"></div>

<h1 style="text-align:center;margin:50px 0;">

🔥 My Top Videos

</h1>

<div class="video-grid">

<div class="video">

<img src="https://iili.io/CSSbXYN.png">

<h3>Top 3 Bloxd.io T-Packs</h3>

<p>Best texture packs for more FPS.</p>

<a href="https://www.youtube.com/watch?v=TBI03pJbXks"

target="_blank">

▶ Watch

</a>

</div>

<div class="video">

<img src="https://iili.io/CSSyK2R.png">

<h3>Best Bloxd.io Bridging Server</h3>

<p>Practice your bridge faster.</p>

<a href="https://www.youtube.com/watch?v=sxrhAhMoOfI"

target="_blank">

▶ Watch

</a>

</div>

<div class="video">

<img src="https://iili.io/CSUdCcG.png">

<h3>Bedwars Against YouTubers</h3>

<p>Epic PvP battles.</p>

<a href="https://www.youtube.com/watch?v=XCsj_I730gw"

target="_blank">

▶ Watch

</a>

</div>

<div class="video">

<img src="https://iili.io/CSU37vj.png">

<h3>Bloxd.io Bedwars ASMR</h3>

<p>Relaxing Bedwars gameplay.</p>

<a href="https://www.youtube.com/watch?v=biOsa8ToOZM"

target="_blank">

▶ Watch

</a>

</div>

<div class="video">

<img src="https://iili.io/CSU9Gtt.png">

<h3>2 Player Obby with Ljmited</h3>

<p>Fun Obby challenge.</p>

<a href="https://www.youtube.com/watch?v=Eqnfmf3UW64"

target="_blank">

▶ Watch

</a>

</div>

<div class="video">

<img src="https://iili.io/CSU2gmQ.png">

<h3>50 Subscribers T-Pack</h3>

<p>Special subscriber release.</p>

<a href="https://www.youtube.com/watch?v=X09gz8hggT4"

target="_blank">

▶ Watch

</a>

</div>

</div>

<!-- ================= MUSIC ================= -->

<div id="music"></div>

<h1 style="text-align:center;margin:60px 0;">

🎵 Best NCS Music

</h1>

<div class="video-grid">

<div class="video">

<img src="https://img.youtube.com/vi/yJg-Y5byMMw/hqdefault.jpg">

<h3>Mortals</h3>

<p>Perfect for Bedwars & PvP.</p>

<a href="https://www.youtube.com/watch?v=yJg-Y5byMMw"

target="_blank">

🎧 Listen

</a>

</div>

<div class="video">

<img src="https://img.youtube.com/vi/zyXmsVwZqX4/hqdefault.jpg">

<h3>Why We Lose</h3>

<p>One of the best gaming songs.</p>

<a href="https://www.youtube.com/watch?v=zyXmsVwZqX4"

target="_blank">

🎧 Listen

</a>

</div>

<div class="video">

<img src="https://img.youtube.com/vi/J2X5mJ3HDYE/hqdefault.jpg">

<h3>Invincible</h3>

<p>Great while bridging.</p>

<a href="https://www.youtube.com/watch?v=J2X5mJ3HDYE"

target="_blank">

🎧 Listen

</a>

</div>

<div class="video">

<img src="https://img.youtube.com/vi/3nQNiWdeH2Q/hqdefault.jpg">

<h3>Heroes Tonight</h3>

<p>Relaxing gameplay music.</p>

<a href="https://www.youtube.com/watch?v=3nQNiWdeH2Q"

target="_blank">

🎧 Listen

</a>

</div>

</div>
<!-- ================= CROSSHAIR SECTION ================= -->

<div id="crosshair"></div>

<h1 style="text-align:center;margin:70px 0;font-size:45px;">
🎯 Saad's Best Crosshairs
</h1>

<p style="text-align:center;font-size:20px;margin-bottom:40px;">
Download the exact crosshairs I use in Bloxd.io!
</p>

<div class="video-grid">

<!-- ================= CROSSHAIR 1 ================= -->

<div class="video crosshair-card">

<div class="crosshair-box">

<img src="https://iili.io/CUuTTJe.png">

</div>

<h3>🎯 Crosshair #1</h3>

<p>

✔ Good for Bedwars

<br>

✔ Clean Visibility

</p>

<a class="download-btn"

href="https://www.mediafire.com/file/w0mb1kbolrd9v0g/c1.txt/file"

target="_blank">

⬇ Download Crosshair

</a>

</div>

<!-- ================= CROSSHAIR 2 ================= -->

<div class="video crosshair-card">

<div class="crosshair-box">

<img src="https://iili.io/CUuTD7e.png">

</div>

<h3>🎯 Crosshair #2</h3>

<p>

✔ Best for Bridging

<br>

✔ Smooth Aim

</p>

<a class="download-btn"

href="https://www.mediafire.com/file/3g7amig9v09968l/c2.txt/file"

target="_blank">

⬇ Download Crosshair

</a>

</div>

<!-- ================= CROSSHAIR 3 ================= -->

<div class="video crosshair-card">

<div class="crosshair-box">

<img src="https://iili.io/CUuucTG.png">

</div>

<h3>🎯 Crosshair #3</h3>

<p>

✔ Great for PvP

<br>

✔ Minimal Design

</p>

<a class="download-btn"

href="https://www.mediafire.com/file/cz33h4nz431r5hz/c3.txt/file"

target="_blank">

⬇ Download Crosshair

</a>

</div>

<!-- ================= CROSSHAIR 4 ================= -->

<div class="video crosshair-card">

<div class="crosshair-box">

<img src="https://iili.io/CUuA2tf.png">

</div>

<h3>🎯 Crosshair #4</h3>

<p>

✔ Balanced

<br>

✔ Great Visibility

</p>

<a class="download-btn"

href="https://www.mediafire.com/file/70d5thsxt1wlonu/c4.txt/file"

target="_blank">

⬇ Download Crosshair

</a>

</div>

<!-- ================= BEST CROSSHAIR ================= -->

<div class="video best">

<div style="
background:black;
padding:15px;
text-align:center;
color:gold;
font-size:24px;
font-weight:bold;">

👑 SAAD'S PICK 👑

</div>

<div class="crosshair-box">

<img src="https://iili.io/qXEaxIV.png">

</div>

<h3 style="color:gold;">

⭐ Best Crosshair ⭐

</h3>

<p>

🔥 The crosshair I currently use!

<br><br>

⭐⭐⭐⭐⭐

<br><br>

Perfect for:

<br>

⚔ PvP

<br>

🛏 Bedwars

<br>

🌉 Bridging

</p>

<a class="download-btn"

href="https://www.mediafire.com/file/zvtpyx30rrnlgg0/c5.txt/file"

target="_blank">

⬇ Download My Crosshair

</a>

</div>

</div>

<br><br>

<div class="card">

<h2 style="text-align:center;color:#145a32;">

💡 Why I Use Crosshair #5

</h2>

<p style="text-align:center;font-size:20px;line-height:35px;">

👑 This is my personal favorite crosshair.

<br><br>

It gives me better visibility during PvP,

helps me bridge more accurately,

and makes Bedwars feel much smoother.

<br><br>

⭐ I highly recommend trying it!

</p>

</div>
<!-- ================= WEBSITE INFO ================= -->

<div class="card">

<h2>👀 Website Visits</h2>

<h1 id="visitor" style="text-align:center;">0</h1>

</div>

<div class="card">

<h2>💡 Bloxd Tip</h2>

<p id="tip" style="text-align:center;font-size:22px;"></p>

</div>

<div class="card">

<h2>🕒 Current Time</h2>

<h1 id="clock" style="text-align:center;"></h1>

</div>

<!-- Scroll To Top -->

<button id="topBtn" onclick="topFunction()">

⬆

</button>

<!-- Falling Blocks -->

<div id="blocks"></div>

<footer>

<h2>🎮 Thanks For Visiting!</h2>

<br>

<p>

Made with ❤️ by <b>Saad</b>

<br><br>

📺 youtube.com/@Saad_Bloxd_YT3

<br>

💬 Discord : saadisonline_

</p>

<br>

© 2026 Saad Bloxd Website

</footer>

<style>

#topBtn{

display:none;
position:fixed;
bottom:25px;
right:25px;
padding:16px;
font-size:22px;
border:none;
border-radius:50%;
background:#ff9800;
color:white;
cursor:pointer;
transition:.3s;
z-index:999;

}

#topBtn:hover{

background:#ffc107;
transform:scale(1.1);

}

#blocks{

position:fixed;
top:0;
left:0;
width:100%;
height:100%;
pointer-events:none;
overflow:hidden;
z-index:-1;

}

.block{

position:absolute;
width:18px;
height:18px;
background:#7CFC00;
animation:fall linear;

}

@keyframes fall{

from{

top:-30px;
transform:rotate(0deg);

}

to{

top:100%;
transform:rotate(360deg);

}

}

/* Click Effect */

.click{

position:absolute;
width:18px;
height:18px;
background:yellow;
border-radius:50%;
pointer-events:none;
animation:clickAnim .6s linear;

}

@keyframes clickAnim{

to{

transform:scale(5);
opacity:0;

}

}

footer{

margin-top:60px;
padding:40px;
background:#0b3d16;
text-align:center;
font-size:18px;

}

</style>

<script>

/* Visitor Counter */

let visits = localStorage.getItem("visits");

if(visits==null){

visits=1;

}else{

visits++;

}

localStorage.setItem("visits",visits);

document.getElementById("visitor").innerHTML=visits;

/* Bloxd Tips */

const tips=[

"🛏 Protect your bed first!",
"⚔ Always carry extra blocks!",
"🌉 Practice bridging every day!",
"💎 Upgrade armor before attacking!",
"🏹 Bow spam can save games!",
"🎯 Use your favorite crosshair!",
"🔥 Don't waste gold early!",
"🚀 Rush smart, not fast!"

];

document.getElementById("tip").innerHTML=

tips[Math.floor(Math.random()*tips.length)];

/* Live Clock */

setInterval(function(){

document.getElementById("clock").innerHTML=

new Date().toLocaleTimeString();

},1000);

/* Scroll Button */

const topBtn=document.getElementById("topBtn");

window.onscroll=function(){

topBtn.style.display=

window.scrollY>300?"block":"none";

}

function topFunction(){

window.scrollTo({

top:0,

behavior:"smooth"

});

}

/* Falling Blocks */

const blocks=document.getElementById("blocks");

setInterval(function(){

let block=document.createElement("div");

block.className="block";

block.style.left=Math.random()*window.innerWidth+"px";

block.style.animationDuration=(Math.random()*3+2)+"s";

blocks.appendChild(block);

setTimeout(function(){

block.remove();

},5000);

},250);

/* Click Effect (Only on Click) */

document.addEventListener("click",function(e){

let c=document.createElement("div");

c.className="click";

c.style.left=(e.pageX-9)+"px";

c.style.top=(e.pageY-9)+"px";

document.body.appendChild(c);

setTimeout(function(){

c.remove();

},600);

});

</script>

</div>

</body>
</html>
