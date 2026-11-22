<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Favourite Person ❤️</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;600;700&family=Poppins:wght@300;400;500;600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
 
body {
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #160b29, #4b1c57, #a34c83);
    color: white;
    overflow-x: hidden;
    scroll-behavior: smooth;
}

body::before {
    content: "";
    position: fixed;
    inset: 0;
    background:
        radial-gradient(circle at 20% 20%, #ff9ad533, transparent 35%),
        radial-gradient(circle at 80% 80%, #c084fc33, transparent 35%);
    pointer-events: none;
    z-index: -1;
}

section {
    padding: 70px 20px;
    text-align: center;
}

.hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.small-text {
    letter-spacing: 4px;
    font-size: 12px;
    color: #ffd6f2;
    margin-bottom: 20px;
}

h1 {
    font-family: 'Dancing Script', cursive;
    font-size: clamp(45px, 10vw, 80px);
    color: #ffcae8;
    text-shadow: 0 0 25px #ff7acb77;
}

.hero p {
    max-width: 330px;
    margin: 20px auto;
    line-height: 1.9;
    color: #f6dff5;
}

button {
    padding: 14px 28px;
    border: none;
    border-radius: 50px;
    background: linear-gradient(135deg, #ff83c5, #c084fc);
    color: white;
    font-size: 15px;
    cursor: pointer;
    box-shadow: 0 0 25px #ff83c544;
    transition: 0.3s;
}

button:hover {
    transform: scale(1.06);
}

.heart {
    font-size: 55px;
    animation: heartbeat 1.5s infinite;
    margin-bottom: 20px;
}

@keyframes heartbeat {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.2); }
}

.floating {
    position: fixed;
    bottom: -30px;
    animation: floatUp linear forwards;
    pointer-events: none;
    z-index: 999;
}

@keyframes floatUp {
    to {
        transform: translateY(-110vh) rotate(360deg);
        opacity: 0;
    }
}

.glass {
    background: #ffffff12;
    border: 1px solid #ffffff22;
    backdrop-filter: blur(12px);
    border-radius: 25px;
    padding: 30px 22px;
    max-width: 500px;
    margin: auto;
    box-shadow: 0 10px 40px #00000015;
}

h2 {
    font-family: 'Dancing Script', cursive;
    font-size: 42px;
    color: #ffd1ed;
    margin-bottom: 25px;
}

.countdown {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
}

.time-box {
    background: #ffffff15;
    padding: 18px 12px;
    border-radius: 18px;
    min-width: 70px;
}

.time-box span {
    display: block;
    font-size: 28px;
    font-weight: 600;
    color: #ffc4e6;
}

.time-box small {
    font-size: 10px;
    letter-spacing: 2px;
}

.gallery {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 15px;
    max-width: 500px;
    margin: auto;
}

.photo-card {
    border-radius: 20px;
    overflow: hidden;
    background: #ffffff12;
    border: 1px solid #ffffff22;
    min-height: 220px;
}

.photo-card img {
    width: 100%;
    height: 220px;
    object-fit: cover;
}

.photo-card p {
    padding: 12px;
    font-family: 'Dancing Script', cursive;
    font-size: 22px;
    color: #ffd1ed;
}

.placeholder {
    height: 220px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background: linear-gradient(135deg, #8b3b83, #e17eb3);
    font-size: 45px;
}

.placeholder small {
    font-size: 11px;
    margin-top: 10px;
    letter-spacing: 1px;
}

.letter {
    line-height: 2;
    text-align: left;
    color: #ffeafa;
    font-size: 14px;
}

.letter p {
    margin-bottom: 18px;
}

.signature {
    font-family: 'Dancing Script', cursive;
    font-size: 30px;
    color: #ffcae8;
    text-align: right;
}

.surprise {
    display: none;
    margin-top: 25px;
    animation: appear 1s ease;
}

@keyframes appear {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

.footer {
    padding: 40px 15px;
    color: #eac5e9;
    font-size: 12px;
}

.music-btn {
    position: fixed;
    right: 15px;
    top: 15px;
    z-index: 999;
    padding: 12px;
    border-radius: 50%;
    width: 45px;
    height: 45px;
}

#finalMessage {
    font-family: 'Dancing Script', cursive;
    font-size: 35px;
    color: #ffc5e9;
    line-height: 1.6;
}

</style>
</head>

<body>

<button class="music-btn" onclick="toggleMusic()" id="musicBtn">🎵</button>

<!-- WELCOME -->
<section class="hero">

    <div class="heart">❤️</div>

    <p class="small-text">A LITTLE SOMETHING FOR SOMEONE SPECIAL</p>

    <h1>Hey, Beautiful!</h1>

    <p>
        I made something for you...
        <br>
        A little world filled with love,
        memories and a thousand feelings.
    </p>

    <button onclick="document.getElementById('countdownSection').scrollIntoView({behavior:'smooth'})">
        Open Your Surprise ✨
    </button>

</section>

<!-- COUNTDOWN -->
<section id="countdownSection">

    <div class="glass">

        <p class="small-text">THE MOST SPECIAL DAY</p>

        <h2>Your Birthday ❤️</h2>

        <div class="countdown" id="countdown">

            <div class="time-box">
                <span id="days">00</span>
                <small>DAYS</small>
            </div>

            <div class="time-box">
                <span id="hours">00</span>
                <small>HOURS</small>
            </div>

            <div class="time-box">
                <span id="minutes">00</span>
                <small>MINUTES</small>
            </div>

            <div class="time-box">
                <span id="seconds">00</span>
                <small>SECONDS</small>
            </div>

        </div>

        <p style="margin-top:25px;color:#ffd6f2;">
            Counting every moment until your special day 🎂
        </p>

    </div>

</section>

<!-- GALLERY -->
<section>

    <p class="small-text">MY FAVOURITE LITTLE MOMENTS</p>

    <h2>Your Beautiful Memories 📸</h2>

    <div class="gallery">

        <div class="photo-card">
            <div class="placeholder">
                🌸
                <small>YOUR PHOTO HERE</small>
            </div>
            <p>Your beautiful smile</p>
        </div>

        <div class="photo-card">
            <div class="placeholder">
                🦋
                <small>YOUR PHOTO HERE</small>
            </div>
            <p>My favourite girl</p>
        </div>

        <div class="photo-card">
            <div class="placeholder">
                💗
                <small>YOUR PHOTO HERE</small>
            </div>
            <p>Simply magical</p>
        </div>

        <div class="photo-card">
            <div class="placeholder">
                🌷
                <small>YOUR PHOTO HERE</small>
            </div>
            <p>My pretty princess</p>
        </div>

</div>

<p style="margin-top:25px;color:#f6dff5;font-size:13px;">
    Every picture of you deserves its own little universe. ❤️
</p>

</section>

<!-- LOVE LETTER -->
<section>

    <p class="small-text">WORDS FROM MY HEART</p>

    <h2>A Little Letter For You 💌</h2>

    <div class="glass letter">

        <p>Dear My Favourite Person, ❤️</p>

        <p>
            I don't know how to explain it, but having you in my life
            makes ordinary days feel a little more beautiful.
        </p>

        <p>
            Your smile, your silly talks, your little tantrums,
            the way you make me laugh for absolutely no reason...
            all these little things have become my favourite things.
        </p>

        <p>
            You might not realise how special you are,
            but to me, you are someone I never want to stop
            making smile.
        </p>

        <p>
            On your birthday, I wish you endless happiness,
            beautiful dreams, success and all the love
            your heart can hold.
        </p>

        <p>
            And if I get one wish,
            I wish to be one of the reasons
            behind your beautiful smile. 🥹
        </p>

        <p class="signature">
            Forever your annoying person ❤️
        </p>

    </div>

</section>

<!-- SURPRISE -->
<section>

    <div class="glass">

        <p class="small-text">ONE LAST THING...</p>

        <h2>Are You Ready? 🥹</h2>

        <button onclick="showSurprise()">
            Tap For Your Surprise 🎁
        </button>

        <div class="surprise" id="surprise">

            <p id="finalMessage">
                Happy Birthday,
                My Beautiful Girl! ❤️
            </p>

            <p style="margin-top:20px;line-height:2;color:#ffeafa;">
                You deserve the entire universe
                and every beautiful thing in it.
                <br><br>
                Never forget how precious you are.
                <br>
                Keep smiling, keep shining
                and keep being YOU. 🌙✨
            </p>

            <div style="font-size:50px;margin-top:20px;">
                🎂 💖 🦋 🌷
            </div>

        </div>

    </div>

</section>

<div class="footer">
    Made with love, just for you ❤️
    <br><br>
    A little surprise from someone who cares about you a lot.
</div>

<script>

// BIRTHDAY COUNTDOWN
const birthday = new Date("December 22, 2026 00:00:00").getTime();

function updateCountdown() {

    const now = new Date().getTime();
    const distance = birthday - now;

    if (distance <= 0) {
        document.getElementById("countdown").innerHTML =
        "<h2>HAPPY BIRTHDAY!! 🎂❤️</h2>";
        return;
    }

    const d = Math.floor(distance / (1000 * 60 * 60 * 24));
    const h = Math.floor((distance / (1000 * 60 * 60)) % 24);
    const m = Math.floor((distance / (1000 * 60)) % 60);
    const s = Math.floor((distance / 1000) % 60);

    document.getElementById("days").innerText = d;
    document.getElementById("hours").innerText = h;
    document.getElementById("minutes").innerText = m;
    document.getElementById("seconds").innerText = s;

}

setInterval(updateCountdown, 1000);
updateCountdown();

// FLOATING HEARTS
function createHeart() {

    const heart = document.createElement("div");

    heart.className = "floating";

    const emojis = ["❤️", "💕", "💗", "✨", "🦋", "🌸"];

    heart.innerText = emojis[Math.floor(Math.random() * emojis.length)];

    heart.style.left = Math.random() * 100 + "vw";

    heart.style.fontSize = (15 + Math.random() * 25) + "px";

    heart.style.animationDuration = (4 + Math.random() * 5) + "s";

    document.body.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 9000);

}

setInterval(createHeart, 700);

// SURPRISE
function showSurprise() {

    const surprise = document.getElementById("surprise");

    surprise.style.display = "block";

    for (let i = 0; i < 30; i++) {
        setTimeout(createHeart, i * 100);
    }

    surprise.scrollIntoView({ behavior: "smooth" });

}

// MUSIC BUTTON
function toggleMusic() {

    alert("Add your favourite romantic song here later 🎵❤️");

}

</script>

</body>
</html># Birthday-Surprise-
