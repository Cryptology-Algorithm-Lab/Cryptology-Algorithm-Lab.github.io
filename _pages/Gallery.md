---
title: "Gallery"
layout: archive
classes: wide
author_profile: false
sidebar:
  nav: "docs"
permalink: /News/Gallery/
header:
  overlay_image: /assets/images/korea.jpg
  overlay_filter: "rgba(31, 25, 20, 0.55)" # warm-tinted overlay matching the card surfaces
# ──────────────────────────────────────────────────────────────────────
# Adding an event to this page
#
# 1. Put the photos in assets/Gallery/. Keep the extension honest: a
#    .jfif from Windows is a JPEG, and GitHub Pages will not necessarily
#    serve it with an image MIME type — rename it to .jpg.
#
# 2. Add a galleryN: block here (N = next free number), a matching
#    <section> in the body below, and bump that year's "<n> events".
#
# 3. Every photo needs `ratio:` (width / height). Do not type it by
#    hand and do not guess it — the layout is chosen from these numbers
#    and a wrong one quietly picks the wrong pattern. Generate them:
#
#        node .site-check/shapes.mjs <repo> --write
#
#    (that tooling lives outside the repo; it rewrites this file in
#    place and is safe to re-run.)
#
# 4. The block's layout follows the photos, so you do not choose it:
#
#        1 photo                      shown whole, never cropped
#        2 photos, none/both portrait 2 up, cells near their own ratio
#        2 photos, one portrait       2x2 lead + the portrait beside it
#        4 photos, no portrait        2 x 2, cells near their own ratio
#        anything else                2x2 lead + tall + wide + squares
#
#    In the last two the slots are filled by SHAPE: a portrait photo
#    takes the tall slot, a landscape one the wide slot. So you do not
#    have to order the list around the grid — order it so the photo you
#    want to lead comes first among the non-portrait ones.
#
# 5. Thumbnails crop from 50% 40%, which suits faces and projected
#    screens. When one still cuts badly, add focus: "50% 20%" to that
#    entry — do not re-crop the file, the lightbox shows it uncropped.
#
# 6. alt is also the lightbox caption. Write it for a reader.
#
# 7. eager=true belongs on the TOPMOST gallery include only — it is the
#    page's largest-contentful-paint image. Move it when a newer event
#    goes in above the current one.
# ──────────────────────────────────────────────────────────────────────
gallery:
  - url: /assets/Gallery/asiacrypt_hyeonbum.png
    image_path: /assets/Gallery/asiacrypt_hyeonbum.png
    ratio: 2.11
    alt: "ASIACRYPT 2022 — Hyeonbum Lee presentation"
  - url: /assets/Gallery/asiacrypt_hyeonbum_1.png
    image_path: /assets/Gallery/asiacrypt_hyeonbum_1.png
    ratio: 2.11
    alt: "ASIACRYPT 2022 — Hyeonbum Lee presentation"
gallery1:
  - url: /assets/Gallery/grad_bs_bora.png
    image_path: /assets/Gallery/grad_bs_bora.png
    ratio: 2.11
    alt: "Bora Jeong graduation"
gallery2:
  - url: /assets/Gallery/banner_cna.png
    image_path: /assets/Gallery/banner_cna.png
    ratio: 1.33
    alt: "C&A Lab banner"
  - url: /assets/Gallery/cryptoanalysis_paik.jpg
    image_path: /assets/Gallery/cryptoanalysis_paik.jpg
    ratio: 1.36
    alt: "Cryptanalysis"
  - url: /assets/Gallery/h1.jpeg
    image_path: /assets/Gallery/h1.jpeg
    ratio: 1.33
    alt: "Achievement"
  - url: /assets/Gallery/h2.jpeg
    image_path: /assets/Gallery/h2.jpeg
    ratio: 1.50
    alt: "Achievement"
gallery3:
  - url: /assets/Gallery/teachersday23_1.png
    image_path: /assets/Gallery/teachersday23_1.png
    ratio: 1.33
    alt: "Teacher's Day 2023"
  - url: /assets/Gallery/teachersday23_2.png
    image_path: /assets/Gallery/teachersday23_2.png
    ratio: 1.00
    alt: "Teacher's Day 2023"
gallery4:
  - url: /assets/Gallery/23_10_1.jpg
    image_path: /assets/Gallery/23_10_1.jpg
    ratio: 1.78
    alt: "Cryptographic Contests 2023"
  - url: /assets/Gallery/23_10_2.jpg
    image_path: /assets/Gallery/23_10_2.jpg
    ratio: 1.78
    alt: "Cryptographic Contests 2023"
  - url: /assets/Gallery/23_10_3.jpg
    image_path: /assets/Gallery/23_10_3.jpg
    ratio: 1.33
    alt: "Cryptographic Contests 2023"
  - url: /assets/Gallery/23_10_4.jpg
    image_path: /assets/Gallery/23_10_4.jpg
    ratio: 1.33
    alt: "Cryptographic Contests 2023"
