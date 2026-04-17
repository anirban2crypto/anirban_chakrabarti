---
layout: default
title: "Anirban Chakrabarti"
description: "Researcher in applied cryptography, privacy-preserving ML, and blockchain privacy. PhD from IISc Bangalore, currently at Microsoft Research India."
---

<section id="about" class="hero-section">
  <div class="profile-container">
    <div class="profile-image-wrapper">
      <img src="{{ '/assets/profile.png' | relative_url }}" alt="Anirban Chakrabarti" class="profile-img" />
    </div>
    <div class="profile-info">
      <h1 class="profile-name">Anirban Chakrabarti</h1>
      <p class="profile-tagline">
        Research Intern, <a href="https://www.microsoft.com/en-us/research/lab/microsoft-research-india/" target="_blank" rel="noopener noreferrer">Microsoft Research India</a><br>
        PhD in Computer Science, <a href="https://iisc.ac.in/" target="_blank" rel="noopener noreferrer">Indian Institute of Science</a>, Bengaluru<br>
        Advisor: <a href="https://www.csa.iisc.ac.in/~bhavana/" target="_blank" rel="noopener noreferrer">Prof. Bhavana Kanukurthi</a>
      </p>
      <p class="profile-summary">
        My research lies at the intersection of applied cryptography, privacy-preserving machine learning, and blockchain privacy. I design and build cryptographic protocols for secure distributed systems, with recent work on zero-knowledge proofs for LLM inference integrity and threshold encryption for mempool privacy.
      </p>
      {% include social.html %}
    </div>
  </div>
</section>

<section id="research" class="content-section" markdown="1">

## Publications & Preprints

<div class="research-card" markdown="1">

### Traceable Threshold Batch Encryption with Applications to Enhancing Mempool Privacy

**A. Chakrabarti, M. Maitra, A. Mondal**

ACM ASIACCS 2026

- Developed a traceable threshold batch encryption scheme for enhancing mempool privacy in blockchain systems
- Designed accountability mechanisms for identifying misbehaving parties in threshold decryption
- Implemented and benchmarked a prototype in Rust

</div>

<div class="research-card" markdown="1">

### Silent Threshold Traitor Tracing & Enhancing Mempool Privacy

**A. Chakrabarti, M. Maitra, A. Mondal, K. Sehgal**

