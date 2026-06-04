<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NVH Repo</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:-apple-system,BlinkMacSystemFont,sans-serif;
}

body{
background:linear-gradient(135deg,#0f0f0f,#1a1a1a);
color:white;
text-align:center;
min-height:100vh;
}

.header{
padding:60px 20px;
}

.logo{
width:120px;
height:120px;
border-radius:28px;
box-shadow:0 0 25px rgba(0,122,255,.4);
}

h1{
margin-top:15px;
font-size:38px;
}

.desc{
color:#bdbdbd;
margin-top:10px;
}

.btn{
display:inline-block;
margin-top:25px;
padding:14px 28px;
background:#007aff;
color:white;
text-decoration:none;
border-radius:14px;
font-weight:bold;
transition:.3s;
}

.btn:hover{
transform:scale(1.05);
}

.card{
max-width:700px;
margin:20px auto;
background:rgba(255,255,255,.05);
backdrop-filter:blur(10px);
padding:20px;
border-radius:20px;
}

.package{
padding:15px;
margin-top:10px;
background:rgba(255,255,255,.05);
border-radius:15px;
}

.footer{
margin-top:40px;
padding:20px;
color:#888;
}
</style>
</head>

<body>

<div class="header">
<img src="logo.png" class="logo">
<h1>NVH Repo</h1>
<p class="desc">Kho ứng dụng & tweak dành cho iOS</p>

<a class="btn"
href="sileo://source/https://nvhrepo.github.io/repo/">
➕ Thêm vào Sileo
</a>
</div>

<div class="card">
<h2>Gói nổi bật</h2>

<div class="package">
<h3>Tweak 1</h3>
<p>Mô tả tweak của bạn.</p>
</div>

<div class="package">
<h3>Tweak 2</h3>
<p>Mô tả tweak của bạn.</p>
</div>

<div class="package">
<h3>Tweak 3</h3>
<p>Mô tả tweak của bạn.</p>
</div>

</div>

<div class="footer">
© 2026 NVH Repo
</div>

</body>
</html>
