# Football
<!DOCTYPE html>
<html lang="so">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AL NASRI FOOTBALL CLUB</title>

<style>
body{
font-family:Arial,sans-serif;
background:#0b4ea2;
margin:0;
padding:0;
color:white;
}

header{
background:#062d63;
padding:20px;
text-align:center;
}

.card{
background:white;
color:black;
margin:15px;
padding:15px;
border-radius:12px;
}

button{
width:100%;
padding:12px;
background:#0b4ea2;
color:white;
border:none;
border-radius:8px;
font-size:18px;
margin-top:5px;
}

.hidden{
display:none;
}

img{
width:100%;
border-radius:10px;
margin-top:10px;
}

footer{
background:#062d63;
padding:15px;
text-align:center;
}
</style>
</head>

<body>

<header>
<h1>🏆 AL NASRI FOOTBALL CLUB</h1>
<p><b>Midnimo • Dadaal • Guul</b></p>
</header>

<div class="card">
<h2>👋 Soo Dhawoow</h2>
<p id="welcome"></p>
</div>

<div class="card">
<h2>⚽ WEEK KA GAMES-KA</h2>

<p>🥇 AL NASRI 🆚 Lama Shaacin Weli</p>
<hr>

<p>🥈 AL NASRI 🆚 Lama Shaacin Weli</p>
<hr>

<p>🥉 AL NASRI 🆚 Lama Shaacin Weli</p>

<p style="color:red;">
📢 Kooxaha kale wali lama shaacin.
</p>
</div>

<div class="card">
<h2>🏆 NATIIJOYINKA CIYAARAHA</h2>

<p>✅ AL NASRI 🆚 Lama Shaacin</p>
<p>✅ AL NASRI 🆚 Lama Shaacin</p>
<p>🤝 AL NASRI 🆚 Lama Shaacin</p>

</div>

<div class="card">

<button onclick="showPhotos()">
📸 SAWIRADA KOOXDA
</button>

<div id="photos" class="hidden">

<img src="logo.jpg">

<img src="team.jpg">

</div>

</div>

<div class="card">

<button onclick="showPlayers()">
👥 LIISKA CIYAARTOYDA
</button>

<div id="players" class="hidden">

<p>1. Xasan GK</p>
<p>2. Xasan C/ GK</p>
<p>3. Maxamed CB</p>
<p>4. C/laahi CB</p>
<p>5. Abuubakar C/ RB</p>
<p>6. Ibraahim LB</p>
<p>7. Cabaz Özil DMF</p>
<p>8. C/Raxmaan AMF</p>
<p>9. Hilowle CF/SS</p>
<p>10. Xuseen AMF</p>
<p>11. Figsane CMF</p>
<p>12. Jestoole RWF</p>
<p>13. Maxamed Dinho LWF</p>
<p>14. Abuu Bkr CF/SS/AMF</p>
<p>15. C/Rammaan DMF</p>
<p>16. Da'uud RWF</p>
<p>17. C/Xamid CMF</p>
<p>18. Binyamin LWF</p>
<p>19. Xamza CMF</p>
<p>20. Braahim CB</p>

</div>

</div>

<div class="card">
<h2>🚑 DHAAWACYADA</h2>
<p>✅ Waqtigan ma jiro ciyaaryahan dhaawac ah.</p>
</div>

<div class="card">
<h2>📢 WARKA KOOXDA</h2>

<p>🔔 OGEYSIIS OGEYSIIS 🔔</p>

<p>
Waxa ciyaartoyda kooxda la ogeysiinayaa in maalinta uu roob imaado wax ma jiro,
haddii uusan imanna uu jiro Insha Allah.
</p>

<p>
⏰ Waqtiga Garoonka: 4:20 PM - 4:25 PM
</p>

</div>

<div class="card">
<h2>📞 CONTACT US</h2>

<p>📱 +252 689008743</p>

<p>Kala xiriir maamulka kooxda.</p>

</div>

<footer>
🏆 AL NASRI FOOTBALL CLUB
</footer>

<script>

let name = prompt("Geli Magacaaga");

document.getElementById("welcome").innerHTML =
"Ku soo dhawoow <b>" + name + "</b> ⚽";

function showPhotos(){
document.getElementById("photos").classList.toggle("hidden");
}

function showPlayers(){
document.getElementById("players").classList.toggle("hidden");
}

</script>

</body>
</html>
