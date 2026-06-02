<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VIRA · Voz Inteligente de Reviews y Alertas</title>
<style>
  :root {
    --bg: #0d0e11;
    --surface: #1a1d21;
    --surface2: #222529;
    --border: rgba(255,255,255,0.07);
    --text: #d1d2d3;
    --muted: #7a7b7c;
    --green: #2eb67d;
    --red: #e03e3e;
    --orange: #e8a838;
    --blue: #4a9eff;
    --purple: #8b5cf6;
    --white: #ffffff;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body { background: var(--bg); color: var(--text); font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; line-height: 1.6; }
  a { color: var(--blue); text-decoration: none; }

  /* NAV */
  nav { position: fixed; top: 0; width: 100%; background: rgba(13,14,17,0.92); backdrop-filter: blur(12px); border-bottom: 1px solid var(--border); z-index: 100; padding: 0 2rem; display: flex; align-items: center; justify-content: space-between; height: 56px; }
  .nav-logo { display: flex; align-items: center; gap: 10px; font-weight: 600; font-size: 15px; color: var(--white); }
  .nav-logo span { background: linear-gradient(135deg, #4a9eff, #8b5cf6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
  .nav-links { display: flex; gap: 2rem; font-size: 13px; color: var(--muted); }
  .nav-links a { color: var(--muted); transition: color .2s; }
  .nav-links a:hover { color: var(--white); }
  .nav-badge { background: var(--green); color: #fff; font-size: 11px; padding: 3px 10px; border-radius: 20px; font-weight: 500; }

  /* HERO */
  .hero { padding: 140px 2rem 80px; text-align: center; max-width: 800px; margin: 0 auto; }
  .hero-tag { display: inline-flex; align-items: center; gap: 6px; background: rgba(74,158,255,0.1); border: 1px solid rgba(74,158,255,0.25); color: var(--blue); font-size: 12px; padding: 5px 14px; border-radius: 20px; margin-bottom: 2rem; }
  .hero h1 { font-size: clamp(2.5rem, 6vw, 4.5rem); font-weight: 700; line-height: 1.1; letter-spacing: -1px; color: var(--white); margin-bottom: 1.5rem; }
  .hero h1 span { background: linear-gradient(135deg, #4a9eff 0%, #8b5cf6 50%, #2eb67d 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
  .hero p { font-size: 1.15rem; color: var(--muted); max-width: 560px; margin: 0 auto 2.5rem; line-height: 1.7; }
  .hero-actions { display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap; }
  .btn-primary { background: var(--blue); color: #fff; padding: 12px 28px; border-radius: 8px; font-weight: 600; font-size: 14px; transition: opacity .2s; }
  .btn-primary:hover { opacity: .85; color: #fff; }
  .btn-secondary { background: transparent; border: 1px solid var(--border); color: var(--text); padding: 12px 28px; border-radius: 8px; font-size: 14px; transition: border-color .2s; }
  .btn-secondary:hover { border-color: rgba(255,255,255,0.3); }

  /* STATS */
  .stats { display: flex; justify-content: center; gap: 3rem; padding: 3rem 2rem; border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); flex-wrap: wrap; }
  .stat { text-align: center; }
  .stat-num { font-size: 2rem; font-weight: 700; color: var(--white); }
  .stat-label { font-size: 12px; color: var(--muted); margin-top: 2px; }

  /* SECTIONS */
  section { padding: 80px 2rem; max-width: 1100px; margin: 0 auto; }
  .section-tag { font-size: 12px; color: var(--blue); font-weight: 600; letter-spacing: 1px; text-transform: uppercase; margin-bottom: 1rem; }
  .section-title { font-size: clamp(1.6rem, 3vw, 2.2rem); font-weight: 700; color: var(--white); margin-bottom: 1rem; line-height: 1.2; }
  .section-sub { color: var(--muted); font-size: 1rem; max-width: 540px; line-height: 1.7; }

  /* HOW IT WORKS */
  .steps { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1.5rem; margin-top: 3rem; }
  .step { background: var(--surface); border: 1px solid var(--border); border-radius: 12px; padding: 1.5rem; position: relative; }
  .step-num { font-size: 11px; color: var(--muted); font-weight: 600; letter-spacing: 1px; margin-bottom: 0.75rem; }
  .step-icon { font-size: 1.5rem; margin-bottom: 0.75rem; }
  .step h3 { font-size: 14px; font-weight: 600; color: var(--white); margin-bottom: 0.5rem; }
  .step p { font-size: 13px; color: var(--muted); line-height: 1.5; }

  /* DEMO SLACK */
  .demo-wrap { background: var(--surface); border: 1px solid var(--border); border-radius: 16px; overflow: hidden; margin-top: 3rem; }
  .demo-header { background: var(--surface2); padding: 1rem 1.5rem; display: flex; align-items: center; gap: 12px; border-bottom: 1px solid var(--border); }
  .demo-header .dots { display: flex; gap: 6px; }
  .dot { width: 12px; height: 12px; border-radius: 50%; }
  .dot-r { background: #ff5f57; }
  .dot-y { background: #febc2e; }
  .dot-g { background: #28c840; }
  .demo-title { font-size: 13px; color: var(--muted); }
  .demo-body { padding: 1.5rem; font-family: 'SF Mono', 'Fira Code', monospace; font-size: 13px; line-height: 1.8; }

  /* MSG FORMATS */
  .msg { margin-bottom: 2rem; }
  .msg-header { display: flex; align-items: center; gap: 10px; margin-bottom: 8px; }
  .msg-avatar { width: 36px; height: 36px; border-radius: 8px; background: linear-gradient(135deg, #4a9eff, #8b5cf6); display: flex; align-items: center; justify-content: center; font-size: 16px; flex-shrink: 0; }
  .msg-meta { display: flex; align-items: baseline; gap: 8px; }
  .msg-name { font-weight: 700; color: var(--white); font-size: 14px; font-family: sans-serif; }
  .msg-time { font-size: 11px; color: var(--muted); font-family: sans-serif; }
  .msg-badge { background: rgba(74,158,255,0.15); border: 1px solid rgba(74,158,255,0.3); color: var(--blue); font-size: 10px; padding: 1px 7px; border-radius: 4px; font-family: sans-serif; }
  .msg-content { padding-left: 46px; }
  .divider { color: var(--muted); }
  .green { color: var(--green); }
  .red { color: var(--red); }
  .orange { color: var(--orange); }
  .blue-t { color: var(--blue); }
  .white { color: var(--white); font-weight: 600; }
  .tag { background: rgba(255,255,255,0.08); color: #bbb; padding: 1px 6px; border-radius: 3px; font-size: 12px; }
  .blockquote { border-left: 3px solid rgba(255,255,255,0.15); padding-left: 10px; color: #aaa; font-style: italic; margin: 4px 0; }
  .blockquote-red { border-left: 3px solid var(--red); padding-left: 10px; color: #aaa; font-style: italic; margin: 4px 0; }
  .blockquote-green { border-left: 3px solid var(--green); padding-left: 10px; color: #aaa; font-style: italic; margin: 4px 0; }
  .iceberg { background: rgba(74,158,255,0.07); border: 1px solid rgba(74,158,255,0.15); border-radius: 8px; padding: 10px 14px; margin-top: 10px; font-family: sans-serif; font-size: 13px; }
  .knock { background: rgba(139,92,246,0.07); border: 1px solid rgba(139,92,246,0.2); border-radius: 8px; padding: 10px 14px; margin-top: 10px; font-family: sans-serif; font-size: 13px; line-height: 1.7; }

  /* TEAMS */
  .teams-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1rem; margin-top: 3rem; }
  .tribe { background: var(--surface); border: 1px solid var(--border); border-radius: 12px; overflow: hidden; }
  .tribe-header { padding: 1rem 1.25rem; border-bottom: 1px solid var(--border); display: flex; align-items: center; gap: 10px; }
  .tribe-dot { width: 8px; height: 8px; border-radius: 50%; }
  .tribe-name { font-size: 12px; font-weight: 600; color: var(--muted); letter-spacing: 0.5px; text-transform: uppercase; }
  .squad { padding: 0.875rem 1.25rem; border-bottom: 1px solid var(--border); }
  .squad:last-child { border-bottom: none; }
  .squad-name { font-size: 13px; font-weight: 600; color: var(--white); margin-bottom: 3px; }
  .squad-channel { font-size: 11px; color: var(--blue); margin-bottom: 4px; }
  .squad-desc { font-size: 12px; color: var(--muted); line-height: 1.5; }

  /* ICEBERG SECTION */
  .iceberg-section { background: var(--surface); border: 1px solid var(--border); border-radius: 16px; padding: 3rem; margin-top: 3rem; display: grid; grid-template-columns: 1fr 1fr; gap: 3rem; align-items: center; }
  .iceberg-visual { text-align: center; }
  .iceberg-tip { background: rgba(255,255,255,0.06); border: 1px solid var(--border); border-radius: 8px; padding: 1rem; margin-bottom: 2px; font-size: 13px; color: var(--white); }
  .iceberg-water { border-top: 2px dashed rgba(74,158,255,0.4); padding-top: 12px; }
  .iceberg-body { background: rgba(74,158,255,0.06); border: 1px solid rgba(74,158,255,0.15); border-radius: 8px; padding: 1.5rem; font-size: 13px; color: var(--muted); }
  .iceberg-num { font-size: 2.5rem; font-weight: 700; color: var(--blue); }
  .iceberg-text h3 { font-size: 1.4rem; font-weight: 700; color: var(--white); margin-bottom: 1rem; }
  .iceberg-text p { color: var(--muted); font-size: 14px; line-height: 1.7; margin-bottom: 1rem; }

  /* FOOTER */
  footer { border-top: 1px solid var(--border); padding: 3rem 2rem; text-align: center; }
  footer p { color: var(--muted); font-size: 13px; }
  footer strong { color: var(--white); }

  @media (max-width: 768px) {
    .iceberg-section { grid-template-columns: 1fr; }
    .stats { gap: 1.5rem; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">🤖 <span>VIRA</span></div>
  <div class="nav-links">
    <a href="#como-funciona">Cómo funciona</a>
    <a href="#demo">Demo</a>
    <a href="#equipos">Equipos</a>
    <a href="#iceberg">Iceberg</a>
  </div>
  <span class="nav-badge">MODO CX</span>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="hero-tag">🤖 Agente CX Intelligence · MODO</div>
  <h1>La <span>voz del cliente</span>,<br>traducida en acción.</h1>
  <p>VIRA lee cada review de la app, detecta bugs, patrones e incidentes, y notifica al equipo correcto — antes de que el problema escale.</p>
  <div class="hero-actions">
    <a href="https://github.com/ursutello95/vira-cx-agent" class="btn-primary">Ver repositorio →</a>
    <a href="#demo" class="btn-secondary">Ver demo</a>
  </div>
</div>

<!-- STATS -->
<div class="stats">
  <div class="stat"><div class="stat-num">7</div><div class="stat-label">Squads etiquetados</div></div>
  <div class="stat"><div class="stat-num">3</div><div class="stat-label">Tribús cubiertas</div></div>
  <div class="stat"><div class="stat-num">×100</div><div class="stat-label">Principio Iceberg</div></div>
  <div class="stat"><div class="stat-num">1h</div><div class="stat-label">Ciclo de análisis</div></div>
  <div class="stat"><div class="stat-num">48hs</div><div class="stat-label">Ventana antes de incidente</div></div>
</div>

<!-- COMO FUNCIONA -->
<section id="como-funciona">
  <div class="section-tag">Arquitectura</div>
  <h2 class="section-title">Cómo funciona VIRA</h2>
  <p class="section-sub">Cada hora, VIRA lee el canal de reviews, clasifica cada feedback con IA, infiere el equipo responsable y postea dos mensajes: un scoreboard general y un knock directo al squad.</p>
  <div class="steps">
    <div class="step">
      <div class="step-num">PASO 01</div>
      <div class="step-icon">👁️</div>
      <h3>Lee el canal</h3>
      <p>Abre #modo-app-user-reviews en Slack y extrae todas las reviews nuevas del AppReviewBot.</p>
    </div>
    <div class="step">
      <div class="step-num">PASO 02</div>
      <div class="step-icon">🧠</div>
      <h3>Clasifica con IA</h3>
      <p>Detecta bugs, fricción, mejoras y promotores. Asigna severidad, tags y el squad responsable.</p>
    </div>
    <div class="step">
      <div class="step-num">PASO 03</div>
      <div class="step-icon">🧊</div>
      <h3>Calcula el iceberg</h3>
      <p>Por cada review visible, estima ~100 usuarios que vivieron lo mismo en silencio.</p>
    </div>
    <div class="step">
      <div class="step-num">PASO 04</div>
      <div class="step-icon">📡</div>
      <h3>Notifica al squad</h3>
      <p>Scoreboard en el canal CX + knock directo en el canal del equipo responsable.</p>
    </div>
    <div class="step">
      <div class="step-num">PASO 05</div>
      <div class="step-icon">📊</div>
      <h3>Resumen semanal</h3>
      <p>Cada viernes a las 17hs publica el diagnóstico completo de la semana agrupado por tribu.</p>
    </div>
  </div>
</section>

<!-- DEMO -->
<section id="demo">
  <div class="section-tag">Notificaciones</div>
  <h2 class="section-title">VIRA en acción</h2>
  <p class="section-sub">Dos mensajes por ciclo: el scoreboard da el mapa completo en 3 líneas; el knock llega directo al canal del squad.</p>

  <div class="demo-wrap">
    <div class="demo-header">
      <div class="dots"><div class="dot dot-r"></div><div class="dot dot-y"></div><div class="dot dot-g"></div></div>
      <div class="demo-title">Slack · #cowork (canal de prueba)</div>
    </div>
    <div class="demo-body">

      <!-- SCOREBOARD -->
      <div class="msg">
        <div class="msg-header">
          <div class="msg-avatar">🤖</div>
          <div class="msg-meta">
            <span class="msg-name">VIRA</span>
            <span class="msg-badge">APP</span>
            <span class="msg-time">14:00</span>
          </div>
        </div>
        <div class="msg-content">
          <span class="white">🤖 VIRA</span> · 27 may · 5 reviews · <em style="color:#aaa">★3.8</em><br>
          <span class="divider">▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔</span><br>
          <span class="blue-t">#cx-guildpusf</span> &nbsp; <span class="red">🔴×2</span> &nbsp; <span class="green">✅×2</span><br>
          <span class="blue-t">#expertos---p2m</span> &nbsp; <span class="green">✅×1</span><br>
          <span class="blue-t">#ctl-detractores</span> &nbsp; <span class="orange">🟠×1</span><br>
          <span class="divider">▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔</span><br>
          <span class="red">🚨 Historia destacada</span> · <span class="blue-t">#cx-guildpusf</span><br>
          <div class="knock">
            &nbsp;&nbsp;Una usuaria cambió de número.<br>
            &nbsp;&nbsp;Quiso entrar a MODO. No pudo.<br>
            &nbsp;&nbsp;Le abrieron un reclamo.<br>
            &nbsp;&nbsp;Nadie la llamó.<br><br>
            &nbsp;&nbsp;Le dio 5 estrellas igual.
          </div>
          <div class="iceberg">
            🧊 2 bugs visibles ≈ 200 usuarios en silencio<br>
            ⏱ <em>Sin acción en 48hs → riesgo de incidente</em>
          </div>
          <br><em style="color:#8a8b8c">GX debe mapear todos los escenarios de pérdida de acceso como un flujo único — hoy son tres bugs separados, en realidad es un solo problema de diseño.</em>
        </div>
      </div>

      <hr style="border-color: rgba(255,255,255,0.05); margin: 1.5rem 0;">

      <!-- KNOCK GX -->
      <div class="msg">
        <div class="msg-header">
          <div class="msg-avatar">🤖</div>
          <div class="msg-meta">
            <span class="msg-name">VIRA</span>
            <span class="msg-badge">APP</span>
            <span class="msg-time">14:01</span>
          </div>
        </div>
        <div class="msg-content">
          <em style="color:#7a7b7c; font-size:12px;">Mensaje directo en #cx-guildpusf</em><br><br>
          <span class="white">🤖 VIRA te trae una señal</span> · 27 may<br>
          <span class="divider">▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔</span><br>
          <div class="knock">
            &nbsp;&nbsp;Una usuaria cambió de número.<br>
            &nbsp;&nbsp;Quiso entrar. No pudo.<br>
            &nbsp;&nbsp;Le abrieron un reclamo. Nadie la llamó.<br>
            &nbsp;&nbsp;Le dio 5 estrellas igual.
          </div>
          <div class="iceberg">
            🧊 1 review visible ≈ 100 usuarios en silencio<br>
            ⏱ <em>Sin acción en 48hs → riesgo de incidente</em>
          </div>
          <br><span class="divider">▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔</span>
        </div>
      </div>

      <hr style="border-color: rgba(255,255,255,0.05); margin: 1.5rem 0;">

      <!-- KNOCK PTM WIN -->
      <div class="msg">
        <div class="msg-header">
          <div class="msg-avatar">🤖</div>
          <div class="msg-meta">
            <span class="msg-name">VIRA</span>
            <span class="msg-badge">APP</span>
            <span class="msg-time">14:01</span>
          </div>
        </div>
        <div class="msg-content">
          <em style="color:#7a7b7c; font-size:12px;">Mensaje directo en #expertos---p2m</em><br><br>
          <span class="white">🤖 VIRA te trae una señal</span> · 27 may<br>
          <span class="divider">▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔</span><br>
          <div class="knock" style="border-color: rgba(46,182,125,0.3); background: rgba(46,182,125,0.05);">
            &nbsp;&nbsp;<em style="color:#aaa">"me olvidé la billetera y me salvó"</em><br>
            &nbsp;&nbsp;<span style="color:#666; font-size:12px;">— Julio A. · Google Play · 27 may</span><br><br>
            &nbsp;&nbsp;<span style="color:#bbb">Salió sin billetera. Pagó igual.<br>
            &nbsp;&nbsp;Sin fricción. Sin llamar a nadie.<br>
            &nbsp;&nbsp;Eso es exactamente para lo que están.</span>
          </div>
          <br><span class="divider">▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔▔</span>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- EQUIPOS -->
<section id="equipos">
  <div class="section-tag">Routing</div>
  <h2 class="section-title">Routing inteligente por equipo</h2>
  <p class="section-sub">VIRA infiere el squad responsable leyendo el contenido de cada review — sin reglas fijas, con IA.</p>
  <div class="teams-grid">

    <div class="tribe">
      <div class="tribe-header">
        <div class="tribe-dot" style="background: var(--blue)"></div>
        <span class="tribe-name">Tribu Customer Journey</span>
      </div>
      <div class="squad">
        <div class="squad-name">GX · Growth Experience</div>
        <div class="squad-channel">#cx-guildpusf</div>
        <div class="squad-desc">Onboarding, registro, vinculación de cuentas/tarjetas, desbloqueos, recuperación de clave, Raspá y Ganá.</div>
      </div>
      <div class="squad">
        <div class="squad-name">Seguridad · Trust</div>
        <div class="squad-channel">#cx-fraude-trust</div>
        <div class="squad-desc">Fraude, desconocimiento de operaciones, validación de identidad, bloqueos por robo o pérdida.</div>
      </div>
    </div>

    <div class="tribe">
      <div class="tribe-header">
        <div class="tribe-dot" style="background: var(--purple)"></div>
        <span class="tribe-name">Tribu P2</span>
      </div>
      <div class="squad">
        <div class="squad-name">PTM · p2m</div>
        <div class="squad-channel">#expertos---p2m</div>
        <div class="squad-desc">Pagos a comercios presenciales/online, QR, NFC, VQR. Todo el proceso desde el escaneo hasta la transacción.</div>
      </div>
      <div class="squad">
        <div class="squad-name">PTP · p2p</div>
        <div class="squad-channel">#cx-p2p</div>
        <div class="squad-desc">Envíos y pedidos de dinero entre usuarios.</div>
      </div>
      <div class="squad">
        <div class="squad-name">MODO+</div>
        <div class="squad-channel">#cx-pagos-in-app</div>
        <div class="squad-desc">Recargas de celular, SUBE, Directv, Playstation.</div>
      </div>
    </div>

    <div class="tribe">
      <div class="tribe-header">
        <div class="tribe-dot" style="background: var(--green)"></div>
        <span class="tribe-name">Tribu Promercios</span>
      </div>
      <div class="squad">
        <div class="squad-name">Loyalty</div>
        <div class="squad-channel">#cx-derivaciones-comercios</div>
        <div class="squad-desc">Comercios presenciales/online, terminales de pago, integración en tienda online, mapa de comercios.</div>
      </div>
      <div class="squad">
        <div class="squad-name">Promociones</div>
        <div class="squad-channel">#ctl-detractores</div>
        <div class="squad-desc">Descuentos, cashback, promociones MODO y bancarias, gestión y análisis de incidencias.</div>
      </div>
    </div>

  </div>
</section>

<!-- ICEBERG -->
<section id="iceberg">
  <div class="section-tag">Metodología</div>
  <h2 class="section-title">El Principio Iceberg</h2>
  <div class="iceberg-section">
    <div class="iceberg-visual">
      <div class="iceberg-tip">
        <span style="font-size: 1.4rem;">📝</span><br>
        <strong style="color: white;">1 review visible</strong><br>
        <span style="font-size: 12px; color: #7a7b7c;">Lo que el equipo ve</span>
      </div>
      <div style="text-align:center; padding: 8px 0; color: rgba(74,158,255,0.5); font-size: 20px;">〰〰〰〰〰</div>
      <div class="iceberg-body">
        <div class="iceberg-num">~100</div>
        <div style="color: #555; font-size: 13px; margin-top: 4px;">usuarios que vivieron lo mismo<br>y no escribieron nada</div>
      </div>
    </div>
    <div class="iceberg-text">
      <h3>Por cada review, hay 100 silencios.</h3>
      <p>La mayoría de los usuarios no dejan reviews cuando tienen una mala experiencia — simplemente se van o dejan de usar la funcionalidad. Cada review visible es la punta de un iceberg mucho más grande.</p>
      <p>VIRA usa este principio para dimensionar el impacto real de cada bug reportado y generar el sentido de urgencia correcto en el equipo.</p>
      <div style="background: rgba(74,158,255,0.08); border: 1px solid rgba(74,158,255,0.2); border-radius: 8px; padding: 1rem; font-size: 13px; color: #bbb;">
        🧊 <strong style="color: white;">3 reviews de clave bloqueada</strong> esta semana<br>
        ≈ <strong style="color: var(--blue);">300 usuarios</strong> potencialmente afectados en silencio
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>Construido con <strong>Claude · Cowork</strong> por <strong>Ursula Tello</strong> · MODO CX Intelligence</p>
  <p style="margin-top: 0.5rem; font-size: 12px;">VIRA · Voz Inteligente de Reviews y Alertas</p>
</footer>

</body>
</html>