gallery5:
  - url: /assets/Gallery/bmvc1.jpg
    image_path: /assets/Gallery/bmvc1.jpg
    ratio: 1.33
    alt: "BMVC 2023"
  - url: /assets/Gallery/bmvc2.jpg
    image_path: /assets/Gallery/bmvc2.jpg
    ratio: 1.50
    alt: "BMVC 2023"
gallery6:
  - url: /assets/Gallery/sp1.jpeg
    image_path: /assets/Gallery/sp1.jpeg
    ratio: 2.11
    alt: "IEEE S&P 2024"
  - url: /assets/Gallery/sp2.jpeg
    image_path: /assets/Gallery/sp2.jpeg
    ratio: 2.16
    alt: "IEEE S&P 2024"
gallery7:
  - url: /assets/Gallery/hb_1.JPG
    image_path: /assets/Gallery/hb_1.JPG
    ratio: 1.06
    alt: "ZKProof6 & ICBC 2024"
  - url: /assets/Gallery/hb_2.jpg
    image_path: /assets/Gallery/hb_2.jpg
    ratio: 1.50
    alt: "ZKProof6 & ICBC 2024"
gallery8:
  - url: /assets/Gallery/workshop'24.JPEG
    image_path: /assets/Gallery/workshop'24.JPEG
    ratio: 1.33
    alt: "MPC & SNARK Workshop 2024"
  - url: /assets/Gallery/workshop'24_1.jpg
    image_path: /assets/Gallery/workshop'24_1.jpg
    ratio: 1.33
    alt: "MPC & SNARK Workshop 2024"
gallery9:
  - url: /assets/Gallery/cryptanalysis_2024.jpg
    image_path: /assets/Gallery/cryptanalysis_2024.jpg
    ratio: 1.33
    alt: "Cryptanalysis Contest 2024"
  - url: /assets/Gallery/cryptanalysis_2024_1.jpg
    image_path: /assets/Gallery/cryptanalysis_2024_1.jpg
    ratio: 1.33
    alt: "Cryptanalysis Contest 2024"
gallery10:
  - url: /assets/Gallery/nation24_1.png
    image_path: /assets/Gallery/nation24_1.png
    ratio: 1.00
    alt: "Cryptographic Technology Contest 2024"
  - url: /assets/Gallery/nation24_2.jpeg
    image_path: /assets/Gallery/nation24_2.jpeg
    ratio: 1.00
    alt: "Cryptographic Technology Contest 2024"
gallery11:
  - url: /assets/Gallery/hb_cel1.jpg
    image_path: /assets/Gallery/hb_cel1.jpg
    ratio: 0.75
    alt: "Hyeonbum Lee graduation"
  - url: /assets/Gallery/hb_cel2.jpg
    image_path: /assets/Gallery/hb_cel2.jpg
    ratio: 0.75
    alt: "Hyeonbum Lee graduation"
gallery12:
  - url: /assets/Gallery/kccv25_1.jpg
    image_path: /assets/Gallery/kccv25_1.jpg
    ratio: 1.33
    alt: "KCCV 2025"
  - url: /assets/Gallery/kccv25_2.jpg
    image_path: /assets/Gallery/kccv25_2.jpg
    ratio: 1.33
    alt: "KCCV 2025"
  - url: /assets/Gallery/kccv25_3.jpg
    image_path: /assets/Gallery/kccv25_3.jpg
    ratio: 0.75
    alt: "KCCV 2025"
  - url: /assets/Gallery/kccv25_4.jpg
    image_path: /assets/Gallery/kccv25_4.jpg
    ratio: 0.75
    alt: "KCCV 2025"
gallery13:
  - url: /assets/Gallery/contest25.jpeg
    image_path: /assets/Gallery/contest25.jpeg
    ratio: 0.75
    alt: "Cryptographic Technology Contest 2025"
  - url: /assets/Gallery/contest25_2.jpeg
    image_path: /assets/Gallery/contest25_2.jpeg
    ratio: 1.33
    alt: "Cryptographic Technology Contest 2025"
gallery14:
  - url: /assets/Gallery/mathday1_sh.jpeg
    image_path: /assets/Gallery/mathday1_sh.jpeg
    ratio: 0.47
    alt: "Day of Mathematics 2025"
  - url: /assets/Gallery/mathday2_sh.jpeg
    image_path: /assets/Gallery/mathday2_sh.jpeg
    ratio: 1.33
    alt: "Day of Mathematics 2025"
