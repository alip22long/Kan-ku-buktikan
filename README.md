
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Untuk Putry ❤️</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:linear-gradient(135deg,#ff9a9e,#fad0c4);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
    padding:20px;
    overflow-x:hidden;
}

.container{
    width:90%;
    max-width:420px;
    padding:30px;
    background:rgba(255,255,255,0.18);
    border-radius:25px;
    backdrop-filter:blur(10px);
    box-shadow:0 0 20px rgba(255,255,255,0.4);
}

h1{
    font-size:28px;
    margin-bottom:15px;
}

p{
    font-size:18px;
    line-height:1.6;
    margin-bottom:25px;
}

button{
    padding:15px 25px;
    border:none;
    border-radius:20px;
    font-size:18px;
    cursor:pointer;
    background:white;
    color:#ff4b7d;
    font-weight:bold;
    transition:0.3s;
}

button:hover{
    transform:scale(1.05);
}

.photo{
    display:none;
    width:100%;
    border-radius:20px;
    margin-top:20px;
    box-shadow:0 0 15px rgba(255,255,255,0.6);
    animation:fadeIn 1s ease;
}

@keyframes fadeIn{
    from{opacity:0; transform:translateY(20px);}
    to{opacity:1; transform:translateY(0);}
}

.heart{
    position:fixed;
    font-size:24px;
    animation:fall 6s linear infinite;
    opacity:0.7;
}

@keyframes fall{
    0%{transform:translateY(-100px);}
    100%{transform:translateY(110vh);}
}
</style>
</head>

<body>

<audio autoplay loop>
    <source src="romantic.mp3" type="audio/mpeg">
</audio>

<div class="heart" style="left:10%">❤️</div>
<div class="heart" style="left:30%;animation-delay:1s;">💖</div>
<div class="heart" style="left:60%;animation-delay:2s;">💕</div>
<div class="heart" style="left:80%;animation-delay:3s;">💘</div>

<div class="container">
    <h1>Untuk Putry Nurhanna Lufya binti Radim Amsaya ❤️</h1>

    <p>
        Sejak hadirnya awak dalam hidup saya, semuanya terasa lebih indah.
        Setiap senyuman awak adalah kebahagiaan saya.
        <br><br>
        <b>Saya sayang awak sepenuh hati 💖</b>
    </p>

    <button onclick="showLove()">Klik sini sayang 💌</button>

    <img id="photo1" class="photo" src="IMG-20260325-WA0065.jpg" alt="gambar pertama">
    <img id="photo2" class="photo" src="IMG-20260325-WA0067.jpg" alt="gambar kedua">
</div>

<script>
function showLove(){
    document.getElementById("photo1").style.display="block";
    document.getElementById("photo2").style.display="block";
}

</body>
