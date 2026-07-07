---
title: Speaker Series
description: Talks and invited speakers hosted by Cryptolets
permalink: /speaker-series/
---

<div style="margin-top: 1rem; padding: 1rem 1.25rem; border-left: 4px solid #1f4f7a; background: #eef5fb; border-radius: 8px;">
  <strong>Interest in cryptographic hardware?</strong> Subscribe to future talks by sending an email to
  <a href="mailto:cryptolets+subscribe@googlegroups.com">cryptolets+subscribe@googlegroups.com</a>. You can also watch past talks on the
  <a href="https://www.youtube.com/watch?v=2lh_tB5UqXA&list=PL187zrvJshWlsHwoIWj6_r-GylHd1nMWG&pp=0gcJCeECOCosWNinsAgC" target="_blank" rel="noopener">YouTube playlist</a>.
</div>

<div style="display: flex; flex-direction: column; gap: 2rem; margin-top: 2rem;">
  <div style="width: 100%; border: 1px solid #ccc; border-radius: 10px; padding: 1.5rem; background: #f9f9f9; box-shadow: 0 2px 8px rgba(0,0,0,0.04);">
    <h2 style="margin-top: 0;">Speaker Series Talk 04</h2>
    <p><strong>Speaker:</strong> <a href="https://www.ccny.cuny.edu/profiles/rosario-gennaro" target="_blank" rel="noopener">Prof. Rosario Gennaro</a> (CUNY)</p>
    <p><strong>Title:</strong> Towards Verifiable AI with Lightweight Cryptographic Proofs of Inference</p>
    <p><strong>Date:</strong> July 8, 2026 @ 3:00 PM EDT</p>
    <p><strong>Zoom:</strong> <a href="https://nyu.zoom.us/j/9039771306" target="_blank" rel="noopener">Join the talk on Zoom</a></p>
    <p>
      <strong>Abstract:</strong>
      When large AI models are deployed as cloud-based services, clients have no guarantee that responses are correct or were produced by the intended model. Running inference locally is often infeasible for large models, and existing cryptographic proof systems, while offering strong correctness guarantees, introduce prohibitive prover overhead. This talk presents a verifiable inference framework that replaces full cryptographic proofs with a lightweight sampling-based approach grounded in statistical properties of neural networks. The prover commits to the execution trace of inference via Merkle-tree-based vector commitments and opens only a small number of entries along randomly sampled paths from output to input. The resulting protocol trades soundness for efficiency, making it well-suited to auditing and large-scale deployment settings where repeated queries amplify detection probability. Experimental results show several orders of magnitude reduction in proving time compared to state-of-the-art cryptographic proof systems, while maintaining practical verification guarantees.
    </p>
  </div>
  <div style="width: 100%; border: 1px solid #ccc; border-radius: 10px; padding: 1.5rem; background: #f9f9f9; box-shadow: 0 2px 8px rgba(0,0,0,0.04);">
    <h2 style="margin-top: 0;">Speaker Series Talk 03</h2>
    <p><strong>Speaker:</strong> <a href="https://austinrovin.ski" target="_blank" rel="noopener">Prof. Austin Rovinski</a> (NYU)</p>
    <p><a href="https://youtu.be/2lh_tB5UqXA?si=6yEqXNYsla7bnKZo" target="_blank" rel="noopener">Watch on YouTube</a></p>
    <p><strong>Title:</strong> An Automated Interconnect Modeling Framework for Rapid Cryptolet Design Space Exploration</p>
    <p><strong>Date:</strong> June 10, 2026 @ 3:00 PM EDT</p>
    <p>
      <strong>Abstract:</strong>
      State-of-the-art cryptographic hardware accelerators often require a huge amount of silicon area, sometimes exceeding what can fit on a single chip. This motivates chiplet-based systems, where multiple chips are tightly integrated in one package instead of relying on one large die. In this talk, Austin Rovinski will present recent work on an automated interconnect modeling framework that simplifies chiplet interconnect modeling and enables rapid, system-level design space exploration for cryptographic chiplet systems, or cryptolets. The talk will also include a sneak-peek demo of the framework ahead of its open-source release next month.
    </p>
  </div>
  <div style="width: 100%; border: 1px solid #ccc; border-radius: 10px; padding: 1.5rem; background: #f9f9f9; box-shadow: 0 2px 8px rgba(0,0,0,0.04);">
    <h2 style="margin-top: 0;">Speaker Series Talk 02</h2>
    <p><strong>Speaker:</strong> <a href="https://engineering.nyu.edu/faculty/brandon-reagen" target="_blank" rel="noopener">Prof. Brandon Reagen</a> (NYU)</p>
    <p><a href="https://youtu.be/np_Z5H1KjkQ?si=JFOV6CxZOn2ttT0A" target="_blank" rel="noopener">Watch on YouTube</a></p>
    <p><strong>Title:</strong> The Cryptolets Program with Applications to Point Addition</p>
    <p><strong>Date:</strong> May 13, 2026 @ 3:00 PM EDT</p>
    <p>
      <strong>Abstract:</strong>
      Cryptographic computing is changing what we can compute and how we think about data sharing. Methods including fully homomorphic encryption and zero-knowledge proofs have gained attention and are starting to be deployed, but high performance overheads still limit ubiquity. Cryptolets supports this growing area by developing an open-source hardware IP repository spanning modular multipliers to full accelerators such as NTT and MSM units. The program also goes beyond an IP library by building open-source chiplet interfaces for scale-out acceleration and tightly integrating formal verification to prove design correctness. This talk reviews those efforts and highlights early library developments for point addition and MSM, which are commonly used in ZKPs.
    </p>
  </div>
  <div style="width: 100%; border: 1px solid #ccc; border-radius: 10px; padding: 1.5rem; background: #f9f9f9; box-shadow: 0 2px 8px rgba(0,0,0,0.04);">
    <h2 style="margin-top: 0;">Speaker Series Talk 01</h2>
    <p><strong>Speaker:</strong> Prof. <a href="https://engineering.nyu.edu/faculty/ramesh-karri" target="_blank" rel="noopener">Ramesh Karri</a> (NYU)</p>
    <p><a href="https://youtu.be/kAClPrr6XXc?si=CG8gBwbmDMTg1cLC" target="_blank" rel="noopener">Watch on YouTube</a></p>
    <p>
      <strong>Title:</strong>
      <a href="https://arxiv.org/abs/2602.09919" target="_blank" rel="noopener">
        LLM4PQC: LLM-Driven High-Level Synthesis for Post-Quantum Cryptography Hardware
      </a>
    </p>
    <p><strong>Date:</strong> April 8, 2026 @ 3:00 PM EDT</p>
    <p>
      <strong>Abstract:</strong>
      Designing hardware accelerators for post-quantum cryptography (PQC) is labor-intensive, with a critical bottleneck being the manual refactoring of NIST PQC reference C code into HLS-ready specifications. We present LLM4PQC, an agentic LLM-based framework that automates this conversion, generating synthesizable HLS C code for complex PQC primitives including NTT accelerators and wide memory interfaces. The framework employs a feedback-driven, hierarchical verification pipeline spanning C compilation, C simulation, and RTL simulation to ensure functional correctness. Preliminary case studies on NIST PQC reference designs, including Kyber, Dilithium, and Falcon, demonstrate significant reductions in manual effort and faster design-space exploration relative to traditional flows. LLM4PQC offers a scalable and efficient pathway for accelerating the hardware realization of next-generation cryptographic standards.
    </p>
  </div>
</div>
