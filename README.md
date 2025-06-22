<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Happy Birthday, Ellysha 🎉</title>

  <!-- 🌸 Aesthetic Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&family=Quicksand&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Quicksand', sans-serif;
      height: 100vh;
      overflow-x: hidden;
      background: url('https://i0.wp.com/picjumbo.com/wp-content/uploads/colorful-love-hearts-wallpaper-free-photo.jpg?w=2210&quality=70') no-repeat center center fixed;
      background-size: cover;
      position: relative;
      color: white;
      animation: fadeIn 3s ease;
    }

    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 30, 0.5);
      z-index: -1;
    }

    .heart-container {
      background: rgba(255, 255, 255, 0.9);
      border-radius: 20px;
      padding: 40px;
      box-shadow: 0 0 25px rgba(255, 105, 180, 0.4);
      color: #b71c46;
      max-width: 700px;
      text-align: center;
      animation: fadeIn 2s ease;
      margin: 40px auto;
      font-family: 'Dancing Script', cursive;
    }

    .heart {
      font-size: 80px;
      animation: heartbeat 1s infinite;
      text-shadow: 0 0 20px #ff4081;
    }

    h1, h2 {
      margin: 20px 0 10px;
      font-size: 3rem;
      color: #d81b60;
      font-family: 'Dancing Script', cursive;
    }

    .message {
      font-size: 1.5rem;
      color: #b71c46;
      font-family: 'Dancing Script', cursive;
    }

    .love-letter {
      margin-top: 40px;
      padding: 25px;
      background: #fff7fb;
      border-left: 5px solid #f06292;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
      border-radius: 10px;
      font-size: 1.3rem;
      color: #444;
      line-height: 1.8;
      text-align: left;
      animation: fadeIn 2.5s ease;
      font-family: 'Dancing Script', cursive;
    }

    .floating-hearts,
    .floating-lyrics {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 0;
    }

    .floating-hearts span {
      position: absolute;
      width: 20px;
      height: 20px;
      background: pink;
      animation: float 10s linear infinite;
      opacity: 0.7;
      transform: rotate(45deg);
    }

    .floating-hearts span::before,
    .floating-hearts span::after {
      content: "";
      position: absolute;
      width: 20px;
      height: 20px;
      background: pink;
      border-radius: 50%;
    }

    .floating-hearts span::before {
      top: -10px;
      left: 0;
    }

    .floating-hearts span::after {
      left: -10px;
      top: 0;
    }

    .floating-lyrics span {
      position: absolute;
      font-size: 1.3rem;
      font-weight: bold;
      color: #ffb6c1;
      white-space: nowrap;
      animation: float 20s linear infinite;
      opacity: 0.9;
      text-shadow: 0 0 12px rgba(255, 182, 193, 0.8);
      font-family: 'Dancing Script', cursive;
    }

    @keyframes float {
      0% {
        transform: translateY(100vh);
        opacity: 0;
      }
      30% {
        opacity: 1;
      }
      100% {
        transform: translateY(-10vh);
        opacity: 0;
      }
    }

    @keyframes heartbeat {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.2);
      }
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    .music-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      padding: 10px 20px;
      background-color: #f06292;
      border: none;
      color: white;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      z-index: 10;
      font-family: 'Quicksand', sans-serif;
    }

    @media screen and (max-width: 600px) {
      .heart-container,
      .love-letter {
        margin: 20px;
        padding: 20px;
        font-size: 1rem;
      }

      h1, h2 {
        font-size: 2rem;
      }

      .music-btn {
        font-size: 0.9rem;
        padding: 8px 15px;
      }
    }
  </style>
</head>