[ACM CCS 2025](https://dl.acm.org/doi/10.1145/3719027.3765099), pp. 1769--1783

- Developed a threshold traitor tracing scheme for encrypted mempools, private voting, and sealed-bid auctions
- Designed accountability mechanisms to identify misbehavior when parties compromise private keys
- Implemented and benchmarked a prototype in Go

</div>

<div class="research-card" markdown="1">

### Secure Fuzzy Deduplication: Definitions and Constructions

**A. Chakrabarti, S. Gupta, B. Kanukurthi, G. Shankar**

[ACM CCSW 2025](https://dl.acm.org/doi/10.1145/3733812.3765537), pp. 80--94

- Proposed a secure deduplication system preserving uniqueness in similar files while eliminating cloud storage redundancy
- Implemented constructions in C++, Python, and Shell
- Validated on real-world datasets (images and genomic data)

</div>

</section>

<section id="experience" class="content-section" markdown="1">

## Research Experience

<div class="experience-block" markdown="1">

### Microsoft Research India
September 2025 to present -- *Research Intern, Applied Cryptography & Secure AI*

- Investigating zero-knowledge proof systems for verifiable LLM inference
- Designing cryptographic protocols for privacy-preserving machine learning pipelines
- Collaborating with MSR researchers on scalable proof systems for AI model integrity

</div>

<div class="experience-block" markdown="1">

### Technical University of Darmstadt, Germany
May 2024 to October 2024 -- *Research Intern*<br>
Host: <a href="https://www.informatik.tu-darmstadt.de/cac/cac/team_cac/sebastian_faust_cac/index.en.jsp" target="_blank" rel="noopener noreferrer">Prof. Sebastian Faust</a>

- Designed threshold cryptographic protocols distributing trust among multiple parties
- Developed a protocol to prevent misuse of Miner Extractable Value (MEV) in DeFi

</div>

</section>

<section id="education" class="content-section" markdown="1">

## Education

<div class="education-block" markdown="1">

### PhD in Computer Science
**Indian Institute of Science, Bengaluru** -- August 2019 to November 2025<br>
Advisor: <a href="https://www.csa.iisc.ac.in/~bhavana/" target="_blank" rel="noopener noreferrer">Prof. Bhavana Kanukurthi</a>

**Thesis:** *Enhancing Privacy and Efficiency of Distributed Encryption*

**Coursework:** Cryptography; Zero-Knowledge Proof Systems; Design and Analysis of Algorithms; Linear Algebra and Probability; Game Theory; Post-Quantum Cryptography from Lattices; Quantum Cryptography

</div>

<div class="education-block" markdown="1">

### B.Tech in Information Technology
**MCKV Institute of Engineering** -- 2007 to 2011

</div>

<div class="highlight-box" markdown="1">

**GATE 2019** (Computer Science and Information Technology) -- Score: **774**, All India Rank: **330**

</div>

</section>

<section id="service" class="content-section" markdown="1">

## Professional Service

<div class="service-list" markdown="1">

**Conference Reviewer**
- ASIACRYPT 2024
- ACNS 2026
- CRYPTO 2026

**Teaching Assistant** -- *Theoretical Foundations of Cryptography*, IISc Bengaluru (Prof. Bhavana Kanukurthi)
- Prepared homework assignments and assisted students with problem-solving

</div>

</section>

<section id="industry" class="content-section" markdown="1">

## Industry Experience

<div class="experience-block" markdown="1">

### Cognizant Technology Solutions
April 2012 to August 2018 -- *Product Specialist (Technical)*

<div class="project-item">
<h4>Production Support, MPFA Application</h4>
<p>Feb 2016 -- Aug 2018 &middot; Hong Kong &middot; Client: Manulife Hong Kong</p>
<ul>
<li>Provided production support for MPFA (Mandatory Provident Fund Schemes) application in a mission-critical financial environment</li>
<li>Designed and deployed code for business features and change requests; improved system performance through program optimization</li>
<li>Developed automation tooling (Unix shell script-based JCL equivalent) to streamline batch processing</li>
</ul>
</div>

<div class="project-item">
<h4>Platform Migration (Mainframe to AIX)</h4>
<p>Jun 2014 -- Feb 2016 &middot; Kolkata &middot; Client: Manulife Hong Kong</p>
<ul>
<li>Led platform migration from Mainframe to AIX for MPFA system</li>
<li>Coordinated with offshore and on-site teams to ensure minimal downtime</li>
</ul>
</div>

<div class="project-item">
<h4>Platform Migration (Mainframe to Windows Server)</h4>
<p>Apr 2012 -- Jun 2014 &middot; Kolkata &middot; Client: Manulife John Hancock Investments</p>
<ul>
<li>Migrated insurance and annuities platform from Mainframe to Windows Server</li>
<li>Ensured business continuity, data integrity, and regulatory compliance during transition</li>
</ul>
</div>

</div>

</section>

<section id="skills" class="content-section">

<div class="skills-grid">

<div class="skill-category">
<h4>Programming</h4>
<span class="skill-tag">Python</span>
<span class="skill-tag">C++</span>
<span class="skill-tag">Rust</span>
<span class="skill-tag">Go</span>
<span class="skill-tag">Java</span>
<span class="skill-tag">Shell</span>
</div>

<div class="skill-category">
<h4>Research Areas</h4>
<span class="skill-tag">ZK Proofs</span>
<span class="skill-tag">Threshold Crypto</span>
<span class="skill-tag">Blockchain Privacy</span>
<span class="skill-tag">Privacy-Preserving ML</span>
</div>

<div class="skill-category">
<h4>Systems</h4>
<span class="skill-tag">Unix/Linux</span>
<span class="skill-tag">Git</span>
<span class="skill-tag">Oracle</span>
<span class="skill-tag">DB2</span>
</div>

</div>

<div class="highlight-box" markdown="1">

**Recognition (September 2017)** -- Received official commendation from the Senior Systems Manager, Director, and AVP at Manulife for exemplary technical support, problem-solving, and collaboration with IT and business analysis teams.

</div>

</section>
