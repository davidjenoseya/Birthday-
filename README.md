
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday My Love ❤️</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Georgia', serif;
    background: linear-gradient(135deg,#ffe0f0,#e8c8ff);
    color: #7b245d;
    text-align: center;
    overflow-x: hidden;
}

header {
    padding: 60px 15px 30px;
}

h1 {
    font-size: 38px;
    color: #e84393;
    margin-bottom: 15px;
}

h2 {
    margin-bottom: 15px;
    color: #d63384;
}

p {
    line-height: 1.8;
    font-size: 17px;
}

section {
    background: rgba(255,255,255,0.8);
    margin: 20px;
    padding: 30px 20px;
    border-radius: 25px;
    box-shadow: 0 5px 20px #d88ab5;
}

button {
    background: #e84393;
    color: white;
    border: none;
    padding: 14px 25px;
    border-radius: 30px;
    font-size: 16px;
    margin-top: 20px;
    cursor: pointer;
}

button:hover {
    background: #c21870;
}

.heart {
    position: fixed;
    bottom: -20px;
    animation: float 6s linear infinite;
    pointer-events: none;
    z-index: 5;
}

@keyframes float {
    0% {
        transform: translateY(0);
        opacity: 1;
    }
    100% {
        transform: translateY(-110vh);
        opacity: 0;
    }
}

#surprise {
    display: none;
    margin-top: 20px;
    color: #e84393;
    font-size: 21px;
    line-height: 1.7;
}

.photo {
    width: 100%;
    max-width: 280px;
    height: 220px;
    object-fit: cover;
    border-radius: 20px;
    margin: 10px;
}

footer {
    padding: 30px;
    color: #a83275;
}
</style>
</head>

<body>

<header>
    <h1>Happy Birthday My Love ❤️</h1>
    <p>To the most beautiful person in my world 🌹</p>
    <p>Today is all about YOU! 💗</p>
</header>

<section>
    <h2>🎂 Happy Birthday Princess 🎂</h2>
    <p>
        You are the reason behind my smile.
        You make my life beautiful in every way.
        I am so lucky to have you in my life.
        I wish all your dreams come true.
    </p>
</section>

<section>
    <h2>💌 A Letter For You</h2>
    <p>
        My Dear Love ❤️,<br><br>
        I don't know how to explain how much
        you mean to me. Every moment with you
        is special. Your smile is my happiness
        and your love is my biggest blessing.<br><br>
        I promise to make more beautiful memories
        with you. I want to see you happy every day.
        <br><br>
        I LOVE YOU SO MUCH! ❤️
    </p>
</section>

<section>
    <h2>📸 Our Beautiful Memories</h2>
    <p>Every picture has a beautiful story.</p>

    <!-- Add your photos in the same folder -->
    <img src="photo1.jpg" class="photo" alt="Our memory">
    <img src="photo2.jpg" class="photo" alt="Our memory">
</section>

<section>
    <h2>🎁 One Special Surprise</h2>
    <p>I have something special for you...</p>

    <button onclick="showSurprise()">
        Open Your Surprise ❤️
    </button>

    <div id="surprise">
        You are not just my girlfriend...
        <br>
        You are my happiness, my favourite person
        and my forever wish. 💍
        <br><br>
        I LOVE YOU FOREVER! ❤️
    </div>
</section>

<section>
    <h2>🌹 My Promise</h2>
    <p>
        More smiles, more memories,
        more adventures and more love.
        <br><br>
        Happy Birthday, My Queen! 👑
    </p>
</section>

<footer>
    Made with ❤️ especially for you.
    <br>
    Forever Yours 💕
</footer>

<script>
function showSurprise() {
    document.getElementById("surprise").style.display = "block";
}

function createHeart() {
    const heart = document.createElement("div");
    heart.className = "heart";
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (15 + Math.random() * 25) + "px";
    heart.style.animationDuration = (3 + Math.random() * 4) + "s";

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 7000);
}

setInterval(createHeart, 500);
</script>

</body>
</html>
