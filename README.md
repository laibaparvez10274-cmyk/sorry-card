<html lang="en">
<head>
<meta charset="UTF-8">
<title>I’m Sorry 💗</title>
<style>
body {
    margin: 0;
    height: 100vh;
    background: linear-gradient(#ffd1dc, #ffe6f0);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-family: "Comic Sans MS", cursive;
    text-align: center;
}

.heart {
    width: 120px;
    height: 120px;
    background: #ff4d6d;
    position: relative;
    transform: rotate(-45deg);
    animation: bounce 1s infinite;
}

.heart::before,
.heart::after {
    content: "";
    width: 120px;
    height: 120px;
    background: #ff4d6d;
    border-radius: 50%;
    position: absolute;
}

.heart::before {
    top: -60px;
    left: 0;
}

.heart::after {
    left: 60px;
    top: 0;
}

@keyframes bounce {
    0% { transform: rotate(-45deg) scale(1); }
    50% { transform: rotate(-45deg) scale(1.15); }
    100% { transform: rotate(-45deg) scale(1); }
}

.message {
    margin-top: 35px;
    font-size: 32px;
    color: #ff2f5b;
    font-weight: bold;
}

.note {
    margin-top: 15px;
    max-width: 320px;
    background: white;
    padding: 15px 20px;
    border-radius: 20px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.15);
    font-size: 16px;
    color: #444;
}

@keyframes float {
    0% { transform: translateY(0); }
    50% { transform: translateY(-6px); }
    100% { transform: translateY(0); }
}

.note {
    animation: float 2s infinite;
}
</style>
</head>

<body>

<div class="heart"></div>

<div class="message">I’m Sorry 🥺</div>

<div class="note">
I know I made a mistake, but my heart never meant to hurt you.  
You mean so much to me, and I promise to do better.  
Please forgive me 💗
</div>

</body>
</html>