<body>

  <!-- Floating Hearts -->
  <div class="floating-hearts">
    <span style="left:10%; animation-delay: 0s;"></span>
    <span style="left:25%; animation-delay: 2s;"></span>
    <span style="left:40%; animation-delay: 4s;"></span>
    <span style="left:60%; animation-delay: 1s;"></span>
    <span style="left:75%; animation-delay: 3s;"></span>
    <span style="left:90%; animation-delay: 5s;"></span>
  </div>

  <!-- Floating Lyrics -->
  <div class="floating-lyrics">
    <span style="left:5%; animation-delay: 0s;">Secrets I have held in my heart</span>
    <span style="left:15%; animation-delay: 3s;">Are harder to hide than I thought</span>
    <span style="left:30%; animation-delay: 6s;">Maybe I just wanna be yours</span>
    <span style="left:50%; animation-delay: 9s;">I wanna be yours</span>
    <span style="left:65%; animation-delay: 11s;">Wanna be yours</span>
    <span style="left:75%; animation-delay: 13s;">Wanna be yours</span>
    <span style="left:20%; animation-delay: 15s;">Wanna be yours</span>
    <span style="left:40%; animation-delay: 17s;">Wanna be yours</span>
  </div>

  <!-- Heart Message -->
  <div class="heart-container">
    <div class="heart">🎂❤️</div>
    <h1>Happy Birthday, Ellysha!</h1>
    <p class="message">You're not just a year older — you're more beautiful, more amazing, and more unforgettable than ever.</p>
  </div>

  <!-- Love Letter -->
  <div class="love-letter">
    <h2>To the most special girl, Ellysha,</h2>
    <p>On this day, the world became brighter because you were born — and I feel incredibly lucky to know you.</p>
    <p>Every smile you share lights up the room. Every word you say makes my day better. I hope this birthday brings you as much happiness as you’ve brought into my life.</p>
    <p>I’m really sorry if it ever felt like I was avoiding you. That was never my intention. The truth is… I care about you more than just a friend, and sometimes being around you gets a little hard when I’m trying to hide that. But I would never want to hurt you or make you feel unwanted. I just didn’t know how to deal with everything I feel.</p>
    <p>I also wanted to be honest about something I’ve been holding in: I like you, Ellysha. A lot. More than I’ve let on. I think about you more than you probably know. Your voice, your laughter, your kindness — it all means the world to me.</p>
    <p>I know you only see me as a friend—and I respect that completely. You have every right to choose who you let into your heart in that way. But still, I want you to know that somewhere between the laughs, the messages, and the quiet moments, I started to feel something more for you.</p>
    <p>I never expected anything in return. I just wanted to be honest with myself—and with you. Loving someone doesn’t always mean being loved back, and I’ve come to accept that. But loving you has shown me the kind of person I want to be: more caring, more patient, more true.</p>
    <p>So thank you—for being someone so genuinely special that my heart noticed. I’ll always be here, cheering for you, even if it’s just as a friend. Sometimes I see the things you repost about wanting to be loved… and I just sit there wondering if you even realize how much I already do.</p>
    <p>Maybe yeah, I was nothing to compare with him right? He’s the first man that made you feel the real love.</p>
    <p>I don’t want to make this day complicated, just more beautiful — so this is a gentle wish and a little confession too. No pressure, no expectations. Just a little piece of truth I wanted to give you.</p>
    <p>I hope today is full of love, surprises, and everything you deserve. And maybe, just maybe, this message makes you smile a little extra.</p>
    <p>Thank you for everything Ellysha, I was enchanted to meet you.</p>
    <p style="margin-top: 2rem;">With all my heart,<br /><strong><span style="font-family: 'Dancing Script', cursive;">Aqil</span></strong></p>
  </div>

  <!-- YouTube Background Music Player (hidden) -->
  <div id="yt-player" style="display:none;">
    <iframe id="ytbg" width="0" height="0"
      src="https://www.youtube.com/embed/fukGbiPuBjU?autoplay=1&loop=1&playlist=fukGbiPuBjU&controls=0&showinfo=0"
      frameborder="0"
      allow="autoplay"
    ></iframe>
  </div>

  <!-- Music Button -->
  <button class="music-btn" onclick="playYouTube()">🎵 Play Music</button>

  <script>
    function playYouTube() {
      const player = document.getElementById("yt-player");
      player.style.display = "block";
    }
  </script>

</body>

</html>
