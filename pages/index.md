---
layout: default
permalink: /
---
<style>
  :root { --fg:#111827; --accent:#2563eb; --accent-700:#1e40af; --muted:#e5e7eb; --muted-2:#d1d5db; --hover:#f3f4f6; }
  * { box-sizing:border-box }
  html,body { height:100% }
  body {
    margin:0;
    font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,"Noto Sans",Arial;
    color:var(--fg);
    /* no page background */
  }
  .center { min-height:100svh; display:grid; place-items:center; text-align:center }
  nav { display:flex; flex-direction:column; gap:16px; align-items:center }
  .btn {
    display:inline-flex; align-items:center; justify-content:center;
    min-width:260px; padding:0.9rem 1.25rem; border-radius:9999px;
    text-decoration:none; font-weight:600; letter-spacing:.2px;
    border:1px solid var(--muted); background:transparent; color:inherit;
    box-shadow:none; transition:background-color .15s ease,border-color .15s ease;
  }
  .btn:hover { background:var(--hover); border-color:var(--muted-2) }
  .btn.primary {
    background:var(--accent); color:#fff; border-color:var(--accent);
  }
  .btn.primary:hover { background:var(--accent-700); border-color:var(--accent-700) }
  :focus-visible { outline:2px solid var(--accent); outline-offset:3px }
</style>
{% include landing.html %}
  <nav>
    <a class="btn primary" href="https://store.steampowered.com/app/3890550">Wishlist J.A.M on Steam!</a>
    <a class="btn" href="/Projects">Our Games</a>
    <a class="btn" href="/About">About Lycoris</a>
  </nav>
