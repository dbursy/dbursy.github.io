---
permalink: /
layout: page
title: Home
hide_header: true
---

<script>
function changeImage() {
    var image = document.getElementById('change-image');
    image.src = './assets/imgs/passbild_contact.jpg';
}

function restoreImage() {
    var image = document.getElementById('change-image');
    image.src = './assets/imgs/passbild.jpg';
}
</script>

<br>
<div style="float: left; margin-right: 1em; width: 200px; height: 200px; overflow: hidden; border-radius: 12px;">
  <img src="./assets/imgs/passbild.jpg" id="change-image" alt="Original Image" 
       style="width: 100%; height: 117.65%; object-fit: cover; object-position: top; display: block;">
</div>

I am a PhD student in Economics at the [Berlin School of Economics](https://berlinschoolofeconomics.de/home), the [DIW Berlin](https://www.diw.de/en), and at the [FU Berlin](https://www.wiwiss.fu-berlin.de/en/index.html). 

My research interests lie in Environmental & Development Economics and Political Economy. In particular, I am interested in how climate, natural disasters and social issues affect regional economic and human development. 

If you are interested in research topics please feel free to reach out: 
<a id="hover-link" onmouseover="changeImage()" onmouseout="restoreImage()">dominik.bursy [at] icloud.com</a>

<div style="margin: 1em 0; display: flex; justify-content: flex-end; gap: 8px; flex-wrap: wrap;">
  <span class="topic-tag">Environment</span>
  <span class="topic-tag">Development</span>
  <span class="topic-tag">Political Economy</span>
  <span class="topic-tag">Spatial Economics</span>
</div>