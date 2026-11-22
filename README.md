
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Little Universe For Pratuu ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;600;700&family=Playfair+Display:ital,wght@0,500;0,600;1,500&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
 background:#160e22;color:#fff;
 font-family:'Poppins',sans-serif;
 overflow-x:hidden;
}
body:before{
 content:"";position:fixed;inset:0;z-index:-1;
 background:
 radial-gradient(circle at 15% 15%,#b44b8755,transparent 35%),
 radial-gradient(circle at 85% 70%,#7050b455,transparent 40%),
 linear-gradient(145deg,#160e22,#321b3c,#170f29);
}
section{padding:85px 20px;text-align:center}
.hero{
 min-height:100vh;display:flex;align-items:center;
 justify-content:center;flex-direction:column;
 padding:30px 20px;
}
.eyebrow{
 font-size:10px;letter-spacing:5px;color:#f5b9dd;
 margin-bottom:22px;
}
h1,h2,.script{font-family:'Dancing Script',cursive}
h1{font-size:clamp(55px,12vw,90px);color:#ffd0e9}
h2{font-size:48px;color:#ffc9e7;margin-bottom:25px}
.hero p{max-width:330px;line-height:2;color:#e8d5ed;margin:20px 0 28px}
.hero-heart{font-size:43px;animation:pulse 1.5s infinite}
@keyframes pulse{50%{transform:scale(1.2)}}
.btn{
 border:1px solid #ffc6e5;background:linear-gradient(120deg,#c65d9d,#8156b8);
 color:white;border-radius:50px;padding:15px 28px;
 font-size:13px;letter-spacing:1px;cursor:pointer;
 box-shadow:0 0 25px #d56eaa44;
 transition:.3s;
}
.btn:active{transform:scale(.96)}
.glass{
 max-width:540px;margin:auto;padding:30px 22px;
 border:1px solid #ffffff25;border-radius:25px;
 background:#ffffff0c;backdrop-filter:blur(12px);
 box-shadow:0 15px 50px #0003;
}
.countdown{display:flex;justify-content:center;gap:10px;flex-wrap:wrap}
.time{
 min-width:68px;padding:15px 10px;border-radius:16px;
 background:#ffffff12;border:1px solid #ffffff18;
}
.time strong{display:block;font-size:27px;color:#ffd0e9}
.time small{font-size:9px;letter-spacing:2px;color:#dcb9df}
.subtext{font-size:12px;color:#d9c2df;line-height:2;margin-top:22px}
.gallery{
 display:grid;grid-template-columns:1fr 1fr;
 gap:14px;max-width:520px;margin:30px auto;
}
.photo{
 position:relative;overflow:hidden;border-radius:20px;
 background:#44254d;border:1px solid #ffffff25;
 box-shadow:0 12px 30px #0004;
}
.photo img{
 width:100%;height:245px;object-fit:cover;display:block;
 transition:transform .6s;
}
.photo:active img{transform:scale(1.06)}
.photo p{
 font-family:'Dancing Script',cursive;font-size:22px;
 color:#ffd0e9;padding:12px 5px;
}
.letter{
 text-align:left;line-height:2.1;color:#f1dff0;
 font-size:13px;
}
.letter p{margin-bottom:17px}
.signature{
 font-family:'Dancing Script',cursive;
 font-size:29px;color:#ffc8e6;text-align:right;
}
.gift-icon{font-size:55px;margin:10px}
#giftMessage{display:none;margin-top:25px;animation:show 1s ease}
@keyframes show{
 from{opacity:0;transform:translateY(25px)}
 to{opacity:1;transform:translateY(0)}
}
#giftMessage h2{font-size:43px}
#giftMessage p{font-size:14px;line-height:2;color:#f5e2f2}
.footer{padding:45px 15px;text-align:center;color:#d9b9d8;font-size:11px}
.floating{
 position:fixed;bottom:-40px;pointer-events:none;z-index:99;
 animation:floatUp linear forwards;
}
@keyframes floatUp{
 to{transform:translateY(-115vh) rotate(360deg);opacity:0}
}
.sparkle{color:#ffd5ed;font-size:20px}
.divider{
 width:65px;height:1px;background:#e9a8d4;
 margin:25px auto;
}
@media(max-width:380px){
 .photo img{height:190px}
 h2{font-size:40px}
 .glass{padding:25px 16px}
}
</style>
</head>

<body>

<!-- WELCOME -->
<section class="hero">
 <div class="hero-heart">♡</div>
 <p class="eyebrow">A LITTLE WORLD MADE JUST FOR YOU</p>
 <h1>Hey, Pratuu!</h1>
 <p>
  Somewhere between ordinary days and unexpected smiles,
  you became someone very special.
  So I made this little universe just for you. 🌙
 </p>
 <button class="btn" onclick="goTo('birthday')">ENTER YOUR WORLD ✨</button>
 <p class="sparkle">Scroll down, beautiful ↓</p>
</section>

<!-- COUNTDOWN -->
<section id="birthday">
 <p class="eyebrow">THE DAY THE WORLD GOT MORE BEAUTIFUL</p>
 <h2>It's Your Day! 🎂</h2>
 <div class="glass">
  <p class="subtext" style="margin-top:0">COUNTING DOWN TO YOUR SPECIAL DAY</p>
  <div class="countdown" id="countdown">
   <div class="time"><strong id="days">00</strong><small>DAYS</small></div>
   <div class="time"><strong id="hours">00</strong><small>HOURS</small></div>
   <div class="time"><strong id="minutes">00</strong><small>MINUTES</small></div>
   <div class="time"><strong id="seconds">00</strong><small>SECONDS</small></div>
  </div>
  <p class="subtext">A special day for my favourite girl. ❤️</p>
 </div>
</section>

<!-- PHOTOS -->
<section id="memories">
 <p class="eyebrow">A FACE THAT MAKES MY DAY</p>
 <h2>Your Little Gallery 📸</h2>
 <div class="gallery">

  <div class="photo">
   <img src="Snapchat-1576273468.jpg" alt="Pratuu's photo">
   <p>Your beautiful smile</p>
  </div>

  <div class="photo">
   <img src="Snapchat-543809548.jpg" alt="Pratuu's photo">
   <p>My favourite girl</p>
  </div>

  <div class="photo">
   <img src="Snapchat-1632423022.jpg" alt="Pratuu's photo">
   <p>Simply magical</p>
  </div>

  <div class="photo">
   <img src="Snapchat-2018473043.jpg" alt="Pratuu's photo">
   <p>One of a kind</p>
  </div>

 </div>
 <p class="subtext">Four pictures, countless reasons to smile. 🦋</p>
</section>

<!-- LOVE LETTER -->
<section>
 <p class="eyebrow">SOME WORDS FROM MY HEART</p>
 <h2>For You, My Love 💌</h2>
 <div class="glass letter">
  <p>Dear Pratuu, ❤️</p>
  <p>
   I may not always find the perfect words,
   but I hope you always know how special you are to me.
  </p>
  <p>
   Your smile, your cute little talks, your nakhre,
   and even the silly moments — somehow, all of them
   make my days a little more beautiful.
  </p>
  <p>
   I don't promise a perfect world,
   but I promise to keep finding little reasons
   to make you smile.
  </p>
  <p>
   On your birthday, I wish you happiness that never ends,
   dreams that come true, and a life full of beautiful surprises.
  </p>
  <p>
   And whenever life gets difficult,
   I hope you remember that someone is always cheering for you.
  </p>
  <p class="signature">Your favourite person ❤️</p>
 </div>
</section>

<!-- SECRET GIFT -->
<section>
 <p class="eyebrow">WAIT... THERE'S ONE MORE THING</p>
 <h2>A Secret For You 🎁</h2>
 <div class="glass">
  <div class="gift-icon">🎁</div>
  <p class="subtext" style="margin:10px 0 22px">
   I kept one little surprise hidden here.
   Only you can open it...
  </p>
  <button class="btn" onclick="openGift()">OPEN YOUR GIFT 💗</button>

  <div id="giftMessage">
   <div class="divider"></div>
   <p class="eyebrow">MY ONE AND ONLY WISH</p>
   <h2>Happy Birthday,<br>Pratuu! ❤️</h2>
   <p>
    If I could gift you one thing in this whole world,
    it would be the ability to see yourself through my eyes.
    <br><br>
    Then you would know how precious, beautiful
    and special you truly are.
    <br><br>
    Keep smiling, my princess.
    May your world always be filled with love,
    laughter and magic. 🦋
   </p>
   <div style="font-size:38px;margin-top:20px">🌷 💖 🌙</div>
   <p class="signature" style="margin-top:20px">Made only for you.</p>
  </div>
 </div>
</section>

<div class="footer">
 Made with lots of love, just for Pratuu ❤️
 <br><br>
 A little universe. A million feelings.
</div>

<script>
function goTo(id){
 document.getElementById(id).scrollIntoView({behavior:"smooth"});
}

const birthday = new Date("December 22, 2026 00:00:00").getTime();

function updateCountdown(){
 const now = Date.now();
 const diff = birthday - now;

 if(diff <= 0){
  document.getElementById("countdown").innerHTML =
  "<h2 style='font-size:30px'>HAPPY BIRTHDAY! 🎂❤️</h2>";
  return;
 }

 document.getElementById("days").textContent =
 Math.floor(diff / 86400000);
 document.getElementById("hours").textContent =
 Math.floor((diff % 86400000) / 3600000);
 document.getElementById("minutes").textContent =
 Math.floor((diff % 3600000) / 60000);
 document.getElementById("seconds").textContent =
 Math.floor((diff % 60000) / 1000);
}
updateCountdown();
setInterval(updateCountdown,1000);

function floatHeart(){
 const el = document.createElement("div");
 const symbols = ["♡","♥","🦋","✦","🌸"];
 el.className = "floating";
 el.textContent = symbols[Math.floor(Math.random()*symbols.length)];
 el.style.left = Math.random()*100+"vw";
 el.style.fontSize = (16+Math.random()*22)+"px";
 el.style.color = "#ffc8e8";
 el.style.animationDuration = (5+Math.random()*5)+"s";
 document.body.appendChild(el);
 setTimeout(()=>el.remove(),10000);
}
setInterval(floatHeart,900);

function openGift(){
 const box = document.getElementById("giftMessage");
 box.style.display = "block";
 for(let i=0;i<45;i++){
  setTimeout(floatHeart,i*90);
 }
 setTimeout(()=>box.scrollIntoView({behavior:"smooth",block:"center"}),100);
}
</script>

</body>
</html>
