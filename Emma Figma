<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Circle — All Screens</title>
<style>
  *, *::before, *::after { box-sizing: border-box; }

  body {
    margin: 0;
    padding: 0;
    background: #1A1F1E;
    font-family: -apple-system, 'Inter', 'Segoe UI', sans-serif;
    -webkit-font-smoothing: antialiased;
  }

  /* Top bar */
  .topbar {
    position: sticky;
    top: 0;
    z-index: 100;
    background: rgba(20, 26, 24, 0.92);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid rgba(255,255,255,0.07);
    padding: 14px 40px;
    display: flex;
    align-items: center;
    gap: 16px;
  }
  .topbar-logo {
    width: 32px; height: 32px;
    border-radius: 10px;
    background: linear-gradient(135deg, #2A7A60 0%, #1F5C49 100%);
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .topbar-title { color: #fff; font-size: 17px; font-weight: 700; letter-spacing: -0.2px; }
  .topbar-sub { color: rgba(255,255,255,0.45); font-size: 13px; font-weight: 500; margin-left: auto; }

  /* Grid */
  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, 395px);
    gap: 56px 40px;
    padding: 60px 60px 100px;
    justify-content: center;
  }

  /* Each screen frame */
  .screen-frame {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 14px;
  }

  .screen-label {
    color: rgba(255,255,255,0.55);
    font-size: 12px;
    font-weight: 600;
    letter-spacing: 0.4px;
    text-transform: uppercase;
    align-self: flex-start;
    margin-left: 10px;
  }

  /* iPhone shell */
  .device-shell {
    position: relative;
    width: 395px;
    height: 852px;
    background: #111;
    border-radius: 54px;
    border: 8px solid #2A2A2A;
    box-shadow:
      0 0 0 1px rgba(255,255,255,0.05),
      inset 0 0 0 1px rgba(255,255,255,0.04),
      0 40px 80px rgba(0,0,0,0.6),
      0 20px 40px rgba(0,0,0,0.4);
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  /* Dynamic island notch */
  .notch {
    position: absolute;
    top: 12px;
    left: 50%;
    transform: translateX(-50%);
    width: 120px;
    height: 34px;
    background: #111;
    border-radius: 20px;
    z-index: 10;
  }

  .device-shell iframe {
    border-radius: 47px;
    display: block;
    pointer-events: none;
  }
</style>
</head>
<body>

<div class="topbar">
  <div class="topbar-logo">
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none">
      <circle cx="12" cy="12" r="9" stroke="white" stroke-width="2"/>
      <circle cx="12" cy="12" r="3.2" fill="white"/>
    </svg>
  </div>
  <span class="topbar-title">Circle App</span>
  <span class="topbar-sub">14 Screens · iPhone 13 mini · 375 × 812</span>
</div>

<div class="grid">

    <div class="screen-frame" id="screen-01">
      <div class="screen-label">01 · Onboarding — Willkommen</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .onb-screen {
    background: linear-gradient(165deg, var(--green-800) 0%, var(--green-700) 45%, var(--green-600) 100%);
  }
  .onb-screen .status-bar, .onb-screen .status-bar * { color: var(--white); }
  .onb-art {
    flex: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
  }
  .blob {
    position: absolute;
    border-radius: 50%;
    background: rgba(255,255,255,0.08);
  }
  .blob.b1 { width: 280px; height: 280px; top: -60px; left: -80px; }
  .blob.b2 { width: 200px; height: 200px; bottom: 40px; right: -60px; background: rgba(235,107,58,0.18); }

  .people-cluster { position: relative; width: 220px; height: 220px; z-index: 2; }
  .pc-avatar {
    position: absolute;
    border-radius: 50%;
    border: 3px solid rgba(255,255,255,0.9);
    object-fit: cover;
    box-shadow: 0 8px 24px rgba(0,0,0,0.25);
  }

  .onb-content {
    padding: 0 32px 0;
    text-align: center;
    flex-shrink: 0;
  }
  .logo-mark {
    width: 56px;
    height: 56px;
    margin: 0 auto 18px;
    border-radius: 18px;
    background: rgba(255,255,255,0.14);
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .onb-title {
    font-size: 30px;
    font-weight: 800;
    color: var(--white);
    letter-spacing: -0.5px;
    line-height: 1.2;
  }
  .onb-sub {
    font-size: 15.5px;
    color: rgba(255,255,255,0.78);
    line-height: 1.55;
    margin-top: 12px;
  }
  .onb-footer {
    padding: 28px 24px 40px;
    flex-shrink: 0;
  }
  .dots { display: flex; justify-content: center; gap: 6px; margin-bottom: 22px; }
  .dot { width: 7px; height: 7px; border-radius: 50%; background: rgba(255,255,255,0.3); }
  .dot.active { width: 20px; background: var(--white); border-radius: 4px; }
  .onb-skip {
    text-align: center;
    margin-top: 14px;
    font-size: 14px;
    font-weight: 600;
    color: rgba(255,255,255,0.65);
  }
  .btn-primary.onb { background: var(--white); color: var(--green-800); box-shadow: 0 8px 24px rgba(0,0,0,0.2); }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen onb-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;white&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;white&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;white&quot;/></svg>
      </div>
    </div>

    <div class=&quot;onb-art&quot;>
      <div class=&quot;blob b1&quot;></div>
      <div class=&quot;blob b2&quot;></div>
      <div class=&quot;people-cluster&quot;>
        <img class=&quot;pc-avatar&quot; style=&quot;width:84px;height:84px;top:10px;left:20px;&quot; src=&quot;https://i.pravatar.cc/160?img=47&quot; alt=&quot;&quot;>
        <img class=&quot;pc-avatar&quot; style=&quot;width:64px;height:64px;top:0px;right:10px;&quot; src=&quot;https://i.pravatar.cc/160?img=12&quot; alt=&quot;&quot;>
        <img class=&quot;pc-avatar&quot; style=&quot;width:70px;height:70px;bottom:10px;left:0px;&quot; src=&quot;https://i.pravatar.cc/160?img=33&quot; alt=&quot;&quot;>
        <img class=&quot;pc-avatar&quot; style=&quot;width:76px;height:76px;bottom:0px;right:0px;&quot; src=&quot;https://i.pravatar.cc/160?img=21&quot; alt=&quot;&quot;>
        <div class=&quot;pc-avatar&quot; style=&quot;width:54px;height:54px;top:70px;left:80px;background:var(--coral-500);display:flex;align-items:center;justify-content:center;&quot;>
          <svg width=&quot;24&quot; height=&quot;24&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.6l-1-1a5.5 5.5 0 0 0-7.8 7.8l1 1L12 21l7.8-7.6 1-1a5.5 5.5 0 0 0 0-7.8z&quot; fill=&quot;white&quot;/></svg>
        </div>
      </div>
    </div>

    <div class=&quot;onb-content&quot;>
      <div class=&quot;logo-mark&quot;>
        <svg width=&quot;28&quot; height=&quot;28&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;9&quot; stroke=&quot;white&quot; stroke-width=&quot;2&quot;/><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;3.2&quot; fill=&quot;white&quot;/></svg>
      </div>
      <h1 class=&quot;onb-title&quot;>Willkommen bei<br>Circle</h1>
      <p class=&quot;onb-sub&quot;>Lerne Menschen kennen, die deine Interessen teilen — bei echten Aktivitäten, nicht beim Wischen.</p>
    </div>

    <div class=&quot;onb-footer&quot;>
      <div class=&quot;dots&quot;>
        <span class=&quot;dot active&quot;></span><span class=&quot;dot&quot;></span><span class=&quot;dot&quot;></span><span class=&quot;dot&quot;></span>
      </div>
      <button class=&quot;btn btn-primary onb&quot;>Los geht's</button>
      <div class=&quot;onb-skip&quot;>Ich habe bereits ein Konto</div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-02">
      <div class="screen-label">02 · Onboarding — Intro</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .onb2-screen { background: var(--green-50); }
  .onb2-header { padding: 18px 20px 4px; flex-shrink: 0; }
  .onb2-skip-link { font-size: 14px; font-weight: 700; color: var(--ink-500); }

  .onb2-hero { padding: 8px 28px 0; flex-shrink: 0; }
  .onb2-title { font-size: 25px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); line-height: 1.25; }

  .feature-list { padding: 28px 24px 0; display: flex; flex-direction: column; gap: 14px; flex: 1; overflow: hidden; }
  .feature-card {
    background: var(--white);
    border: 1px solid var(--ink-100);
    border-radius: var(--r-lg);
    padding: 18px;
    display: flex;
    gap: 16px;
    align-items: flex-start;
    box-shadow: var(--shadow-sm);
  }
  .feature-icon {
    width: 48px; height: 48px;
    border-radius: 14px;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .feature-icon.green { background: var(--green-100); color: var(--green-700); }
  .feature-icon.coral { background: var(--coral-100); color: var(--coral-600); }
  .feature-text-title { font-size: 15.5px; font-weight: 700; color: var(--ink-900); }
  .feature-text-sub { font-size: 13.5px; color: var(--ink-500); margin-top: 3px; line-height: 1.4; }

  .onb-footer { padding: 20px 24px 40px; flex-shrink: 0; }
  .dots { display: flex; justify-content: center; gap: 6px; margin-bottom: 20px; }
  .dot { width: 7px; height: 7px; border-radius: 50%; background: var(--green-200); }
  .dot.active { width: 20px; background: var(--green-700); border-radius: 4px; }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen onb2-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;onb2-header row-between&quot;>
      <div></div>
      <div class=&quot;onb2-skip-link&quot;>Überspringen</div>
    </div>

    <div class=&quot;onb2-hero&quot;>
      <div class=&quot;text-micro&quot; style=&quot;color:var(--coral-600);&quot;>So funktioniert Circle</div>
      <h1 class=&quot;onb2-title mt-8&quot;>Drei Schritte zu echten Freundschaften.</h1>
    </div>

    <div class=&quot;feature-list&quot;>
      <div class=&quot;feature-card&quot;>
        <div class=&quot;feature-icon green&quot;>
          <svg width=&quot;22&quot; height=&quot;22&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;9&quot; cy=&quot;8&quot; r=&quot;3.2&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;17&quot; cy=&quot;9&quot; r=&quot;2.6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M3.5 19c0-3 2.5-5 5.5-5s5.5 2 5.5 5&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/><path d=&quot;M15 14.5c2.2 0.2 4 1.8 4 4.5&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        </div>
        <div>
          <div class=&quot;feature-text-title&quot;>Tritt einer Gruppe bei</div>
          <div class=&quot;feature-text-sub&quot;>Finde Menschen mit deinen Interessen — von Fotografie bis Brettspiele.</div>
        </div>
      </div>

      <div class=&quot;feature-card&quot;>
        <div class=&quot;feature-icon coral&quot;>
          <svg width=&quot;22&quot; height=&quot;22&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><rect x=&quot;4&quot; y=&quot;5&quot; width=&quot;16&quot; height=&quot;15&quot; rx=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4 9.5h16&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M8 3v3M16 3v3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        </div>
        <div>
          <div class=&quot;feature-text-title&quot;>Nimm an Aktivitäten teil</div>
          <div class=&quot;feature-text-sub&quot;>Café-Treffen, Spaziergänge, Spieleabende — echte Termine, echte Orte.</div>
        </div>
      </div>

      <div class=&quot;feature-card&quot;>
        <div class=&quot;feature-icon green&quot;>
          <svg width=&quot;22&quot; height=&quot;22&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.6l-1-1a5.5 5.5 0 0 0-7.8 7.8l1 1L12 21l7.8-7.6 1-1a5.5 5.5 0 0 0 0-7.8z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.6&quot; stroke-linejoin=&quot;round&quot;/></svg>
        </div>
        <div>
          <div class=&quot;feature-text-title&quot;>Lerne neue Freunde kennen</div>
          <div class=&quot;feature-text-sub&quot;>Speichere Kontakte nach dem Treffen und bleibt einfach in Verbindung.</div>
        </div>
      </div>
    </div>

    <div class=&quot;onb-footer&quot;>
      <div class=&quot;dots&quot;>
        <span class=&quot;dot&quot;></span><span class=&quot;dot active&quot;></span><span class=&quot;dot&quot;></span><span class=&quot;dot&quot;></span>
      </div>
      <button class=&quot;btn btn-primary&quot;>Weiter</button>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-03">
      <div class="screen-label">03 · Onboarding — Interessen</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .onb3-screen { background: var(--ink-50); }
  .onb3-header { padding: 8px 20px 0; flex-shrink: 0; }
  .progress-track { height: 4px; background: var(--ink-100); border-radius: var(--r-pill); margin-top: 14px; overflow: hidden; }
  .progress-fill { height: 100%; width: 60%; background: var(--green-600); border-radius: var(--r-pill); }

  .onb3-hero { padding: 20px 20px 0; flex-shrink: 0; }
  .onb3-title { font-size: 24px; font-weight: 800; color: var(--ink-900); letter-spacing: -0.4px; }
  .onb3-sub { font-size: 14.5px; color: var(--ink-500); margin-top: 6px; }

  .interest-grid {
    flex: 1;
    overflow-y: auto;
    padding: 22px 20px 16px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
    align-content: start;
  }
  .interest-tile {
    position: relative;
    border-radius: var(--r-md);
    padding: 16px 14px;
    border: 1.5px solid var(--ink-150, var(--ink-100));
    background: var(--white);
    display: flex;
    flex-direction: column;
    gap: 10px;
    min-height: 92px;
    justify-content: space-between;
  }
  .interest-tile .emoji { font-size: 24px; }
  .interest-tile .label { font-size: 14px; font-weight: 700; color: var(--ink-900); }
  .interest-tile.selected {
    border-color: var(--green-600);
    background: var(--green-50);
  }
  .check-mark {
    position: absolute;
    top: 10px; right: 10px;
    width: 20px; height: 20px;
    border-radius: 50%;
    background: var(--green-600);
    display: flex; align-items: center; justify-content: center;
  }

  .onb-footer { padding: 16px 20px 36px; flex-shrink: 0; background: var(--ink-50); border-top: 1px solid var(--ink-100); }
  .selected-count { font-size: 13px; color: var(--ink-500); text-align: center; margin-bottom: 12px; font-weight: 600; }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen onb3-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;onb3-header&quot;>
      <div class=&quot;row-between&quot;>
        <div class=&quot;nav-back&quot;>
          <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M15 18l-6-6 6-6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        </div>
        <div class=&quot;text-small-strong&quot;>Schritt 3 von 5</div>
      </div>
      <div class=&quot;progress-track&quot;><div class=&quot;progress-fill&quot;></div></div>
    </div>

    <div class=&quot;onb3-hero&quot;>
      <h1 class=&quot;onb3-title&quot;>Was interessiert dich?</h1>
      <p class=&quot;onb3-sub&quot;>Wähle mindestens 3 Interessen — wir zeigen dir passende Gruppen &amp; Aktivitäten.</p>
    </div>

    <div class=&quot;interest-grid&quot;>
      <div class=&quot;interest-tile selected&quot;>
        <div class=&quot;check-mark&quot;><svg width=&quot;11&quot; height=&quot;11&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M5 13l5 5L20 7&quot; stroke=&quot;white&quot; stroke-width=&quot;3&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg></div>
        <span class=&quot;emoji&quot;>📷</span>
        <span class=&quot;label&quot;>Fotografie &amp; Spaziergänge</span>
      </div>
      <div class=&quot;interest-tile&quot;>
        <span class=&quot;emoji&quot;>🎮</span>
        <span class=&quot;label&quot;>Gaming Community</span>
      </div>
      <div class=&quot;interest-tile selected&quot;>
        <div class=&quot;check-mark&quot;><svg width=&quot;11&quot; height=&quot;11&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M5 13l5 5L20 7&quot; stroke=&quot;white&quot; stroke-width=&quot;3&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg></div>
        <span class=&quot;emoji&quot;>📚</span>
        <span class=&quot;label&quot;>Bücherclub</span>
      </div>
      <div class=&quot;interest-tile&quot;>
        <span class=&quot;emoji&quot;>🏋️</span>
        <span class=&quot;label&quot;>Fitness Buddies</span>
      </div>
      <div class=&quot;interest-tile selected&quot;>
        <div class=&quot;check-mark&quot;><svg width=&quot;11&quot; height=&quot;11&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M5 13l5 5L20 7&quot; stroke=&quot;white&quot; stroke-width=&quot;3&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg></div>
        <span class=&quot;emoji&quot;>☕</span>
        <span class=&quot;label&quot;>Café &amp; Lernen</span>
      </div>
      <div class=&quot;interest-tile&quot;>
        <span class=&quot;emoji&quot;>🎲</span>
        <span class=&quot;label&quot;>Brettspielabend</span>
      </div>
      <div class=&quot;interest-tile&quot;>
        <span class=&quot;emoji&quot;>🍳</span>
        <span class=&quot;label&quot;>Kochen &amp; Backen</span>
      </div>
      <div class=&quot;interest-tile&quot;>
        <span class=&quot;emoji&quot;>🎨</span>
        <span class=&quot;label&quot;>Kunst &amp; Kreativität</span>
      </div>
      <div class=&quot;interest-tile&quot;>
        <span class=&quot;emoji&quot;>🌳</span>
        <span class=&quot;label&quot;>Natur &amp; Wandern</span>
      </div>
      <div class=&quot;interest-tile&quot;>
        <span class=&quot;emoji&quot;>🎵</span>
        <span class=&quot;label&quot;>Musik &amp; Konzerte</span>
      </div>
    </div>

    <div class=&quot;onb-footer&quot;>
      <div class=&quot;selected-count&quot;>3 Interessen ausgewählt</div>
      <button class=&quot;btn btn-primary&quot;>Weiter</button>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-04">
      <div class="screen-label">04 · Onboarding — Profil erstellen</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .onb4-screen { background: var(--ink-50); }
  .onb4-header { padding: 8px 20px 0; flex-shrink: 0; }
  .progress-track { height: 4px; background: var(--ink-100); border-radius: var(--r-pill); margin-top: 14px; overflow: hidden; }
  .progress-fill { height: 100%; width: 90%; background: var(--green-600); border-radius: var(--r-pill); }

  .onb4-hero { padding: 20px 20px 0; flex-shrink: 0; }
  .onb4-title { font-size: 24px; font-weight: 800; color: var(--ink-900); letter-spacing: -0.4px; }
  .onb4-sub { font-size: 14.5px; color: var(--ink-500); margin-top: 6px; }

  .onb4-form { flex: 1; overflow-y: auto; padding: 26px 24px 16px; }

  .avatar-upload {
    width: 100px; height: 100px;
    border-radius: 50%;
    margin: 0 auto 26px;
    position: relative;
    background: var(--green-100);
    display: flex; align-items: center; justify-content: center;
    border: 2px dashed var(--green-300);
  }
  .avatar-upload .cam-badge {
    position: absolute;
    bottom: -2px; right: -2px;
    width: 34px; height: 34px;
    border-radius: 50%;
    background: var(--coral-500);
    border: 3px solid var(--ink-50);
    display: flex; align-items: center; justify-content: center;
  }

  .field-group { margin-bottom: 18px; }
  .field-label { font-size: 13px; font-weight: 700; color: var(--ink-700); margin-bottom: 8px; display: block; }
  textarea.text-field { resize: none; height: 88px; font-family: var(--font-base); }
  .char-count { text-align: right; font-size: 12px; color: var(--ink-400); margin-top: 6px; }

  .interest-tags { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 4px; }

  .onb-footer { padding: 16px 24px 36px; flex-shrink: 0; background: var(--ink-50); border-top: 1px solid var(--ink-100); }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen onb4-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;onb4-header&quot;>
      <div class=&quot;row-between&quot;>
        <div class=&quot;nav-back&quot;>
          <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M15 18l-6-6 6-6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        </div>
        <div class=&quot;text-small-strong&quot;>Schritt 5 von 5</div>
      </div>
      <div class=&quot;progress-track&quot;><div class=&quot;progress-fill&quot;></div></div>
    </div>

    <div class=&quot;onb4-hero&quot;>
      <h1 class=&quot;onb4-title&quot;>Erstelle dein Profil</h1>
      <p class=&quot;onb4-sub&quot;>So lernen dich andere Mitglieder vor dem Treffen kennen.</p>
    </div>

    <div class=&quot;onb4-form&quot;>
      <div class=&quot;avatar-upload&quot;>
        <svg width=&quot;32&quot; height=&quot;32&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M4 7a2 2 0 0 1 2-2h2l1.5-2h5L16 5h2a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V7z&quot; stroke=&quot;var(--green-600)&quot; stroke-width=&quot;1.6&quot;/><circle cx=&quot;12&quot; cy=&quot;13&quot; r=&quot;3.4&quot; stroke=&quot;var(--green-600)&quot; stroke-width=&quot;1.6&quot;/></svg>
        <div class=&quot;cam-badge&quot;>
          <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M4 7a2 2 0 0 1 2-2h2l1.5-2h5L16 5h2a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V7z&quot; stroke=&quot;white&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;13&quot; r=&quot;3&quot; stroke=&quot;white&quot; stroke-width=&quot;1.8&quot;/></svg>
        </div>
      </div>

      <div class=&quot;field-group&quot;>
        <label class=&quot;field-label&quot;>Name</label>
        <input class=&quot;text-field&quot; type=&quot;text&quot; value=&quot;Mia Hoffmann&quot; placeholder=&quot;Dein Name&quot;>
      </div>

      <div class=&quot;field-group&quot;>
        <label class=&quot;field-label&quot;>Alter</label>
        <input class=&quot;text-field&quot; type=&quot;text&quot; value=&quot;27&quot; placeholder=&quot;Dein Alter&quot;>
      </div>

      <div class=&quot;field-group&quot;>
        <label class=&quot;field-label&quot;>Über mich</label>
        <textarea class=&quot;text-field&quot; placeholder=&quot;Erzähl etwas über dich…&quot;>Lernbegeisterte Designstudentin auf der Suche nach Café-Buddies &amp; Buchclub-Freunden ☕📚</textarea>
        <div class=&quot;char-count&quot;>78 / 150</div>
      </div>

      <div class=&quot;field-group&quot; style=&quot;margin-bottom:4px;&quot;>
        <label class=&quot;field-label&quot;>Deine Interessen</label>
        <div class=&quot;interest-tags&quot;>
          <span class=&quot;chip&quot;>📷 Fotografie</span>
          <span class=&quot;chip&quot;>📚 Bücherclub</span>
          <span class=&quot;chip&quot;>☕ Café &amp; Lernen</span>
          <span class=&quot;chip outline&quot;>+ Mehr</span>
        </div>
      </div>
    </div>

    <div class=&quot;onb-footer&quot;>
      <button class=&quot;btn btn-primary&quot;>Profil erstellen</button>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-05">
      <div class="screen-label">05 · Home</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .home-screen { background: var(--ink-50); }

  .home-header { padding: 14px 20px 0; flex-shrink: 0; }
  .greeting-row { display: flex; align-items: center; justify-content: space-between; }
  .greeting-text { font-size: 13.5px; color: var(--ink-500); font-weight: 600; }
  .greeting-name { font-size: 22px; font-weight: 800; color: var(--ink-900); letter-spacing: -0.3px; margin-top: 2px; }
  .header-actions { display: flex; gap: 10px; }

  .home-search { padding: 16px 20px 0; flex-shrink: 0; }

  .home-scroll { padding-top: 20px; }

  /* Spontaneous activity notification banner (Scenario 3) */
  .notif-banner {
    margin: 0 20px 22px;
    background: linear-gradient(120deg, var(--coral-500), var(--coral-600));
    border-radius: var(--r-lg);
    padding: 16px;
    display: flex;
    gap: 12px;
    align-items: flex-start;
    box-shadow: var(--shadow-coral);
    position: relative;
    overflow: hidden;
  }
  .notif-banner::after {
    content: &quot;&quot;;
    position: absolute;
    width: 120px; height: 120px;
    background: rgba(255,255,255,0.10);
    border-radius: 50%;
    top: -50px; right: -30px;
  }
  .notif-icon {
    width: 38px; height: 38px;
    border-radius: 50%;
    background: rgba(255,255,255,0.22);
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .notif-title { font-size: 14px; font-weight: 800; color: var(--white); }
  .notif-text { font-size: 13px; color: rgba(255,255,255,0.92); margin-top: 2px; line-height: 1.4; }
  .notif-cta { margin-top: 10px; display: inline-flex; align-items: center; gap: 4px; font-size: 13px; font-weight: 800; color: var(--white); }

  .section { margin-bottom: 28px; }
  .section-header { display: flex; align-items: baseline; justify-content: space-between; padding: 0 20px; margin-bottom: 14px; }
  .section-title { font-size: 18px; font-weight: 800; color: var(--ink-900); letter-spacing: -0.2px; }
  .section-link { font-size: 13px; font-weight: 700; color: var(--green-700); }

  /* Quick actions */
  .quick-actions { display: flex; gap: 12px; padding: 0 20px; }
  .qa-item {
    flex: 1;
    background: var(--white);
    border: 1px solid var(--ink-100);
    border-radius: var(--r-md);
    padding: 14px 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 8px;
    box-shadow: var(--shadow-sm);
  }
  .qa-icon {
    width: 38px; height: 38px;
    border-radius: 12px;
    display: flex; align-items: center; justify-content: center;
  }
  .qa-icon.coral { background: var(--coral-100); color: var(--coral-600); }
  .qa-icon.green { background: var(--green-100); color: var(--green-700); }
  .qa-label { font-size: 11.5px; font-weight: 700; color: var(--ink-700); text-align: center; line-height: 1.25; }

  /* Activity cards (horizontal scroll) */
  .h-scroll { display: flex; gap: 14px; overflow-x: auto; padding: 0 20px 4px; scrollbar-width: none; }
  .h-scroll::-webkit-scrollbar { display: none; }

  .activity-card {
    flex: 0 0 248px;
    background: var(--white);
    border-radius: var(--r-lg);
    border: 1px solid var(--ink-100);
    overflow: hidden;
    box-shadow: var(--shadow-sm);
  }
  .activity-card .ac-image {
    height: 110px;
    background-size: cover;
    background-position: center;
    position: relative;
  }
  .activity-card .ac-time-badge {
    position: absolute;
    top: 10px; left: 10px;
    background: rgba(255,255,255,0.95);
    color: var(--ink-900);
    font-size: 11px;
    font-weight: 800;
    padding: 5px 10px;
    border-radius: var(--r-pill);
  }
  .activity-card .ac-body { padding: 14px; }
  .activity-card .ac-title { font-size: 15px; font-weight: 700; color: var(--ink-900); }
  .activity-card .ac-meta { display:flex; align-items:center; gap:5px; font-size: 12.5px; color: var(--ink-500); margin-top: 5px; }
  .ac-footer { display: flex; align-items: center; justify-content: space-between; margin-top: 12px; }
  .ac-avatars-count { display: flex; align-items: center; gap: 6px; }
  .ac-avatars-count .avatar { width: 22px; height: 22px; }
  .ac-avatars-count span { font-size: 12px; color: var(--ink-500); font-weight: 600; }

  /* Group cards */
  .group-card {
    margin: 0 20px 12px;
    background: var(--white);
    border: 1px solid var(--ink-100);
    border-radius: var(--r-lg);
    padding: 14px;
    display: flex;
    gap: 14px;
    align-items: center;
    box-shadow: var(--shadow-sm);
  }
  .group-thumb { width: 56px; height: 56px; border-radius: 16px; object-fit: cover; flex-shrink: 0; }
  .group-info { flex: 1; min-width: 0; }
  .group-name { font-size: 15px; font-weight: 700; color: var(--ink-900); }
  .group-meta { font-size: 12.5px; color: var(--ink-500); margin-top: 3px; }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen home-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;home-header&quot;>
      <div class=&quot;greeting-row&quot;>
        <div>
          <div class=&quot;greeting-text&quot;>Guten Morgen 👋</div>
          <div class=&quot;greeting-name&quot;>Mia Hoffmann</div>
        </div>
        <div class=&quot;header-actions&quot;>
          <div class=&quot;icon-btn&quot; style=&quot;position:relative;&quot;>
            <svg width=&quot;18&quot; height=&quot;18&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M18 8a6 6 0 1 0-12 0c0 3-1 5-2 6.5h16C19 13 18 11 18 8z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.7&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/><path d=&quot;M9.5 17a2.5 2.5 0 0 0 5 0&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.7&quot; stroke-linecap=&quot;round&quot;/></svg>
            <span class=&quot;badge-dot&quot;></span>
          </div>
        </div>
      </div>
    </div>

    <div class=&quot;home-search&quot;>
      <div class=&quot;input-search&quot;>
        <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;11&quot; cy=&quot;11&quot; r=&quot;7&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot;/><path d=&quot;M21 21l-4.3-4.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot;/></svg>
        Gruppen, Aktivitäten suchen…
      </div>
    </div>

    <div class=&quot;scroll-area&quot;>
      <div class=&quot;home-scroll&quot;>

        <!-- Scenario 3: Mia bekommt Benachrichtigung über spontane Aktivität -->
        <div class=&quot;notif-banner&quot;>
          <div class=&quot;notif-icon&quot;>
            <svg width=&quot;18&quot; height=&quot;18&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M13 2L4 14h6l-1 8 9-12h-6l1-8z&quot; fill=&quot;white&quot;/></svg>
          </div>
          <div style=&quot;position:relative;z-index:1;&quot;>
            <div class=&quot;notif-title&quot;>Spontane Aktivität in deiner Nähe!</div>
            <div class=&quot;notif-text&quot;>&quot;Abendspaziergang am See&quot; startet heute in 2 Std. — 4 Plätze frei.</div>
            <div class=&quot;notif-cta&quot;>Jetzt beitreten
              <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M9 18l6-6-6-6&quot; stroke=&quot;white&quot; stroke-width=&quot;2.4&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
            </div>
          </div>
        </div>

        <!-- Quick Actions -->
        <div class=&quot;section&quot;>
          <div class=&quot;quick-actions&quot;>
            <div class=&quot;qa-item&quot;>
              <div class=&quot;qa-icon coral&quot;>
                <svg width=&quot;19&quot; height=&quot;19&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 5v14M5 12h14&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot;/></svg>
              </div>
              <div class=&quot;qa-label&quot;>Aktivität erstellen</div>
            </div>
            <div class=&quot;qa-item&quot;>
              <div class=&quot;qa-icon green&quot;>
                <svg width=&quot;19&quot; height=&quot;19&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;9&quot; cy=&quot;8&quot; r=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M3.5 19c0-3 2.5-5.2 5.5-5.2s5.5 2.2 5.5 5.2&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/><circle cx=&quot;17&quot; cy=&quot;9&quot; r=&quot;2.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
              </div>
              <div class=&quot;qa-label&quot;>Gruppen finden</div>
            </div>
            <div class=&quot;qa-item&quot;>
              <div class=&quot;qa-icon green&quot;>
                <svg width=&quot;19&quot; height=&quot;19&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M21 11.5a8.4 8.4 0 0 1-12.1 7.4L4 20l1.2-4.7A8.4 8.4 0 1 1 21 11.5z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
              </div>
              <div class=&quot;qa-label&quot;>Meine Chats</div>
            </div>
          </div>
        </div>

        <!-- Empfohlene Aktivitäten -->
        <div class=&quot;section&quot;>
          <div class=&quot;section-header&quot;>
            <div class=&quot;section-title&quot;>Aktivitäten für dich</div>
            <div class=&quot;section-link&quot;>Alle ansehen</div>
          </div>
          <div class=&quot;h-scroll&quot;>

            <!-- Scenario 1: Café &amp; Lernen -->
            <div class=&quot;activity-card&quot;>
              <div class=&quot;ac-image&quot; style=&quot;background-image:url('https://images.unsplash.com/photo-1521017432531-fbd92d768814?w=400&amp;h=220&amp;fit=crop');&quot;>
                <div class=&quot;ac-time-badge&quot;>Heute, 16:00</div>
              </div>
              <div class=&quot;ac-body&quot;>
                <div class=&quot;ac-title&quot;>Café &amp; Lernen</div>
                <div class=&quot;ac-meta&quot;>
                  <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
                  Bücherei-Café, Mitte
                </div>
                <div class=&quot;ac-footer&quot;>
                  <div class=&quot;ac-avatars-count&quot;>
                    <div class=&quot;avatar-stack&quot;>
                      <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=5&quot;>
                      <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=8&quot;>
                      <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=15&quot;>
                    </div>
                    <span>5/8</span>
                  </div>
                  <span class=&quot;chip&quot;>Bücherclub</span>
                </div>
              </div>
            </div>

            <div class=&quot;activity-card&quot;>
              <div class=&quot;ac-image&quot; style=&quot;background-image:url('https://images.unsplash.com/photo-1488998427799-e3d84e6ec1ec?w=400&amp;h=220&amp;fit=crop');&quot;>
                <div class=&quot;ac-time-badge&quot;>Sa, 14:00</div>
              </div>
              <div class=&quot;ac-body&quot;>
                <div class=&quot;ac-title&quot;>Fotospaziergang</div>
                <div class=&quot;ac-meta&quot;>
                  <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
                  Stadtpark Nord
                </div>
                <div class=&quot;ac-footer&quot;>
                  <div class=&quot;ac-avatars-count&quot;>
                    <div class=&quot;avatar-stack&quot;>
                      <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=22&quot;>
                      <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=31&quot;>
                    </div>
                    <span>6/10</span>
                  </div>
                  <span class=&quot;chip&quot;>Fotografie</span>
                </div>
              </div>
            </div>

            <div class=&quot;activity-card&quot;>
              <div class=&quot;ac-image&quot; style=&quot;background-image:url('https://images.unsplash.com/photo-1610890716171-6b1bb98ffd09?w=400&amp;h=220&amp;fit=crop');&quot;>
                <div class=&quot;ac-time-badge&quot;>So, 19:00</div>
              </div>
              <div class=&quot;ac-body&quot;>
                <div class=&quot;ac-title&quot;>Brettspielabend</div>
                <div class=&quot;ac-meta&quot;>
                  <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
                  Spielecafé König
                </div>
                <div class=&quot;ac-footer&quot;>
                  <div class=&quot;ac-avatars-count&quot;>
                    <div class=&quot;avatar-stack&quot;>
                      <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=44&quot;>
                      <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=9&quot;>
                    </div>
                    <span>4/6</span>
                  </div>
                  <span class=&quot;chip&quot;>Gaming</span>
                </div>
              </div>
            </div>

          </div>
        </div>

        <!-- Empfohlene Gruppen -->
        <div class=&quot;section&quot;>
          <div class=&quot;section-header&quot;>
            <div class=&quot;section-title&quot;>Gruppen für dich</div>
            <div class=&quot;section-link&quot;>Alle ansehen</div>
          </div>

          <div class=&quot;group-card&quot;>
            <img class=&quot;group-thumb&quot; src=&quot;https://images.unsplash.com/photo-1452587925148-ce544e77e70d?w=120&amp;h=120&amp;fit=crop&quot;>
            <div class=&quot;group-info&quot;>
              <div class=&quot;group-name&quot;>Fotografie &amp; Spaziergänge</div>
              <div class=&quot;group-meta&quot;>312 Mitglieder · 3 Aktivitäten diese Woche</div>
            </div>
            <button class=&quot;btn btn-pill-sm&quot;>Beitreten</button>
          </div>

          <div class=&quot;group-card&quot;>
            <img class=&quot;group-thumb&quot; src=&quot;https://images.unsplash.com/photo-1481627834876-b7833e8f5570?w=120&amp;h=120&amp;fit=crop&quot;>
            <div class=&quot;group-info&quot;>
              <div class=&quot;group-name&quot;>Bücherclub Berlin</div>
              <div class=&quot;group-meta&quot;>158 Mitglieder · 1 Aktivität diese Woche</div>
            </div>
            <button class=&quot;btn btn-pill-sm joined&quot;>Beigetreten</button>
          </div>

          <div class=&quot;group-card&quot;>
            <img class=&quot;group-thumb&quot; src=&quot;https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=120&amp;h=120&amp;fit=crop&quot;>
            <div class=&quot;group-info&quot;>
              <div class=&quot;group-name&quot;>Fitness Buddies</div>
              <div class=&quot;group-meta&quot;>204 Mitglieder · 5 Aktivitäten diese Woche</div>
            </div>
            <button class=&quot;btn btn-pill-sm&quot;>Beitreten</button>
          </div>

        </div>

      </div>
    </div>

    <!-- Tab Bar -->
    <div class=&quot;tab-bar&quot;>
      <div class=&quot;tab-item active&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M4 11.5L12 4l8 7.5&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/><path d=&quot;M6 10v9a1 1 0 0 0 1 1h3v-5a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v5h3a1 1 0 0 0 1-1v-9&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Home
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;9&quot; cy=&quot;8&quot; r=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M3 19c0-3 2.5-5.2 6-5.2s6 2.2 6 5.2&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/><circle cx=&quot;17.5&quot; cy=&quot;9&quot; r=&quot;2.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M14.5 14.2c2.6.3 4.5 2 4.5 4.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Gruppen
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><rect x=&quot;4&quot; y=&quot;5&quot; width=&quot;16&quot; height=&quot;15&quot; rx=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4 9.5h16&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M8 3v3M16 3v3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Aktivitäten
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.6l-1-1a5.5 5.5 0 0 0-7.8 7.8l1 1L12 21l7.8-7.6 1-1a5.5 5.5 0 0 0 0-7.8z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Kontakte
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;8&quot; r=&quot;3.6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4.5 20c0-4 3.4-6.8 7.5-6.8s7.5 2.8 7.5 6.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Profil
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-06">
      <div class="screen-label">06 · Gruppenübersicht</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .groups-screen { background: var(--ink-50); }

  .groups-header { padding: 14px 20px 0; flex-shrink: 0; }
  .page-title-row { display: flex; align-items: center; justify-content: space-between; }

  .groups-search { padding: 16px 20px 0; flex-shrink: 0; }

  .category-scroll { display: flex; gap: 10px; overflow-x: auto; padding: 16px 20px 4px; flex-shrink: 0; scrollbar-width: none; }
  .category-scroll::-webkit-scrollbar { display: none; }
  .cat-pill {
    flex-shrink: 0;
    padding: 9px 16px;
    border-radius: var(--r-pill);
    font-size: 13.5px;
    font-weight: 700;
    background: var(--white);
    color: var(--ink-600);
    border: 1px solid var(--ink-100);
  }
  .cat-pill.active { background: var(--green-700); color: var(--white); border-color: var(--green-700); }

  .groups-list { padding: 16px 20px 20px; }

  .result-count { font-size: 13px; color: var(--ink-500); font-weight: 600; margin-bottom: 14px; }

  .group-list-card {
    background: var(--white);
    border: 1px solid var(--ink-100);
    border-radius: var(--r-lg);
    margin-bottom: 14px;
    overflow: hidden;
    box-shadow: var(--shadow-sm);
  }
  .glc-cover { height: 96px; background-size: cover; background-position: center; position: relative; }
  .glc-cat-tag {
    position: absolute; top: 10px; left: 12px;
    background: rgba(255,255,255,0.95);
    color: var(--ink-900);
    font-size: 11px; font-weight: 800;
    padding: 5px 10px; border-radius: var(--r-pill);
  }
  .glc-body { padding: 14px; }
  .glc-title-row { display: flex; align-items: flex-start; justify-content: space-between; gap: 10px; }
  .glc-title { font-size: 16px; font-weight: 700; color: var(--ink-900); }
  .glc-desc { font-size: 13px; color: var(--ink-500); margin-top: 5px; line-height: 1.45; }
  .glc-footer { display: flex; align-items: center; justify-content: space-between; margin-top: 12px; }
  .glc-members { display: flex; align-items: center; gap: 8px; }
  .glc-members .avatar { width: 24px; height: 24px; }
  .glc-members span { font-size: 12.5px; color: var(--ink-500); font-weight: 600; }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen groups-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;groups-header&quot;>
      <div class=&quot;page-title-row&quot;>
        <h1 class=&quot;text-display&quot;>Gruppen</h1>
        <div class=&quot;icon-btn&quot;>
          <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 5v14M5 12h14&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot;/></svg>
        </div>
      </div>
    </div>

    <div class=&quot;groups-search&quot;>
      <div class=&quot;input-search&quot;>
        <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;11&quot; cy=&quot;11&quot; r=&quot;7&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot;/><path d=&quot;M21 21l-4.3-4.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot;/></svg>
        Gruppen durchsuchen…
      </div>
    </div>

    <div class=&quot;category-scroll&quot;>
      <div class=&quot;cat-pill active&quot;>Alle</div>
      <div class=&quot;cat-pill&quot;>📷 Fotografie</div>
      <div class=&quot;cat-pill&quot;>🎮 Gaming</div>
      <div class=&quot;cat-pill&quot;>📚 Bücher</div>
      <div class=&quot;cat-pill&quot;>🏋️ Fitness</div>
      <div class=&quot;cat-pill&quot;>☕ Café</div>
    </div>

    <div class=&quot;scroll-area&quot;>
      <div class=&quot;groups-list&quot;>

        <div class=&quot;result-count&quot;>38 Gruppen in deiner Nähe</div>

        <!-- Scenario 2: Tom tritt &quot;Fotografie &amp; Spaziergänge&quot; bei -->
        <div class=&quot;group-list-card&quot;>
          <div class=&quot;glc-cover&quot; style=&quot;background-image:url('https://images.unsplash.com/photo-1452587925148-ce544e77e70d?w=500&amp;h=240&amp;fit=crop');&quot;>
            <div class=&quot;glc-cat-tag&quot;>📷 Fotografie</div>
          </div>
          <div class=&quot;glc-body&quot;>
            <div class=&quot;glc-title-row&quot;>
              <div class=&quot;glc-title&quot;>Fotografie &amp; Spaziergänge</div>
            </div>
            <div class=&quot;glc-desc&quot;>Für alle, die gerne mit der Kamera unterwegs sind — von Smartphone bis Vollformat.</div>
            <div class=&quot;glc-footer&quot;>
              <div class=&quot;glc-members&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=22&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=31&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=14&quot;>
                </div>
                <span>312 Mitglieder</span>
              </div>
              <button class=&quot;btn btn-pill-sm&quot;>Beitreten</button>
            </div>
          </div>
        </div>

        <div class=&quot;group-list-card&quot;>
          <div class=&quot;glc-cover&quot; style=&quot;background-image:url('https://images.unsplash.com/photo-1542751371-adc38448a05e?w=500&amp;h=240&amp;fit=crop');&quot;>
            <div class=&quot;glc-cat-tag&quot;>🎮 Gaming</div>
          </div>
          <div class=&quot;glc-body&quot;>
            <div class=&quot;glc-title-row&quot;>
              <div class=&quot;glc-title&quot;>Gaming Community</div>
            </div>
            <div class=&quot;glc-desc&quot;>Brett-, Konsolen- und PC-Spiele — gemeinsam zocken statt alleine.</div>
            <div class=&quot;glc-footer&quot;>
              <div class=&quot;glc-members&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=44&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=9&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=51&quot;>
                </div>
                <span>271 Mitglieder</span>
              </div>
              <button class=&quot;btn btn-pill-sm&quot;>Beitreten</button>
            </div>
          </div>
        </div>

        <div class=&quot;group-list-card&quot;>
          <div class=&quot;glc-cover&quot; style=&quot;background-image:url('https://images.unsplash.com/photo-1481627834876-b7833e8f5570?w=500&amp;h=240&amp;fit=crop');&quot;>
            <div class=&quot;glc-cat-tag&quot;>📚 Bücher</div>
          </div>
          <div class=&quot;glc-body&quot;>
            <div class=&quot;glc-title-row&quot;>
              <div class=&quot;glc-title&quot;>Bücherclub Berlin</div>
            </div>
            <div class=&quot;glc-desc&quot;>Ein Buch im Monat, ein gemütliches Treffen — für Vielleser und Gelegenheitsleser.</div>
            <div class=&quot;glc-footer&quot;>
              <div class=&quot;glc-members&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=5&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=8&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=15&quot;>
                </div>
                <span>158 Mitglieder</span>
              </div>
              <button class=&quot;btn btn-pill-sm joined&quot;>Beigetreten</button>
            </div>
          </div>
        </div>

        <div class=&quot;group-list-card&quot;>
          <div class=&quot;glc-cover&quot; style=&quot;background-image:url('https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=500&amp;h=240&amp;fit=crop');&quot;>
            <div class=&quot;glc-cat-tag&quot;>🏋️ Fitness</div>
          </div>
          <div class=&quot;glc-body&quot;>
            <div class=&quot;glc-title-row&quot;>
              <div class=&quot;glc-title&quot;>Fitness Buddies</div>
            </div>
            <div class=&quot;glc-desc&quot;>Gemeinsam trainieren motiviert mehr — Laufen, Yoga, Outdoor-Workouts.</div>
            <div class=&quot;glc-footer&quot;>
              <div class=&quot;glc-members&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=33&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=21&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=47&quot;>
                </div>
                <span>204 Mitglieder</span>
              </div>
              <button class=&quot;btn btn-pill-sm&quot;>Beitreten</button>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- Tab Bar -->
    <div class=&quot;tab-bar&quot;>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M4 11.5L12 4l8 7.5&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/><path d=&quot;M6 10v9a1 1 0 0 0 1 1h3v-5a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v5h3a1 1 0 0 0 1-1v-9&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Home
      </div>
      <div class=&quot;tab-item active&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;9&quot; cy=&quot;8&quot; r=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M3 19c0-3 2.5-5.2 6-5.2s6 2.2 6 5.2&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/><circle cx=&quot;17.5&quot; cy=&quot;9&quot; r=&quot;2.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M14.5 14.2c2.6.3 4.5 2 4.5 4.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Gruppen
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><rect x=&quot;4&quot; y=&quot;5&quot; width=&quot;16&quot; height=&quot;15&quot; rx=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4 9.5h16&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M8 3v3M16 3v3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Aktivitäten
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.6l-1-1a5.5 5.5 0 0 0-7.8 7.8l1 1L12 21l7.8-7.6 1-1a5.5 5.5 0 0 0 0-7.8z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Kontakte
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;8&quot; r=&quot;3.6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4.5 20c0-4 3.4-6.8 7.5-6.8s7.5 2.8 7.5 6.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Profil
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-07">
      <div class="screen-label">07 · Gruppenprofil</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .group-profile-screen { background: var(--ink-50); }

  .gp-cover {
    height: 200px;
    flex-shrink: 0;
    background: url('https://images.unsplash.com/photo-1452587925148-ce544e77e70d?w=800&amp;h=420&amp;fit=crop') center/cover;
    position: relative;
  }
  .gp-cover::after {
    content: &quot;&quot;;
    position: absolute; inset: 0;
    background: linear-gradient(180deg, rgba(15,46,38,0.35) 0%, rgba(15,46,38,0.05) 40%, rgba(15,46,38,0.55) 100%);
  }
  .gp-cover-nav {
    position: absolute; top: 0; left: 0; right: 0;
    display: flex; align-items: center; justify-content: space-between;
    padding: 56px 16px 0;
    z-index: 2;
  }
  .gp-cover-nav .nav-back, .gp-cover-nav .icon-btn { background: rgba(255,255,255,0.92); border: none; }

  .gp-header-card {
    margin: -36px 20px 0;
    background: var(--white);
    border-radius: var(--r-lg);
    box-shadow: var(--shadow-md);
    padding: 18px 18px 16px;
    position: relative;
    z-index: 2;
    flex-shrink: 0;
  }
  .gp-cat-chip { margin-bottom: 8px; }
  .gp-title { font-size: 21px; font-weight: 800; color: var(--ink-900); letter-spacing: -0.3px; }
  .gp-members-row { display: flex; align-items: center; gap: 8px; margin-top: 8px; }
  .gp-members-row .avatar { width: 24px; height: 24px; }
  .gp-members-row span { font-size: 13px; color: var(--ink-500); font-weight: 600; }

  .gp-actions { display: flex; gap: 10px; margin-top: 16px; }
  .gp-actions .btn-primary { padding: 13px; font-size: 14.5px; }
  .gp-actions .btn-outline { padding: 13px 16px; }

  .gp-content { padding: 22px 20px 20px; }

  .gp-section { margin-bottom: 26px; }
  .gp-section-title { font-size: 17px; font-weight: 800; color: var(--ink-900); margin-bottom: 12px; }

  .gp-desc-text { font-size: 14.5px; color: var(--ink-700); line-height: 1.6; }

  .member-avatars-grid { display: flex; gap: -8px; }
  .member-row { display: flex; align-items: center; justify-content: space-between; }
  .member-row .avatar-stack .avatar { width: 38px; height: 38px; }

  .chat-preview-card {
    background: var(--white);
    border: 1px solid var(--ink-100);
    border-radius: var(--r-lg);
    padding: 14px;
    box-shadow: var(--shadow-sm);
  }
  .chat-msg-row { display: flex; gap: 10px; margin-bottom: 12px; }
  .chat-msg-row:last-child { margin-bottom: 0; }
  .chat-msg-row .avatar { width: 32px; height: 32px; }
  .chat-msg-bubble { background: var(--green-50); border-radius: 12px; padding: 8px 12px; font-size: 13.5px; color: var(--ink-800); max-width: 220px; }
  .chat-msg-name { font-size: 11.5px; font-weight: 700; color: var(--ink-500); margin-bottom: 3px; }
  .chat-cta-row { display: flex; align-items: center; justify-content: space-between; margin-top: 12px; padding-top: 12px; border-top: 1px solid var(--ink-100); }

  .gp-activity-card {
    display: flex; gap: 12px; align-items: center;
    background: var(--white); border: 1px solid var(--ink-100); border-radius: var(--r-md);
    padding: 12px; margin-bottom: 10px; box-shadow: var(--shadow-sm);
  }
  .gp-act-date {
    width: 48px; height: 48px; border-radius: 12px; background: var(--green-50);
    display: flex; flex-direction: column; align-items: center; justify-content: center; flex-shrink: 0;
  }
  .gp-act-date .d-num { font-size: 16px; font-weight: 800; color: var(--green-700); line-height: 1; }
  .gp-act-date .d-mon { font-size: 10px; font-weight: 700; color: var(--green-600); text-transform: uppercase; }
  .gp-act-title { font-size: 14px; font-weight: 700; color: var(--ink-900); }
  .gp-act-meta { font-size: 12px; color: var(--ink-500); margin-top: 2px; }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen group-profile-screen&quot;>

    <div class=&quot;gp-cover&quot;>
      <div class=&quot;gp-cover-nav&quot;>
        <div class=&quot;nav-back&quot;>
          <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M15 18l-6-6 6-6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        </div>
        <div class=&quot;icon-btn&quot;>
          <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;5&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/><circle cx=&quot;12&quot; cy=&quot;19&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/></svg>
        </div>
      </div>
    </div>

    <div class=&quot;scroll-area&quot;>

      <div class=&quot;gp-header-card&quot;>
        <span class=&quot;chip gp-cat-chip&quot;>📷 Fotografie</span>
        <div class=&quot;gp-title&quot;>Fotografie &amp; Spaziergänge</div>
        <div class=&quot;gp-members-row&quot;>
          <div class=&quot;avatar-stack&quot;>
            <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=22&quot;>
            <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=31&quot;>
            <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=14&quot;>
          </div>
          <span>312 Mitglieder · 12 online</span>
        </div>
        <div class=&quot;gp-actions&quot;>
          <button class=&quot;btn btn-primary&quot; style=&quot;flex:1;&quot;>Gruppe beigetreten ✓</button>
          <button class=&quot;btn-outline icon-btn&quot; style=&quot;border-radius: var(--r-pill); width:48px; height:48px;&quot;>
            <svg width=&quot;18&quot; height=&quot;18&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M21 11.5a8.4 8.4 0 0 1-12.1 7.4L4 20l1.2-4.7A8.4 8.4 0 1 1 21 11.5z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
          </button>
        </div>
      </div>

      <div class=&quot;gp-content&quot;>

        <div class=&quot;gp-section&quot;>
          <div class=&quot;gp-section-title&quot;>Über die Gruppe</div>
          <p class=&quot;gp-desc-text&quot;>Für alle, die gerne mit der Kamera unterwegs sind — egal ob Smartphone oder Vollformat. Wir treffen uns regelmäßig zu Fotospaziergängen, tauschen Tipps aus und entdecken neue Orte in der Stadt. Anfänger und Profis willkommen!</p>
        </div>

        <div class=&quot;gp-section&quot;>
          <div class=&quot;row-between&quot; style=&quot;margin-bottom:12px;&quot;>
            <div class=&quot;gp-section-title&quot; style=&quot;margin-bottom:0;&quot;>Mitglieder</div>
            <div class=&quot;section-link&quot; style=&quot;color:var(--green-700); font-size:13px; font-weight:700;&quot;>Alle 312</div>
          </div>
          <div class=&quot;member-row&quot;>
            <div class=&quot;avatar-stack&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=22&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=31&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=14&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=51&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=9&quot;>
              <div class=&quot;avatar&quot; style=&quot;width:38px;height:38px;border:2px solid white;margin-left:-10px; background:var(--green-700); display:flex; align-items:center; justify-content:center; font-size:11px; font-weight:800; color:white;&quot;>+307</div>
            </div>
          </div>
        </div>

        <!-- Scenario 2: Tom entdeckt Fotospaziergang in der Gruppe -->
        <div class=&quot;gp-section&quot;>
          <div class=&quot;row-between&quot; style=&quot;margin-bottom:12px;&quot;>
            <div class=&quot;gp-section-title&quot; style=&quot;margin-bottom:0;&quot;>Aktivitäten der Gruppe</div>
          </div>

          <div class=&quot;gp-activity-card&quot;>
            <div class=&quot;gp-act-date&quot;><span class=&quot;d-num&quot;>22</span><span class=&quot;d-mon&quot;>Jun</span></div>
            <div style=&quot;flex:1;&quot;>
              <div class=&quot;gp-act-title&quot;>Fotospaziergang — Stadtpark Nord</div>
              <div class=&quot;gp-act-meta&quot;>14:00 Uhr · 6/10 Teilnehmer</div>
            </div>
            <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M9 18l6-6-6-6&quot; stroke=&quot;var(--ink-300)&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
          </div>

          <div class=&quot;gp-activity-card&quot;>
            <div class=&quot;gp-act-date&quot;><span class=&quot;d-num&quot;>28</span><span class=&quot;d-mon&quot;>Jun</span></div>
            <div style=&quot;flex:1;&quot;>
              <div class=&quot;gp-act-title&quot;>Goldene-Stunde-Shooting</div>
              <div class=&quot;gp-act-meta&quot;>19:30 Uhr · 3/8 Teilnehmer</div>
            </div>
            <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M9 18l6-6-6-6&quot; stroke=&quot;var(--ink-300)&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
          </div>
        </div>

        <div class=&quot;gp-section&quot; style=&quot;margin-bottom:0;&quot;>
          <div class=&quot;gp-section-title&quot;>Gruppenchat</div>
          <div class=&quot;chat-preview-card&quot;>
            <div class=&quot;chat-msg-row&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=31&quot;>
              <div>
                <div class=&quot;chat-msg-name&quot;>Tom Weber</div>
                <div class=&quot;chat-msg-bubble&quot;>Wer ist am Samstag beim Fotospaziergang dabei? 📸</div>
              </div>
            </div>
            <div class=&quot;chat-msg-row&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=14&quot;>
              <div>
                <div class=&quot;chat-msg-name&quot;>Lena K.</div>
                <div class=&quot;chat-msg-bubble&quot;>Ich bin dabei! Bringe mein neues Objektiv mit 😊</div>
              </div>
            </div>
            <div class=&quot;chat-cta-row&quot;>
              <span class=&quot;text-small&quot; style=&quot;color:var(--ink-400);&quot;>14 neue Nachrichten</span>
              <span class=&quot;section-link&quot; style=&quot;color:var(--green-700); font-size:13px; font-weight:700;&quot;>Chat öffnen →</span>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- Tab Bar -->
    <div class=&quot;tab-bar&quot;>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M4 11.5L12 4l8 7.5&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/><path d=&quot;M6 10v9a1 1 0 0 0 1 1h3v-5a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v5h3a1 1 0 0 0 1-1v-9&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Home
      </div>
      <div class=&quot;tab-item active&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;9&quot; cy=&quot;8&quot; r=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M3 19c0-3 2.5-5.2 6-5.2s6 2.2 6 5.2&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/><circle cx=&quot;17.5&quot; cy=&quot;9&quot; r=&quot;2.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M14.5 14.2c2.6.3 4.5 2 4.5 4.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Gruppen
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><rect x=&quot;4&quot; y=&quot;5&quot; width=&quot;16&quot; height=&quot;15&quot; rx=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4 9.5h16&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M8 3v3M16 3v3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Aktivitäten
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.6l-1-1a5.5 5.5 0 0 0-7.8 7.8l1 1L12 21l7.8-7.6 1-1a5.5 5.5 0 0 0 0-7.8z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Kontakte
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;8&quot; r=&quot;3.6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4.5 20c0-4 3.4-6.8 7.5-6.8s7.5 2.8 7.5 6.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Profil
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-08">
      <div class="screen-label">08 · Gruppenchat</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .chat-screen { background: var(--ink-50); }

  .chat-header {
    display: flex; align-items: center; gap: 12px;
    padding: 8px 16px 14px;
    flex-shrink: 0;
    background: var(--ink-50);
    border-bottom: 1px solid var(--ink-100);
  }
  .chat-header-info { flex: 1; display: flex; flex-direction: column; }
  .chat-header-name { font-size: 15.5px; font-weight: 700; color: var(--ink-900); }
  .chat-header-meta { font-size: 12px; color: var(--ink-500); margin-top: 1px; }
  .chat-header-avatar { width: 38px; height: 38px; border-radius: 12px; object-fit: cover; }

  .chat-body { flex: 1; overflow-y: auto; padding: 18px 16px; display: flex; flex-direction: column; gap: 16px; scrollbar-width: none; }
  .chat-body::-webkit-scrollbar { display: none; }

  .day-divider { text-align: center; margin: 4px 0 8px; }
  .day-divider span { font-size: 11.5px; font-weight: 700; color: var(--ink-400); background: var(--ink-100); padding: 4px 12px; border-radius: var(--r-pill); }

  .msg-row { display: flex; gap: 10px; max-width: 85%; }
  .msg-row.mine { align-self: flex-end; flex-direction: row-reverse; }
  .msg-row .avatar { width: 30px; height: 30px; flex-shrink: 0; }
  .msg-content { display: flex; flex-direction: column; gap: 4px; }
  .msg-row.mine .msg-content { align-items: flex-end; }
  .msg-author { font-size: 11.5px; font-weight: 700; color: var(--green-700); }
  .msg-bubble {
    background: var(--white);
    border: 1px solid var(--ink-100);
    border-radius: 16px 16px 16px 4px;
    padding: 10px 14px;
    font-size: 14.5px;
    color: var(--ink-800);
    line-height: 1.45;
  }
  .msg-row.mine .msg-bubble {
    background: var(--green-700);
    color: var(--white);
    border: none;
    border-radius: 16px 16px 4px 16px;
  }
  .msg-time { font-size: 11px; color: var(--ink-400); padding: 0 4px; }

  .system-msg { text-align: center; font-size: 12px; color: var(--ink-500); margin: 4px 0; }
  .system-msg b { color: var(--ink-700); }

  .activity-share-card {
    background: var(--white);
    border: 1.5px solid var(--green-300);
    border-radius: var(--r-md);
    padding: 12px;
    display: flex;
    gap: 12px;
    align-items: center;
    max-width: 260px;
  }
  .asc-icon { width: 40px; height: 40px; border-radius: 10px; background: var(--green-100); color: var(--green-700); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .asc-title { font-size: 13.5px; font-weight: 700; color: var(--ink-900); }
  .asc-meta { font-size: 11.5px; color: var(--ink-500); margin-top: 2px; }

  .chat-input-bar {
    display: flex; align-items: center; gap: 10px;
    padding: 10px 14px;
    background: var(--white);
    border-top: 1px solid var(--ink-100);
    flex-shrink: 0;
  }
  .chat-plus-btn { width: 34px; height: 34px; border-radius: 50%; background: var(--green-50); color: var(--green-700); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .chat-text-input {
    flex: 1;
    background: var(--ink-50);
    border: 1px solid var(--ink-100);
    border-radius: var(--r-pill);
    padding: 11px 16px;
    font-size: 14.5px;
    color: var(--ink-400);
  }
  .chat-send-btn { width: 36px; height: 36px; border-radius: 50%; background: var(--coral-500); color: var(--white); display: flex; align-items: center; justify-content: center; flex-shrink: 0; box-shadow: var(--shadow-coral); }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen chat-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;chat-header&quot;>
      <div class=&quot;nav-back&quot;>
        <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M15 18l-6-6 6-6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
      </div>
      <img class=&quot;chat-header-avatar&quot; src=&quot;https://images.unsplash.com/photo-1452587925148-ce544e77e70d?w=100&amp;h=100&amp;fit=crop&quot;>
      <div class=&quot;chat-header-info&quot;>
        <div class=&quot;chat-header-name&quot;>Fotografie &amp; Spaziergänge</div>
        <div class=&quot;chat-header-meta&quot;>312 Mitglieder · 12 online</div>
      </div>
      <div class=&quot;icon-btn&quot;>
        <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;5&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/><circle cx=&quot;12&quot; cy=&quot;19&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/></svg>
      </div>
    </div>

    <div class=&quot;chat-body&quot;>

      <div class=&quot;day-divider&quot;><span>Heute</span></div>

      <div class=&quot;system-msg&quot;><b>Lena K.</b> ist der Gruppe beigetreten</div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=31&quot;>
        <div class=&quot;msg-content&quot;>
          <span class=&quot;msg-author&quot;>Tom Weber</span>
          <div class=&quot;msg-bubble&quot;>Wer ist am Samstag beim Fotospaziergang dabei? 📸</div>
          <span class=&quot;msg-time&quot;>10:14</span>
        </div>
      </div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=14&quot;>
        <div class=&quot;msg-content&quot;>
          <span class=&quot;msg-author&quot;>Lena K.</span>
          <div class=&quot;msg-bubble&quot;>Ich bin dabei! Bringe mein neues Objektiv mit 😊</div>
          <span class=&quot;msg-time&quot;>10:16</span>
        </div>
      </div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=14&quot;>
        <div class=&quot;msg-content&quot;>
          <div class=&quot;activity-share-card&quot;>
            <div class=&quot;asc-icon&quot;>
              <svg width=&quot;20&quot; height=&quot;20&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><rect x=&quot;4&quot; y=&quot;5&quot; width=&quot;16&quot; height=&quot;15&quot; rx=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4 9.5h16&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
            </div>
            <div>
              <div class=&quot;asc-title&quot;>Fotospaziergang</div>
              <div class=&quot;asc-meta&quot;>Sa, 14:00 · Stadtpark Nord</div>
            </div>
          </div>
          <span class=&quot;msg-time&quot;>10:17</span>
        </div>
      </div>

      <div class=&quot;msg-row mine&quot;>
        <div class=&quot;msg-content&quot;>
          <div class=&quot;msg-bubble&quot;>Super, bin auch dabei! Treffpunkt am Eingang Nord? 🌳</div>
          <span class=&quot;msg-time&quot;>10:22</span>
        </div>
      </div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=31&quot;>
        <div class=&quot;msg-content&quot;>
          <span class=&quot;msg-author&quot;>Tom Weber</span>
          <div class=&quot;msg-bubble&quot;>Genau, 14 Uhr am Haupteingang. Bis Samstag! 👋</div>
          <span class=&quot;msg-time&quot;>10:25</span>
        </div>
      </div>

    </div>

    <div class=&quot;chat-input-bar&quot;>
      <div class=&quot;chat-plus-btn&quot;>
        <svg width=&quot;18&quot; height=&quot;18&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 5v14M5 12h14&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot;/></svg>
      </div>
      <div class=&quot;chat-text-input&quot;>Nachricht schreiben…</div>
      <div class=&quot;chat-send-btn&quot;>
        <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M5 12h14M13 6l6 6-6 6&quot; stroke=&quot;white&quot; stroke-width=&quot;2.3&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-09">
      <div class="screen-label">09 · Aktivitätenübersicht</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .acts-screen { background: var(--ink-50); }

  .acts-header { padding: 14px 20px 0; flex-shrink: 0; }
  .page-title-row { display: flex; align-items: center; justify-content: space-between; }

  .acts-search { padding: 16px 20px 0; flex-shrink: 0; }

  .category-scroll { display: flex; gap: 10px; overflow-x: auto; padding: 16px 20px 4px; flex-shrink: 0; scrollbar-width: none; }
  .category-scroll::-webkit-scrollbar { display: none; }
  .cat-pill { flex-shrink: 0; padding: 9px 16px; border-radius: var(--r-pill); font-size: 13.5px; font-weight: 700; background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-100); }
  .cat-pill.active { background: var(--green-700); color: var(--white); border-color: var(--green-700); }

  .acts-list { padding: 16px 20px 100px; position: relative; }

  .date-group-label { font-size: 13px; font-weight: 800; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.5px; margin: 18px 0 10px; }
  .date-group-label:first-child { margin-top: 4px; }

  .act-list-card {
    display: flex; gap: 14px;
    background: var(--white); border: 1px solid var(--ink-100); border-radius: var(--r-lg);
    padding: 14px; margin-bottom: 12px; box-shadow: var(--shadow-sm);
    align-items: stretch;
  }
  .alc-time-col {
    display: flex; flex-direction: column; align-items: center; justify-content: center;
    width: 52px; flex-shrink: 0; border-right: 1px solid var(--ink-100); padding-right: 12px;
  }
  .alc-time-col .t1 { font-size: 15px; font-weight: 800; color: var(--ink-900); }
  .alc-time-col .t2 { font-size: 11px; color: var(--ink-400); font-weight: 600; }
  .alc-info { flex: 1; min-width: 0; }
  .alc-title { font-size: 15px; font-weight: 700; color: var(--ink-900); }
  .alc-meta { display: flex; align-items: center; gap: 5px; font-size: 12.5px; color: var(--ink-500); margin-top: 5px; }
  .alc-footer { display: flex; align-items: center; justify-content: space-between; margin-top: 10px; }
  .alc-avatars .avatar { width: 22px; height: 22px; }
  .alc-spots { font-size: 11.5px; font-weight: 700; color: var(--green-700); background: var(--green-50); padding: 4px 9px; border-radius: var(--r-pill); }
  .alc-spots.urgent { color: var(--coral-600); background: var(--coral-50); }

  .fab-create {
    position: absolute;
    bottom: 100px;
    right: 20px;
    width: 56px; height: 56px;
    border-radius: 50%;
    background: var(--coral-500);
    color: white;
    display: flex; align-items: center; justify-content: center;
    box-shadow: var(--shadow-coral);
    z-index: 40;
  }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen acts-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;acts-header&quot;>
      <div class=&quot;page-title-row&quot;>
        <h1 class=&quot;text-display&quot;>Aktivitäten</h1>
        <div class=&quot;icon-btn&quot;>
          <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M4 6h16M7 12h10M10 18h4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot;/></svg>
        </div>
      </div>
    </div>

    <div class=&quot;acts-search&quot;>
      <div class=&quot;input-search&quot;>
        <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;11&quot; cy=&quot;11&quot; r=&quot;7&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot;/><path d=&quot;M21 21l-4.3-4.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot;/></svg>
        Aktivitäten durchsuchen…
      </div>
    </div>

    <div class=&quot;category-scroll&quot;>
      <div class=&quot;cat-pill active&quot;>Alle</div>
      <div class=&quot;cat-pill&quot;>Heute</div>
      <div class=&quot;cat-pill&quot;>Diese Woche</div>
      <div class=&quot;cat-pill&quot;>In der Nähe</div>
    </div>

    <div class=&quot;scroll-area&quot;>
      <div class=&quot;acts-list&quot;>

        <div class=&quot;date-group-label&quot;>Heute</div>

        <!-- Scenario 1: Café &amp; Lernen -->
        <div class=&quot;act-list-card&quot;>
          <div class=&quot;alc-time-col&quot;><span class=&quot;t1&quot;>16:00</span><span class=&quot;t2&quot;>Uhr</span></div>
          <div class=&quot;alc-info&quot;>
            <div class=&quot;alc-title&quot;>Café &amp; Lernen</div>
            <div class=&quot;alc-meta&quot;>
              <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
              Bücherei-Café, Mitte
            </div>
            <div class=&quot;alc-footer&quot;>
              <div class=&quot;alc-avatars&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=5&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=8&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=15&quot;>
                </div>
              </div>
              <span class=&quot;alc-spots&quot;>5/8 Plätze</span>
            </div>
          </div>
        </div>

        <div class=&quot;act-list-card&quot;>
          <div class=&quot;alc-time-col&quot;><span class=&quot;t1&quot;>19:00</span><span class=&quot;t2&quot;>Uhr</span></div>
          <div class=&quot;alc-info&quot;>
            <div class=&quot;alc-title&quot;>Abendspaziergang am See</div>
            <div class=&quot;alc-meta&quot;>
              <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
              Weißer See
            </div>
            <div class=&quot;alc-footer&quot;>
              <div class=&quot;alc-avatars&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=12&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=47&quot;>
                </div>
              </div>
              <span class=&quot;alc-spots urgent&quot;>Nur noch 4 Plätze</span>
            </div>
          </div>
        </div>

        <div class=&quot;date-group-label&quot;>Samstag, 21. Juni</div>

        <!-- Scenario 2: Fotospaziergang -->
        <div class=&quot;act-list-card&quot;>
          <div class=&quot;alc-time-col&quot;><span class=&quot;t1&quot;>14:00</span><span class=&quot;t2&quot;>Uhr</span></div>
          <div class=&quot;alc-info&quot;>
            <div class=&quot;alc-title&quot;>Fotospaziergang</div>
            <div class=&quot;alc-meta&quot;>
              <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
              Stadtpark Nord
            </div>
            <div class=&quot;alc-footer&quot;>
              <div class=&quot;alc-avatars&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=22&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=31&quot;>
                </div>
              </div>
              <span class=&quot;alc-spots&quot;>6/10 Plätze</span>
            </div>
          </div>
        </div>

        <div class=&quot;date-group-label&quot;>Sonntag, 22. Juni</div>

        <div class=&quot;act-list-card&quot;>
          <div class=&quot;alc-time-col&quot;><span class=&quot;t1&quot;>19:30</span><span class=&quot;t2&quot;>Uhr</span></div>
          <div class=&quot;alc-info&quot;>
            <div class=&quot;alc-title&quot;>Brettspielabend</div>
            <div class=&quot;alc-meta&quot;>
              <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
              Spielecafé König
            </div>
            <div class=&quot;alc-footer&quot;>
              <div class=&quot;alc-avatars&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=44&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=9&quot;>
                </div>
              </div>
              <span class=&quot;alc-spots&quot;>4/6 Plätze</span>
            </div>
          </div>
        </div>

        <div class=&quot;act-list-card&quot;>
          <div class=&quot;alc-time-col&quot;><span class=&quot;t1&quot;>10:00</span><span class=&quot;t2&quot;>Uhr</span></div>
          <div class=&quot;alc-info&quot;>
            <div class=&quot;alc-title&quot;>Wandern im Grunewald</div>
            <div class=&quot;alc-meta&quot;>
              <svg width=&quot;13&quot; height=&quot;13&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
              Grunewald, S-Bahn
            </div>
            <div class=&quot;alc-footer&quot;>
              <div class=&quot;alc-avatars&quot;>
                <div class=&quot;avatar-stack&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=33&quot;>
                  <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=21&quot;>
                </div>
              </div>
              <span class=&quot;alc-spots&quot;>8/12 Plätze</span>
            </div>
          </div>
        </div>

        <div class=&quot;fab-create&quot;>
          <svg width=&quot;24&quot; height=&quot;24&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 5v14M5 12h14&quot; stroke=&quot;white&quot; stroke-width=&quot;2.4&quot; stroke-linecap=&quot;round&quot;/></svg>
        </div>

      </div>
    </div>

    <!-- Tab Bar -->
    <div class=&quot;tab-bar&quot;>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M4 11.5L12 4l8 7.5&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/><path d=&quot;M6 10v9a1 1 0 0 0 1 1h3v-5a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v5h3a1 1 0 0 0 1-1v-9&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Home
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;9&quot; cy=&quot;8&quot; r=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M3 19c0-3 2.5-5.2 6-5.2s6 2.2 6 5.2&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/><circle cx=&quot;17.5&quot; cy=&quot;9&quot; r=&quot;2.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M14.5 14.2c2.6.3 4.5 2 4.5 4.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Gruppen
      </div>
      <div class=&quot;tab-item active&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><rect x=&quot;4&quot; y=&quot;5&quot; width=&quot;16&quot; height=&quot;15&quot; rx=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4 9.5h16&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M8 3v3M16 3v3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Aktivitäten
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.6l-1-1a5.5 5.5 0 0 0-7.8 7.8l1 1L12 21l7.8-7.6 1-1a5.5 5.5 0 0 0 0-7.8z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Kontakte
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;8&quot; r=&quot;3.6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4.5 20c0-4 3.4-6.8 7.5-6.8s7.5 2.8 7.5 6.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Profil
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-10">
      <div class="screen-label">10 · Aktivitätsdetails</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .act-detail-screen { background: var(--ink-50); }

  .ad-cover {
    height: 220px;
    flex-shrink: 0;
    background: url('https://images.unsplash.com/photo-1521017432531-fbd92d768814?w=800&amp;h=440&amp;fit=crop') center/cover;
    position: relative;
  }
  .ad-cover::after { content:&quot;&quot;; position:absolute; inset:0; background: linear-gradient(180deg, rgba(15,46,38,0.4) 0%, rgba(15,46,38,0.0) 35%, rgba(15,46,38,0.15) 100%); }
  .ad-cover-nav { position: absolute; top: 0; left: 0; right: 0; display: flex; align-items: center; justify-content: space-between; padding: 56px 16px 0; z-index: 2; }
  .ad-cover-nav .nav-back, .ad-cover-nav .icon-btn { background: rgba(255,255,255,0.92); border: none; }

  .ad-header-card {
    margin: -32px 20px 0;
    background: var(--white);
    border-radius: var(--r-lg);
    box-shadow: var(--shadow-md);
    padding: 18px;
    position: relative; z-index: 2;
    flex-shrink: 0;
  }
  .ad-chip-row { display: flex; gap: 8px; margin-bottom: 10px; }
  .ad-title { font-size: 21px; font-weight: 800; color: var(--ink-900); letter-spacing: -0.3px; line-height: 1.25; }

  .ad-meta-list { margin-top: 14px; display: flex; flex-direction: column; gap: 10px; }
  .ad-meta-item { display: flex; gap: 10px; align-items: flex-start; }
  .ad-meta-icon { width: 34px; height: 34px; border-radius: 10px; background: var(--green-50); color: var(--green-700); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .ad-meta-text-main { font-size: 14px; font-weight: 700; color: var(--ink-900); }
  .ad-meta-text-sub { font-size: 12.5px; color: var(--ink-500); margin-top: 1px; }

  .ad-content { padding: 22px 20px 110px; }
  .ad-section { margin-bottom: 24px; }
  .ad-section-title { font-size: 16.5px; font-weight: 800; color: var(--ink-900); margin-bottom: 10px; }
  .ad-desc { font-size: 14.5px; color: var(--ink-700); line-height: 1.6; }

  .organizer-row { display: flex; align-items: center; gap: 12px; background: var(--white); border: 1px solid var(--ink-100); border-radius: var(--r-md); padding: 12px 14px; box-shadow: var(--shadow-sm); }
  .organizer-row .avatar { width: 42px; height: 42px; }
  .organizer-name { font-size: 14px; font-weight: 700; color: var(--ink-900); }
  .organizer-role { font-size: 12px; color: var(--ink-500); margin-top: 1px; }

  .participants-row { display: flex; align-items: center; justify-content: space-between; }
  .participants-row .avatar-stack .avatar { width: 40px; height: 40px; }

  .map-placeholder {
    height: 130px;
    border-radius: var(--r-md);
    background: linear-gradient(135deg, var(--green-100), var(--green-50));
    border: 1px solid var(--ink-100);
    position: relative;
    overflow: hidden;
    margin-top: 10px;
  }
  .map-placeholder svg { position: absolute; top: 50%; left: 50%; transform: translate(-50%,-60%); }

  .sticky-footer {
    position: absolute; bottom: 0; left: 0; right: 0;
    background: var(--white);
    border-top: 1px solid var(--ink-100);
    padding: 14px 20px 28px;
    display: flex; align-items: center; gap: 14px;
    z-index: 40;
  }
  .footer-spots { flex-shrink: 0; }
  .footer-spots .num { font-size: 18px; font-weight: 800; color: var(--green-700); }
  .footer-spots .lbl { font-size: 11px; color: var(--ink-500); font-weight: 600; }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen act-detail-screen&quot;>

    <div class=&quot;ad-cover&quot;>
      <div class=&quot;ad-cover-nav&quot;>
        <div class=&quot;nav-back&quot;>
          <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M15 18l-6-6 6-6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        </div>
        <div class=&quot;icon-btn&quot;>
          <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M17 4H7a1 1 0 0 0-1 1v15l6-3.5 6 3.5V5a1 1 0 0 0-1-1z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
        </div>
      </div>
    </div>

    <div class=&quot;scroll-area&quot; style=&quot;position:relative;&quot;>

      <div class=&quot;ad-header-card&quot;>
        <div class=&quot;ad-chip-row&quot;>
          <span class=&quot;chip&quot;>📚 Bücherclub</span>
          <span class=&quot;chip coral&quot;>Heute</span>
        </div>
        <div class=&quot;ad-title&quot;>Café &amp; Lernen</div>

        <div class=&quot;ad-meta-list&quot;>
          <div class=&quot;ad-meta-item&quot;>
            <div class=&quot;ad-meta-icon&quot;>
              <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;9&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M12 7v5l3.5 2&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
            </div>
            <div>
              <div class=&quot;ad-meta-text-main&quot;>Heute, 16:00 – 18:00 Uhr</div>
              <div class=&quot;ad-meta-text-sub&quot;>Dauer ca. 2 Stunden</div>
            </div>
          </div>
          <div class=&quot;ad-meta-item&quot;>
            <div class=&quot;ad-meta-icon&quot;>
              <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/></svg>
            </div>
            <div>
              <div class=&quot;ad-meta-text-main&quot;>Bücherei-Café, Mitte</div>
              <div class=&quot;ad-meta-text-sub&quot;>Dorotheenstraße 12, Berlin · 1,2 km entfernt</div>
            </div>
          </div>
        </div>
      </div>

      <div class=&quot;ad-content&quot;>

        <div class=&quot;ad-section&quot;>
          <div class=&quot;ad-section-title&quot;>Beschreibung</div>
          <p class=&quot;ad-desc&quot;>Gemeinsam lernen statt allein zuhause! Wir treffen uns im gemütlichen Bücherei-Café zum konzentrierten Arbeiten — mit Pausen für Austausch und Kaffee. Egal ob Uni, Sprachen oder Weiterbildung: jede:r ist willkommen. Laptop oder Bücher mitbringen.</p>
        </div>

        <div class=&quot;ad-section&quot;>
          <div class=&quot;ad-section-title&quot;>Organisiert von</div>
          <div class=&quot;organizer-row&quot;>
            <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=5&quot;>
            <div>
              <div class=&quot;organizer-name&quot;>Sarah Klein</div>
              <div class=&quot;organizer-role&quot;>Mitglied seit 8 Monaten · 14 Aktivitäten</div>
            </div>
          </div>
        </div>

        <div class=&quot;ad-section&quot;>
          <div class=&quot;row-between&quot; style=&quot;margin-bottom:10px;&quot;>
            <div class=&quot;ad-section-title&quot; style=&quot;margin-bottom:0;&quot;>Teilnehmer</div>
            <span class=&quot;text-small-strong&quot; style=&quot;color:var(--green-700);&quot;>5 von 8</span>
          </div>
          <div class=&quot;participants-row&quot;>
            <div class=&quot;avatar-stack&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=5&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=8&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=15&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=23&quot;>
              <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=27&quot;>
            </div>
          </div>
        </div>

        <div class=&quot;ad-section&quot; style=&quot;margin-bottom:0;&quot;>
          <div class=&quot;ad-section-title&quot;>Ort</div>
          <div class=&quot;map-placeholder&quot;>
            <svg width=&quot;180&quot; height=&quot;100&quot; viewBox=&quot;0 0 180 100&quot; fill=&quot;none&quot;>
              <path d=&quot;M0 70 Q 40 50, 80 65 T 180 55&quot; stroke=&quot;var(--green-300)&quot; stroke-width=&quot;3&quot; fill=&quot;none&quot;/>
              <path d=&quot;M0 40 Q 60 20, 120 35 T 180 30&quot; stroke=&quot;var(--green-300)&quot; stroke-width=&quot;2&quot; fill=&quot;none&quot;/>
            </svg>
            <svg width=&quot;30&quot; height=&quot;30&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; style=&quot;position:absolute; top:50%; left:50%; transform:translate(-50%,-100%);&quot;>
              <path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; fill=&quot;var(--coral-500)&quot;/>
              <circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.6&quot; fill=&quot;white&quot;/>
            </svg>
          </div>
        </div>

      </div>

      <div class=&quot;sticky-footer&quot;>
        <div class=&quot;footer-spots&quot;>
          <div class=&quot;num&quot;>5/8</div>
          <div class=&quot;lbl&quot;>Plätze belegt</div>
        </div>
        <button class=&quot;btn btn-primary&quot; style=&quot;flex:1;&quot;>Jetzt teilnehmen</button>
      </div>

    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-11">
      <div class="screen-label">11 · Aktivitätschat</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .act-chat-screen { background: var(--ink-50); }

  .chat-header { display: flex; align-items: center; gap: 12px; padding: 8px 16px 14px; flex-shrink: 0; background: var(--ink-50); border-bottom: 1px solid var(--ink-100); }
  .chat-header-info { flex: 1; display: flex; flex-direction: column; }
  .chat-header-name { font-size: 15.5px; font-weight: 700; color: var(--ink-900); }
  .chat-header-meta { font-size: 12px; color: var(--ink-500); margin-top: 1px; display:flex; align-items:center; gap:5px; }
  .chat-header-avatar { width: 38px; height: 38px; border-radius: 12px; object-fit: cover; }

  .activity-pin-card {
    margin: 12px 16px 0;
    background: var(--green-700);
    border-radius: var(--r-md);
    padding: 12px 14px;
    display: flex; align-items: center; gap: 10px;
    flex-shrink: 0;
  }
  .apc-icon { width: 32px; height: 32px; border-radius: 9px; background: rgba(255,255,255,0.18); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .apc-text-main { font-size: 13px; font-weight: 700; color: white; }
  .apc-text-sub { font-size: 11.5px; color: rgba(255,255,255,0.75); margin-top: 1px; }

  .chat-body { flex: 1; overflow-y: auto; padding: 16px 16px; display: flex; flex-direction: column; gap: 16px; scrollbar-width: none; }
  .chat-body::-webkit-scrollbar { display: none; }

  .day-divider { text-align: center; margin: 4px 0 8px; }
  .day-divider span { font-size: 11.5px; font-weight: 700; color: var(--ink-400); background: var(--ink-100); padding: 4px 12px; border-radius: var(--r-pill); }

  .msg-row { display: flex; gap: 10px; max-width: 85%; }
  .msg-row.mine { align-self: flex-end; flex-direction: row-reverse; }
  .msg-row .avatar { width: 30px; height: 30px; flex-shrink: 0; }
  .msg-content { display: flex; flex-direction: column; gap: 4px; }
  .msg-row.mine .msg-content { align-items: flex-end; }
  .msg-author { font-size: 11.5px; font-weight: 700; color: var(--green-700); }
  .msg-bubble { background: var(--white); border: 1px solid var(--ink-100); border-radius: 16px 16px 16px 4px; padding: 10px 14px; font-size: 14.5px; color: var(--ink-800); line-height: 1.45; }
  .msg-row.mine .msg-bubble { background: var(--green-700); color: var(--white); border: none; border-radius: 16px 16px 4px 16px; }
  .msg-time { font-size: 11px; color: var(--ink-400); padding: 0 4px; }
  .system-msg { text-align: center; font-size: 12px; color: var(--ink-500); margin: 4px 0; }
  .system-msg b { color: var(--ink-700); }

  .chat-input-bar { display: flex; align-items: center; gap: 10px; padding: 10px 14px; background: var(--white); border-top: 1px solid var(--ink-100); flex-shrink: 0; }
  .chat-plus-btn { width: 34px; height: 34px; border-radius: 50%; background: var(--green-50); color: var(--green-700); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .chat-text-input { flex: 1; background: var(--ink-50); border: 1px solid var(--ink-100); border-radius: var(--r-pill); padding: 11px 16px; font-size: 14.5px; color: var(--ink-900); }
  .chat-send-btn { width: 36px; height: 36px; border-radius: 50%; background: var(--coral-500); color: var(--white); display: flex; align-items: center; justify-content: center; flex-shrink: 0; box-shadow: var(--shadow-coral); }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen act-chat-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;chat-header&quot;>
      <div class=&quot;nav-back&quot;>
        <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M15 18l-6-6 6-6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
      </div>
      <img class=&quot;chat-header-avatar&quot; src=&quot;https://images.unsplash.com/photo-1521017432531-fbd92d768814?w=100&amp;h=100&amp;fit=crop&quot;>
      <div class=&quot;chat-header-info&quot;>
        <div class=&quot;chat-header-name&quot;>Café &amp; Lernen</div>
        <div class=&quot;chat-header-meta&quot;>
          <div class=&quot;avatar-stack&quot; style=&quot;margin-right:2px;&quot;>
            <img class=&quot;avatar&quot; style=&quot;width:16px;height:16px;&quot; src=&quot;https://i.pravatar.cc/40?img=5&quot;>
            <img class=&quot;avatar&quot; style=&quot;width:16px;height:16px;&quot; src=&quot;https://i.pravatar.cc/40?img=8&quot;>
          </div>
          5 Teilnehmer
        </div>
      </div>
      <div class=&quot;icon-btn&quot;>
        <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;5&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/><circle cx=&quot;12&quot; cy=&quot;19&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/></svg>
      </div>
    </div>

    <div class=&quot;activity-pin-card&quot;>
      <div class=&quot;apc-icon&quot;>
        <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 21s-7-5.5-7-11a7 7 0 1 1 14 0c0 5.5-7 11-7 11z&quot; stroke=&quot;white&quot; stroke-width=&quot;1.8&quot;/><circle cx=&quot;12&quot; cy=&quot;10&quot; r=&quot;2.4&quot; stroke=&quot;white&quot; stroke-width=&quot;1.8&quot;/></svg>
      </div>
      <div>
        <div class=&quot;apc-text-main&quot;>Heute, 16:00 Uhr · Bücherei-Café</div>
        <div class=&quot;apc-text-sub&quot;>Dorotheenstraße 12, Berlin-Mitte</div>
      </div>
    </div>

    <div class=&quot;chat-body&quot;>

      <div class=&quot;day-divider&quot;><span>Heute</span></div>
      <div class=&quot;system-msg&quot;><b>Mia Hoffmann</b> ist der Aktivität beigetreten</div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=5&quot;>
        <div class=&quot;msg-content&quot;>
          <span class=&quot;msg-author&quot;>Sarah Klein</span>
          <div class=&quot;msg-bubble&quot;>Hey zusammen! Freue mich auf heute 😊 Ich sitze meist am Tisch hinten links.</div>
          <span class=&quot;msg-time&quot;>11:02</span>
        </div>
      </div>

      <div class=&quot;msg-row mine&quot;>
        <div class=&quot;msg-content&quot;>
          <div class=&quot;msg-bubble&quot;>Hi! Bin auch gespannt, bringe meine Statistik-Unterlagen mit 📊</div>
          <span class=&quot;msg-time&quot;>11:14</span>
        </div>
      </div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=23&quot;>
        <div class=&quot;msg-content&quot;>
          <span class=&quot;msg-author&quot;>Jonas P.</span>
          <div class=&quot;msg-bubble&quot;>Perfekt, ich brauch auch Lerngesellschaft fürs Examen 🙌</div>
          <span class=&quot;msg-time&quot;>11:20</span>
        </div>
      </div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=5&quot;>
        <div class=&quot;msg-content&quot;>
          <span class=&quot;msg-author&quot;>Sarah Klein</span>
          <div class=&quot;msg-bubble&quot;>Bis später dann! Ich reserviere uns einen großen Tisch.</div>
          <span class=&quot;msg-time&quot;>11:25</span>
        </div>
      </div>

    </div>

    <div class=&quot;chat-input-bar&quot;>
      <div class=&quot;chat-plus-btn&quot;>
        <svg width=&quot;18&quot; height=&quot;18&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 5v14M5 12h14&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot;/></svg>
      </div>
      <div class=&quot;chat-text-input&quot; style=&quot;color:var(--ink-400);&quot;>Nachricht schreiben…</div>
      <div class=&quot;chat-send-btn&quot;>
        <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M5 12h14M13 6l6 6-6 6&quot; stroke=&quot;white&quot; stroke-width=&quot;2.3&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-12">
      <div class="screen-label">12 · Kontakte</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .contacts-screen { background: var(--ink-50); }

  .contacts-header { padding: 14px 20px 0; flex-shrink: 0; }
  .contacts-search { padding: 16px 20px 0; flex-shrink: 0; }

  .new-contacts-section { padding: 20px 20px 4px; flex-shrink: 0; }
  .nc-title { font-size: 15px; font-weight: 800; color: var(--ink-900); margin-bottom: 4px; }
  .nc-sub { font-size: 12.5px; color: var(--ink-500); margin-bottom: 12px; }

  .new-contact-card {
    flex: 0 0 132px;
    background: var(--white);
    border: 1.5px solid var(--coral-100);
    border-radius: var(--r-lg);
    padding: 14px 12px;
    display: flex; flex-direction: column; align-items: center;
    text-align: center;
    box-shadow: var(--shadow-sm);
  }
  .new-contact-card .avatar { width: 56px; height: 56px; margin-bottom: 10px; }
  .new-contact-card .nc-name { font-size: 13px; font-weight: 700; color: var(--ink-900); }
  .new-contact-card .nc-context { font-size: 10.5px; color: var(--ink-500); margin-top: 3px; line-height: 1.3; }
  .new-contact-card .btn-pill-sm { margin-top: 10px; width: 100%; font-size: 12px; padding: 8px; background: var(--coral-500); }

  .nc-scroll { display: flex; gap: 12px; overflow-x: auto; padding: 0 20px 4px; scrollbar-width: none; }
  .nc-scroll::-webkit-scrollbar { display: none; }

  .section-divider { height: 8px; background: transparent; }

  .friends-list-header { padding: 22px 20px 12px; flex-shrink: 0; display: flex; align-items: center; justify-content: space-between; }
  .friends-count { font-size: 17px; font-weight: 800; color: var(--ink-900); }

  .friends-list { padding: 0 20px 20px; }
  .alpha-divider { font-size: 12px; font-weight: 800; color: var(--ink-400); padding: 14px 4px 8px; }

  .friend-row {
    display: flex; align-items: center; gap: 12px;
    padding: 11px 4px;
    border-bottom: 1px solid var(--ink-100);
  }
  .friend-row:last-child { border-bottom: none; }
  .friend-row .avatar { width: 46px; height: 46px; position: relative; }
  .online-dot { position: absolute; bottom: -1px; right: -1px; width: 12px; height: 12px; border-radius: 50%; background: var(--green-500); border: 2px solid white; }
  .friend-info { flex: 1; min-width: 0; }
  .friend-name { font-size: 14.5px; font-weight: 700; color: var(--ink-900); }
  .friend-context { font-size: 12px; color: var(--ink-500); margin-top: 2px; }
  .friend-chat-btn { width: 34px; height: 34px; border-radius: 50%; background: var(--green-50); color: var(--green-700); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen contacts-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;contacts-header&quot;>
      <h1 class=&quot;text-display&quot;>Kontakte</h1>
    </div>

    <div class=&quot;contacts-search&quot;>
      <div class=&quot;input-search&quot;>
        <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;11&quot; cy=&quot;11&quot; r=&quot;7&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot;/><path d=&quot;M21 21l-4.3-4.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot;/></svg>
        Kontakte durchsuchen…
      </div>
    </div>

    <div class=&quot;scroll-area&quot;>

      <!-- Scenario 1 follow-up: Mia speichert neue Kontakte nach &quot;Café &amp; Lernen&quot; -->
      <div class=&quot;new-contacts-section&quot;>
        <div class=&quot;nc-title&quot;>Neu kennengelernt 🎉</div>
        <div class=&quot;nc-sub&quot;>Nach &quot;Café &amp; Lernen&quot; — jetzt als Kontakt speichern</div>
      </div>
      <div class=&quot;nc-scroll&quot;>
        <div class=&quot;new-contact-card&quot;>
          <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/100?img=5&quot;>
          <div class=&quot;nc-name&quot;>Sarah Klein</div>
          <div class=&quot;nc-context&quot;>Café &amp; Lernen · Heute</div>
          <button class=&quot;btn btn-pill-sm&quot;>Speichern</button>
        </div>
        <div class=&quot;new-contact-card&quot;>
          <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/100?img=23&quot;>
          <div class=&quot;nc-name&quot;>Jonas P.</div>
          <div class=&quot;nc-context&quot;>Café &amp; Lernen · Heute</div>
          <button class=&quot;btn btn-pill-sm&quot;>Speichern</button>
        </div>
        <div class=&quot;new-contact-card&quot;>
          <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/100?img=27&quot;>
          <div class=&quot;nc-name&quot;>Anna Müller</div>
          <div class=&quot;nc-context&quot;>Café &amp; Lernen · Heute</div>
          <button class=&quot;btn btn-pill-sm&quot;>Speichern</button>
        </div>
      </div>

      <div class=&quot;friends-list-header&quot;>
        <div class=&quot;friends-count&quot;>Meine Freunde</div>
        <span class=&quot;text-small-strong&quot; style=&quot;color:var(--green-700);&quot;>24</span>
      </div>

      <div class=&quot;friends-list&quot;>

        <div class=&quot;alpha-divider&quot;>A</div>
        <div class=&quot;friend-row&quot;>
          <div class=&quot;avatar&quot;><img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=14&quot;><span class=&quot;online-dot&quot;></span></div>
          <div class=&quot;friend-info&quot;>
            <div class=&quot;friend-name&quot;>Anna Bergmann</div>
            <div class=&quot;friend-context&quot;>Kennengelernt bei &quot;Bücherclub&quot; · vor 2 Wochen</div>
          </div>
          <div class=&quot;friend-chat-btn&quot;>
            <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M21 11.5a8.4 8.4 0 0 1-12.1 7.4L4 20l1.2-4.7A8.4 8.4 0 1 1 21 11.5z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
          </div>
        </div>

        <div class=&quot;alpha-divider&quot;>L</div>
        <div class=&quot;friend-row&quot;>
          <div class=&quot;avatar&quot;><img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=44&quot;></div>
          <div class=&quot;friend-info&quot;>
            <div class=&quot;friend-name&quot;>Lukas Schmidt</div>
            <div class=&quot;friend-context&quot;>Kennengelernt bei &quot;Brettspielabend&quot; · vor 1 Monat</div>
          </div>
          <div class=&quot;friend-chat-btn&quot;>
            <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M21 11.5a8.4 8.4 0 0 1-12.1 7.4L4 20l1.2-4.7A8.4 8.4 0 1 1 21 11.5z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
          </div>
        </div>

        <div class=&quot;alpha-divider&quot;>T</div>
        <div class=&quot;friend-row&quot;>
          <div class=&quot;avatar&quot;><img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=31&quot;><span class=&quot;online-dot&quot;></span></div>
          <div class=&quot;friend-info&quot;>
            <div class=&quot;friend-name&quot;>Tom Weber</div>
            <div class=&quot;friend-context&quot;>Kennengelernt bei &quot;Fotospaziergang&quot; · vor 3 Tagen</div>
          </div>
          <div class=&quot;friend-chat-btn&quot;>
            <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M21 11.5a8.4 8.4 0 0 1-12.1 7.4L4 20l1.2-4.7A8.4 8.4 0 1 1 21 11.5z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
          </div>
        </div>
        <div class=&quot;friend-row&quot;>
          <div class=&quot;avatar&quot;><img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/80?img=9&quot;></div>
          <div class=&quot;friend-info&quot;>
            <div class=&quot;friend-name&quot;>Theresa Voss</div>
            <div class=&quot;friend-context&quot;>Kennengelernt bei &quot;Gaming Community&quot; · vor 2 Monaten</div>
          </div>
          <div class=&quot;friend-chat-btn&quot;>
            <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M21 11.5a8.4 8.4 0 0 1-12.1 7.4L4 20l1.2-4.7A8.4 8.4 0 1 1 21 11.5z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
          </div>
        </div>

      </div>
    </div>

    <!-- Tab Bar -->
    <div class=&quot;tab-bar&quot;>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M4 11.5L12 4l8 7.5&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/><path d=&quot;M6 10v9a1 1 0 0 0 1 1h3v-5a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v5h3a1 1 0 0 0 1-1v-9&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Home
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;9&quot; cy=&quot;8&quot; r=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M3 19c0-3 2.5-5.2 6-5.2s6 2.2 6 5.2&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/><circle cx=&quot;17.5&quot; cy=&quot;9&quot; r=&quot;2.3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M14.5 14.2c2.6.3 4.5 2 4.5 4.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Gruppen
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><rect x=&quot;4&quot; y=&quot;5&quot; width=&quot;16&quot; height=&quot;15&quot; rx=&quot;3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4 9.5h16&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M8 3v3M16 3v3&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Aktivitäten
      </div>
      <div class=&quot;tab-item active&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.6l-1-1a5.5 5.5 0 0 0-7.8 7.8l1 1L12 21l7.8-7.6 1-1a5.5 5.5 0 0 0 0-7.8z&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
        Kontakte
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;8&quot; r=&quot;3.6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot;/><path d=&quot;M4.5 20c0-4 3.4-6.8 7.5-6.8s7.5 2.8 7.5 6.8&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;1.8&quot; stroke-linecap=&quot;round&quot;/></svg>
        Profil
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-13">
      <div class="screen-label">13 · Privatchat</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  .priv-chat-screen { background: var(--ink-50); }

  .chat-header { display: flex; align-items: center; gap: 12px; padding: 8px 16px 14px; flex-shrink: 0; background: var(--ink-50); border-bottom: 1px solid var(--ink-100); }
  .chat-header-info { flex: 1; display: flex; flex-direction: column; }
  .chat-header-name { font-size: 15.5px; font-weight: 700; color: var(--ink-900); }
  .chat-header-meta { font-size: 12px; color: var(--green-600); font-weight: 600; margin-top: 1px; }
  .chat-header-avatar { width: 38px; height: 38px; border-radius: 50%; object-fit: cover; }

  .friend-since-banner {
    margin: 12px 16px 0;
    background: var(--green-50);
    border-radius: var(--r-md);
    padding: 10px 14px;
    display: flex; align-items: center; gap: 8px;
    flex-shrink: 0;
  }
  .friend-since-banner span { font-size: 12px; color: var(--green-700); font-weight: 600; }

  .chat-body { flex: 1; overflow-y: auto; padding: 16px 16px; display: flex; flex-direction: column; gap: 14px; scrollbar-width: none; }
  .chat-body::-webkit-scrollbar { display: none; }

  .day-divider { text-align: center; margin: 4px 0 8px; }
  .day-divider span { font-size: 11.5px; font-weight: 700; color: var(--ink-400); background: var(--ink-100); padding: 4px 12px; border-radius: var(--r-pill); }

  .msg-row { display: flex; gap: 10px; max-width: 80%; }
  .msg-row.mine { align-self: flex-end; flex-direction: row-reverse; }
  .msg-row .avatar { width: 28px; height: 28px; flex-shrink: 0; }
  .msg-content { display: flex; flex-direction: column; gap: 4px; }
  .msg-row.mine .msg-content { align-items: flex-end; }
  .msg-bubble { background: var(--white); border: 1px solid var(--ink-100); border-radius: 16px 16px 16px 4px; padding: 10px 14px; font-size: 14.5px; color: var(--ink-800); line-height: 1.45; }
  .msg-row.mine .msg-bubble { background: var(--green-700); color: var(--white); border: none; border-radius: 16px 16px 4px 16px; }
  .msg-time { font-size: 11px; color: var(--ink-400); padding: 0 4px; }
  .msg-time.read { color: var(--green-600); }

  .typing-indicator { display: flex; gap: 10px; align-items: center; }
  .typing-bubble { background: var(--white); border: 1px solid var(--ink-100); border-radius: 16px; padding: 12px 16px; display: flex; gap: 4px; }
  .typing-dot { width: 6px; height: 6px; border-radius: 50%; background: var(--ink-300); }

  .chat-input-bar { display: flex; align-items: center; gap: 10px; padding: 10px 14px; background: var(--white); border-top: 1px solid var(--ink-100); flex-shrink: 0; }
  .chat-plus-btn { width: 34px; height: 34px; border-radius: 50%; background: var(--green-50); color: var(--green-700); display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
  .chat-text-input { flex: 1; background: var(--ink-50); border: 1px solid var(--ink-100); border-radius: var(--r-pill); padding: 11px 16px; font-size: 14.5px; color: var(--ink-900); }
  .chat-send-btn { width: 36px; height: 36px; border-radius: 50%; background: var(--coral-500); color: var(--white); display: flex; align-items: center; justify-content: center; flex-shrink: 0; box-shadow: var(--shadow-coral); }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen priv-chat-screen&quot;>

    <div class=&quot;status-bar&quot;>
      <span class=&quot;time&quot;>9:41</span>
      <div class=&quot;icons&quot;>
        <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;2&quot; width=&quot;14&quot; height=&quot;9&quot; rx=&quot;2&quot; stroke=&quot;#1C2220&quot; stroke-width=&quot;1&quot;/><rect x=&quot;15.5&quot; y=&quot;4&quot; width=&quot;1.5&quot; height=&quot;4&quot; rx=&quot;0.5&quot; fill=&quot;#1C2220&quot;/><rect x=&quot;1.5&quot; y=&quot;3.5&quot; width=&quot;11&quot; height=&quot;6&quot; rx=&quot;1&quot; fill=&quot;#1C2220&quot;/></svg>
      </div>
    </div>

    <div class=&quot;chat-header&quot;>
      <div class=&quot;nav-back&quot;>
        <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M15 18l-6-6 6-6&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
      </div>
      <img class=&quot;chat-header-avatar&quot; src=&quot;https://i.pravatar.cc/80?img=5&quot;>
      <div class=&quot;chat-header-info&quot;>
        <div class=&quot;chat-header-name&quot;>Sarah Klein</div>
        <div class=&quot;chat-header-meta&quot;>Online</div>
      </div>
      <div class=&quot;icon-btn&quot;>
        <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><circle cx=&quot;12&quot; cy=&quot;5&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/><circle cx=&quot;12&quot; cy=&quot;19&quot; r=&quot;1.6&quot; fill=&quot;currentColor&quot;/></svg>
      </div>
    </div>

    <div class=&quot;friend-since-banner&quot;>
      <svg width=&quot;14&quot; height=&quot;14&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M20.8 4.6a5.5 5.5 0 0 0-7.8 0L12 5.6l-1-1a5.5 5.5 0 0 0-7.8 7.8l1 1L12 21l7.8-7.6 1-1a5.5 5.5 0 0 0 0-7.8z&quot; stroke=&quot;var(--green-700)&quot; stroke-width=&quot;1.8&quot; stroke-linejoin=&quot;round&quot;/></svg>
      <span>Befreundet seit &quot;Café &amp; Lernen&quot; · Heute</span>
    </div>

    <div class=&quot;chat-body&quot;>

      <div class=&quot;day-divider&quot;><span>Heute</span></div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=5&quot;>
        <div class=&quot;msg-content&quot;>
          <div class=&quot;msg-bubble&quot;>Hey Mia! War super nett heute beim Lernen 😊 Sollen wir nächste Woche wieder zusammen lernen?</div>
          <span class=&quot;msg-time&quot;>18:32</span>
        </div>
      </div>

      <div class=&quot;msg-row mine&quot;>
        <div class=&quot;msg-content&quot;>
          <div class=&quot;msg-bubble&quot;>Auf jeden Fall! Hat richtig Spaß gemacht, war viel produktiver als allein 📚</div>
          <span class=&quot;msg-time read&quot;>18:34 · Gelesen</span>
        </div>
      </div>

      <div class=&quot;msg-row mine&quot;>
        <div class=&quot;msg-content&quot;>
          <div class=&quot;msg-bubble&quot;>Gleicher Ort, gleiche Zeit nächsten Donnerstag?</div>
          <span class=&quot;msg-time read&quot;>18:34 · Gelesen</span>
        </div>
      </div>

      <div class=&quot;msg-row&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=5&quot;>
        <div class=&quot;msg-content&quot;>
          <div class=&quot;msg-bubble&quot;>Perfekt, ich erstelle die Aktivität gleich in der App 🙌</div>
          <span class=&quot;msg-time&quot;>18:36</span>
        </div>
      </div>

      <div class=&quot;typing-indicator&quot;>
        <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/60?img=5&quot;>
        <div class=&quot;typing-bubble&quot;>
          <span class=&quot;typing-dot&quot;></span><span class=&quot;typing-dot&quot;></span><span class=&quot;typing-dot&quot;></span>
        </div>
      </div>

    </div>

    <div class=&quot;chat-input-bar&quot;>
      <div class=&quot;chat-plus-btn&quot;>
        <svg width=&quot;18&quot; height=&quot;18&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M12 5v14M5 12h14&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.2&quot; stroke-linecap=&quot;round&quot;/></svg>
      </div>
      <div class=&quot;chat-text-input&quot; style=&quot;color:var(--ink-400);&quot;>Nachricht schreiben…</div>
      <div class=&quot;chat-send-btn&quot;>
        <svg width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot;><path d=&quot;M5 12h14M13 6l6 6-6 6&quot; stroke=&quot;white&quot; stroke-width=&quot;2.3&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;/></svg>
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
    <div class="screen-frame" id="screen-14">
      <div class="screen-label">14 · Profilseite</div>
      <div class="device-shell">
        <div class="notch"></div>
        <iframe
          srcdoc="<!DOCTYPE html><html lang='de'><head><meta charset='UTF-8'><style>
* { box-sizing: border-box; }
html, body { margin: 0; padding: 0; font-family: -apple-system, 'SF Pro Text', 'Inter', 'Segoe UI', Roboto, sans-serif; -webkit-font-smoothing: antialiased; }
/* ============================================================
   CIRCLE — DESIGN SYSTEM
   Hauptfarbe: Deep Teal/Forest (ruhig, vertrauensvoll, &quot;real life&quot;)
   Kontrastfarbe: Warmes Koralle/Orange (Aktionen, Einladung, Wärme)
   ============================================================ */

:root {
  /* ---------- Hauptfarbe: Circle Green (Abstufungen) ---------- */
  --green-900: #0F2E26;
  --green-800: #164336;
  --green-700: #1F5C49;
  --green-600: #2A7A60;
  --green-500: #38997A;
  --green-400: #5FB395;
  --green-300: #93CCB6;
  --green-200: #C3E4D6;
  --green-100: #E4F2EC;
  --green-50:  #F3FAF7;

  /* ---------- Kontrastfarbe: Circle Coral (einzige Akzentfarbe) ---------- */
  --coral-700: #C7491F;
  --coral-600: #DD5A2C;
  --coral-500: #EB6B3A;
  --coral-400: #F08A5F;
  --coral-100: #FCE6DA;
  --coral-50:  #FDF2EC;

  /* ---------- Neutrale Töne (warmes Grau, kein reines Schwarz) ---------- */
  --ink-900: #1C2220;
  --ink-700: #3C4542;
  --ink-500: #6B7572;
  --ink-400: #8C958F;
  --ink-300: #B7BEB9;
  --ink-200: #DDE2DE;
  --ink-100: #EEF1EE;
  --ink-50:  #F7F9F7;
  --white:   #FFFFFF;

  /* ---------- Funktional ---------- */
  --success: #2A7A60;
  --danger:  #C0432B;

  /* ---------- Typografie ---------- */
  --font-base: -apple-system, &quot;SF Pro Text&quot;, &quot;Inter&quot;, &quot;Segoe UI&quot;, Roboto, sans-serif;

  /* ---------- Radien ---------- */
  --r-sm: 10px;
  --r-md: 14px;
  --r-lg: 20px;
  --r-xl: 28px;
  --r-pill: 999px;

  /* ---------- Schatten ---------- */
  --shadow-sm: 0 1px 2px rgba(28, 34, 32, 0.06);
  --shadow-md: 0 4px 16px rgba(28, 34, 32, 0.08);
  --shadow-lg: 0 12px 32px rgba(28, 34, 32, 0.14);
  --shadow-coral: 0 8px 20px rgba(235, 107, 58, 0.30);
}

* { box-sizing: border-box; }

html, body {
  margin: 0;
  padding: 0;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--ink-50);
  -webkit-font-smoothing: antialiased;
}

/* ============================================================
   DEVICE FRAME — iPhone 13 mini (375 × 812)
   ============================================================ */
.device {
  width: 375px;
  height: 812px;
  background: var(--ink-50);
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-lg);
  border-radius: 0;
}

.screen {
  width: 375px;
  height: 812px;
  display: flex;
  flex-direction: column;
  position: relative;
  overflow: hidden;
  background: var(--ink-50);
}

/* Status bar */
.status-bar {
  height: 47px;
  flex-shrink: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  font-size: 15px;
  font-weight: 600;
  color: var(--ink-900);
  background: transparent;
}
.status-bar .time { letter-spacing: 0.2px; }
.status-bar .icons { display: flex; gap: 5px; align-items: center; }

/* Scrollable content area */
.scroll-area {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}
.scroll-area::-webkit-scrollbar { display: none; }

/* ============================================================
   TAB BAR
   ============================================================ */
.tab-bar {
  height: 83px;
  flex-shrink: 0;
  display: flex;
  align-items: flex-start;
  padding-top: 8px;
  background: rgba(255,255,255,0.92);
  backdrop-filter: blur(20px);
  border-top: 1px solid var(--ink-100);
  position: relative;
  z-index: 50;
}
.tab-item {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  color: var(--ink-400);
  font-size: 11px;
  font-weight: 600;
  cursor: pointer;
}
.tab-item svg { width: 24px; height: 24px; }
.tab-item.active { color: var(--green-700); }
.tab-item.active svg { color: var(--green-700); }
.tab-item svg { color: var(--ink-400); }

/* ============================================================
   TYPOGRAPHY
   ============================================================ */
h1, h2, h3, h4, p { margin: 0; }

.text-display {
  font-size: 28px;
  font-weight: 800;
  letter-spacing: -0.5px;
  line-height: 1.15;
  color: var(--ink-900);
}
.text-h1 { font-size: 24px; font-weight: 800; letter-spacing: -0.4px; color: var(--ink-900); }
.text-h2 { font-size: 19px; font-weight: 700; letter-spacing: -0.2px; color: var(--ink-900); }
.text-h3 { font-size: 16px; font-weight: 700; color: var(--ink-900); }
.text-body { font-size: 15px; font-weight: 400; line-height: 1.5; color: var(--ink-700); }
.text-body-strong { font-size: 15px; font-weight: 600; color: var(--ink-900); }
.text-small { font-size: 13px; font-weight: 400; color: var(--ink-500); }
.text-small-strong { font-size: 13px; font-weight: 600; color: var(--ink-700); }
.text-micro { font-size: 11px; font-weight: 600; color: var(--ink-400); text-transform: uppercase; letter-spacing: 0.6px; }
.text-coral { color: var(--coral-600); }
.text-green { color: var(--green-700); }

/* ============================================================
   BUTTONS
   ============================================================ */
.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: none;
  cursor: pointer;
  font-family: var(--font-base);
  font-weight: 700;
  transition: transform 0.15s ease, opacity 0.15s ease;
}
.btn:active { transform: scale(0.97); opacity: 0.9; }

.btn-primary {
  background: var(--coral-500);
  color: var(--white);
  font-size: 16px;
  border-radius: var(--r-pill);
  padding: 16px 24px;
  box-shadow: var(--shadow-coral);
  width: 100%;
}
.btn-secondary {
  background: var(--green-50);
  color: var(--green-700);
  font-size: 15px;
  border-radius: var(--r-pill);
  padding: 13px 20px;
  width: 100%;
}
.btn-outline {
  background: transparent;
  color: var(--ink-700);
  font-size: 15px;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-pill);
  padding: 12px 20px;
}
.btn-pill-sm {
  background: var(--green-700);
  color: var(--white);
  font-size: 13px;
  font-weight: 700;
  border-radius: var(--r-pill);
  padding: 9px 18px;
}
.btn-pill-sm.joined {
  background: var(--green-100);
  color: var(--green-700);
}
.btn-ghost {
  background: transparent;
  color: var(--green-700);
  font-size: 15px;
  font-weight: 700;
  padding: 8px;
}

/* ============================================================
   CARDS
   ============================================================ */
.card {
  background: var(--white);
  border-radius: var(--r-lg);
  box-shadow: var(--shadow-sm);
  border: 1px solid var(--ink-100);
}

.chip {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  background: var(--green-100);
  color: var(--green-700);
  font-size: 12px;
  font-weight: 700;
  padding: 6px 12px;
  border-radius: var(--r-pill);
  white-space: nowrap;
}
.chip.coral { background: var(--coral-100); color: var(--coral-700); }
.chip.outline { background: var(--white); color: var(--ink-600); border: 1px solid var(--ink-200); }

/* ============================================================
   AVATARS
   ============================================================ */
.avatar {
  border-radius: 50%;
  object-fit: cover;
  flex-shrink: 0;
  display: block;
  background: var(--green-200);
}
.avatar-stack { display: flex; }
.avatar-stack .avatar { border: 2px solid var(--white); margin-left: -10px; }
.avatar-stack .avatar:first-child { margin-left: 0; }

/* ============================================================
   INPUTS
   ============================================================ */
.input-search {
  display: flex;
  align-items: center;
  gap: 10px;
  background: var(--white);
  border: 1px solid var(--ink-150, var(--ink-100));
  border-radius: var(--r-pill);
  padding: 13px 16px;
  color: var(--ink-500);
  font-size: 15px;
}
.input-search svg { flex-shrink: 0; color: var(--ink-400); }

.text-field {
  width: 100%;
  border: 1.5px solid var(--ink-200);
  border-radius: var(--r-md);
  padding: 14px 16px;
  font-size: 15px;
  font-family: var(--font-base);
  color: var(--ink-900);
  background: var(--white);
}
.text-field:focus { outline: none; border-color: var(--green-500); }
.text-field::placeholder { color: var(--ink-400); }

/* ============================================================
   NAV HEADER
   ============================================================ */
.nav-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 8px 20px 14px;
  flex-shrink: 0;
}
.nav-back {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}
.icon-btn {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: var(--white);
  border: 1px solid var(--ink-100);
  display: flex;
  align-items: center;
  justify-content: center;
  color: var(--ink-900);
  flex-shrink: 0;
}

/* ============================================================
   BADGE / NOTIFICATION DOT
   ============================================================ */
.badge-dot {
  position: absolute;
  top: -2px;
  right: -2px;
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--coral-500);
  border: 1.5px solid var(--white);
}

/* Utility */
.row { display: flex; align-items: center; }
.row-between { display: flex; align-items: center; justify-content: space-between; }
.col { display: flex; flex-direction: column; }
.gap-4 { gap: 4px; } .gap-6 { gap: 6px; } .gap-8 { gap: 8px; } .gap-10 { gap: 10px; } .gap-12 { gap: 12px; } .gap-16 { gap: 16px; }
.px-20 { padding-left: 20px; padding-right: 20px; }
.mt-8{margin-top:8px;} .mt-12{margin-top:12px;} .mt-16{margin-top:16px;} .mt-20{margin-top:20px;} .mt-24{margin-top:24px;} .mt-28{margin-top:28px;}


  /* ============================================================
     SCREEN-SPECIFIC: Profilseite
     ============================================================ */
  .profile-header {
    background: linear-gradient(160deg, var(--green-800) 0%, var(--green-600) 100%);
    padding: 8px 20px 56px;
    position: relative;
    flex-shrink: 0;
  }
  .profile-header .nav-header { padding: 8px 0 0; }
  .profile-header .icon-btn {
    background: rgba(255,255,255,0.16);
    border: 1px solid rgba(255,255,255,0.22);
    color: var(--white);
  }

  .profile-identity {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin-top: 6px;
  }
  .profile-avatar-wrap {
    position: relative;
    width: 92px;
    height: 92px;
  }
  .profile-avatar-wrap .avatar {
    width: 92px;
    height: 92px;
    border: 3px solid rgba(255,255,255,0.5);
  }
  .online-dot-lg {
    position: absolute;
    bottom: 2px;
    right: 2px;
    width: 18px;
    height: 18px;
    border-radius: 50%;
    background: var(--green-400);
    border: 3px solid var(--green-700);
  }
  .profile-name { color: var(--white); font-size: 21px; font-weight: 800; margin-top: 14px; letter-spacing: -0.3px; }
  .profile-sub { color: rgba(255,255,255,0.78); font-size: 13.5px; font-weight: 500; margin-top: 4px; }

  /* Floating stats card overlapping header */
  .stats-card {
    background: var(--white);
    border-radius: var(--r-lg);
    box-shadow: var(--shadow-md);
    margin: -36px 20px 0;
    padding: 18px 8px;
    display: flex;
    position: relative;
    z-index: 5;
  }
  .stat-item {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2px;
  }
  .stat-num { font-size: 19px; font-weight: 800; color: var(--ink-900); letter-spacing: -0.3px; }
  .stat-label { font-size: 11.5px; font-weight: 500; color: var(--ink-500); }
  .stat-divider { width: 1px; background: var(--ink-100); margin: 2px 0; }

  /* Section title row */
  .section-title-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 12px;
  }

  /* Bio card */
  .bio-card { padding: 16px; }

  /* Interest chips wrap */
  .interest-wrap { display: flex; flex-wrap: wrap; gap: 8px; }

  /* Badge/achievement tiles */
  .badge-tile {
    flex: 1;
    background: var(--white);
    border: 1px solid var(--ink-100);
    border-radius: var(--r-md);
    padding: 14px 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 6px;
    text-align: center;
  }
  .badge-icon-circle {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .badge-tile .badge-label { font-size: 11px; font-weight: 700; color: var(--ink-700); line-height: 1.3; }

  /* Settings list */
  .settings-list { background: var(--white); border-radius: var(--r-lg); border: 1px solid var(--ink-100); overflow: hidden; }
  .settings-row {
    display: flex;
    align-items: center;
    gap: 14px;
    padding: 15px 16px;
    border-bottom: 1px solid var(--ink-100);
  }
  .settings-row:last-child { border-bottom: none; }
  .settings-icon {
    width: 34px;
    height: 34px;
    border-radius: 10px;
    background: var(--green-50);
    color: var(--green-700);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
  }
  .settings-icon.coral { background: var(--coral-50); color: var(--coral-600); }
  .settings-row .label { flex: 1; font-size: 15px; font-weight: 600; color: var(--ink-900); }
  .settings-row .chevron { color: var(--ink-300); }
  .settings-row.logout .label { color: var(--coral-600); }
  .settings-row.logout .settings-icon { background: var(--coral-50); color: var(--coral-600); }

</style></head><body><div class=&quot;device&quot;>
  <div class=&quot;screen&quot;>

    <!-- Header / Identity -->
    <div class=&quot;profile-header&quot;>
      <div class=&quot;status-bar&quot; style=&quot;color: var(--white);&quot;>
        <span class=&quot;time&quot;>9:41</span>
        <div class=&quot;icons&quot;>
          <svg width=&quot;18&quot; height=&quot;12&quot; viewBox=&quot;0 0 18 12&quot; fill=&quot;none&quot;><rect x=&quot;0&quot; y=&quot;3&quot; width=&quot;3&quot; height=&quot;8&quot; rx=&quot;0.5&quot; fill=&quot;white&quot;/><rect x=&quot;4.5&quot; y=&quot;1.5&quot; width=&quot;3&quot; height=&quot;9.5&quot; rx=&quot;0.5&quot; fill=&quot;white&quot;/><rect x=&quot;9&quot; y=&quot;0&quot; width=&quot;3&quot; height=&quot;11&quot; rx=&quot;0.5&quot; fill=&quot;white&quot;/><rect x=&quot;13.5&quot; y=&quot;0&quot; width=&quot;3.5&quot; height=&quot;11&quot; rx=&quot;1&quot; fill=&quot;none&quot; stroke=&quot;white&quot; stroke-width=&quot;0.8&quot;/></svg>
        </div>
      </div>

      <div class=&quot;nav-header&quot;>
        <span class=&quot;text-h2&quot; style=&quot;color: var(--white);&quot;>Profil</span>
        <div class=&quot;icon-btn&quot;>
          <svg width=&quot;18&quot; height=&quot;18&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;3&quot;/><path d=&quot;M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 1 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 1 1-4 0v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 1 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 1 1 0-4h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 1 1 2.83-2.83l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 1 1 4 0v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 1 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 1 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z&quot;/></svg>
        </div>
      </div>

      <div class=&quot;profile-identity&quot;>
        <div class=&quot;profile-avatar-wrap&quot;>
          <img class=&quot;avatar&quot; src=&quot;https://i.pravatar.cc/200?img=47&quot; alt=&quot;Mia Hoffmann&quot;>
          <div class=&quot;online-dot-lg&quot;></div>
        </div>
        <div class=&quot;profile-name&quot;>Mia Hoffmann</div>
        <div class=&quot;profile-sub&quot;>27 Jahre · Berlin, Mitte</div>
      </div>
    </div>

    <div class=&quot;scroll-area&quot;>

      <!-- Stats card -->
      <div class=&quot;stats-card&quot;>
        <div class=&quot;stat-item&quot;>
          <span class=&quot;stat-num&quot;>3</span>
          <span class=&quot;stat-label&quot;>Gruppen</span>
        </div>
        <div class=&quot;stat-divider&quot;></div>
        <div class=&quot;stat-item&quot;>
          <span class=&quot;stat-num&quot;>9</span>
          <span class=&quot;stat-label&quot;>Aktivitäten</span>
        </div>
        <div class=&quot;stat-divider&quot;></div>
        <div class=&quot;stat-item&quot;>
          <span class=&quot;stat-num&quot;>24</span>
          <span class=&quot;stat-label&quot;>Freunde</span>
        </div>
      </div>

      <!-- Bio -->
      <div class=&quot;px-20 mt-20&quot;>
        <div class=&quot;card bio-card&quot;>
          <span class=&quot;text-micro&quot;>Über mich</span>
          <p class=&quot;text-body mt-8&quot;>Liebe ruhige Cafés, gute Bücher und lange Spaziergänge durch die Stadt. Suche Lernpartner &amp; neue Leute mit echten Interessen. 📚☕️</p>
        </div>
      </div>

      <!-- Interests -->
      <div class=&quot;px-20 mt-20&quot;>
        <div class=&quot;section-title-row&quot;>
          <span class=&quot;text-h3&quot;>Meine Interessen</span>
          <span class=&quot;text-small-strong text-green&quot;>Bearbeiten</span>
        </div>
        <div class=&quot;interest-wrap&quot;>
          <span class=&quot;chip&quot;>📷 Fotografie</span>
          <span class=&quot;chip&quot;>📚 Bücherclub</span>
          <span class=&quot;chip&quot;>☕ Café &amp; Lernen</span>
          <span class=&quot;chip&quot;>🚶 Spaziergänge</span>
          <span class=&quot;chip outline&quot;>+ Mehr hinzufügen</span>
        </div>
      </div>

      <!-- Badges / Achievements -->
      <div class=&quot;px-20 mt-24&quot;>
        <div class=&quot;section-title-row&quot;>
          <span class=&quot;text-h3&quot;>Erfolge</span>
        </div>
        <div class=&quot;row gap-10&quot;>
          <div class=&quot;badge-tile&quot;>
            <div class=&quot;badge-icon-circle&quot; style=&quot;background: var(--coral-50);&quot;>
              <svg width=&quot;20&quot; height=&quot;20&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;var(--coral-600)&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M8.21 13.89 7 23l5-3 5 3-1.21-9.12&quot;/><circle cx=&quot;12&quot; cy=&quot;8&quot; r=&quot;7&quot;/></svg>
            </div>
            <span class=&quot;badge-label&quot;>Erste<br>Aktivität</span>
          </div>
          <div class=&quot;badge-tile&quot;>
            <div class=&quot;badge-icon-circle&quot; style=&quot;background: var(--green-100);&quot;>
              <svg width=&quot;20&quot; height=&quot;20&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;var(--green-700)&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2&quot;/><circle cx=&quot;9&quot; cy=&quot;7&quot; r=&quot;4&quot;/><path d=&quot;M23 21v-2a4 4 0 0 0-3-3.87&quot;/><path d=&quot;M16 3.13a4 4 0 0 1 0 7.75&quot;/></svg>
            </div>
            <span class=&quot;badge-label&quot;>Social<br>Starter</span>
          </div>
          <div class=&quot;badge-tile&quot;>
            <div class=&quot;badge-icon-circle&quot; style=&quot;background: var(--green-100);&quot;>
              <svg width=&quot;20&quot; height=&quot;20&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;var(--green-700)&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z&quot;/></svg>
            </div>
            <span class=&quot;badge-label&quot;>Stammgast<br>Bücherclub</span>
          </div>
        </div>
      </div>

      <!-- Settings -->
      <div class=&quot;px-20 mt-24&quot;>
        <span class=&quot;text-h3&quot;>Einstellungen</span>
        <div class=&quot;settings-list mt-12&quot;>
          <div class=&quot;settings-row&quot;>
            <div class=&quot;settings-icon&quot;>
              <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2&quot;/><circle cx=&quot;12&quot; cy=&quot;7&quot; r=&quot;4&quot;/></svg>
            </div>
            <span class=&quot;label&quot;>Profil bearbeiten</span>
            <svg class=&quot;chevron&quot; width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.5&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M9 18l6-6-6-6&quot;/></svg>
          </div>
          <div class=&quot;settings-row&quot;>
            <div class=&quot;settings-icon&quot;>
              <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9&quot;/><path d=&quot;M13.73 21a2 2 0 0 1-3.46 0&quot;/></svg>
            </div>
            <span class=&quot;label&quot;>Benachrichtigungen</span>
            <svg class=&quot;chevron&quot; width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.5&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M9 18l6-6-6-6&quot;/></svg>
          </div>
          <div class=&quot;settings-row&quot;>
            <div class=&quot;settings-icon&quot;>
              <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><rect x=&quot;3&quot; y=&quot;11&quot; width=&quot;18&quot; height=&quot;11&quot; rx=&quot;2&quot;/><path d=&quot;M7 11V7a5 5 0 0 1 10 0v4&quot;/></svg>
            </div>
            <span class=&quot;label&quot;>Privatsphäre</span>
            <svg class=&quot;chevron&quot; width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.5&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M9 18l6-6-6-6&quot;/></svg>
          </div>
          <div class=&quot;settings-row&quot;>
            <div class=&quot;settings-icon&quot;>
              <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><circle cx=&quot;12&quot; cy=&quot;12&quot; r=&quot;10&quot;/><path d=&quot;M12 16v-4&quot;/><path d=&quot;M12 8h.01&quot;/></svg>
            </div>
            <span class=&quot;label&quot;>Hilfe &amp; Support</span>
            <svg class=&quot;chevron&quot; width=&quot;16&quot; height=&quot;16&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2.5&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M9 18l6-6-6-6&quot;/></svg>
          </div>
          <div class=&quot;settings-row logout&quot;>
            <div class=&quot;settings-icon coral&quot;>
              <svg width=&quot;17&quot; height=&quot;17&quot; viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4&quot;/><path d=&quot;M16 17l5-5-5-5&quot;/><path d=&quot;M21 12H9&quot;/></svg>
            </div>
            <span class=&quot;label&quot;>Abmelden</span>
          </div>
        </div>
      </div>

      <div style=&quot;height: 24px;&quot;></div>
    </div>

    <!-- Tab Bar -->
    <div class=&quot;tab-bar&quot;>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z&quot;/><path d=&quot;M9 22V12h6v10&quot;/></svg>
        <span>Home</span>
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2&quot;/><circle cx=&quot;9&quot; cy=&quot;7&quot; r=&quot;4&quot;/><path d=&quot;M23 21v-2a4 4 0 0 0-3-3.87&quot;/><path d=&quot;M16 3.13a4 4 0 0 1 0 7.75&quot;/></svg>
        <span>Gruppen</span>
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><rect x=&quot;3&quot; y=&quot;4&quot; width=&quot;18&quot; height=&quot;18&quot; rx=&quot;2&quot;/><path d=&quot;M16 2v4&quot;/><path d=&quot;M8 2v4&quot;/><path d=&quot;M3 10h18&quot;/></svg>
        <span>Aktivitäten</span>
      </div>
      <div class=&quot;tab-item&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;none&quot; stroke=&quot;currentColor&quot; stroke-width=&quot;2&quot; stroke-linecap=&quot;round&quot; stroke-linejoin=&quot;round&quot;><path d=&quot;M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2&quot;/><circle cx=&quot;12&quot; cy=&quot;7&quot; r=&quot;4&quot;/></svg>
        <span>Kontakte</span>
      </div>
      <div class=&quot;tab-item active&quot;>
        <svg viewBox=&quot;0 0 24 24&quot; fill=&quot;currentColor&quot; stroke=&quot;none&quot;><path d=&quot;M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2&quot;/><circle cx=&quot;12&quot; cy=&quot;7&quot; r=&quot;4&quot;/></svg>
        <span>Profil</span>
      </div>
    </div>

  </div>
</div></body></html>"
          width="375"
          height="812"
          frameborder="0"
          scrolling="no"
        ></iframe>
      </div>
    </div>
</div>

</body>
</html>
