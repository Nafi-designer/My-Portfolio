

................HTML.............



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>My first portfolio</title>
</head>
<body>
 <a href="#" class="logo">Nafi</a>

 <div class="card">
    <p>
        <h1>Hi!✌ <br> It's Nafi...</h1>
        <h4>I'm Nafi, a passionate Web Designer & WordPress Developer. I love building clean, user-friendly websites and fixing WordPress issues. I'm currently learning HTML, CSS, JavaScript, and working hard to become a full-stack developer. I believe in creativity, consistency, and continuous learning. Let's build something amazing together!</h4>
     </p>
     <button>Contact me</button>
 </div>
    
</body>
</html>

















..................CSS.................


body{

    background-image: url("Bg.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 100vh;
}

.logo{
    font-size: 100px;
    font-weight: bold;
    color: white;
    text-decoration: none;
}

.card{
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10ox);
    border-radius: 15px;
    padding: 50px;
    max-width: 500px;
    margin: 150px auto;
    text-align: center;
    color: white;
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.25);
    border: 1px solid rgba(255, 255, 255, 0.2);
}

.card h1{
    font-size: 32px;
    margin-bottom: 15px;
}

.card p{
    font-size: 18px;
    margin-bottom: 25px;
    line-height: 1.5;
}

.card button{
    background-color: #00bfff;
    color: white;
    padding: 12px 24px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: 0.3s ease;
}

.card .button:hover{
    background-color: #009acd;
}
