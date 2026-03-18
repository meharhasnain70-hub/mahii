<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Eid Mubarak</title>

<style>
body {
    margin: 0;
    padding: 0;
    background: linear-gradient(to top, #0f2027, #203a43, #2c5364);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
    font-family: Arial, sans-serif;
}

h1 {
    font-size: 60px;
    color: #fff;
    text-align: center;
    animation: glow 2s infinite alternate;
}

@keyframes glow {
    from {
        text-shadow: 0 0 10px #fff, 0 0 20px #00ffcc;
    }
    to {
        text-shadow: 0 0 20px #ffcc00, 0 0 30px #ff6600;
    }
}

/* Moon */
.moon {
    position: absolute;
    width: 120px;
    height: 120px;
    background: #fff;
    border-radius: 50%;
    top: 50px;
    right: 100px;
    box-shadow: 0 0 20px #fff;
}

/* Stars */
.star {
    position: absolute;
    width: 3px;
    height: 3px;
    background: white;
    animation: blink 1.5s infinite;
}

@keyframes blink {
    0%, 100% {opacity: 0;}
    50% {opacity: 1;}
}
</style>
</head>

<body>

<div class="moon"></div>

<h1>Eid Mubarak 🌙</h1>

<!-- Stars -->
<div class="star" style="top:20%; left:30%;"></div>
<div class="star" style="top:40%; left:70%;"></div>
<div class="star" style="top:60%; left:20%;"></div>
<div class="star" style="top:80%; left:50%;"></div>

</body>
</html>
