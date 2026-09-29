<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Under Maintenance</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

    :root {
      --bg: #05050a;
      --text: #f5f5f7;
      --muted: #858592;

      --purple: #8b5cf6;
      --blue: #3b82f6;
      --cyan: #22d3ee;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html,
    body {
      width: 100%;
      min-height: 100%;
    }

    body {
      background: var(--bg);
      color: var(--text);

      font-family: "Inter", sans-serif;

      overflow: hidden;
    }

    /* =========================================
       BACKGROUND
    ========================================= */

    .background {
      position: fixed;
      inset: 0;
      overflow: hidden;
      z-index: 0;

      background:
        radial-gradient(
          circle at 50% 40%,
          rgba(94, 58, 180, 0.12),
          transparent 45%
        ),
        #05050a;
    }

    /* Aurora */
    .aurora {
      position: absolute;

      width: 700px;
      height: 700px;

      left: 50%;
      top: 50%;

      transform:
        translate(-50%, -50%)
        rotate(0deg);

      border-radius: 50%;

      background:
        conic-gradient(
          from 0deg,
          transparent,
          rgba(139, 92, 246, .35),
          rgba(34, 211, 238, .28),
          rgba(59, 130, 246, .25),
          transparent
        );

      filter: blur(90px);

      animation:
        auroraRotate 18s linear infinite,
        auroraPulse 7s ease-in-out infinite alternate;
    }

    @keyframes auroraRotate {
      to {
        transform:
          translate(-50%, -50%)
          rotate(360deg);
      }
    }

    @keyframes auroraPulse {
      from {
        scale: .85;
        opacity: .6;
      }

      to {
        scale: 1.15;
        opacity: 1;
      }
    }

    /* Moving grid */

    .grid {
      position: absolute;
      inset: -100%;

      opacity: .15;

      background-image:
        linear-gradient(
          rgba(255,255,255,.045) 1px,
          transparent 1px
        ),
        linear-gradient(
          90deg,
          rgba(255,255,255,.045) 1px,
          transparent 1px
        );

      background-size: 70px 70px;

      transform:
        perspective(500px)
        rotateX(60deg)
        translateY(0);

      animation: gridMove 10s linear infinite;
    }

    @keyframes gridMove {
      from {
        background-position: 0 0;
      }

      to {
        background-position: 0 70px;
      }
    }

    /* Noise */

    .noise {
      position: absolute;
      inset: 0;

      opacity: .045;

      background-image:
        url("data:image/svg+xml,%3Csvg viewBox='0 0 180 180' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='.8'/%3E%3C/svg%3E");
    }

    /* Cursor glow */

    .cursor-glow {
      position: fixed;

      width: 300px;
      height: 300px;

      border-radius: 50%;

      pointer-events: none;

      background:
        radial-gradient(
          circle,
          rgba(139, 92, 246, .12),
          transparent 65%
        );

      transform: translate(-50%, -50%);

      z-index: 1;

      filter: blur(20px);
    }

    /* =========================================
       CONTENT
    ========================================= */

    .page {
      position: relative;
      z-index: 5;

      min-height: 100vh;

      display: flex;
      align-items: center;
      justify-content: center;

      padding: 40px;
    }

    .content {
      width: min(850px, 100%);

      text-align: center;

      animation:
        entrance 1.2s cubic-bezier(.16,1,.3,1)
        forwards;
    }

    @keyframes entrance {
      from {
        opacity: 0;
        transform:
          translateY(35px)
          scale(.97);
      }

      to {
        opacity: 1;
        transform:
          translateY(0)
          scale(1);
      }
    }

    /* =========================================
       STATUS
    ========================================= */

    .status {
      display: inline-flex;

      align-items: center;
      gap: 10px;

      padding: 9px 15px;

      margin-bottom: 30px;

      border: 1px solid rgba(255,255,255,.1);

      border-radius: 999px;

      background:
        rgba(255,255,255,.035);

      backdrop-filter: blur(15px);

      color: #b8b8c2;

      font-size: 12px;
      font-weight: 500;

      letter-spacing: .08em;
      text-transform: uppercase;
    }

    .status-dot {
      position: relative;

      width: 7px;
      height: 7px;

      border-radius: 50%;

      background: #22d3ee;

      box-shadow:
        0 0 12px #22d3ee;
    }

    .status-dot::after {
      content: "";

      position: absolute;

      inset: -5px;

      border-radius: 50%;

      border: 1px solid #22d3ee;

      animation: ping 2s ease-out infinite;
    }

    @keyframes ping {
      0% {
        opacity: .8;
        transform: scale(.5);
      }

      100% {
        opacity: 0;
        transform: scale(1.8);
      }
    }

    /* =========================================
       TITLE
    ========================================= */

    h1 {
      font-size:
        clamp(58px, 10vw, 120px);

      line-height: .9;

      letter-spacing: -.075em;

      font-weight: 800;

      margin-bottom: 32px;
    }

    .gradient-text {
      display: block;

      background:
        linear-gradient(
          100deg,
          #ffffff 10%,
          #b7a4ff 45%,
          #67e8f9 85%
        );

      -webkit-background-clip: text;
      background-clip: text;

      color: transparent;

      background-size: 200% auto;

      animation:
        gradientMove 5s linear infinite;
    }

    @keyframes gradientMove {
      to {
        background-position: 200% center;
      }
    }

    .title-secondary {
      display: block;

      color: rgba(255,255,255,.3);
    }

    /* =========================================
       DESCRIPTION
    ========================================= */

    .description {
      max-width: 540px;

      margin: 0 auto;

      color: var(--muted);

      font-size: 15px;

      line-height: 1.8;
    }

    /* =========================================
       PROGRESS
    ========================================= */

    .progress-container {
      width: min(420px, 100%);

      margin: 48px auto 0;
    }

    .progress-info {
      display: flex;

      justify-content: space-between;

      margin-bottom: 11px;

      color: #666672;

      font-size: 11px;

      text-transform: uppercase;

      letter-spacing: .08em;
    }

    .progress {
      position: relative;

      height: 3px;

      overflow: hidden;

      background: rgba(255,255,255,.08);

      border-radius: 99px;
    }

    .progress-bar {
      position: absolute;

      height: 100%;

      width: 68%;

      border-radius: inherit;

      background:
        linear-gradient(
          90deg,
          var(--purple),
          var(--blue),
          var(--cyan)
        );

      box-shadow:
        0 0 20px rgba(139,92,246,.6);

      animation: progress 3s ease-in-out infinite alternate;
    }

    @keyframes progress {
      from {
        width: 58%;
      }

      to {
        width: 76%;
      }
    }

    /* =========================================
       FOOTER
    ========================================= */

    .footer {
      position: fixed;

      bottom: 28px;
      left: 0;
      right: 0;

      z-index: 10;

      text-align: center;

      color: #4d4d57;

      font-size: 11px;

      letter-spacing: .05em;
    }

    /* =========================================
       RESPONSIVE
    ========================================= */

    @media (max-width: 600px) {

      .page {
        padding: 24px;
      }

      h1 {
        font-size: 58px;
      }

      .description {
        font-size: 14px;
      }

      .aurora {
        width: 450px;
        height: 450px;
      }

      .grid {
        background-size: 45px 45px;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      *,
      *::before,
      *::after {
        animation-duration: .01ms !important;
        animation-iteration-count: 1 !important;
      }
    }
  </style>
</head>

<body>

  <!-- Background -->
  <div class="background">
    <div class="aurora"></div>
    <div class="grid"></div>
    <div class="noise"></div>
  </div>

  <!-- Cursor -->
  <div class="cursor-glow"></div>


  <!-- Content -->
  <main class="page">

    <section class="content">

      <div class="status">
        <span class="status-dot"></span>
        System Maintenance
      </div>

      <h1>
        <span class="gradient-text">
          Be right back.
        </span>

        <span class="title-secondary">
          We're upgrading.
        </span>
      </h1>

      <p class="description">
        We're making a few improvements behind the scenes.
        Everything will be back online shortly.
      </p>

      <div class="progress-container">

        <div class="progress-info">
          <span>Maintenance progress</span>
          <span id="percentage">68%</span>
        </div>

        <div class="progress">
          <div class="progress-bar"></div>
        </div>

      </div>

    </section>

  </main>


  <footer class="footer">
    © <span id="year"></span> — Temporarily offline
  </footer>


  <script>
    /*
      YEAR
    */

    document.getElementById("year").textContent =
      new Date().getFullYear();


    /*
      CURSOR PARALLAX
    */

    const glow =
      document.querySelector(".cursor-glow");

    let mouseX = window.innerWidth / 2;
    let mouseY = window.innerHeight / 2;

    let currentX = mouseX;
    let currentY = mouseY;

    window.addEventListener("mousemove", (e) => {

      mouseX = e.clientX;
      mouseY = e.clientY;

    });

    function animateCursor() {

      currentX +=
        (mouseX - currentX) * 0.08;

      currentY +=
        (mouseY - currentY) * 0.08;

      glow.style.left = currentX + "px";
      glow.style.top = currentY + "px";

      requestAnimationFrame(animateCursor);
    }

    animateCursor();


    /*
      FAKE PROGRESS
    */

    const percentage =
      document.getElementById("percentage");

    let value = 68;

    setInterval(() => {

      value +=
        Math.random() * 2 - 1;

      value =
        Math.max(
          62,
          Math.min(76, value)
        );

      percentage.textContent =
        Math.round(value) + "%";

    }, 1200);
  </script>

</body>
</html>
