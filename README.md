<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rheinfelde RP</title>

<style>

/* GRUNDSTIL */

html{
scroll-behavior:smooth;
}

body{
margin:0;
font-family:Arial,sans-serif;
background:#1a1a1a;
color:white;
text-align:center;
display:flex;
flex-direction:column;
min-height:100vh;
}

/* HEADER */

header{
background:linear-gradient(90deg,rgba(10,61,98,0.7),rgba(20,90,134,0.7)),
url('meer-bg.jpg') center/cover no-repeat;
padding:100px 20px;
display:flex;
flex-direction:column;
align-items:center;
justify-content:center;
}

header img{
width:150px;
margin-bottom:10px;
}

header h1{
margin:10px 0;
font-size:clamp(28px,6vw,50px);
}

header p{
opacity:0.9;
font-size:18px;
}

/* NAVIGATION */

nav{
background:#111;
padding:15px;
}

nav a{
color:white;
text-decoration:none;
margin:0 20px;
font-weight:bold;
font-size:18px;
transition:0.3s;
}

nav a:hover{
color:#00d4ff;
}

@media (max-width:600px){
nav a{
display:block;
margin:10px 0;
}
}

/* INHALT */

main{
flex:1;
padding:50px 20px;
}

.section{
margin:80px 0;
}

.boxes{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
}

/* BOX */

.box{
background:#2c2c2c;
padding:30px;
max-width:350px;
border-radius:12px;
transition:0.3s;
}

.box:hover{
transform:scale(1.05);
box-shadow:0 0 15px rgba(0,212,255,0.6);
}

/* SERVER STATUS */

.server-status{
background:#1a3d62;
padding:25px;
border-radius:12px;
max-width:350px;
text-align:left;
transition:0.3s;
}

.server-status.online{
border-left:6px solid #00ff88;
}

.server-status.offline{
border-left:6px solid #ff3333;
}

.server-status:hover{
transform:scale(1.05);
box-shadow:0 0 15px rgba(0,212,255,0.6);
}

/* BUTTON */

button,.button{
background:#5865F2;
border:none;
padding:14px 25px;
color:white;
font-size:16px;
border-radius:8px;
cursor:pointer;
margin-top:15px;
transition:0.3s;
text-decoration:none;
display:inline-block;
}

button:hover,.button:hover{
background:#4752c4;
transform:scale(1.05);
}

/* FOOTER */

footer{
background:#0a3d62;
padding:20px;
margin-top:60px;
}

</style>
</head>

<body>

<header>

<img src="logo.png" alt="Rheinfelde RP Logo">

<h1>Rheinfelde RP</h1>

<p>Dein deutscher FiveM Roleplay Server</p>

<button onclick="window.location.href='https://discord.gg/rREEXEza'">
Discord beitreten
</button>

</header>

<nav>

<a href="#start">Start</a>
<a href="#fraktionen">Fraktionen</a>
<a href="#regeln">Regelwerk</a>
<a href="#discord">Discord</a>

</nav>

<main>

<section class="section" id="start">

<h2>Willkommen auf Rheinfelde RP</h2>

<p>Erlebe realistisches Roleplay in der Stadt Rheinfelde.</p>

<div class="boxes">

<div class="box">

<h3>Community</h3>

<p>Tritt unserem Discord bei und starte dein Roleplay Abenteuer.</p>

<button onclick="window.location.href='https://discord.gg/rREEXEza'">
Discord öffnen
</button>

</div>

<div class="server-status online">

<h3>Server Status</h3>

<p>Status: Online</p>

<p>Spieler online: 0 / 64</p>

<p>Ping: 45ms</p>

</div>

</div>

</section>

<section class="section" id="fraktionen">

<h2>Fraktionen</h2>

<p style="font-size:20px">
🚓 Polizei • 🚑 Rettungsdienst • 🚒 Feuerwehr • 🔧 Mechaniker • 💀 Fraktionen
</p>

</section>

<section class="section" id="regeln">

<h2>Server Regelwerk</h2>

<p>Bitte lies unser Regelwerk bevor du auf dem Server spielst.</p>

<div class="box">

<h3>Roleplay Regeln</h3>

<p>
Hier findest du alle wichtigen Regeln für unser Roleplay.
</p>

<a class="button" href="https://discord.gg/rREEXEza" target="_blank">
Regelwerk öffnen
</a>

</div>

</section>

<section class="section" id="discord">

<h2>Discord Server</h2>

<p>Trete unserer Community bei:</p>

<a class="button" href="https://discord.gg/rREEXEza" target="_blank">
Discord öffnen
</a>

</section>

</main>

<footer>

© 2026 Rheinfelde RP

</footer>

</body>
</html>
