
<!DOCTYPE html>
<html lang="mr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>माझ्या बाळासाठी ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Devanagari:wght@400;500;600;700&family=Tiro+Devanagari+Marathi&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
 background:#180e25;color:#fff;
 font-family:'Noto Sans Devanagari',sans-serif;
 overflow-x:hidden;
}
body:before{
 content:"";position:fixed;inset:0;z-index:-1;
 background:
 radial-gradient(circle at 15% 15%,#c34b9155,transparent 38%),
 radial-gradient(circle at 85% 75%,#7750b555,transparent 40%),
 linear-gradient(145deg,#180e25,#402044,#1b102c);
}
section{padding:75px 18px;text-align:center}
.hero{
 min-height:100vh;display:flex;flex-direction:column;
 align-items:center;justify-content:center;padding:25px;
}
.script{font-family:'Tiro Devanagari Marathi',serif}
h1{
 font-family:'Tiro Devanagari Marathi',serif;
 font-size:clamp(38px,9vw,65px);
 color:#ffd0e8;line-height:1.5;
}
h2{
 font-family:'Tiro Devanagari Marathi',serif;
 font-size:36px;color:#ffd0e8;margin-bottom:23px;
}
.eyebrow{
 color:#f2b6d8;font-size:11px;
 letter-spacing:2px;margin-bottom:18px;
}
.hero p{
 max-width:340px;line-height:2;
 color:#f0d9ed;margin:20px 0;
}
.heart{font-size:48px;animation:pulse 1.5s infinite}
@keyframes pulse{50%{transform:scale(1.2)}}
.btn{
 border:1px solid #ffc6e5;
 background:linear-gradient(120deg,#c65d9d,#8156b8);
 color:white;border-radius:40px;padding:14px 24px;
 font-family:inherit;font-size:14px;
 cursor:pointer;box-shadow:0 0 25px #d56eaa44;
}
.glass{
 max-width:540px;margin:auto;padding:28px 20px;
 border:1px solid #ffffff28;border-radius:24px;
 background:#ffffff0d;backdrop-filter:blur(12px);
 box-shadow:0 15px 45px #0003;
}
.countdown{
 display:flex;justify-content:center;gap:9px;flex-wrap:wrap;
}
.time{
 min-width:67px;padding:14px 8px;
 border-radius:15px;background:#ffffff14;
}
.time strong{display:block;font-size:25px;color:#ffd0e9}
.time small{font-size:10px;color:#e6c6e5}
.sub{
 font-size:13px;line-height:2;color:#e8d3e8;
 margin-top:18px;
}
.gallery{
 display:grid;grid-template-columns:1fr 1fr;
 gap:13px;max-width:520px;margin:28px auto;
}
.photo{
 overflow:hidden;border-radius:18px;
 background:#ffffff12;border:1px solid #ffffff25;
}
.photo img{
 display:block;width:100%;height:230px;object-fit:cover;
}
.photo p{
 padding:12px 5px;color:#ffd0e8;
 font-family:'Tiro Devanagari Marathi',serif;
 font-size:16px;
}
.letter{
 text-align:left;line-height:2.1;
 font-size:14px;color:#f4e4f1;
}
.letter p{margin-bottom:16px}
.signature{
 text-align:right;font-size:22px;
 color:#ffc7e7;font-family:'Tiro Devanagari Marathi',serif;
}
#surprise{display:none;margin-top:25px;animation:appear 1s ease}
@keyframes appear{
 from{opacity:0;transform:translateY(20px)}
 to{opacity:1;transform:translateY(0)}
}
#surprise h2{font-size:38px}
#surprise p{line-height:2;color:#f5e1f1;font-size:14px}
.footer{
 padding:40px 15px;text-align:center;
 color:#dfbfdf;font-size:12px;line-height:2;
}
.float{
 position:fixed;bottom:-40px;pointer-events:none;z-index:99;
 animation:up linear forwards;
}
@keyframes up{
 to{transform:translateY(-110vh) rotate(360deg);opacity:0}
}
.divider{height:1px;width:65px;background:#e9a8d4;margin:20px auto}
@media(max-width:380px){
 .photo img{height:185px}
 h2{font-size:31px}
}
</style>
</head>

<body>

<!-- सुरुवात -->
<section class="hero">
 <div class="heart">❤️</div>
 <p class="eyebrow">♡ फक्त माझ्या बाळासाठी ♡</p>
 <h1>अगं माझ्या बाळा…</h1>
 <h2 style="font-size:27px;margin:12px 0">तुझ्यासाठी काहीतरी खास आहे बघ! 😘</h2>
 <p>
  एकदा उघडून तर बघ…<br>
  तुझ्यासाठी खूप काही लपवलंय.<br>
  आणि हो, शेवटपर्यंत नक्की बघायचं हं! 🥹
 </p>
 <button class="btn" onclick="go('birthday')">चल बघूया ❤️</button>
 <p>खाली अजून सरप्राइज आहेत ↓</p>
</section>

<!-- वाढदिवस -->
<section id="birthday">
 <p class="eyebrow">तो खास दिवस...</p>
 <h2>माझ्या बाळाचा वाढदिवस 🎂</h2>
 <div class="glass">
  <p class="sub" style="margin-top:0">तुझ्या खास दिवसाची आतुरतेने वाट पाहतोय...</p>
  <div class="countdown" id="countdown">
   <div class="time"><strong id="days">00</strong><small>दिवस</small></div>
   <div class="time"><strong id="hours">00</strong><small>तास</small></div>
   <div class="time"><strong id="minutes">00</strong><small>मिनिटं</small></div>
   <div class="time"><strong id="seconds">00</strong><small>सेकंद</small></div>
  </div>
  <p class="sub">कारण हा दिवस माझ्यासाठीसुद्धा खूप खास आहे. ❤️</p>
 </div>
</section>

<!-- फोटो -->
<section>
 <p class="eyebrow">माझ्या आवडत्या व्यक्तीचे क्षण</p>
 <h2>माझी सुंदर परी 📸</h2>
 <div class="gallery">
  <div class="photo">
   <img src="Snapchat-1576273468.jpg" alt="तुझा फोटो">
   <p>तुझं गोड हसू ❤️</p>
  </div>
  <div class="photo">
   <img src="Snapchat-543809548.jpg" alt="तुझा फोटो">
   <p>माझी आवडती व्यक्ती 🦋</p>
  </div>
  <div class="photo">
   <img src="Snapchat-1632423022.jpg" alt="तुझा फोटो">
   <p>एकदम परीसारखी 🌸</p>
  </div>
  <div class="photo">
   <img src="Snapchat-2018473043.jpg" alt="तुझा फोटो">
   <p>माझं छोटंसं जग 💗</p>
  </div>
 </div>
 <p class="sub">तुझे फोटो बघताना वेळ कसा जातो कळतच नाही. 🥹</p>
</section>

<!-- प्रेमपत्र -->
<section>
 <p class="eyebrow">मनातल्या काही गोष्टी...</p>
 <h2>माझ्या बाळासाठी एक पत्र 💌</h2>
 <div class="glass letter">
  <p>अगं माझ्या बाळा... ❤️</p>
  <p>
   खरं सांगू का, तुला काय लिहावं हेच कधी कधी समजत नाही.
   कारण तू माझ्यासाठी किती खास आहेस हे शब्दांत सांगणं
   थोडंसं कठीण आहे.
  </p>
  <p>
   तुझं हसणं, तुझं बोलणं, तुझे छोटे छोटे नखरे,
   आणि माझी फिरकी घेण्याची तुझी सवय...
   या सगळ्या गोष्टी मला खूप आवडतात. 😁
  </p>
  <p>
   कधी तू रागावतेस, कधी हसवतेस,
   कधी विनाकारण त्रास देतेस...
   पण तरीही तुझ्याशी बोलल्याशिवाय दिवस पूर्ण झाल्यासारखा वाटत नाही.
  </p>
  <p>
   तुझ्या आयुष्यात खूप आनंद यावा,
   तुझी प्रत्येक इच्छा पूर्ण व्हावी,
   आणि तुझ्या चेहऱ्यावरचं हसू असंच कायम राहावं,
   हीच मनापासून इच्छा आहे.
  </p>
  <p>
   आणि हो, कितीही मोठी झालीस तरी
   अशीच गोड, वेडी आणि खोडकर राहायचं! 😘
  </p>
  <p class="signature">तुझाच एक वेडा ❤️</p>
 </div>
</section>

<!-- गुपित भेट -->
<section>
 <p class="eyebrow">अजून एक गोष्ट बाकी आहे...</p>
 <h2>तुझ्यासाठी एक छोटीशी भेट 🎁</h2>
 <div class="glass">
  <div style="font-size:55px">🎁</div>
  <p class="sub">
   अगं, ही भेट उघडण्याआधी एकदा हसून दाखव बरं! 😁
  </p>
  <button class="btn" onclick="openSurprise()">इथे क्लिक कर बघू 😘</button>

  <div id="surprise">
   <div class="divider"></div>
   <h2>वाढदिवसाच्या खूप खूप शुभेच्छा माझ्या बाळा! ❤️</h2>
   <p>
    अगं वेडे, तुला या जगातलं सगळं सुख मिळावं.
    तुझ्या प्रत्येक स्वप्नाला सुंदर पंख मिळावेत.
    <br><br>
    आयुष्याच्या प्रत्येक वळणावर तुला आनंद भेटावा,
    तुझ्या चेहऱ्यावरचं हसू कधीच कमी होऊ नये.
    <br><br>
    आणि एक गोष्ट लक्षात ठेव...
    तू आहेस तशीच खूप खास आहेस.
    कधी स्वतःची किंमत कमी समजू नकोस.
    <br><br>
    खूप खूप प्रेम माझ्या परी! 🥹😘
   </p>
   <div style="font-size:42px;margin-top:20px">🌷🦋💗🎂</div>
   <p class="signature" style="margin-top:20px">फक्त तुझ्यासाठी ❤️</p>
  </div>
 </div>
</section>

<div class="footer">
 माझ्या बाळासाठी, खूप साऱ्या प्रेमाने ❤️
 <br>
 ही छोटीशी दुनिया फक्त तुझीच आहे. 🦋
</div>

<script>
function go(id){
 document.getElementById(id).scrollIntoView({behavior:"smooth"});
}

const birthday = new Date("December 22, 2026 00:00:00").getTime();

function updateCountdown(){
 const diff = birthday - Date.now();

 if(diff <= 0){
  document.getElementById("countdown").innerHTML =
  "<h2 style='font-size:27px'>वाढदिवसाच्या शुभेच्छा! 🎂❤️</h2>";
  return;
 }

 document.getElementById("days").textContent =
 Math.floor(diff/86400000);
 document.getElementById("hours").textContent =
 Math.floor((diff%86400000)/3600000);
 document.getElementById("minutes").textContent =
 Math.floor((diff%3600000)/60000);
 document.getElementById("seconds").textContent =
 Math.floor((diff%60000)/1000);
}
updateCountdown();
setInterval(updateCountdown,1000);

function floatLove(){
 const el=document.createElement("div");
 const symbols=["❤️","💕","🦋","🌸","✨","💗"];
 el.className="float";
 el.textContent=symbols[Math.floor(Math.random()*symbols.length)];
 el.style.left=Math.random()*100+"vw";
 el.style.fontSize=(17+Math.random()*20)+"px";
 el.style.animationDuration=(5+Math.random()*5)+"s";
 document.body.appendChild(el);
 setTimeout(()=>el.remove(),10000);
}
setInterval(floatLove,850);

function openSurprise(){
 document.getElementById("surprise").style.display="block";
 for(let i=0;i<40;i++){
  setTimeout(floatLove,i*100);
 }
 setTimeout(()=>{
  document.getElementById("surprise").scrollIntoView({
   behavior:"smooth",block:"center"
  });
 },100);
}
</script>

<!-- MY HEART TO YOU ❤️ -->
<section class="my-love-letter">
  <div class="letter-heart">💌</div>

  <h2>माझ्या बाळासाठी… ❤️</h2>
  <p class="letter-subtitle">मनातलं थोडंसं… 🥹</p>

  <div class="letter-paper">
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

    <h3>आणि हो… 😅</h3>
    <p class="last-line">
      असाच माझ्यासोबत भांडत रहा! 😅😘
    </p>

    <div class="signature">
      फक्त तुझाच… ❤️
    </div>
  </div>

  <div class="letter-footer">Forever & Always ♾️</div>
</section>

<style>
.my-love-letter {
  margin: 35px 15px;
  padding: 28px 16px;
  text-align: center;
  border-radius: 28px;
  background: linear-gradient(145deg,#ffe1ed,#eee0ff,#fff0f5);
  box-shadow: 0 8px 30px rgba(190,80,140,.2);
  color: #85264f;
}

.letter-heart {
  font-size: 55px;
  animation: letterBeat 1.4s infinite;
}

.my-love-letter h2 {
  font-size: 27px;
  margin: 12px 0 5px;
}

.letter-subtitle {
  font-size: 15px;
  font-style: italic;
}

.letter-paper {
  margin-top: 25px;
  padding: 25px 19px;
  border-radius: 18px;
  background: rgba(255,255,255,.85);
  box-shadow: 0 5px 18px rgba(120,50,90,.12);
  text-align: left;
  line-height: 2;
}

.letter-paper p {
  font-size: 16px;
  margin-bottom: 17px;
}

.letter-paper h3 {
  text-align: center;
  color: #d63384;
  font-size: 23px;
}

.last-line {
  text-align: center;
  font-size: 19px !important;
  font-weight: bold;
  color: #d63384;
}

.signature {
  text-align: right;
  font-size: 20px;
  font-weight: bold;
  margin-top: 25px;
}

.letter-footer {
  margin-top: 22px;
  font-size: 19px;
  font-style: italic;
  letter-spacing: 2px;
}

@keyframes letterBeat {
  0%,100% { transform: scale(1); }
  50% { transform: scale(1.18); }
}
</style>

<!-- SECRET SURPRISE FOR PRATUU 🥹❤️ -->

<section class="secret-love">
  <div class="secret-icon">🦋</div>

  <h2>बाळा, तुझ्यासाठी एक छोटंसं Surprise! ❤️</h2>

  <p>माझ्यासाठी एकदा डोळे बंद कर ना… 🥹</p>

  <button id="secretLoveBtn">
    इथे क्लिक कर माझ्या बाळा 💗
  </button>

  <div id="secretLoveMessage" hidden>
    <div class="surprise-heart">💖</div>

    <h2>आता डोळे उघड! 😘</h2>

    <p>
      तुझ्यासाठी माझं संपूर्ण जग इथे आहे…
      आणि त्या जगातली सर्वात सुंदर गोष्ट म्हणजे तू! 🥹
    </p>

    <h3>तू आहेस म्हणून माझं जग सुंदर आहे! ❤️</h3>

    <p>खूप खूप प्रेम करतो तुझ्यावर, माझ्या बायको! 😘🩷</p>

    <div class="surprise-end">Forever Mine ♾️</div>
  </div>
</section>

<style>
.secret-love {
  margin: 35px 15px;
  padding: 30px 18px;
  text-align: center;
  border-radius: 28px;
  background: linear-gradient(140deg,#ffe0ed,#e9dcff,#fff0f5);
  color: #92245c;
  box-shadow: 0 8px 28px rgba(180,70,130,.2);
}

.secret-icon {
  font-size: 55px;
  animation: butterflyFloat 2s infinite ease-in-out;
}

.secret-love h2 {
  font-size: 23px;
}

.secret-love p {
  font-size: 16px;
  line-height: 1.8;
}

#secretLoveBtn {
  border: none;
  border-radius: 30px;
  padding: 15px 23px;
  margin: 15px 0;
  background: linear-gradient(120deg,#ff5c9a,#bd69db);
  color: white;
  font-size: 16px;
  font-weight: bold;
  box-shadow: 0 5px 15px #e8a0ca;
  cursor: pointer;
}

#secretLoveMessage {
  margin-top: 25px;
  padding: 22px 12px;
  background: rgba(255,255,255,.75);
  border-radius: 20px;
  animation: revealLove 1.2s ease;
}

#secretLoveMessage[hidden] {
  display: none;
}

.surprise-heart {
  font-size: 65px;
  animation: heartBeat 1s infinite;
}

#secretLoveMessage h3 {
  line-height: 1.7;
  color: #d63384;
}

.surprise-end {
  margin-top: 20px;
  font-size: 20px;
  font-style: italic;
}

.love-particle {
  position: fixed;
  top: 100vh;
  left: var(--left);
  z-index: 9999;
  pointer-events: none;
  font-size: 27px;
  animation: flyLove var(--duration) ease-out forwards;
}

@keyframes butterflyFloat {
  0%,100% { transform: translateY(0) rotate(-8deg); }
  50% { transform: translateY(-12px) rotate(8deg); }
}

@keyframes heartBeat {
  0%,100% { transform: scale(1); }
  50% { transform: scale(1.2); }
}

@keyframes revealLove {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes flyLove {
  to {
    transform: translateY(-120vh) translateX(var(--drift)) rotate(360deg);
    opacity: 0;
  }
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const button = document.getElementById("secretLoveBtn");
  const message = document.getElementById("secretLoveMessage");

  if (!button || !message) return;

  button.addEventListener("click", function () {
    message.hidden = false;
    button.textContent = "माझं प्रेम फक्त तुझ्यासाठी! ❤️";

    const symbols = ["💗", "💕", "🦋", "❤️", "🌸", "💖"];

    for (let i = 0; i < 28; i++) {
      const particle = document.createElement("div");
      particle.className = "love-particle";
      particle.textContent =
        symbols[Math.floor(Math.random() * symbols.length)];

      particle.style.setProperty("--left", Math.random() * 100 + "vw");
      particle.style.setProperty("--drift", (Math.random() * 160 - 80) + "px");
      particle.style.setProperty("--duration", (3 + Math.random() * 3) + "s");

      document.body.appendChild(particle);

      setTimeout(function () {
        particle.remove();
      }, 6500);
    }
  });
});
</script>
</body>
</html>
