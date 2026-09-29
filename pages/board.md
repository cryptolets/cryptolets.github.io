---
title: Board
description: Industry board of the Cryptolets program
permalink: /board/
---

<style>
  .cryptolets-board-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(min(150px, 100%), 1fr));
    gap: 1.5rem;
    margin-top: 2rem;
  }
  .cryptolets-board-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
    border: 1px solid #ccc;
    border-radius: 10px;
    padding: 1.5rem 1rem 1rem;
    background: #fff;
    box-shadow: 0 2px 8px rgba(0,0,0,0.04);
    text-decoration: none;
    color: inherit;
    transition: box-shadow 0.15s ease, transform 0.15s ease;
  }
  .cryptolets-board-card:hover,
  .cryptolets-board-card:focus-visible {
    box-shadow: 0 4px 14px rgba(0,0,0,0.10);
    transform: translateY(-2px);
    text-decoration: none;
  }
  .cryptolets-board-logo {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 80px;
    width: 100%;
  }
  .cryptolets-board-logo img {
    max-height: 50px;
    max-width: 85%;
    object-fit: contain;
  }
  .cryptolets-board-name {
    font-weight: 600;
    text-align: center;
  }
</style>

<p>The Cryptolets board brings together industry partners working across semiconductors, computing, and cryptographic technologies.</p>

<div class="cryptolets-board-grid">
  {% for member in site.data.board %}
    <a class="cryptolets-board-card" href="{{ member.url }}" target="_blank" rel="noopener">
      <div class="cryptolets-board-logo">
        <img src="{{ member.logo | relative_url }}" alt="{{ member.name }} logo" loading="lazy">
      </div>
      <div class="cryptolets-board-name">{{ member.name }}</div>
    </a>
  {% endfor %}
</div>
