<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sazol Smart Card</title>

<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"/>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1200') no-repeat center center/cover;
overflow:hidden;
}

body::before{
content:'';
position:absolute;
width:100%;
height:100%;
background:rgba(0,0,0,0.65);
backdrop-filter:blur(8px);
}

.card{
position:relative;
width:350px;
padding:30px;
border-radius:25px;
background:rgba(255,255,255,0.08);
backdrop-filter:blur(15px);
border:1px solid rgba(255,255,255,0.2);
text-align:center;
color:white;
animation:float 4s ease-in-out infinite;
box-shadow:0 0 30px rgba(0,0,0,0.5);
}

@keyframes float{
0%{transform:translateY(0px);}
50%{transform:translateY(-10px);}
100%{transform:translateY(0px);}
}

.profile{
width:120px;
height:120px;
border-radius:50%;
border:4px solid white;
object-fit:cover;
margin-bottom:15px;
box-shadow:0 0 25px rgba(255,255,255,0.4);
}

h1{
font-size:28px;
margin-bottom:5px;
}

p{
opacity:0.8;
margin-bottom:25px;
letter-spacing:2px;
}

.socials a{
display:flex;
align-items:center;
justify-content:center;
gap:10px;
margin:12px 0;
padding:14px;
border-radius:15px;
text-decoration:none;
color:white;
font-size:18px;
font-weight:bold;
transition:0.4s;
background:rgba(255,255,255,0.08);
}

.socials a:hover{
transform:scale(1.05);
box-shadow:0 0 20px white;
}

.facebook:hover{
background:#1877f2;
}

.whatsapp:hover{
background:#25d366;
}

.instagram:hover{
background:#e1306c;
}

.tiktok:hover{
background:#000;
}

.email:hover{
background:#ff4444;
}

.qr{
margin-top:20px;
font-size:14px;
opacity:0.8;
}

</style>
</head>

<body>

<div class="card">

<img class="profile"
src="https://i.imgur.com/2DhmtJ4.jpeg">

<h1>SAZOL KUMAR</h1>
<p>TRAVELLER</p>

<div class="socials">

<a class="facebook"
href="https://facebook.com/sazol.raj1"
target="_blank">
<i class="fab fa-facebook-f"></i>
Facebook
</a>

<a class="whatsapp"
href="https://wa.me/8801718929840"
target="_blank">
<i class="fab fa-whatsapp"></i>
WhatsApp
</a>

<a class="instagram"
href="https://instagram.com/sazol_mohonta_"
target="_blank">
<i class="fab fa-instagram"></i>
Instagram
</a>

<a class="tiktok"
href="https://tiktok.com/sazol_mohonta_"
target="_blank">
<i class="fab fa-tiktok"></i>
TikTok
</a>

<a class="email"
href="mailto:sazolkumarmohonta@gmail.com">
<i class="fas fa-envelope"></i>
Email
</a>

</div>

<div class="qr">
SCAN QR • CONNECT • EXPLORE
</div>

</div>

</body>
</html>