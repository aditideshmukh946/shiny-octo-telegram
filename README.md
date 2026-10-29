# shiny-octo-telegram
A special surprise for Khadus 💗
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Khadus 💗</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Georgia, serif;
  text-align: center;
  color: #633b70;
  background: linear-gradient(135deg, #ffe4f0, #eee0ff, #fff0f7);
}

section {
  min-height: 100vh;
  padding: 70px 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

h1 {
  font-size: clamp(48px, 12vw, 75px);
  color: #c34e91;
  text-shadow: 2px 3px 0 white;
  animation: float 2s infinite ease-in-out;
}

h2 {
  color: #a14f9c;
}

p {
  max-width: 520px;
  line-height: 1.9;
  font-size: 17px;
}

button {
  border: none;
  border-radius: 30px;
  padding: 14px 25px;
  margin: 12px;
  background: #c45b9d;
  color: white;
  font-size: 16px;
  cursor: pointer;
  box-shadow: 0 5px 15px #d9a4ce;
}

button:hover {
  background: #9d438e;
  transform: scale(1.04);
}

.card {
  max-width: 600px;
  width: 100%;
  background: #ffffffa8;
  border: 2px dashed #d88bbd;
  border-radius: 25px;
  padding: 25px;
  margin: 18px auto;
  box-shadow: 0 8px 25px #d8b5df55;
}

.heart {
  font-size: 28px;
  animation: beat 1s infinite;
}

.hidden {
  display: none;
}

footer {
  padding: 25px;
  color: #98649c;
}

@keyframes float {
  50% { transform: translateY(-10px); }
}

@keyframes beat {
  50% { transform: scale(1.25); }
}
</style>
</head>

<body>

<section id="home">
  <div class="heart">💗 ✨ 💗</div>
  <h1>Khadus</h1>
  <h2>Hey Khadus — Yes, YOU! 🎀</h2>
  <p>1 Year 3 Months ♥ Countless Memories</p>
  <p>A little corner of the internet, made especially for you.</p>
  <button onclick="showSurprise()">Open Your Surprise 💌</button>
  <p>Made with lots of love & a little bit of pagalpan 🌷</p>
</section>

<section id="surprise" class="hidden">
  <h1 style="font-size:45px">For You, Khadus 💕</h1>

  <div class="card">
    <h2>🌸 Our Little Chapter 🌸</h2>
    <p>
      1 year and 3 months of hostel life, random talks,
      silly moments, laughter, and memories that will
      always have a special place in my heart.
    </p>
    <p>
      Some days were ordinary, but somehow, they became
      memories I'll never want to forget. 🧿
    </p>
  </div>

  <div class="card">
    <h2>📸 Memory Corner</h2>
    <p>
      This space is waiting for our favourite photos!
      Every picture has a story, and every story is worth keeping. 💗
    </p>
    <p>🌷 Little moments. Big memories. Forever treasured. 🌷</p>
  </div>

  <div class="card">
    <h2>💌 A Little Letter</h2>
    <p>
      Khadus,
    </p>
    <p>
      Your engineering journey has reached a beautiful milestone,
      and now a new chapter is waiting for you.
    </p>
    <p>
      I hope life brings you opportunities that excite you,
      people who support you, and success that makes every
      bit of hard work worth it.
    </p>
    <p>
      No matter how busy life gets or how far your next
      chapter takes you, I hope you always remember the
      little hostel moments that made this journey special.
    </p>
    <p>
      Keep growing, keep shining, and never stop believing
      in yourself. You deserve beautiful things. 🫶🏻
    </p>
    <p>
      All the best for everything that's coming next! 🌸
    </p>
    <p>— Someone who will always treasure these memories 💗</p>
  </div>

  <button onclick="showFinal()">One Last Thing... 💝</button>

  <div id="final" class="card hidden">
    <div class="heart">💗 💗 💗</div>
    <h2>Your Next Chapter Starts Now! ✨</h2>
    <p>
      The hostel chapter may be ending, but the memories
      we've made will always be a beautiful part of the story.
    </p>
    <p>Go make the world proud, Khadus! 🌷</p>
    <h2>YOU'VE GOT THIS! 💌</h2>
  </div>
</section>

<footer>Made specially for Khadus 🌸</footer>

<script>
function showSurprise() {
  document.getElementById("surprise").classList.remove("hidden");
  document.getElementById("surprise").scrollIntoView({
    behavior: "smooth"
  });
}

function showFinal() {
  document.getElementById("final").classList.remove("hidden");
  document.getElementById("final").scrollIntoView({
    behavior: "smooth"
  });
}
</script>

</body>
</html>
