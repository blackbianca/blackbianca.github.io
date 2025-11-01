---
layout: default
title: "Home"
---

<!-- 👤 Avatar + Name + Description -->
<img src="{{ site.author.avatar }}" alt="{{ site.author.name }}" width="160" style="border-radius:50%; display:block; margin:auto; box-shadow:0 0 8px rgba(0,0,0,0.2);">

<h1 style="text-align:center; margin-top: 1rem;">{{ site.author.name }}</h1>

<!-- Renders Markdown (italics) from _config.yml -->
<p style="text-align:center; margin-top: 0.5rem;">{{ site.description | markdownify }}</p>

<!-- Bio -->
<p style="text-align:center; font-style:italic;">{{ site.author.bio }}</p>

---

### Bio

Hi! I’m Alessandro, I am a radio astronomer, currently based in {{ site.author.location }}.  
I am into HI science, and enjoy every step of it, from data reduction to beautiful 21-cm images. This website gathers some information about me.

---

### 🚀 Featured Projects

A few things I’ve been working on lately:

- **[Pulsar Finder](https://github.com/blackbianca/pulsar-finder):** A Python tool to analyze pulsar timing data.  
- **[StarPy](https://github.com/blackbianca/starpy):** A small astronomy package for stellar spectra visualization.  
- **[CosmicWebViz](https://github.com/blackbianca/cosmicwebviz):** Interactive visualization of the cosmic web using Python + D3.js.

👉 See more on the [Projects page](/projects/).

---

### 📚 Recent Publications

- *Bianchetti et al. (2024)* — “Detection of Fast Radio Bursts with LOFAR.”  
  _Astrophysical Journal_ [[ADS](https://ui.adsabs.harvard.edu/)]
- *Bianchetti et al. (2023)* — “Machine Learning for Pulsar Classification.”  
  _Monthly Notices of the RAS_

👉 Full list on the [Publications page](/publications/).

---

### Collaborations

- Euclid
- MIGHTEE
- EDFS-MeerKAT
- superMIGHTEE

### 🌐 Connect with me

<div style="text-align:center; font-size:1.1em;">
  <a href="{{ site.social_links.github }}" target="_blank">🐙 GitHub</a> &nbsp;|&nbsp;
  <a href="{{ site.social_links.linkedin }}" target="_blank">💼 LinkedIn</a> &nbsp;|&nbsp;
  <a href="{{ site.social_links.instagram }}" target="_blank">📸 Instagram</a>
</div>

---

<p style="text-align:center; color:gray; font-size:0.9em; margin-top:2rem;">
Made with ❤️ and the <a href="https://github.com/pages-themes/cayman">Cayman</a> theme.
</p>
