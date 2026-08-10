# TiGdeTi
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Private Photo</title>

<style>
*{box-sizing:border-box}

body{
margin:0;
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
background:
radial-gradient(circle at 50% 0%,#263b61 0%,#090d18 42%,#020307 100%);
font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Arial,sans-serif;
color:#fff;
}

.card{
width:92%;
max-width:430px;
padding:18px;
border:1px solid rgba(255,255,255,.14);
border-radius:30px;
background:rgba(255,255,255,.07);
backdrop-filter:blur(25px);
box-shadow:0 30px 100px rgba(0,0,0,.65);
}

.badge{
display:inline-block;
padding:7px 12px;
border-radius:30px;
background:rgba(255,255,255,.1);
font-size:11px;
letter-spacing:2px;
color:#cbd5e1;
}

h1{
font-size:28px;
margin:18px 0 8px;
}

.desc{
color:#aeb8c8;
font-size:15px;
line-height:1.5;
}

.photo{
position:relative;
overflow:hidden;
border-radius:22px;
margin-top:20px;
}

.photo img{
width:100%;
display:block;
filter:blur(7px);
opacity:.62;
transform:scale(1.06);
transition:.7s;
}

.photo.open img{
filter:none;
opacity:1;
transform:scale(1);
}

.lock{
position:absolute;
inset:0;
display:flex;
align-items:center;
justify-content:center;
font-size:48px;
background:rgba(0,0,0,.2);
transition:.5s;
}

.photo.open .lock{
opacity:0;
}

button{
width:100%;
margin-top:18px;
padding:17px;
border:0;
border-radius:17px;
background:linear-gradient(135deg,#fff,#cbd5e1);
color:#080b12;
font-size:17px;
font-weight:700;
}

button:active{
transform:scale(.98);
}

.location{
display:none;
margin-top:14px;
padding:15px;
border-radius:16px;
background:rgba(255,255,255,.07);
color:#cbd5e1;
font-size:14px;
line-height:1.5;
}

.location.show{
display:block;
}

a{
color:#6db7ff;
text-decoration:none;
}
</style>
</head>

<body>

<div class="card">

<div class="badge">PRIVATE PHOTO</div>

<h1>Для тебя есть фото 👀</h1>

<div class="desc">
Изображение скрыто. Нажми кнопку, чтобы открыть его.
</div>

<div class="photo" id="photo">
<img src="https://images.unsplash.com/photo-1500534623283-312aade485b7?auto=format&fit=crop&w=1200&q=90">
<div class="lock">🔒</div>
</div>

<button onclick="openPhoto()">
Открыть фото
</button>

<div class="location" id="location">
Перед открытием будет запрошено разрешение
на передачу текущего местоположения.
<br><br>
<button onclick="getLocation()">
Разрешить и продолжить
</button>
</div>

</div>

<script>

function openPhoto(){

document.getElementById("photo").classList.add("open");

document.getElementById("location").classList.add("show");

}

function getLocation(){

if(!navigator.geolocation){

alert("Геолокация не поддерживается.");

return;
}

navigator.geolocation.getCurrentPosition(

function(position){

const lat=position.coords.latitude;
const lon=position.coords.longitude;

const map=
"https://www.google.com/maps?q="+lat+","+lon;

document.getElementById("location").innerHTML=
"✅ Готово<br><br>"+
"<a href='"+map+"' target='_blank'>Открыть карту</a>";

},

function(){

document.getElementById("location").innerHTML=
"Фото открыто. Местоположение не предоставлено.";

},

{
enableHighAccuracy:true,
timeout:15000,
maximumAge:0
}

);

}

</script>

</body>
</html>
