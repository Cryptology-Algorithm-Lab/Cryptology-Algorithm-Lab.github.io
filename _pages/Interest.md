---
title: "Interest"
layout: splash
classes: wide
author_profile: false
permalink: /Interest/
excerpt: 'Interesting Cryptography!'
header:
  overlay_image: /assets/images/seoul.jpg
  overlay_filter: "rgba(31, 25, 20, 0.55)" # warm-tinted overlay matching the card surfaces
---

<nav class="cna-page-toc" aria-label="Research areas" markdown="0">
  <span class="cna-page-toc-label">Topics</span>
  <a class="cna-page-toc-item" href="#verifiable-computation">Verifiable Computation</a>
  <a class="cna-page-toc-item" href="#secure-ml">Secure ML</a>
  <a class="cna-page-toc-item" href="#blockchain">Blockchain</a>
  <a class="cna-page-toc-item" href="#functional-encryption">Functional Encryption</a>
</nav>

<section class="cna-section cna-cat-people" markdown="0">
  <header class="cna-section-head">
    <h2 id="verifiable-computation">Verifiable Computation</h2>
  </header>

  <div class="cna-prose cna-cat-people">
    <p>In the Wikipedia entry for “Verifiable computing,” verifiable computing (or verified computation / verified computing) enables a computer to offload the computation of some function to other, perhaps untrusted, clients while maintaining verifiable results. The other clients evaluate the function and return the result with a proof that the computation was carried out correctly.</p>
    <p>The introduction of this notion came as a result of the increasingly common phenomenon of outsourcing computation to untrusted users in projects such as <a href="https://en.wikipedia.org/wiki/SETI@home">SETI@home</a>, and of the growing desire of weak clients to outsource computational tasks to a more powerful computation service such as cloud computing.</p>

    <details class="cna-learn-more">
      <summary>What is NIZK?</summary>
      <p><b>Interactive Proofs (IPs) and Arguments.</b> A Prover <i>P</i> and a Verifier <i>V</i> interact as follows: <i>P</i> solves a problem on a given input, tells <i>V</i> the answer, and then proves to <i>V</i> that the answer is correct.</p>
      <p>The proof system must satisfy two properties:</p>
      <ul>
        <li><u>Completeness</u>: If the answer is true, the honest <i>V</i> will be convinced of this fact by an untrusted <i>P</i> (honest <i>P</i> in ZKP).</li>
        <li><u>Soundness</u>: If the answer is false, no <i>P</i> (no cheating <i>P</i> in ZKP) can convince the honest <i>V</i> that it is true, except with some small probability.</li>
      </ul>
      <p>The difference between IPs and arguments is that the prover is restricted to be a polynomial-time algorithm for an interactive argument, whereas no such restriction applies for an interactive proof.</p>
      <p><b>Zero-Knowledge Proof (ZKP) and Non-Interactive Proofs.</b> ZKP is a method by which <i>P</i> can prove to <i>V</i> that they know a secret, without conveying any information apart from the fact that they know the secret. The additional requirement is:</p>
      <ul>
        <li><u>Zero-knowledge</u>: If the answer is true, no <i>V</i> learns anything other than the fact that the answer is true.</li>
      </ul>
      <p>Non-interactive proofs require no interaction between <i>P</i> and <i>V</i>. Therefore, non-interactive zero-knowledge proofs (also known as NIZK, zk-SNARK) are zero-knowledge proofs that require no interaction between the prover and the verifier.</p>
    </details>

    <details class="cna-learn-more">
      <summary>What is PCD?</summary>
      <p><a href="https://projects.csail.mit.edu/pcd/">Proof-Carrying Data (PCD)</a> is a cryptographic primitive applied to distributed computing in a DAG (directed acyclic graph) setting, where multiple subjects without mutual trust generally participate.</p>
      <p>In distributed computing, when a large operation is performed in multiple steps, the subject at each node sends a message including the result of its step to the subject who performs the next step. A proof is attached to the message, attesting to the correctness of the result at both the present node and the previous one.</p>
      <p>PCD can usually be built by recursive proof composition of cryptographic proof systems such as SNARK. In recursive proof composition, in order to generate the proof as mentioned above, the verifier algorithm of the component proof system must be embedded in the arithmetic circuit proved by the system. However, depending on the time complexity of the verifier algorithm, the size of the proof grows larger as the operation proceeds, so verifying the proof can require more computation than performing the operation directly, making verification meaningless. Research on the types of proof systems that can be used as components of recursive proof composition, and on the method of recursive proof composition itself, is ongoing.</p>
    </details>
  </div>
