---
layout: home
title: Cryptolets
description: Open-source cryptographic hardware for secure computing
background: /assets/theme/images/chuttersnap-146799-unsplash.jpg
permalink: /
---

<div class="row align-items-center g-4 mt-4">
  <div class="col-12">
    <p class="lead">
      Cryptolets is an open-source research program building reusable hardware blocks, design tools, and a community around cryptographic computing.
    </p>
    <p>
      Modern privacy-preserving systems, including zero-knowledge proofs, fully homomorphic encryption, and post-quantum cryptography, need fast and trustworthy hardware. Cryptolets develops a shared hardware repository and supporting workflows so researchers and builders can explore cryptographic accelerators from modular arithmetic primitives through larger chiplet-scale systems.
    </p>
    <div class="cryptolets-home-actions d-flex flex-wrap justify-content-center gap-2 mt-4">
      <a class="btn btn-outline-primary" href="{{ '/speaker-series/' | relative_url }}">Speaker series</a>
      <a class="btn btn-outline-primary" href="{{ '/tutorials/' | relative_url }}">Tutorials</a>
    </div>
  </div>
</div>

<div class="cryptolets-involved-band mt-4">
  <div>
    <h2 class="mt-0">Get Involved</h2>
    <p class="mb-0">
      Follow the code, join the mailing list, or catch up on talks and tutorials from the Cryptolets community.
    </p>
  </div>
  <div class="cryptolets-involved-links">
    <a class="btn btn-outline-primary" href="https://github.com/cryptolets/cryptolets" target="_blank" rel="noopener">GitHub Repository</a>
    <a class="btn btn-outline-primary" href="https://groups.google.com/u/1/g/cryptolets" target="_blank" rel="noopener">Subscribe Google Group</a>
  </div>
</div>

<div class="mt-5 p-4" style="border-left: 4px solid #1f4f7a; background: #eef5fb; border-radius: 8px;">
  <h2 class="mt-0">Program Overview</h2>
  <p>
    Cryptolets brings together open-source hardware IP, automated design-space exploration, and community education for cryptographic acceleration. The project is rooted in the NSF-supported Cryptolets program and is organized around practical, inspectable artifacts: source code, tutorials, talks, and reproducible design flows.
  </p>
  <p class="mb-0">
    The public repository includes infrastructure for cryptographic hardware modules, including primitive building blocks, modular operations, design sweeps, Tcl cores, and analysis utilities.
  </p>
</div>

<div class="cryptolets-card-section mt-4">
  <div class="navigation-wrapper" aria-label="Program pillar navigation">
    <button class="cryptolets-card-nav" type="button" data-cryptolets-scroll="prev" aria-label="Previous program pillar">&lsaquo;</button>
    <button class="cryptolets-card-nav" type="button" data-cryptolets-scroll="next" aria-label="Next program pillar">&rsaquo;</button>
  </div>

  <div class="swiper card-carousel swiper-initialized swiper-horizontal swiper-backface-hidden cryptolets-card-carousel">
    <div class="cryptolets-card-track">
      <div class="swiper-slide card cryptolets-pillar-card">
        <div class="card-body">
          <h3 class="h5 card-title">Open Hardware IP</h3>
          <p class="card-text">Reusable cryptographic building blocks for modular arithmetic, point operations, NTT-style kernels, and related accelerator components.</p>
        </div>
      </div>

      <div class="swiper-slide card cryptolets-pillar-card">
        <div class="card-body">
          <h3 class="h5 card-title">Design Exploration</h3>
          <p class="card-text">Scripts and sweep flows for comparing architecture choices across performance, area, implementation targets, and design constraints.</p>
        </div>
      </div>

      <div class="swiper-slide card cryptolets-pillar-card">
        <div class="card-body">
          <h3 class="h5 card-title">Verification</h3>
          <p class="card-text">A focus on correctness and reproducibility, connecting cryptographic hardware generation with testing, analysis, and future formal methods.</p>
        </div>
      </div>

      <div class="swiper-slide card cryptolets-pillar-card">
        <div class="card-body">
          <h3 class="h5 card-title">Community</h3>
          <p class="card-text">Talks, tutorials, workshops, and shared resources for researchers working on cryptographic hardware and secure computing systems.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var track = document.querySelector(".cryptolets-card-track");
    var controls = document.querySelectorAll("[data-cryptolets-scroll]");

    if (!track || controls.length === 0) {
      return;
    }

    controls.forEach(function (control) {
      control.addEventListener("click", function () {
        var direction = control.getAttribute("data-cryptolets-scroll") === "prev" ? -1 : 1;
        var scrollAmount = Math.min(track.clientWidth * 0.85, 560);
        track.scrollBy({ left: direction * scrollAmount, behavior: "smooth" });
      });
    });
  });
</script>

<div class="mt-4">
  <h2>What We Are Building</h2>
  <ul>
    <li>An open repository for cryptographic hardware modules and reusable implementation flows.</li>
    <li>Hardware components that support proof systems, post-quantum cryptography, and privacy-preserving computation.</li>
    <li>Design-space exploration tools for evaluating accelerators across FPGA and ASIC-oriented workflows.</li>
    <li>Community resources that make cryptographic hardware easier to learn, reproduce, and extend.</li>
  </ul>
</div>

<div class="mt-4">
  <h2>Reference</h2>
  <p>
    Cryptolets was originally supported through
    <a href="https://www.nsf.gov/awardsearch/show-award?AWD_ID=2450539" target="_blank" rel="noopener">NSF Award</a>.
  </p>
</div>