gallery15:
  - url: /assets/Gallery/SP_grad1.jpeg
    image_path: /assets/Gallery/SP_grad1.jpeg
    ratio: 1.33
    alt: "Sunpill Kim graduation"
  - url: /assets/Gallery/SP_grad2.jpeg
    image_path: /assets/Gallery/SP_grad2.jpeg
    ratio: 1.33
    alt: "Sunpill Kim graduation"
gallery16:
  - url: /assets/Gallery/math1.jpeg
    image_path: /assets/Gallery/math1.jpeg
    ratio: 1.33
    alt: "MATH Workshop"
  - url: /assets/Gallery/math2.jpeg
    image_path: /assets/Gallery/math2.jpeg
    ratio: 1.33
    alt: "MATH Workshop"
gallery17:
  - url: /assets/Gallery/best_paper_2603.png
    image_path: /assets/Gallery/best_paper_2603.png
    ratio: 1.05
    alt: "Outstanding Paper, Hanyang University"
  - url: /assets/Gallery/best_paper_2603_1.jpeg
    image_path: /assets/Gallery/best_paper_2603_1.jpeg
    ratio: 1.33
    alt: "Outstanding Paper, Hanyang University"
gallery18:
  - url: /assets/Gallery/ccs2026_2.jpg
    image_path: /assets/Gallery/ccs2026_2.jpg
    ratio: 2.11
    alt: "Casting the Net! Revisiting MasterFace Impersonation Attacks — ML Attacks session, ACM CCS 2026"
  - url: /assets/Gallery/ccs2026_4.jpg
    image_path: /assets/Gallery/ccs2026_4.jpg
    ratio: 0.47
    alt: "Seunghun Paik at ACM CCS 2026"
  - url: /assets/Gallery/ccs2026_1.jpg
    image_path: /assets/Gallery/ccs2026_1.jpg
    ratio: 2.11
    alt: "ACM CCS 2026 opening"
  - url: /assets/Gallery/ccs2026_3.jpg
    image_path: /assets/Gallery/ccs2026_3.jpg
    ratio: 0.47
    focus: "50% 55%"
    alt: "Seunghun Paik presenting at ACM CCS 2026"
---

<details class="cna-year" open markdown="0">
  <summary>
    <h3>2026</h3>
    <span class="cna-year-count">4 events</span>
    <svg class="cna-year-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4"><path d="M6 9l6 6 6-6"/></svg>
  </summary>
  <div class="cna-year-body">

  <section class="cna-section cna-cat-talk" markdown="0">
    <header class="cna-section-head">
      <h3>Seunghun Paik — ACM CCS 2026</h3>
      <span class="cna-chip cna-chip-talk">Conference</span>
    </header>
    {% include cna-gallery.html id="gallery18" eager=true %}
  </section>

  <section class="cna-section cna-cat-award" markdown="0">
    <header class="cna-section-head">
      <h3>Outstanding Paper, Hanyang University</h3>
      <span class="cna-chip cna-chip-award">Award</span>
    </header>
    {% include cna-gallery.html id="gallery17" %}
  </section>

  <section class="cna-section cna-cat-seminar" markdown="0">
    <header class="cna-section-head">
      <h3>MATH: Make AI Trust Higher — Workshop at Hanyang University</h3>
      <span class="cna-chip cna-chip-seminar">Workshop</span>
    </header>
    {% include cna-gallery.html id="gallery16" %}
  </section>

  <section class="cna-section cna-cat-member" markdown="0">
    <header class="cna-section-head">
      <h3>Celebrating Sunpill Kim’s graduation</h3>
      <span class="cna-chip cna-chip-member">Member</span>
    </header>
    {% include cna-gallery.html id="gallery15" %}
  </section>

  </div>
</details>

<details class="cna-year" open markdown="0">
  <summary>
    <h3>2025</h3>
    <span class="cna-year-count">4 events</span>
    <svg class="cna-year-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4"><path d="M6 9l6 6 6-6"/></svg>
  </summary>
  <div class="cna-year-body">

  <section class="cna-section cna-cat-seminar" markdown="0">
    <header class="cna-section-head">
      <h3>Seunghun Paik’s invited talk — Day of Mathematics 2025</h3>
      <span class="cna-chip cna-chip-seminar">Invited Talk</span>
    </header>
    {% include cna-gallery.html id="gallery14" %}
  </section>

  <section class="cna-section cna-cat-award" markdown="0">
    <header class="cna-section-head">
      <h3>National Cryptography Contest 2025</h3>
      <span class="cna-chip cna-chip-award">Award</span>
    </header>
    {% include cna-gallery.html id="gallery13" %}
  </section>

  <section class="cna-section cna-cat-talk" markdown="0">
    <header class="cna-section-head">
      <h3>KCCV 2025 — and a birthday celebration for Changjin Kim</h3>
      <span class="cna-chip cna-chip-talk">Conference</span>
    </header>
    {% include cna-gallery.html id="gallery12" %}
  </section>

  <section class="cna-section cna-cat-member" markdown="0">
    <header class="cna-section-head">
      <h3>Celebrating Hyeonbum Lee’s graduation</h3>
      <span class="cna-chip cna-chip-member">Member</span>
    </header>
    {% include cna-gallery.html id="gallery11" %}
  </section>

  </div>
