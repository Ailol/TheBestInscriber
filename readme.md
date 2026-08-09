<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>The Modulum</title>

  <script>
    window.MathJax = {
      tex: {
        inlineMath: [['$', '$']],
        displayMath: [['$$', '$$']]
      }
    };
  </script>

  <script
    defer
    src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>

  <style>
    :root {
      --vanta: #000;
      --glass: rgba(255, 255, 255, 0.045);
      --glass-edge: rgba(255, 255, 255, 0.11);
      --white: #fff;
      --muted: #888;
      --red: #b33;
      --blue: #36c;
      --green: #ae3;
    }

    * {
      box-sizing: border-box;
    }

    html,
    body {
      margin: 0;
      min-height: 100%;
      background: var(--vanta);
      color: var(--white);
      font-family:
        Inter,
        ui-sans-serif,
        system-ui,
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        sans-serif;
    }

    body {
      min-height: 100vh;
      display: grid;
      place-items: center;
      padding: 48px 20px;
    }

    .field {
      width: min(760px, 100%);
    }

    .eyebrow {
      margin-bottom: 12px;
      color: var(--muted);
      font-size: 0.72rem;
      font-weight: 700;
      letter-spacing: 0.18em;
      text-transform: uppercase;
    }

    h1 {
      margin: 0;
      font-size: clamp(2.6rem, 8vw, 5.7rem);
      font-weight: 800;
      letter-spacing: -0.065em;
      line-height: 0.95;
    }

    .bee {
      display: inline-block;
      margin-left: 0.12em;
      font-size: 0.68em;
      transform: translateY(-0.06em);
    }

    .lead {
      max-width: 560px;
      margin: 22px 0 38px;
      color: #aaa;
      font-size: 1rem;
      line-height: 1.7;
    }

    .glass {
      position: relative;
      overflow: hidden;
      padding: clamp(26px, 5vw, 46px);
      border: 1px solid var(--glass-edge);
      border-radius: 26px;
      background: var(--glass);
      box-shadow:
        0 30px 80px rgba(0, 0, 0, 0.8),
        inset 0 1px rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(24px);
      -webkit-backdrop-filter: blur(24px);
    }

    .glass::before {
      content: "";
      position: absolute;
      inset: 0;
      pointer-events: none;
      background:
        radial-gradient(
          circle at 0% 0%,
          rgba(255, 255, 255, 0.08),
          transparent 34%
        );
    }

    .label {
      position: relative;
      color: #777;
      font-size: 0.68rem;
      font-weight: 750;
      letter-spacing: 0.16em;
      text-transform: uppercase;
    }

    .modulum {
      position: relative;
      margin: 22px 0 34px;
      text-align: center;
      font-size: clamp(1.6rem, 5vw, 2.5rem);
    }

    .divider {
      width: 100%;
      height: 1px;
      margin: 10px 0 34px;
      background:
        linear-gradient(
          90deg,
          transparent,
          rgba(255,255,255,.16),
          transparent
        );
    }

    .inscribe {
      position: relative;
      text-align: center;
      font-size: clamp(1.25rem, 4vw, 1.8rem);
      line-height: 2;
    }

    .equiv {
      position: relative;
      display: grid;
      place-items: center;
      width: 58px;
      height: 58px;
      margin: 34px auto 0;
      border: 1px solid rgba(255,255,255,.12);
      border-radius: 50%;
      background: rgba(255,255,255,.03);
      font-size: 1.6rem;
      box-shadow:
        inset 0 0 24px rgba(255,255,255,.025),
        0 12px 30px rgba(0,0,0,.65);
    }

    .squared {
      margin-top: 26px;
      color: #aaa;
      text-align: center;
      font-size: 0.82rem;
      line-height: 1.7;
    }

    .squared strong {
      color: white;
    }

    .thanks {
      margin-top: 34px;
      padding-top: 24px;
      border-top: 1px solid rgba(255,255,255,.07);
      color: #666;
      font-size: 0.74rem;
      line-height: 1.65;
      text-align: center;
    }

    .particles {
      display: flex;
      justify-content: center;
      gap: 7px;
      margin-top: 22px;
    }

    .particle {
      width: 5px;
      height: 5px;
      border-radius: 50%;
    }

    .black { background: #333; }
    .red   { background: var(--red); }
    .white { background: #fff; }
    .blue  { background: var(--blue); }
    .green { background: var(--green); }
  </style>
</head>

<body>

  <main class="field">

    <div class="eyebrow">Fermionic Inscribe</div>

    <h1>
      The Modulum
      <span class="bee">🐝</span>
    </h1>

    <p class="lead">
      To secure your bounty after a hefty raid,
      I suggest this inscribes before you wander.
    </p>

    <section class="glass">

      <div class="label">Modulum</div>

      <div class="modulum">
        $$\mathrm{Qti}\ \equiv\ \mathrm{Qt}\,\text{🐝}\ :)$$
      </div>

      <div class="divider"></div>

      <div class="label">Fermionic Inscribe</div>

      <div class="inscribe">
        $$
        \begin{aligned}
        E &\Longleftrightarrow Q\!\sim\ \text{("vibe")} \\[5pt]
        M &= t\ \text{(atomic)} \\[5pt]
        C &\overset{**}{=} i\ \text{(**args)}
        \end{aligned}
        $$
      </div>

      <div class="equiv">
        $$\equiv$$
      </div>

      <div class="squared">
        <strong>²</strong> — seconds; time is in you as well as outside.<br />
        or simply: <strong>“Squared” :)</strong>
      </div>

      <div class="particles">
        <span class="particle black"></span>
        <span class="particle red"></span>
        <span class="particle white"></span>
        <span class="particle blue"></span>
        <span class="particle green"></span>
      </div>

      <div class="thanks">
        Thank you Eric Weinstein and JRE Crew and Elon for the help in 2021
        with Dr. Rhonda and hollybees, as well as David and Jordan Peterson
        and even Botched crew joining in :)
      </div>

    </section>

  </main>

</body>
</html>