</section>

<section class="cna-section cna-cat-people" markdown="0">
  <header class="cna-section-head">
    <h2 id="secure-ml">Secure Machine Learning (Cryptographic Approach)</h2>
  </header>

  <div class="cna-prose cna-cat-people">
    <p>With the successful development of deep learning, biometric authentication technology based on convolutional neural networks has remarkably advanced. <a href="https://arxiv.org/abs/1801.07698/">ArcFace</a>, based on a <a href="https://arxiv.org/abs/1512.03385">Residual neural network</a>, is the recent state-of-the-art face recognition system and outputs highly discriminative feature templates for face authentication using additive angular margin loss.</p>
    <p>However, when a face recognition system becomes able to compress face images into feature templates more and more compactly, the leakage of face templates becomes a more serious threat to user privacy. For example, face images can be reconstructed from face feature templates using <a href="https://arxiv.org/abs/1703.00832">neighborly de-convolutional neural networks</a>, posing a serious threat to user privacy.</p>
    <p>To address this, we developed a modular architecture, <a href="https://openaccess.thecvf.com/content/CVPR2021/html/Kim_IronMask_Modular_Architecture_for_Protecting_Deep_Face_Template_CVPR_2021_paper.html">IronMask</a>, for protecting face feature templates that can be combined with any face recognition system using an angular distance metric, such as <a href="https://arxiv.org/abs/1704.08063">SphereFace</a>, <a href="https://arxiv.org/abs/1801.09414">CosFace</a>, and <a href="https://arxiv.org/abs/1801.07698">ArcFace</a>.</p>
    <img src="{{ site.url }}{{ site.baseurl }}/assets/images/CVPR.jpg" alt="IronMask architecture overview from CVPR 2021">
  </div>
</section>

<section class="cna-section cna-cat-people" markdown="0">
  <header class="cna-section-head">
    <h2 id="blockchain">Blockchain</h2>
  </header>

  <div class="cna-prose cna-cat-people">
    <p>A number of third-party services require personal data, and users need to delegate personal data to service providers who may modify and share the data with other service providers. For example, patients must share their medical records with hospitals, which can be updated and shared among different departments, hospitals, and even insurance companies. Internet users have to consent to personal data collection to use various services (e.g., location-based services, social media services), and personal data may be updated and shared for use across inter-connected services.</p>
    <p>Additionally, IoT devices in smart home systems exchange data with smart home hubs (e.g., Google Home, Amazon Alexa, Apple HomeKit). Even though such modification and sharing occur with the users’ consent, more transparency for the user is desired throughout the entire procedure.</p>
    <img src="{{ site.url }}{{ site.baseurl }}/assets/images/blockchain.png" alt="Blockchain-based data provenance diagram">
    <p>Personal data are shared by their owners with service providers for different needs, and these data can be modified and further shared among other service providers. For transparency and accountability of such delegated data, a personal data provenance monitoring system that records how owners’ data are propagated and modified is necessary. However, achieving this involves significant challenges, due to the decentralized relationships between different service providers.</p>
    <p>Therefore, we propose using blockchain to track the provenance of owners’ data. For privacy reasons, what service providers can upload to the blockchain is limited to sharing records that do not reveal the data contents, and blockchain peers must validate these records without seeing the actual data. We propose a new extended vector commitment (EVC) scheme for monitoring personal data provenance in third-party services.</p>
  </div>
</section>

<section class="cna-section cna-cat-people" markdown="0">
  <header class="cna-section-head">
    <h2 id="functional-encryption">Functional Encryption</h2>
  </header>

  <div class="cna-prose cna-cat-people">
    <p>Functional Encryption (FE) is a new public key encryption system that extends the existing public-key encryption concept more flexibly. It is a public-key encryption that allows the decryption condition of a ciphertext to be specified as an arbitrary function. Functional Encryption guarantees complete privacy by not exposing unnecessary information related to the ciphertext to system outsiders or even system insiders.</p>
    <p>The purpose of our ongoing research — <i>Research on Functional Encryption Technique Design, Analysis and Implementation Technology</i>, supported by IITP — is to obtain the important source technologies of FE, considered to be next-generation public-key encryption, and to study extended techniques of FE for cloud computing. We also study other cryptographic primitives such as lattices.</p>
  </div>
</section>
