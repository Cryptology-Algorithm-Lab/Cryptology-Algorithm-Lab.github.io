---
title: "Publications"
layout: splash
classes: wide
author_profile: false
permalink: /Publications/
excerpt: 'Stay hungry, Stay foolish.'
header:
  overlay_image: /assets/images/PH.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
---

<style type="text/css">
.cna-pubs-counter{
  display:flex; flex-wrap:wrap; align-items:center; gap:8px;
  margin:8px 0 24px; padding:14px 18px;
  background:#fafaf6; border:1px solid #e6e2d8; border-radius:12px;
  font-size:13.5px;
}
.cna-pubs-counter-label{ font-weight:600; color:#52575f; letter-spacing:.02em; margin-right:6px; }
.cna-pubs-tally{
  font-size:12px; font-weight:600; letter-spacing:.06em;
  padding:4px 10px; border-radius:999px; white-space:nowrap;
  background:#eaf1fa; color:#2b5285;
}

.cna-pubs-year{
  border:1px solid #e6e2d8; border-radius:14px;
  margin:0 0 12px; padding:0;
  background:#fff;
  box-shadow:0 1px 2px rgba(31,34,39,.04);
}
.cna-pubs-year > summary{
  cursor:pointer; user-select:none; list-style:none;
  display:flex; align-items:baseline; justify-content:space-between;
  gap:12px; padding:14px 18px;
  border-radius:14px;
  transition:background .15s ease;
}
.cna-pubs-year > summary::-webkit-details-marker{ display:none; }
.cna-pubs-year > summary:hover{ background:rgba(0,0,0,.025); }
.cna-pubs-year > summary h3{
  margin:0; padding:0; border:none;
  font-size:1.2rem; font-weight:600; color:#1f2227;
}
.cna-pubs-year-count{ font-size:13px; color:#8a909a; }
.cna-pubs-year[open] > summary{ border-bottom:1px solid #f0ecdf; border-radius:14px 14px 0 0; }
.cna-pubs-year > .cna-pubs-list{ padding:8px 18px 14px; }

.cna-pub{
  display:grid;
  grid-template-columns:46px 1fr 200px;
  gap:14px; align-items:start;
  padding:14px 0;
  border-bottom:1px solid #f4f0e2;
}
.cna-pubs-list .cna-pub:last-child{ border-bottom:none; }

.cna-pub-id{
  font-size:11.5px; font-weight:700; letter-spacing:.04em;
  color:#8a909a; padding-top:3px;
}
.cna-pub-main{ min-width:0; }
.cna-pub-authors{ font-size:14.5px; color:#1f2227; line-height:1.5; }
.cna-pub-title{ font-size:14.5px; color:#52575f; line-height:1.5; margin-top:3px; }
.cna-pub-title i{ color:#1f2227; }

.cna-pub-venue{
  display:flex; flex-direction:column; align-items:flex-end; gap:6px;
  font-size:12px;
}
.cna-venue-chip{
  font-size:11px; font-weight:600; letter-spacing:.06em;
  padding:4px 10px; border-radius:999px; white-space:nowrap;
  text-align:center;
}
.cna-venue-chip.cna-red  { background:#fbe7eb; color:#b6102d; }
.cna-venue-chip.cna-blue { background:#eaf1fa; color:#2b5285; }
.cna-pub-venue-detail{ color:#8a909a; font-size:11.5px; text-align:right; }
.cna-pub-venue-detail a{ color:#52575f; }

@media (max-width:760px){
  .cna-pub{ grid-template-columns:36px 1fr; }
  .cna-pub-venue{ grid-column:2; align-items:flex-start; flex-direction:row; flex-wrap:wrap; gap:8px; }
  .cna-pub-venue-detail{ text-align:left; }
}
</style>

<div class="cna-pubs-counter" markdown="0">
  <span class="cna-pubs-counter-label">Highlights</span>
  <span class="cna-pubs-tally">CCS × 2</span>
  <span class="cna-pubs-tally">S&amp;P × 1</span>
  <span class="cna-pubs-tally">NDSS × 1</span>
  <span class="cna-pubs-tally">CVPR × 1</span>
  <span class="cna-pubs-tally">ICCV × 1</span>
  <span class="cna-pubs-tally">ECCV × 1</span>
  <span class="cna-pubs-tally">NeurIPS × 1</span>
  <span class="cna-pubs-tally">CRYPTO × 1</span>
  <span class="cna-pubs-tally">EUROCRYPT × 1</span>
  <span class="cna-pubs-tally">ASIACRYPT × 2</span>
  <span class="cna-pubs-tally">J. Cryptology × 1</span>
</div>

## Journal

<details class="cna-pubs-year" open markdown="0">
  <summary><h3>2026</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J34</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Minsu Kim&dagger;</b>, <b>Seunghun Paik&dagger;</b>, <b>Seongae Baek</b>, <b>Sangyoon Shin</b>, <b>Sunpill Kim</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>SilverMask: Face Template Protection with Fine-Grained Noise Correction</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE Access</span>
      <span class="cna-pub-venue-detail">TBA</span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J33</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Hyeonbum Lee</b>, <b>Seunghun Paik</b>, <b>Hyunjung Son</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Cougar: Cubic Root Verifier Inner Product Argument under Discrete Logarithm Assumption</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE Access</span>
      <span class="cna-pub-venue-detail">TBA</span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2025</h3><span class="cna-pubs-year-count">4 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J32</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Hyunjung Son</b>, <b>Seunghun Paik</b>, <b>Yunki Kim</b>, <b>Sunpill Kim</b>, Heewon Chung, <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Doubly Efficient Fuzzy Private Set Intersection for High-dimensional Data with Cosine Similarity</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE Access</span>
      <span class="cna-pub-venue-detail"><a href="https://ieeexplore.ieee.org/abstract/document/11316118">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J31</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Seunghun Paik</b>, <b>Dongsoo Kim</b>, <b>Chanwoo Hwang</b>, <b>Sunpill Kim</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Towards Certifiably Robust Face Recognition: Analyses and Improvements</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE TBIOM</span>
      <span class="cna-pub-venue-detail"><a href="https://doi.org/10.1109/TBIOM.2025.3644396">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J30</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Seunghun Paik</b>, <b>Chanwoo Hwang</b>, <b>Sunpill Kim</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>On the Reversibility of Locality-Sensitive Hashing-based Biometric Template Protections</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE TDSC</span>
      <span class="cna-pub-venue-detail"><a href="https://ieeexplore.ieee.org/document/11269699">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J29</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Sunpill Kim</b>, Hoyong Shin and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Deep Face Template Protection in the Wild</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Pattern Recognition</span>
      <span class="cna-pub-venue-detail">Apr 2025 · <a href="https://doi.org/10.1016/j.patcog.2024.111336">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2024</h3><span class="cna-pubs-year-count">1 paper</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J28</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Changhao Chenli, Wenyi Tang, <b>Hyeonbum Lee</b>, and Taeho Jung</div>
      <div class="cna-pub-title"><i>Fair2Trade: Digital Trading Platform Ensuring Exchange and Distribution Fairness</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE TDSC</span>
      <span class="cna-pub-venue-detail">Feb 2024 · <a href="https://ieeexplore.ieee.org/document/10420492">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2023</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J27</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Sungwook Kim, <b>Hyeonbum Lee</b>, <b>Gwangwoon Lee</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Leopard: Sublinear Verifier Inner Product Argument under Discrete Logarithm Assumption.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE TIFS</span>
      <span class="cna-pub-venue-detail">Aug 2023 · <a href="https://ieeexplore.ieee.org/document/10198341">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J26</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Hyung Tae Lee and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>On the Security of Functional Encryption in the Generic Group Model.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Designs, Codes &amp; Crypto.</span>
      <span class="cna-pub-venue-detail">May 2023 · <a href="https://doi.org/10.1007/s10623-023-01237-1">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2022</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J25</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Bora Jeong</b>, <b>Sunpill Kim</b>, <b>Seunghun Paik</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Analysis on Secure Triplet Loss.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE Access</span>
      <span class="cna-pub-venue-detail">Nov 2022 · <a href="https://ieeexplore.ieee.org/document/9965373">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J24</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Heewon Chung</b>, Kyoohyung Han, Chanyang Ju, Myungsun Kim, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Bulletproofs+: Shorter Proofs for a Privacy-Enhanced Distributed Ledger.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE Access</span>
      <span class="cna-pub-venue-detail">Apr 2022 · <a href="https://ieeexplore.ieee.org/document/9758733">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2021</h3><span class="cna-pubs-year-count">3 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J23</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Chanyang Ju, <b>Hyeonbum Lee</b>, <b>Heewon Chung</b>, <b>Jae Hong Seo</b>, and Sungwook Kim*</div>
      <div class="cna-pub-title"><i>Efficient Sum-Check Protocol for Convolution.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE Access</span>
      <span class="cna-pub-venue-detail">Dec 2021 · <a href="https://ieeexplore.ieee.org/document/9638642">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J22</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Chanyang Ju, <b>Hyeonbum Lee</b>, <b>Heewon Chung</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Analysis of Zero-Knowledge Protocols for Verifiable Computation and Its Applications (연산을 검증하기 위한 영지식 증명 프로토콜의 기법 및 응용 사례 분석).</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">KIISC 정보보호학회논문지</span>
      <span class="cna-pub-venue-detail">2021 · <a href="https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE10596717">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J21</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Keita Emura, <b>Jae Hong Seo</b>, and Yohei Watanabe*</div>
      <div class="cna-pub-title"><i>Efficient revocable identity-based encryption with short public parameters.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Theor. Computer Science</span>
      <span class="cna-pub-venue-detail">Apr 2021 · <a href="https://www.sciencedirect.com/science/article/pii/S0304397521001134">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2020</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J20</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Hyung Tae Lee, San Ling, <b>Jae Hong Seo*</b>, Huaxiong Wang, and Taek-Young Youn</div>
      <div class="cna-pub-title"><i>Public key encryption with equality test in the standard model.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Information Sciences</span>
      <span class="cna-pub-venue-detail">Mar 2020 · <a href="https://www.sciencedirect.com/science/article/pii/S0020025516322290">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J19</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b></div>
      <div class="cna-pub-title"><i>Efficient Digital Signatures from RSA without Random Oracles</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Information Sciences</span>
      <span class="cna-pub-venue-detail">Mar 2020 · <a href="https://www.sciencedirect.com/science/article/pii/S0020025519309478?via%3Dihub">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2019</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J18</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Hyung Tae Lee, San Ling, <b>Jae Hong Seo*</b>, and Huaxiong Wang; [alphabetical order]</div>
      <div class="cna-pub-title"><i>Public Key Encryption with Equality Test from Generic Assumptions in the Random Oracle Model</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Information Sciences</span>
      <span class="cna-pub-venue-detail">2019 · <a href="https://www.sciencedirect.com/science/article/pii/S002002551930430X?via%3Dihub">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J17</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Sungwook Kim, Jinsu Kim, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>A New Approach for Practical Function-Private Inner Product Encryption.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Theor. Computer Science</span>
      <span class="cna-pub-venue-detail">Sep 2019 · <a href="https://www.sciencedirect.com/science/article/pii/S0304397519301690?via%3Dihub">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2018</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J16</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b>, Keita Emura, Keita Xagawa, and Kazuki Yoneyama</div>
      <div class="cna-pub-title"><i>Accumulable Optimistic Fair Exchange from Verifiably Encrypted Homomorphic Signatures.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Int. J. Info. Security</span>
      <span class="cna-pub-venue-detail">2018 · <a href="https://link.springer.com/article/10.1007/s10207-017-0367-z">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J15</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Jinsu Kim, Sungwook Kim, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>A new Scale-Invariant Homomorphic Encryption Scheme.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Information Sciences</span>
      <span class="cna-pub-venue-detail">2018 · <a href="https://www.sciencedirect.com/science/article/pii/S0020025517309313">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2017</h3><span class="cna-pubs-year-count">1 paper</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J14</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b></div>
      <div class="cna-pub-title"><i>Short Signatures from Diffie–Hellman: Realizing Almost Compact Public Key</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">J. Cryptology</span>
      <span class="cna-pub-venue-detail">Jul 2017 · <a href="https://link.springer.com/article/10.1007/s00145-016-9234-8">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2016</h3><span class="cna-pubs-year-count">4 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J13</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Hyung Tae Lee, San Ling, <b>Jae Hong Seo*</b>, and Huaxiong Wang; [alphabetical order]</div>
      <div class="cna-pub-title"><i>Semi-Generic Construction of Public Key Encryption and Identity-Based Encryption with Equality Test</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Information Sciences</span>
      <span class="cna-pub-venue-detail">2016 · <a href="https://www.sciencedirect.com/science/article/pii/S0020025516307654">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J12</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Hyung Tae Lee, San Ling, <b>Jae Hong Seo*</b> and Huaxiong Wang</div>
      <div class="cna-pub-title"><i>CCA2 attack and modification of Huang et al.'s public key encryption with authorized equality test</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">The Computer Journal</span>
      <span class="cna-pub-venue-detail">2016 · <a href="https://ieeexplore.ieee.org/document/8130169">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J11</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>Revocable hierarchical identity-based encryption via history-free approach</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Theor. Computer Science</span>
      <span class="cna-pub-venue-detail">2016 · <a href="https://www.sciencedirect.com/science/article/pii/S0304397515011354">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J10</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Keita Emura, <b>Jae Hong Seo*</b>, and Taek-Young Youn; [alphabetical order]</div>
      <div class="cna-pub-title"><i>Semi-generic Transformation of Revocable Hierarchical Identity-Based Encryption and its DBDH Instantiation</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEICE Trans. Fundamentals</span>
      <span class="cna-pub-venue-detail">Jan 2016 · <a href="https://dblp.org/rec/journals/ieicet/EmuraSY16.html">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2014</h3><span class="cna-pubs-year-count">3 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J9</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>Revocable Identity-Based Encryption with Rejoin Functionality</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEICE Trans. Fundamentals</span>
      <span class="cna-pub-venue-detail">Aug 2014 · <a href="https://search.ieice.org/bin/summary.php?id=e97-a_8_1806&category=A&year=2014&lang=E&abst=">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J8</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>Revocable Identity-Based Cryptosystem Revisited: Security Models and Constructions</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEEE TIFS</span>
      <span class="cna-pub-venue-detail">2014 · <a href="https://ieeexplore.ieee.org/document/6824197?arnumber=6824197">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J7</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>Revocable Hierarchical Identity-Based Encryption</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">Theor. Computer Science</span>
      <span class="cna-pub-venue-detail">2014 · <a href="https://www.sciencedirect.com/science/article/pii/S0304397514003363?via%3Dihub">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2013</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J6</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>A Remark on "Efficient Revocable ID-Based Encryption with a Public Channel"</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEICE Trans. Fundamentals</span>
      <span class="cna-pub-venue-detail">Nov 2013 · <a href="https://www.jstage.jst.go.jp/article/transfun/E96.A/11/E96.A_2282/_article">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J5</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>On Discrete Logarithm based Additively Homomorphic Encryption</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEICE Trans. Fundamentals</span>
      <span class="cna-pub-venue-detail">Nov 2013 · <a href="https://search.ieice.org/bin/summary.php?id=e96-a_11_2286&category=A&year=2013&lang=E&abst=">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2012</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J4</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Jung Hee Cheon, Stanislaw Jarecki, and <b>Jae Hong Seo*</b>; [alphabetical order]</div>
      <div class="cna-pub-title"><i>Multi-Party Privacy-Preserving Set Intersection with Quasi-linear Complexity</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEICE Trans. Fundamentals</span>
      <span class="cna-pub-venue-detail">Aug 2012 · <a href="https://search.ieice.org/bin/summary.php?id=e95-a_8_1366&category=A&year=2012&lang=E&abst=">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">J3</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b></div>
      <div class="cna-pub-title"><i>Short Round Sub-linear Zero-Knowledge Argument for Linear Algebraic Relations</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEICE Trans. Fundamentals</span>
      <span class="cna-pub-venue-detail">Apr 2012 · <a href="https://search.ieice.org/bin/summary.php?id=e95-a_4_776&category=A&year=2012&lang=E&abst=">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2011</h3><span class="cna-pubs-year-count">1 paper</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J2</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b>, Tetsutaro Kobayashi, Miyako Ohkubo, and Koutarou Suzuki</div>
      <div class="cna-pub-title"><i>Anonymous Hierarchical Identity-Based Encryption with Short Ciphertexts</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">IEICE Trans. Fundamentals</span>
      <span class="cna-pub-venue-detail">Jan 2011 · <a href="https://search.ieice.org/bin/summary.php?id=e94-a_1_45&category=A&year=2011&lang=E&abst=">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2009</h3><span class="cna-pubs-year-count">1 paper</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">J1</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b>, HyoJin Yoon, Seongan Lim, Jung Hee Cheon, and Dowon Hong</div>
      <div class="cna-pub-title"><i>Analysis of Privacy-Preserving Element Reduction of a Multiset</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-red">J. Korean Math. Soc.</span>
      <span class="cna-pub-venue-detail">2009 · <a href="http://koreascience.or.kr/article/JAKO200907841290235.page">DOI</a></span>
    </div>
  </article>

  </div>
</details>

## Conference

<details class="cna-pubs-year" open markdown="0">
  <summary><h3>2026</h3><span class="cna-pubs-year-count">3 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C31</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Seunghun Paik&dagger;</b>, <b>Sunpill Kim&dagger;</b>, <b>Chanwoo Hwang</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Casting the Net! Revisiting MasterFace Impersonation Attacks</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ACM CCS</span>
      <span class="cna-pub-venue-detail">2026 · TBA</span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C30</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Seunghun Paik</b>, Nirajan Koirala, Jack Nero, <b>Hyunjung Son</b>, <b>Yunki Kim</b>, <b>Jae Hong Seo*</b>, and Taeho Jung*</div>
      <div class="cna-pub-title"><i>Scalable Private Set Intersection over Distributed Encrypted Data</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ASIACCS</span>
      <span class="cna-pub-venue-detail">2026 · TBA</span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C29</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Nirajan Koirala, <b>Seunghun Paik</b>, Sam Martin, Helena Berens, Tasha Januszewicz, Jonathan Takeshita, <b>Jae Hong Seo</b>, Taeho Jung</div>
      <div class="cna-pub-title"><i>Select-Then-Compute: Encrypted Label Selection and Analytics over Distributed Datasets using FHE</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">NDSS</span>
      <span class="cna-pub-venue-detail">2026 · TBA</span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2025</h3><span class="cna-pubs-year-count">5 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C28</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Sunpill Kim</b>, <b>Seunghun Paik</b>, <b>Chanwoo Hwang</b>, <b>Minsu Kim</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Non-Adaptive Adversarial Face Generation</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">NeurIPS</span>
      <span class="cna-pub-venue-detail">2025 · TBA</span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C27</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Changjin Kim</b>, <b>Chanwoo Hwang</b>, <b>Sunpill Kim</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>A Survey of Model Inversion Attacks on Image Domain</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ICTC</span>
      <span class="cna-pub-venue-detail">2025 · <a href="https://ieeexplore.ieee.org/abstract/document/11388195">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C26</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Yunki Kim</b>, <b>Hyunjung Son</b>, <b>Seunghun Paik</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>A Survey on Fuzzy Private Set Intersection Protocols</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ICTC</span>
      <span class="cna-pub-venue-detail">2025 · <a href="https://ieeexplore.ieee.org/abstract/document/11388448">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C25</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Sunpill Kim&dagger;</b>, <b>Seunghun Paik&dagger;</b>, <b>Chanwoo Hwang</b>, <b>Dongsoo Kim</b>, Junbum Shin, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>IDFace: Face Template Protection for Secure and Efficient Identification</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ICCV</span>
      <span class="cna-pub-venue-detail">2025 · <a href="https://openaccess.thecvf.com/content/ICCV2025/html/Kim_IDFace_Face_Template_Protection_for_Efficient_and_Secure_Identification_ICCV_2025_paper.html">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C24</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Jaehwan Park&dagger;, <b>Hyeonbum Lee&dagger;</b>, Junbeom Hur, <b>Jae Hong Seo*</b> and Doowon Kim*</div>
      <div class="cna-pub-title"><i>UTRA: Universal Token Reusability Attack and Token Unforgeable Delegatable Order-Revealing Encryption</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ESORICS</span>
      <span class="cna-pub-venue-detail">2025 · <a href="https://link.springer.com/chapter/10.1007/978-3-032-07891-9_17">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2024</h3><span class="cna-pubs-year-count">4 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C23</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Seunghun Paik</b>, <b>Dongsoo Kim</b>, <b>Chanwoo Hwang</b>, <b>Sunpill Kim</b> and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Towards Certifiably Robust Face Recognition</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ECCV</span>
      <span class="cna-pub-venue-detail">2024 · <a href="https://doi.org/10.1007/978-3-031-73013-9_9">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C22</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Seunghun Paik</b>, <b>Dongsoo Kim</b>, <b>Chanwoo Hwang</b>, <b>Sunpill Kim</b> and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>On the Certifiable Robustness of Face Recognition Systems</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">CISC-S</span>
      <span class="cna-pub-venue-detail">2024</span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C21</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Hyeonbum Lee</b>, <b>Kyuhwan Lee</b>, Wenyi Tang, Shankha Shubhra Mukherjee, <b>Jae Hong Seo</b>, and Taeho Jung</div>
      <div class="cna-pub-title"><i>PrivHChain: Monitoring the Supply Chain of Controlled Substances with Privacy-Preserving Hierarchical Blockchain</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IEEE ICBC</span>
      <span class="cna-pub-venue-detail">2024 · <a href="https://ieeexplore.ieee.org/document/10634378">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C20</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Sunpill Kim</b>, Yong Kiam Tan, <b>Bora Jeong</b>, Soumik Mondal, Khin Mi Mi Aung, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Scores Tell Everything about Bob: Non-adaptive Face Reconstruction on Face Recognition Systems</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IEEE S&amp;P</span>
      <span class="cna-pub-venue-detail">2024 · <a href="https://www.computer.org/csdl/proceedings-article/sp/2024/313000a161/1Ub24A2RzHi">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2023</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C19</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Seunghun Paik</b>, <b>Sunpill Kim</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Security Analysis on Locality-Sensitive Hashing-Based Biometric Template Protection Schemes.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">BMVC (Oral)</span>
      <span class="cna-pub-venue-detail">2023 · <a href="https://papers.bmvc2023.org/0535.pdf">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C18</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Hyeonbum Lee</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>TENET : Sublogarithmic Proof and Sublinear Verifier Inner Product Argument without a Trusted Setup.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IWSEC</span>
      <span class="cna-pub-venue-detail">2023 · <a href="https://link.springer.com/chapter/10.1007/978-3-031-41326-1_12">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2022</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C17</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Sungwook Kim, <b>Hyeonbum Lee</b>, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>Efficient Zero-Knowledge Arguments in Discrete Logarithm Setting: Sublogarithmic Proof or Sublinear Verifier</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-ASIACRYPT</span>
      <span class="cna-pub-venue-detail">2022 · <a href="https://link.springer.com/chapter/10.1007/978-3-031-22966-4_14">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C16</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Chanyang Ju, Wenyi Tang, Changhao Chenli, <b>Gwangwoon Lee</b>, <b>Jae Hong Seo</b>, and Taeho Jung</div>
      <div class="cna-pub-title"><i>Monitoring Provenance of Delegated Personal Data With Blockchain.</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IEEE Blockchain</span>
      <span class="cna-pub-venue-detail">2022 · acc. 15.3% · <a href="https://ieeexplore.ieee.org/document/9881821">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2021</h3><span class="cna-pubs-year-count">1 paper</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C15</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Sunpill Kim</b>, Yunseong Jeong, Jinsu Kim, Jungkon Kim, Hyung Tae Lee, and <b>Jae Hong Seo*</b></div>
      <div class="cna-pub-title"><i>IronMask: Modular Architecture for Protecting Deep Face Template</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">CVPR</span>
      <span class="cna-pub-venue-detail">2021 · acc. 23.7% · <a href="https://openaccess.thecvf.com/content/CVPR2021/html/Kim_IronMask_Modular_Architecture_for_Protecting_Deep_Face_Template_CVPR_2021_paper.html">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2017</h3><span class="cna-pubs-year-count">1 paper</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C14</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Yohei Watanabe, Keita Emura, and <b>Jae Hong Seo</b></div>
      <div class="cna-pub-title"><i>New Revocable IBE in Prime-Order Groups: Adaptively Secure, Decryption Key Exposure Resistant, and with Short Public Parameters</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">CT-RSA</span>
      <span class="cna-pub-venue-detail">2017 · <a href="https://link.springer.com/chapter/10.1007%2F978-3-319-52153-4_25">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2015</h3><span class="cna-pubs-year-count">3 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C13</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>Adaptive-ID Secure Revocable Hierarchical Identity-Based Encryption</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IWSEC</span>
      <span class="cna-pub-venue-detail">2015 · <a href="https://link.springer.com/chapter/10.1007%2F978-3-319-22425-1_2">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C12</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b>, Keita Emura, Keita Xagawa, and Kazuki Yoneyama</div>
      <div class="cna-pub-title"><i>Accumulable Optimistic Fair Exchange from Verifiably Encrypted Homomorphic Signatures</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ACNS</span>
      <span class="cna-pub-venue-detail">2015 · <a href="https://link.springer.com/chapter/10.1007%2F978-3-319-28166-7_10">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C11</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>Revocable Hierarchical Identity-Based Encryption: History-Free Update, Security Against Insiders, and Short Ciphertexts</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">CT-RSA</span>
      <span class="cna-pub-venue-detail">2015 · acc. 23.4% · <a href="https://link.springer.com/chapter/10.1007%2F978-3-319-16715-2_6">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2014</h3><span class="cna-pubs-year-count">2 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C10</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Jung Hee Cheon, Hyung Tae Lee, and <b>Jae Hong Seo</b>; [alphabetical order]</div>
      <div class="cna-pub-title"><i>A New Additive Homomorphic Encryption based on the co-ACD Problem</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">ACM CCS</span>
      <span class="cna-pub-venue-detail">2014 · acc. 19.5% · <a href="https://dl.acm.org/doi/10.1145/2660267.2660335">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C9</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Hyung Tae Lee and <b>Jae Hong Seo*</b>; [alphabetical order]</div>
      <div class="cna-pub-title"><i>Security Analysis of Multilinear Maps over the Integers</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-CRYPTO</span>
      <span class="cna-pub-venue-detail">2014 · acc. 26% · <a href="https://link.springer.com/chapter/10.1007%2F978-3-662-44371-2_13">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2013</h3><span class="cna-pubs-year-count">3 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C8</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors">Florian Böhl, Dennis Hofheinz, Tibor Jager, Jessica Koch, <b>Jae Hong Seo</b>, and Christoph Striecks; [alphabetical order]</div>
      <div class="cna-pub-title"><i>Practical Signatures from Standard Assumptions</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-EUROCRYPT</span>
      <span class="cna-pub-venue-detail">2013 · acc. 20% · <a href="https://link.springer.com/chapter/10.1007/978-3-642-38348-9_28">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C7</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>Revocable Identity-Based Encryption, Revisited: Security Definition and Construction</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-PKC</span>
      <span class="cna-pub-venue-detail">2013 · acc. 28% · <a href="https://eprint.iacr.org/2013/016">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C6</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Keita Emura</div>
      <div class="cna-pub-title"><i>Efficient Delegation of Key Generation and Revocation Functionalities in Identity-Based Encryption</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">CT-RSA</span>
      <span class="cna-pub-venue-detail">2013 · acc. 28% · <a href="https://eprint.iacr.org/2013/018">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2012</h3><span class="cna-pubs-year-count">3 papers</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C5</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b></div>
      <div class="cna-pub-title"><i>On the (Im)possibility of Projecting Property in Prime-Order Setting</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-ASIACRYPT</span>
      <span class="cna-pub-venue-detail">2012 · acc. 17% · <a href="https://eprint.iacr.org/2013/186">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C4</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b>, Jung Hee Cheon, and Jonathan Katz</div>
      <div class="cna-pub-title"><i>Constant-Round Multi-Party Private Set Union using Reversed Laurent Series</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-PKC</span>
      <span class="cna-pub-venue-detail">2012 · acc. 22% · <a href="https://link.springer.com/chapter/10.1007/978-3-642-30057-8_24">DOI</a></span>
    </div>
  </article>

  <article class="cna-pub">
    <span class="cna-pub-id">C3</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b> and Jung Hee Cheon</div>
      <div class="cna-pub-title"><i>Beyond the Limitation of Prime-Order Bilinear Groups, and Round Optimal Blind Signatures</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-TCC</span>
      <span class="cna-pub-venue-detail">2012 · acc. 27% · <a href="https://eprint.iacr.org/2012/198">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2011</h3><span class="cna-pubs-year-count">1 paper</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C2</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b></div>
      <div class="cna-pub-title"><i>Round-Efficient Sub-linear Zero-Knowledge Arguments for Linear Algebra</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-PKC</span>
      <span class="cna-pub-venue-detail">2011 · acc. 27% · <a href="https://link.springer.com/chapter/10.1007/978-3-642-19379-8_24">DOI</a></span>
    </div>
  </article>

  </div>
</details>

<details class="cna-pubs-year" markdown="0">
  <summary><h3>2009</h3><span class="cna-pubs-year-count">1 paper</span></summary>
  <div class="cna-pubs-list">

  <article class="cna-pub">
    <span class="cna-pub-id">C1</span>
    <div class="cna-pub-main">
      <div class="cna-pub-authors"><b>Jae Hong Seo</b>, Tetsutaro Kobayashi, Miyako Ohkubo, and Koutarou Suzuki</div>
      <div class="cna-pub-title"><i>Anonymous Hierarchical Identity-Based Encryption with Constant Size Ciphertexts</i></div>
    </div>
    <div class="cna-pub-venue">
      <span class="cna-venue-chip cna-blue">IACR-PKC</span>
      <span class="cna-pub-venue-detail">2009 · acc. 25% · <a href="https://link.springer.com/chapter/10.1007/978-3-642-00468-1_13">DOI</a></span>
    </div>
  </article>

  </div>
</details>

The corresponding author is marked with *.
The equal contribution is marked with &dagger;.
