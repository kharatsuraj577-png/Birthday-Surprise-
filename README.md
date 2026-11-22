
<!DOCTYPE html>
<html lang="mr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Pratuu ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Devanagari:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: 'Noto Sans Devanagari', sans-serif;
  background: linear-gradient(150deg,#fff0f6,#f4eaff,#ffe5ef);
  color: #813052;
  text-align: center;
  overflow-x: hidden;
}

section {
  margin: 25px 14px;
  padding: 28px 18px;
  border-radius: 25px;
  background: rgba(255,255,255,.72);
  box-shadow: 0 8px 28px rgba(180,70,130,.13);
}

.hero {
  min-height: 85vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: linear-gradient(145deg,#ffd8e9,#eadcff,#fff1f6);
  margin: 0;
  border-radius: 0 0 35px 35px;
  padding: 35px 20px;
}

.hero-heart {
  font-size: 65px;
  animation: beat 1.3s infinite;
}

.hero h1 {
  font-size: 34px;
  line-height: 1.6;
  color: #a52d69;
}

.hero p {
  font-size: 17px;
  line-height: 1.9;
}

.small-note {
  font-size: 13px;
  opacity: .8;
}

h2 {
  color: #a52d69;
  font-size: 24px;
  line-height: 1.6;
}

p {
  font-size: 16px;
  line-height: 1.9;
}

.count-number {
  font-size: 35px;
  font-weight: 800;
  color: #d13d83;
}

.gallery {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
  margin-top: 20px;
}

.gallery img {
  width: 100%;
  height: 210px;
  object-fit: cover;
  border-radius: 17px;
  box-shadow: 0 5px 15px #e7b5d0;
}

.photo-caption {
  font-size: 13px;
  margin-top: 5px;
}

.letter {
  text-align: left;
  padding: 23px 18px;
  background: #fff9fc;
  border-radius: 18px;
  line-height: 2;
}

.letter p {
  margin-bottom: 16px;
}

.signature {
  text-align: right;
  font-weight: bold;
  font-size: 19px;
}

button {
  font-family: inherit;
  border: none;
  border-radius: 30px;
  padding: 14px 23px;
  background: linear-gradient(120deg,#ff5b9b,#bd65d9);
  color: white;
  font-size: 16px;
  font-weight: bold;
  box-shadow: 0 5px 15px #e7a4c9;
  cursor: pointer;
  margin: 12px 0;
}

button:active {
  transform: scale(.96);
}

.hidden {
  display: none !important;
}

.surprise-card {
  margin-top: 22px;
  padding: 20px 13px;
  border-radius: 20px;
  background: #fff5fa;
  animation: appear 1s ease;
}

.big-heart {
  font-size: 65px;
  animation: beat 1s infinite;
}

.cake-button {
  background: transparent;
  box-shadow: none;
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 15px auto;
  color: #a52d69;
}

.cake-emoji {
  font-size: 100px;
  animation: bounce 1.5s infinite;
}

.cake-hint {
  font-size: 14px;
}

.final-message {
  padding: 20px 10px;
  border-radius: 18px;
  background: #fff3f9;
  animation: appear 1s ease;
}

.footer {
  padding: 30px 15px 45px;
  font-size: 15px;
}

.particle {
  position: fixed;
  z-index: 9999;
  pointer-events: none;
  top: 100vh;
  left: var(--left);
  font-size: 25px;
  animation: fly var(--duration) ease-out forwards;
}

@keyframes beat {
  0%,100% { transform: scale(1); }
  50% { transform: scale(1.2); }
}

@keyframes bounce {
  0%,100% { transform: translateY(0) rotate(-3deg); }
  50% { transform: translateY(-12px) rotate(3deg); }
}

@keyframes appear {
  from { opacity: 0; transform: translateY(20px) scale(.95); }
  to { opacity: 1; transform: translateY(0) scale(1); }
}

@keyframes fly {
  to {
    transform: translateY(-120vh) translateX(var(--drift)) rotate(360deg);
    opacity: 0;
  }
}
</style>
</head>

<body>

<!-- WELCOME -->
<header class="hero">
  <div class="hero-heart">💗</div>
  <h1>अगं माझ्या बाळा… 🥹</h1>
  <p>
    तुझ्यासाठी काहीतरी खास आहे बघ! 😘<br>
    आज फक्त तुझाच दिवस आहे, माझ्या राणी!
  </p>
  <p class="small-note">A little surprise made with lots of love ❤️</p>
  <button onclick="goTo('countdown')">चला बघूया… 💕</button>
</header>

<!-- COUNTDOWN -->
<section id="countdown">
  <h2>तुझ्या खास दिवसाची उलटी गणती 🎂</h2>
  <p>माझ्या प्रातूचा वाढदिवस येतोय! ❤️</p>
  <div class="count-number" id="timer">Loading...</div>
  <p>२२ डिसेंबर २०२६ 🥹</p>
</section>

<!-- PHOTO GALLERY -->
<section>
  <h2>माझ्या आवडत्या चार फोटोंमधली तू… 😘</h2>
  <p>प्रत्येक फोटोमध्ये माझं आवडतं जग दिसतं. ❤️</p>

  <div class="gallery">
    <div>
      <img src="Snapchat-1576273468.jpg" alt="Pratuu photo 1">
      <div class="photo-caption">माझं सुंदर हसू 💗</div>
    </div>

    <div>
      <img src="Snapchat-543809548.jpg" alt="Pratuu photo 2">
      <div class="photo-caption">माझी लाडकी 🥹</div>
    </div>

    <div>
      <img src="Snapchat-1632423022.jpg" alt="Pratuu photo 3">
      <div class="photo-caption">माझी राणी 👑</div>
    </div>

    <div>
      <img src="Snapchat-2018473043.jpg" alt="Pratuu photo 4">
      <div class="photo-caption">माझं छोटंसं जग ❤️</div>
    </div>
  </div>
</section>

<!-- LOVE LETTER -->
<section>
  <h2>माझ्या बाळासाठी एक पत्र… 💌</h2>
  <p>मनातलं थोडंसं… 🥹</p>

  <div class="letter">
    <p>बाळा, ऐक ना… एक सांगू? 🥹</p>

    <p>
      माझं तुझ्यावर किती प्रेम आहे, ते मी तुला
      शब्दांत सांगू शकत नाही. पण जेवढं काही आहे,
      ते सगळं तुझ्यावरच आहे आणि कायमस्वरूपी राहणार.
    </p>

    <p>
      मी प्रॉमिस देतो तुला, मी तुला कधीच Hurt
      करणार नाही. फक्त माझी एकच इच्छा आहे,
      तू मला कधीच एकटं सोडू नकोस.
    </p>

    <p>
      तुला खूप सुखी ठेवण्यासाठी माझ्याकडून
      जेवढं होईल तेवढं करण्याचा मी नेहमी प्रयत्न करेन.
      काय माझं नशीब, देवाने तुला माझ्यासोबत जोडलं! ❤️
    </p>

    <p>
      त्या देवाकडे पण माझी एकच मागणी आहे…
      जसं आपल्याला जोडलं, तसंच शेवटपर्यंत
      आपल्याला एकमेकांसोबत ठेव. 🥹
    </p>

    <p>
      आज मी खूप खुश आहे, कारण आज माझ्या
      लाडक्या बायकोचा Birthday आहे! 😘
    </p>

    <p>
      आणि शेवटी परत एकदा माझ्या बायकोला
      माझ्याकडून वाढदिवसाच्या खूप खूप शुभेच्छा!
      तू कायम खुश राहा. 😘🩷
    </p>

    <h3 style="text-align:center;color:#d63384">
      आणि हो… 😅
    </h3>

    <p style="text-align:center;font-weight:bold;color:#d63384">
      असाच माझ्यासोबत भांडत रहा! 😅😘
    </p>

    <div class="signature">फक्त तुझाच… ❤️</div>
  </div>
</section>

<!-- SECRET SURPRISE -->
<section>
  <div style="font-size:50px">🦋</div>
  <h2>बाळा, तुझ्यासाठी एक छोटंसं Surprise! ❤️</h2>
  <p>माझ्यासाठी एकदा डोळे बंद कर ना… 🥹</p>

  <button id="secretBtn">इथे क्लिक कर माझ्या बाळा 💗</button>

  <div id="secretMessage" class="surprise-card hidden">
    <div class="big-heart">💖</div>
    <h2>आता डोळे उघड! 😘</h2>
    <p>
      तुझ्यासाठी माझं संपूर्ण जग इथे आहे…
      आणि त्या जगातली सर्वात सुंदर गोष्ट म्हणजे तू! 🥹
    </p>
    <h3>तू आहेस म्हणून माझं जग सुंदर आहे! ❤️</h3>
    <p>खूप खूप प्रेम करतो तुझ्यावर, माझ्या बायको! 😘🩷</p>
    <p>Forever Mine ♾️</p>
  </div>
</section>

<!-- BIRTHDAY CAKE -->
<section>
  <h2>आता तुझ्यासाठी अजून एक Surprise! 🎀</h2>
  <p>माझ्या बाळा, हा केक कापशील का? 🥹</p>

  <button class="cake-button" id="cakeBtn">
    <span style="font-size:32px">🕯️</span>
    <span class="cake-emoji">🎂</span>
    <span class="cake-hint">माझ्यावर क्लिक कर ❤️</span>
  </button>

  <div id="birthdayWish" class="final-message hidden">
    <div class="big-heart">🎉💖🎉</div>
    <h2>Happy Birthday Pratuu! 🎂</h2>
    <div style="font-size:35px">🌹🌸🌹</div>
    <p>
      आजचा दिवस तुझ्यासारखाच सुंदर जावो.
      तुझ्या चेहऱ्यावरचं हसू कधीच कमी होऊ नये.
      तुझी प्रत्येक इच्छा पूर्ण होवो.
    </p>
    <h3>खूप खूप प्रेम माझ्या बायको! 😘🩷</h3>
    <p><b>तुझाच… आज, उद्या आणि कायम! ❤️</b></p>
  </div>
</section>

<footer class="footer">
  <div style="font-size:35px">❤️</div>
  <p>Made with endless love, just for you.</p>
  <p><b>Suraj ❤️ Pratuu</b></p>
  <p>Forever & Always ♾️</p>
</footer>

<script>
// COUNTDOWN
function updateCountdown() {
  const birthday = new Date("December 23, 2026 00:00:00").getTime();
  const now = new Date().getTime();
  const distance = birthday - now;
  const timer = document.getElementById("timer");

  if (distance <= 0) {
    timer.textContent = "Happy Birthday! 🎂❤️";
    return;
  }

  const days = Math.floor(distance / (1000 * 60 * 60 * 24));
  const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  const seconds = Math.floor((distance % (1000 * 60)) / 1000);

  timer.textContent =
    days + " दिवस " + hours + " तास " +
    minutes + " मिनिटे " + seconds + " सेकंद";
}

updateCountdown();
setInterval(updateCountdown, 1000);

// SCROLL
function goTo(id) {
  document.getElementById(id).scrollIntoView({
    behavior: "smooth"
  });
}

// FLOATING HEARTS AND FLOWERS
function createParticles(total) {
  const symbols = ["💗","💕","🦋","❤️","🌸","💖","🌹","✨"];

  for (let i = 0; i < total; i++) {
    const item = document.createElement("span");
    item.className = "particle";
    item.textContent = symbols[Math.floor(Math.random() * symbols.length)];

    item.style.setProperty("--left", Math.random() * 100 + "vw");
    item.style.setProperty("--drift", (Math.random() * 160 - 80) + "px");
    item.style.setProperty("--duration", (3 + Math.random() * 3) + "s");

    document.body.appendChild(item);
    setTimeout(() => item.remove(), 6500);
  }
}

// SECRET BUTTON
document.getElementById("secretBtn").addEventListener("click", function() {
  const message = document.getElementById("secretMessage");
  message.classList.remove("hidden");
  this.textContent = "माझं प्रेम फक्त तुझ्यासाठी! ❤️";
  createParticles(28);
  message.scrollIntoView({ behavior: "smooth", block: "center" });
});

// CAKE BUTTON
document.getElementById("cakeBtn").addEventListener("click", function() {
  const wish = document.getElementById("birthdayWish");
  wish.classList.remove("hidden");
  this.querySelector(".cake-hint").textContent = "तुझ्यासाठी खूप सारा प्रेम! ❤️";
  createParticles(55);
  wish.scrollIntoView({ behavior: "smooth", block: "center" });
});
</script>

</body>
</html>
