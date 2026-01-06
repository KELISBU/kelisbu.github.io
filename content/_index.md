---
title: ""
hideMeta: true
---

<style>
.hero{ display:flex; gap:2.5rem; align-items:flex-start; margin-top:1rem; }
.hero-left{ flex:1 1 auto; min-width:280px; }
.hero-right{ flex:0 0 320px; }
.portrait{ width:320px; max-width:100%; border-radius:10px; box-shadow:0 10px 25px rgba(0,0,0,.12); }
@media (max-width:900px){
  .hero{ flex-direction:column; }
  .hero-right{ flex-basis:auto; }
}
</style>

<div class="hero">
  <div class="hero-left">
...
  </div>

  <div class="hero-right">
    <img class="portrait" src="{{ "img/me.jpg" | relURL }}" alt="portrait">
  </div>
</div>

## News
{{< news >}}