</details>

<details class="cna-year" markdown="0">
  <summary>
    <h3>2024</h3>
    <span class="cna-year-count">5 events</span>
    <svg class="cna-year-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4"><path d="M6 9l6 6 6-6"/></svg>
  </summary>
  <div class="cna-year-body">

  <section class="cna-section cna-cat-award" markdown="0">
    <header class="cna-section-head">
      <h3>National Cryptography Contest 2024</h3>
      <span class="cna-chip cna-chip-award">Award</span>
    </header>
    {% include cna-gallery.html id="gallery10" %}
  </section>

  <section class="cna-section cna-cat-award" markdown="0">
    <header class="cna-section-head">
      <h3>Cryptanalysis Contest 2024</h3>
      <span class="cna-chip cna-chip-award">Award</span>
    </header>
    {% include cna-gallery.html id="gallery9" %}
  </section>

  <section class="cna-section cna-cat-seminar" markdown="0">
    <header class="cna-section-head">
      <h3>MPC &amp; SNARK Workshop 2024</h3>
      <span class="cna-chip cna-chip-seminar">Workshop</span>
    </header>
    {% include cna-gallery.html id="gallery8" %}
  </section>

  <section class="cna-section cna-cat-talk" markdown="0">
    <header class="cna-section-head">
      <h3>Hyeonbum Lee — ZKProof6 &amp; IEEE ICBC 2024</h3>
      <span class="cna-chip cna-chip-talk">Conference</span>
    </header>
    {% include cna-gallery.html id="gallery7" %}
  </section>

  <section class="cna-section cna-cat-talk" markdown="0">
    <header class="cna-section-head">
      <h3>Sunpill Kim — IEEE S&amp;P 2024</h3>
      <span class="cna-chip cna-chip-talk">Conference</span>
    </header>
    {% include cna-gallery.html id="gallery6" %}
  </section>

  </div>
</details>

<details class="cna-year" markdown="0">
  <summary>
    <h3>2023</h3>
    <span class="cna-year-count">3 events</span>
    <svg class="cna-year-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4"><path d="M6 9l6 6 6-6"/></svg>
  </summary>
  <div class="cna-year-body">

  <section class="cna-section cna-cat-talk" markdown="0">
    <header class="cna-section-head">
      <h3>Seunghun Paik — BMVC 2023</h3>
      <span class="cna-chip cna-chip-talk">Conference</span>
    </header>
    {% include cna-gallery.html id="gallery5" %}
  </section>

  <section class="cna-section cna-cat-award" markdown="0">
    <header class="cna-section-head">
      <h3>National Cryptographic Technology &amp; Cryptanalysis Contests 2023</h3>
      <span class="cna-chip cna-chip-award">Award</span>
    </header>
    {% include cna-gallery.html id="gallery4" %}
  </section>

  <section class="cna-section cna-cat-member" markdown="0">
    <header class="cna-section-head">
      <h3>Teacher’s Day with the lab</h3>
      <span class="cna-chip cna-chip-people">Lab Life</span>
    </header>
    {% include cna-gallery.html id="gallery3" %}
  </section>

  </div>
</details>

<details class="cna-year" markdown="0">
  <summary>
    <h3>2022 &amp; earlier</h3>
    <span class="cna-year-count">3 events</span>
    <svg class="cna-year-chevron" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4"><path d="M6 9l6 6 6-6"/></svg>
  </summary>
  <div class="cna-year-body">

  <section class="cna-section cna-cat-talk" markdown="0">
    <header class="cna-section-head">
      <h3>Hyeonbum Lee — ASIACRYPT 2022</h3>
      <span class="cna-chip cna-chip-talk">Conference</span>
    </header>
    {% include cna-gallery.html id="gallery" %}
  </section>

  <section class="cna-section cna-cat-award" markdown="0">
    <header class="cna-section-head">
      <h3>Researcher achievements</h3>
      <span class="cna-chip cna-chip-award">Award</span>
    </header>
    {% include cna-gallery.html id="gallery2" %}
  </section>

  <section class="cna-section cna-cat-people" markdown="0">
    <header class="cna-section-head">
      <h3>Welcome — Bora Jeong</h3>
      <span class="cna-chip cna-chip-member">Member</span>
    </header>
    {% include cna-gallery.html id="gallery1" %}
  </section>

  </div>
</details>
