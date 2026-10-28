
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For Gella 🤍❣️</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      padding: 22px 15px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: Arial, sans-serif;
      color: #852b50;
      background: linear-gradient(135deg, #ffe4ed, #ffabc7, #fff0f5);
      overflow-x: hidden;
    }

    .card {
      position: relative;
      z-index: 2;
      width: 100%;
      max-width: 400px;
      padding: 30px 22px;
      border-radius: 28px;
      text-align: center;
      background: rgba(255, 255, 255, 0.9);
      border: 2px solid white;
      box-shadow: 0 15px 40px rgba(160, 48, 91, 0.2);
    }

    .heart {
      font-size: 65px;
      animation: beat 1.2s infinite;
    }

    @keyframes beat {
      50% { transform: scale(1.15); }
    }

    h1 {
      font-size: 30px;
      margin: 14px 0;
    }

    h2 {
      font-size: 23px;
      line-height: 1.4;
    }

    p {
      font-size: 16px;
      line-height: 1.8;
    }

    .buttons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 25px;
    }

    button {
      padding: 14px 20px;
      border: none;
      border-radius: 30px;
      font-size: 15px;
      font-weight: bold;
      cursor: pointer;
    }

    #yes {
      background: #ed4f89;
      color: white;
      box-shadow: 0 5px 15px #f4b1ca;
    }

    #no {
      background: #ffe3ed;
      color: #a32e5b;
    }

    #result {
      display: none;
      margin-top: 25px;
      padding: 18px;
      background: #fff0f6;
      border-radius: 20px;
      line-height: 1.8;
      animation: appear 0.5s ease;
    }

    @keyframes appear {
      from {
        opacity: 0;
        transform: translateY(12px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .footer {
      font-size: 12px;
      margin-top: 25px;
      color: #b05b7d;
    }

    .floating {
      position: fixed;
      bottom: -40px;
      z-index: 1;
      pointer-events: none;
      animation: rise 4s linear forwards;
    }

    @keyframes rise {
      to {
        transform: translateY(-110vh) rotate(30deg);
        opacity: 0;
      }
    }
  </style>
</head>

<body>

  <main class="card">

    <div class="heart">🤍</div>

    <h1>Hey, Gella! 🤍❣️</h1>

    <p>
      Sooo, Gella... 🥹💕
      I have a little question for you.
      And yes, I've actually been thinking about this. 😂
    </p>

    <p>
      Imagine us sharing random snaps every day,
      laughing at silly things, sending random
      updates, and having our own little tradition. 🔥
    </p>

    <p>
      Nothing complicated. Just a little reason
      to smile whenever our notifications pop up. 🫶🏽
    </p>

    <h2>Gella, will you be my streak partner? 🤍❣️</h2>

    <p>
      One snap a day, one little tradition,
      and lots of cute memories. 💗
    </p>

    <div class="buttons">
      <button id="yes" onclick="sayYes()">
        YES, DAVID! 🤍
      </button>

      <button id="no" onclick="sayNo()">
        Let me think 😂
      </button>
    </div>

    <section id="result" aria-live="polite"></section>

    <div class="footer">
      Made with 🤍 and a little courage.
      <br>
      Just for Gella ❣️
    </div>

  </main>

  <script>
    function sayYes() {
      const result = document.getElementById("result");

      result.innerHTML = `
        <h2>GELLA SAID YES?! 🥹🤍❣️</h2>

        <p>
          Gella, you have no idea how cute this
          little moment feels. 🥰
        </p>

        <p>
          Okay, it's official! 🔥🤍
          Here's to daily snaps, random conversations,
          silly moments, inside jokes, and a streak
          that keeps getting longer.
        </p>

        <p>
          And honestly, Gella...
          maybe becoming one of your favourite
          notifications wouldn't be so bad. 👀💕
        </p>

        <h2>Our little streak starts now! 🫶🏽</h2>

        <p>
          This little corner of the internet
          was made just for you. 🤍❣️
        </p>
      `;

      result.style.display = "block";

      document.getElementById("yes").textContent =
        "GELLA SAID YES! 🤍";

      celebrate();

      result.scrollIntoView({
        behavior: "smooth",
        block: "nearest"
      });
    }

    function sayNo() {
      const result = document.getElementById("result");

      result.innerHTML = `
        <h2>GELLA, TAKE YOUR TIME 😂🤍</h2>

        <p>
          No pressure, Gella. ❣️
          I just thought having our own little
          streak together would be cute. 🫶🏽
        </p>

        <p>
          The offer is still here if you change
          your mind. 😂💕
        </p>
      `;

      result.style.display = "block";
    }

    function celebrate() {
      const emojis = ["🤍", "❣️", "💕", "💗", "💖"];

      for (let i = 0; i < 25; i++) {
        setTimeout(() => {
          const heart = document.createElement("div");

          heart.className = "floating";
          heart.textContent =
            emojis[Math.floor(Math.random() * emojis.length)];

          heart.style.left = Math.random() * 100 + "vw";
          heart.style.fontSize =
            (20 + Math.random() * 20) + "px";

          heart.style.animationDuration =
            (3 + Math.random() * 3) + "s";

          document.body.appendChild(heart);

          heart.addEventListener("animationend", () => {
            heart.remove();
          });
        }, i * 100);
      }
    }
  </script>

</body>
</html>
