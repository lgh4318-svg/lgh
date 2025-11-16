<!doctype html>
<html lang="ko">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>청첩장 — 신랑 ♥ 신부</title>
  :root{--bg:#faf8f5;--accent:#2b2b2b;--muted:#7a7a7a;--card:#fff}
  *{box-sizing:border-box}
  body{margin:0;font-family: "Noto Sans KR", system-ui, -apple-system, "Segoe UI", Roboto; background:var(--bg); color:var(--accent); -webkit-font-smoothing:antialiased;}
  header{min-height:56vh;display:flex;align-items:center;justify-content:center;padding:28px;background-image:linear-gradient(rgba(255,255,255,0.65),rgba(255,255,255,0.65)),url('hero.jpg');background-size:cover;background-position:center;}
  .hero-card{background:rgba(255,255,255,0.8);padding:18px;border-radius:14px;text-align:center;max-width:720px;width:100%;}
  .names{font-size:1.6rem;font-weight:700;letter-spacing:0.02em;}
  .date{margin-top:6px;color:var(--muted);font-size:0.95rem;}
  main{padding:18px;max-width:720px;margin:0 auto;}
  section{background:var(--card);border-radius:12px;padding:14px;margin-bottom:14px;box-shadow:0 6px 18px rgba(11,11,11,0.04);}
  h2{margin:0 0 8px 0;font-size:1rem}
  p.lead{margin:0;color:var(--muted);line-height:1.5}
  .info-row{display:flex;justify-content:space-between;gap:12px;align-items:center;}
  .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:#111;color:#fff;text-decoration:none;font-weight:600}
  .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:6px}
  .gallery img{width:100%;display:block;border-radius:8px;height:80px;object-fit:cover}
  .map-links{display:flex;gap:8px;flex-wrap:wrap}
  .bank{font-family:monospace;background:#f7f7f7;padding:8px;border-radius:8px}
  .copy-btn{margin-left:8px;padding:6px 8px;border-radius:8px;border:1px solid #ddd;background:#fff;cursor:pointer}
  footer{padding:20px;text-align:center;color:var(--muted);font-size:0.85rem}
  /* responsive */
  @media(min-width:600px){ .gallery img{height:120px} header{min-height:40vh} .names{font-size:2rem} }
  /* RSVP floating button */
  .rsvp-fab{position:fixed;right:16px;bottom:16px;z-index:40;}
  .rsvp-fab button{background:#e76f51;border:none;padding:14px 18px;border-radius:999px;color:white;font-weight:700;box-shadow:0 8px 20px rgba(0,0,0,0.15);cursor:pointer}
  /* simple modal */
  .modal{position:fixed;inset:0;background:rgba(0,0,0,0.45);display:none;align-items:center;justify-content:center;padding:20px}
  .modal .card{background:white;padding:18px;border-radius:12px;width:100%;max-width:420px}
  .close{float:right;background:#eee;border-radius:8px;padding:6px 8px;border:none;cursor:pointer}
  .countdown{font-weight:700;font-size:1.05rem}
