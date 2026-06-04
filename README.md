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
    font-family:Arial,sans-serif;
}

body{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#0f172a,#1e293b,#2563eb);
    color:white;
}

.card{
    text-align:center;
    backdrop-filter:blur(15px);
    background:rgba(255,255,255,.08);
    padding:40px;
    border-radius:25px;
    width:90%;
    max-width:420px;
    box-shadow:0 0 30px rgba(0,0,0,.4);
}

.avatar{
    width:130px;
    height:130px;
    border-radius:50%;
    border:4px solid #3b82f6;
    margin-bottom:15px;
}

h1{
    margin-bottom:10px;
}

p{
    color:#d1d5db;
    margin-bottom:20px;
}

.btn{
    display:inline-block;
    padding:12px 30px;
    background:#3b82f6;
    color:white;
    text-decoration:none;
    border-radius:12px;
    transition:.3s;
}

.btn:hover{
    transform:scale(1.05);
}
</style>
</head>

<body>

<div class="card">
    <img class="avatar" src="https://avatars.githubusercontent.com/u/9919?v=4">
    <h1>NVH REPO</h1>
    <p>Website cá nhân được host bằng GitHub Pages</p>

    <a class="btn" href="https://github.com" target="_blank">
        GitHub
    </a>
</div>

</body>
</html>
