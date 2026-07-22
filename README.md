# Vermietungswagen
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Premium Wohnwagenvermietung</title>

<link href="https://cdn.jsdelivr.net/npm/fullcalendar@6.1.15/index.global.min.css" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:Arial,sans-serif;background:#f5f5f5;color:#333;}
header{
background:url("https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1600&q=80") center/cover;
height:70vh;
display:flex;
justify-content:center;
align-items:center;
color:white;
text-align:center;
}
header div{
background:rgba(0,0,0,.5);
padding:30px;
border-radius:15px;
}
.btn{
display:inline-block;
margin-top:20px;
background:#2ecc71;
padding:14px 30px;
border-radius:8px;
color:white;
text-decoration:none;
font-weight:bold;
}
section{
max-width:1200px;
margin:auto;
padding:60px 20px;
}
h2{
margin-bottom:25px;
text-align:center;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:220px;
object-fit:cover;
border-radius:10px;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.box{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.status{
display:flex;
justify-content:center;
margin:20px 0;
}

.available{
background:#2ecc71;
color:white;
padding:15px 30px;
border-radius:8px;
font-size:20px;
font-weight:bold;
}

form{
display:grid;
gap:15px;
max-width:700px;
margin:auto;
}

input,textarea{
padding:15px;
border:1px solid #ccc;
border-radius:8px;
font-size:16px;
}

button{
padding:15px;
border:none;
background:#2ecc71;
color:white;
font-size:18px;
border-radius:8px;
cursor:pointer;
}

footer{
background:#222;
color:white;
text-align:center;
padding:30px;
margin-top:50px;
}
</style>
</head>

<body>

<header>
<div>
<h1>Premium Wohnwagenvermietung</h1>
<p>Dein Urlaub beginnt hier.</p>
<a class="btn" href="#anfrage">Jetzt anfragen</a>
</div>
</header>

<section>

</div>

</section>

<section>

<h2>Ausstattung</h2>

<div class="features">

<div class="box">
<h3>2 Schlafplätze</h3>
<p>Ideal für Familien.</p>
</div>

<div class="box">
<h3>Küche</h3>
<p>Kühlschrank, Herd und Spüle.</p>
</div>


<div class="box">
<h3>Markise</h3>
<p>Großer Außenbereich.</p>
</div>

</div>

</section>

<section>

<h2>Verfügbarkeit</h2>

<div class="status">
<div class="available">
🟢 Aktuell verfügbar
</div>
</div>

<div id="calendar"></div>

</section>

<section id="anfrage">

<h2>Online-Anfrage</h2>

<form>

<input type="text" placeholder="Name" required>

<input type="email" placeholder="E-Mail" required>

<input type="date" required>

<input type="date" required>

<textarea rows="5" placeholder="Nachricht"></textarea>

<button>Anfrage senden</button>

</form>

</section>

<footer>

© 2026 Premium Wohnwagenvermietung
