---
title: Cryptolets Tutorial at ISCA 2026
date: 2026-06-27
categories: tutorial
background: /assets/theme/images/cryptolets_header.png
---

<h2 align="center"><strong>Cryptolets: Building a Community and Open-Source Hardware Repository for Cryptographic Computing</strong></h2>

**Event:** [ISCA 2026](https://iscaconf.org/isca2026/program/workshops.php) Tutorial  
**Date:** June 27, 2026 (Saturday afternoon, half day)  
**Location:** ISCA 2026 Conference Venue, Room 301B

<h3 style="margin-top: 2rem; margin-bottom: 2rem;">Schedule</h3>

<div class="col-md-12">
<table class="table table-hover" style="width: 100%;">
<thead class="thead-light">
<tr>
<th colspan="4" scope="col">Saturday June 27, 2026 <em>(all times are local conference time)</em></th>
</tr>
<tr>
<th scope="col" style="width: 18%;">Time</th>
<th scope="col" style="width: 34%;">Title</th>
<th scope="col" style="width: 32%;">Speaker</th>
<th scope="col" style="width: 16%;">Details</th>
</tr>
</thead>
<tbody>
<tr bgcolor="#EBF5FB">
<th scope="row">1:00-1:30</th>
<td>Introducing Cryptolets</td>
<td>Brandon Reagen</td>
<td><a href="#speaker1">Abstract</a></td>
</tr>
<tr>
<th scope="row">1:30-2:00</th>
<td>Connecting Cryptolet Chiplets</td>
<td>Thierry Tambe</td>
<td><a href="#speaker2">Abstract</a></td>
</tr>
<tr>
<th scope="row">2:00-2:30</th>
<td>Zero Knowledge Proofs</td>
<td>David Inyangson</td>
<td><a href="#speaker3">Abstract</a></td>
</tr>
<tr bgcolor="#FEF9E7">
<th scope="row">2:40-3:00</th>
<td>Break</td>
<td>-</td>
<td>&nbsp;</td>
</tr>
<tr>
<th scope="row">3:00-3:30</th>
<td>A Chiplet Interface Model for System-Level PPA Exploration</td>
<td>Austin Rovinski</td>
<td><a href="#speaker4">Abstract</a></td>
</tr>
<tr>
<th scope="row">3:30-4:00</th>
<td>Formal Verification</td>
<td>Caroline Trippel</td>
<td><a href="#speaker5">Abstract</a></td>
</tr>
<tr>
<th scope="row">4:00-4:30</th>
<td>Code generation for cryptographic kernels using multi-word modular arithmetic</td>
<td>Naifeng Zhang</td>
<td><a href="#speaker6">Abstract</a></td>
</tr>
<tr>
<th scope="row">4:30-4:45</th>
<td>The Cryptolets Design Challenge</td>
<td>Warren Savage</td>
<td><a href="#speaker7">Abstract</a></td>
</tr>
<tr>
<th scope="row">4:45-5:15</th>
<td>Demo and question and answer session</td>
<td>Code and Demo (Alhad Daftardar and Gaurav Kuwar)</td>
<td><a href="#speaker8">Abstract</a></td>
</tr>
<tr bgcolor="#EBF5FB">
<th scope="row">5:15-5:30</th>
<td>Conclusion and Networking</td>
<td>-</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>
</div>

<h3 style="margin-top: 2rem; margin-bottom: 2rem;">What is Cryptolets?</h3>

Cryptolets is an NSF CIRC Grand project building an open hardware ecosystem for cryptographic computing, including zero-knowledge proofs and fully homomorphic encryption.

<h3 style="margin-top: 2rem; margin-bottom: 2rem;">Why Cryptolets?</h3>

Cryptographic computing enables strong guarantees for privacy, integrity, and verifiability, but current systems are often too slow and too hard to build. Cryptolets lowers the barrier to entry with reusable hardware building blocks, chiplet-aware design flows, and shared evaluation infrastructure.

<h3 style="margin-top: 2rem; margin-bottom: 2rem;">What this tutorial covers</h3>

- The Cryptolets vision and how to get involved
- Open-source hardware IP and chiplet-aware design and EDA workflows
- Benchmarking and verification infrastructure for reproducible comparisons
- Modular, extensible accelerators rather than one-off bespoke designs

<h3 style="margin-top: 2rem; margin-bottom: 2rem;">Speaker Abstracts</h3>

<section id="speakers" class="section speakers">
<div class="container" style="display: flex; align-items: flex-start; flex-wrap: wrap; gap: 20px;">
<div class="speaker-info" style="flex: 1;">
<h4 id="speaker1" style="margin-top: 1em; margin-bottom: 0.1em;">Introducing Cryptolets</h4>
<strong>Brandon Reagen:</strong> In this talk I will introduce the Cryptolets program, goals, and initial accomplishments. I will explain ways to get involved and showcase initial development on modular functional units and point addition.
</div>
</div>

<div class="container" style="display: flex; align-items: flex-start; flex-wrap: wrap; gap: 20px;">
<div class="speaker-info" style="flex: 1;">
<h4 id="speaker2" style="margin-top: 1em; margin-bottom: 0.1em;">Connecting Cryptolet Chiplets</h4>
<strong>Thierry Tambe:</strong> We will present a library of HLS-synthesizable hardware components to design spec-adherent UCIe controllers for high-performance chiplet-to-chiplet communication as well as CHIPKIT, which is an agile, reusable open-source framework for rapid test chip development.
</div>
</div>

<div class="container" style="display: flex; align-items: flex-start; flex-wrap: wrap; gap: 20px;">
<div class="speaker-info" style="flex: 1;">
<h4 id="speaker3" style="margin-top: 1em; margin-bottom: 0.1em;">Zero Knowledge Proofs</h4>
<strong>David Inyangson:</strong> Abstract to be announced.
</div>
</div>

<div class="container" style="display: flex; align-items: flex-start; flex-wrap: wrap; gap: 20px;">
<div class="speaker-info" style="flex: 1;">
<h4 id="speaker4" style="margin-top: 1em; margin-bottom: 0.1em;">A Chiplet Interface Model for System-Level PPA Exploration</h4>
<strong>Austin Rovinski:</strong> State-of-the-art cryptographic hardware accelerators often require a huge amount of silicon area, sometimes exceeding what can fit on a single chip. This motivates chiplet-based systems, where multiple chips are tightly integrated in one package instead of relying on one large die. In this talk, Austin Rovinski will present recent work on an automated interconnect modeling framework that simplifies chiplet interconnect modeling and enables rapid, system-level design space exploration for generic chiplet systems. A demonstration of the framework will follow later in the session.
</div>
</div>

<div class="container" style="display: flex; align-items: flex-start; flex-wrap: wrap; gap: 20px;">
<div class="speaker-info" style="flex: 1;">
<h4 id="speaker5" style="margin-top: 1em; margin-bottom: 0.1em;">Formal Verification</h4>
<strong>Caroline Trippel:</strong> A 2024 Siemens EDA study found that even though verification consumed more than 50% of development resources, critical bugs still escaped to silicon in more than 85% of the studied industrial hardware design projects, indicating that verification is a major bottleneck. This 20-year low in first-silicon success coincides with a near-doubling of projects featuring AI accelerators, reaching 59% since 2022. These findings reflect the proliferation of hardware accelerators whose increasing variety and complexity exacerbate the challenge of traditional verification. This talk will challenge the conventional wisdom that rigorous formal verification is a manual task reserved for experts and introduce new approaches and tools we are developing to automate, scale, and democratize formal hardware verification.
</div>
</div>

<div class="container" style="display: flex; align-items: flex-start; flex-wrap: wrap; gap: 20px;">
<div class="speaker-info" style="flex: 1;">
<h4 id="speaker6" style="margin-top: 1em; margin-bottom: 0.1em;">Code generation for cryptographic kernels using multi-word modular arithmetic</h4>
<strong>Naifeng Zhang:</strong> Fully homomorphic encryption and zero-knowledge proofs are emerging as solutions for data security in distributed environments. However, widespread adoption is hindered by significant computational overhead from core cryptographic operations involving large integer arithmetic. This work presents a formalization of multi-word modular arithmetic (MoMA), which breaks down large bit-width integer arithmetic into operations on machine words. We further develop a rewrite system that implements MoMA through recursive rewriting of data types for compatibility with compiler infrastructures and code generators. We evaluate MoMA by generating cryptographic kernels, including BLAS operations and the number theoretic transform, targeting multiple GPUs. Our MoMA-based BLAS operations outperform state-of-the-art multi-precision libraries by orders of magnitude, and MoMA-based NTTs achieve near-ASIC performance on commodity GPUs.
</div>
</div>

<div class="container" style="display: flex; align-items: flex-start; flex-wrap: wrap; gap: 20px;">
<div class="speaker-info" style="flex: 1;">
<h4 id="speaker7" style="margin-top: 1em; margin-bottom: 0.1em;">The Cryptolets Design Challenge</h4>
<strong>Warren Savage:</strong> I will explain the challenge and how you can get access to free silicon.
</div>
</div>

<div class="container" style="display: flex; align-items: flex-start; flex-wrap: wrap; gap: 20px;">
<div class="speaker-info" style="flex: 1;">
<h4 id="speaker8" style="margin-top: 1em; margin-bottom: 0.1em;">Demo and question and answer session</h4>
<strong>Code and Demo (Alhad Daftardar and Gaurav Kuwar):</strong> Live code demo followed by Q&amp;A.
</div>
</div>
</section>

<h3 style="margin-top: 2rem; margin-bottom: 2rem;">Organizers</h3>

- Warren Savage (Rocksavage Technology)
- Brandon Reagen, Siddharth Garg, Austin Rovinski, Ramesh Karri (NYU)
- Caroline Trippel, Thierry Tambe (Stanford)
- Tushar Jois, Rosario Gennaro (CUNY)

---
For more details, contact the organizers or visit [ISCA 2026](https://iscaconf.org/isca2026/program/workshops.php).
