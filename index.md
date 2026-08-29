---
layout: default
---

<header class="hero">
  <div class="wrap">
    <h1 class="title">
      CrownFusion
      <span class="sub">3D Dental Crown Generation Using Geometry Images and Latent Diffusion</span>
    </h1>

    <div class="venue">MICCAI 2025</div>

    <p class="authors">
      Johan Ziruo Ye<sup>1,2,*</sup> &nbsp;
      Xingguang Yan<sup>3,*</sup> &nbsp;
      Søren Hauberg<sup>1</sup> &nbsp;
      Angel X. Chang<sup>3,4</sup> &nbsp;
      Hao Zhang<sup>3</sup> &nbsp;
      Peter Lempel Søndergaard<sup>2</sup>
    </p>

    <p class="affil">
      <sup>1</sup>Technical University of Denmark &nbsp;·&nbsp;
      <sup>2</sup>3Shape &nbsp;·&nbsp;
      <sup>3</sup>Simon Fraser University &nbsp;·&nbsp;
      <sup>4</sup>Canada-CIFAR AI Chair, Amii
    </p>

    <p class="note">* Equal contribution</p>

    <div class="links">
      <a href="{{ site.paper_url }}">
        <svg viewBox="0 0 384 512"><path d="M320 464c8.8 0 16-7.2 16-16V160H256c-17.7 0-32-14.3-32-32V48H64c-8.8 0-16 7.2-16 16V448c0 8.8 7.2 16 16 16H320zM0 64C0 28.7 28.7 0 64 0H229.5c17 0 33.3 6.7 45.3 18.7l90.5 90.5c12 12 18.7 28.3 18.7 45.3V448c0 35.3-28.7 64-64 64H64c-35.3 0-64-28.7-64-64V64z"/></svg>
        Paper
      </a>
      <a href="{{ site.arxiv_url }}">
        <svg viewBox="0 0 448 512"><path d="M448 80v48c0 44.2-100.3 80-224 80S0 172.2 0 128V80C0 35.8 100.3 0 224 0S448 35.8 448 80zM393.2 214.7c20.8-7.4 39.9-16.9 54.8-28.6V288c0 44.2-100.3 80-224 80S0 332.2 0 288V186.1c14.9 11.8 34 21.2 54.8 28.6C99.7 230.7 159.5 240 224 240s124.3-9.3 169.2-25.3zM0 346.1c14.9 11.8 34 21.2 54.8 28.6C99.7 390.7 159.5 400 224 400s124.3-9.3 169.2-25.3c20.8-7.4 39.9-16.9 54.8-28.6V432c0 44.2-100.3 80-224 80S0 476.2 0 432V346.1z"/></svg>
        arXiv
      </a>
      <a href="{{ site.code_url }}">
        <svg viewBox="0 0 496 512"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8z"/></svg>
        Code
      </a>
      <a href="{{ site.data_url }}">
        <svg viewBox="0 0 448 512"><path d="M448 80v48c0 44.2-100.3 80-224 80S0 172.2 0 128V80C0 35.8 100.3 0 224 0S448 35.8 448 80zM393.2 214.7c20.8-7.4 39.9-16.9 54.8-28.6V288c0 44.2-100.3 80-224 80S0 332.2 0 288V186.1c14.9 11.8 34 21.2 54.8 28.6C99.7 230.7 159.5 240 224 240s124.3-9.3 169.2-25.3zM0 346.1c14.9 11.8 34 21.2 54.8 28.6C99.7 390.7 159.5 400 224 400s124.3-9.3 169.2-25.3c20.8-7.4 39.9-16.9 54.8-28.6V432c0 44.2-100.3 80-224 80S0 476.2 0 432V346.1z"/></svg>
        FDI 16 Crown Dataset
      </a>
      <a href="#bibtex">
        <svg viewBox="0 0 384 512"><path d="M0 48V487.7C0 501.1 10.9 512 24.3 512c5 0 9.9-1.5 14-4.4L192 400 345.7 507.6c4.1 2.9 9 4.4 14 4.4c13.4 0 24.3-10.9 24.3-24.3V48c0-26.5-21.5-48-48-48H48C21.5 0 0 21.5 0 48z"/></svg>
        BibTeX
      </a>
    </div>

    <div class="logos">
      <img src="{{ '/static/DTU_logo.png' | relative_url }}" alt="Technical University of Denmark">
      <img src="{{ '/static/Logo_highres.png' | relative_url }}" alt="3Shape">
    </div>
  </div>
</header>

<main>

<section class="wrap">
  <figure>
    <img src="{{ '/static/fig_teaser.png' | relative_url }}" alt="CrownFusion overview">
    <figcaption>
      <strong>Overview.</strong> From left to right: (1) Input — prepared tooth (bronze) and surrounding dentition
      (gray) from an intraoral scan. (2) Baseline — point cloud-based methods with Poisson reconstruction yield
      overly smooth geometry, eroding occlusal detail. (3) Ours — a diffusion transformer generates a geometry image
      encoding of the crown surface, which is then meshed to recover the 3D crown, preserving fine occlusal features.
    </figcaption>
  </figure>
</section>

<hr>

<section class="wrap">
  <h2>Abstract</h2>
  <div class="abstract">
    <p>
      We introduce <em>CrownFusion</em>, a latent diffusion model to generate 3D dental crown designs from
      <em>geometry images</em>, a 2D-grid encoding of surface coordinates. Departing from traditional approaches that
      use point clouds, our <em>CrownImage</em> representation not only unlocks the full power of image-based
      generative architectures, but also preserves fine geometric detail by operating at far higher spatial
      resolutions than point clouds to alleviate smoothing artifacts in the 3D generation.
    </p>
    <p>
      Conditioned on jointly learned embeddings of the surrounding dentition, our probabilistic diffusion model
      produces anatomically plausible crowns with morphological variations tailored to individual patient cases.
      To accommodate multiple valid designs, we propose an occlusal fit metric based on proximity to the antagonist
      teeth. We evaluate our method through quantitative experiments and qualitative studies involving expert
      testimonials. We also release the <em>FDI 16 Crown Dataset</em>, comprising 11,513 annotated intra-oral scans,
      to support future research in dental CAD.
    </p>
  </div>

  <div class="cards">
    <div class="card">
      <b>Representation</b>
      <span>CrownImage — teeth as geometry images, preserving cusps and fissures.</span>
    </div>
    <div class="card">
      <b>Model</b>
      <span>First latent diffusion model for dental crown generation.</span>
    </div>
    <div class="card">
      <b>Metric</b>
      <span>Occlusal fit measured by antagonist proximity and intersections.</span>
    </div>
    <div class="card">
      <b>Dataset</b>
      <span>11,513 annotated intraoral scans paired with crown restorations.</span>
    </div>
  </div>
</section>

<hr>

<section class="wrap">
  <h2>Why crown design needs a generative model</h2>
  <p>
    A clinically acceptable crown must achieve adequate occlusal fit with the opposing dentition, maintain functional
    contact without hyperocclusion, and reflect natural tooth morphology — including well-defined occlusal grooves that
    direct food flow during mastication. In practice, however, <strong>there is no single correct crown</strong> for a
    given case. Multiple clinically acceptable designs exist, shaped by the technician's training, experience, and
    aesthetic judgement.
  </p>
  <p>
    This motivates a generative approach that captures a <em>space</em> of clinically acceptable solutions rather than
    predicting a single outcome. Prior work is limited by its choice of representation: point cloud methods frame crown
    design as shape completion and tend to erode sharp fissures, while depth image methods are confined to a single
    viewpoint and discard 3D information — for instance, the lingual surface of an antagonist tooth that directly
    contacts the generated crown may be entirely occluded.
  </p>
</section>

<hr>

<section class="wrap">
  <h2>CrownImage: teeth as geometry images</h2>
  <p>
    We represent a dental crown mesh as a 3-channel geometry image, with each pixel storing an
    <em>(x, y, z)</em> surface coordinate as color. Because a tooth is a topological zero-genus surface, a single
    global chart suffices — no patch segmentation or stitching required. We flatten the mesh into a disk via
    boundary-fixed harmonic parameterization, then apply a fisheye-style radial transform that allocates more
    resolution to the center (the occlusal surface) and less to the outer rim (the axial surfaces).
  </p>
  <figure>
    <img src="{{ '/static/fig_repr_poster.png' | relative_url }}" alt="CrownImage construction pipeline">
    <figcaption>
      <strong>CrownImage construction.</strong> <em>M</em>: crown mesh. <em>M<sub>uv</sub></em>: parametrized mesh on
      the unit disk via boundary-fixed harmonic mapping. <em>M<sub>uv*</sub></em>: fisheye-transformed UV mesh (inner
      disk expanded, outer annulus compressed). <em>O</em>: rasterized geometry image encoding (x, y, z) and α.
      <em>M*</em>: remeshed crown recovered by triangulating <em>O</em>.
    </figcaption>
  </figure>
  <p>
    Unlike single-view depth renderings, geometry images retain full 3D geometric information, while supporting far
    higher spatial resolutions than point clouds to better preserve fine-grained, high-curvature tooth features.
  </p>
</section>

<hr>

<section class="wrap">
  <h2>Method</h2>
  <p>
    CrownFusion is a latent diffusion pipeline operating on CrownImages. A <strong>finetuned FLUX VAE</strong> encodes
    geometry images into latent codes — finetuning is essential, since CrownImages encode continuous spatial
    coordinates rather than color values, and small latent errors map directly to geometric distortions on the
    reconstructed surface.
  </p>
  <p>
    A <strong>Scalable Interpolant Transformer (SiT)</strong>, trained from scratch, generates crowns in this latent
    space. It is conditioned on the surrounding dentition — the prepared tooth's neighbors, the antagonist, and the
    antagonist's neighbors — represented as a point cloud and encoded with a jointly trained shape encoder
    (3DShape2VecSet). The embedding is injected via cross-attention at each denoising step, letting the model infer
    occlusal surface features from the antagonist and cusp/fissure placement from the neighboring teeth. The margin
    line of the prepared tooth anchors the crown's seating position and constrains the geometry from below.
  </p>
  <figure>
    <img src="{{ '/static/fig_pipeline_poster.png' | relative_url }}" alt="CrownFusion architecture">
    <figcaption>
      <strong>Overview of CrownFusion.</strong> Left: VAE reconstruction from geometry images. Right: conditional
      generation via SiT diffusion in the learned latent space.
    </figcaption>
  </figure>
</section>

<hr>

<section class="wrap">
  <h2>Results</h2>

  <h3>Autoencoding fidelity</h3>
  <p>
    Since generation quality is bounded by the autoencoder, we first evaluate our VAE against point cloud-based
    autoencoders benchmarked on the FDI 16 Tooth Dataset. Baselines input and output 2,048 points; we convert our
    output CrownImage into a mesh and project each ground-truth point onto its surface.
  </p>
  <div class="tablewrap">
    <table>
      <thead>
        <tr>
          <th>Metric</th><th>DPM</th><th>SetVAE</th><th>LION</th><th>FoldingNet</th><th>VF-Net</th><th>CrownFusion</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>CD (×10²) ↓</td><td>10.04</td><td>21.50</td><td>5.35</td><td>5.26</td><td>1.21</td><td><strong>0.02</strong></td></tr>
        <tr><td>EMD (×10²) ↓</td><td>43.98</td><td>59.24</td><td>22.85</td><td>33.67</td><td>6.30</td><td><strong>0.45</strong></td></tr>
      </tbody>
    </table>
  </div>
  <figure>
    <img src="{{ '/static/fig_recon_cmp_poster.png' | relative_url }}" alt="Reconstruction comparison">
    <figcaption>
      Surface distance heatmaps to ground truth show VF-Net's errors concentrated at cusps and fissures, while our
      geometry image VAE stays close to GT across the entire crown surface.
    </figcaption>
  </figure>

  <h3>Occlusal fit</h3>
  <p>
    Relying on a single technician-designed crown as ground truth is problematic, since designs vary substantially
    between technicians. We therefore evaluate <strong>occlusal fit</strong> by measuring proximity between the
    generated occlusal surface and the antagonist dentition (mean distance of the closest 10th-percentile of 30,000
    sampled antagonist points), and report <strong>intersections</strong> — both count and area — since occlusal
    intersections require significant manual sculpting to correct.
  </p>
  <div class="tablewrap">
    <table>
      <thead>
        <tr>
          <th>Model</th>
          <th>Crown Similarity<br>CD-L2 (mm) ↓</th>
          <th>Bite Proximity<br>10% closest ↓</th>
          <th>Intersections<br>num ↓</th>
          <th>Intersections<br>area (mm²) ↓</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>DMC</td><td>0.433</td><td>0.734</td><td>256</td><td>1.110</td></tr>
        <tr><td>VBCD</td><td><strong>0.353</strong></td><td>0.747</td><td>143</td><td>2.363</td></tr>
        <tr><td>CrownFusion (ours)</td><td>0.412</td><td><strong>0.733</strong></td><td><strong>127</strong></td><td><strong>0.612</strong></td></tr>
        <tr><td>Ground truth</td><td>—</td><td>0.716</td><td>12</td><td>0.0437</td></tr>
      </tbody>
    </table>
  </div>
  <p>
    CrownFusion achieves the closest occlusal alignment to the antagonist teeth, with fewer intersections than both
    baselines — roughly half the intersection rate of DMC — and substantially smaller intersection area when they
    do occur.
  </p>
  <figure>
    <img src="{{ '/static/fig_generation_cmp.png' | relative_url }}" alt="Generation comparison">
    <figcaption>
      <strong>Generation comparison.</strong> <strong>Left:</strong> dental arch with prepared abutment (top) and the
      reference crown in context (bottom). <strong>Right:</strong> occlusal views of crowns generated by DMC, VBCD,
      and CrownFusion, colored by signed distance to the antagonist (blue: gap; red: intersection). VBCD shows a large
      uniform gap, indicating poor occlusal contact. DMC exhibits a localized intersection. CrownFusion achieves the
      closest antagonist proximity with no intersections, and preserves well-defined occlusal anatomy.
    </figcaption>
  </figure>

  <h3>Morphological variation</h3>
  <p>
    While marginal ridge height and gross cusp placement are constrained by the surrounding dentition, the occlusal
    surface is the primary locus of design freedom in clinical practice. Our samples vary exactly along these axes.
    Notably, the features that vary are those most difficult to sculpt manually — existing CAD tools primarily support
    local adjustments rather than global morphological changes.
  </p>
  <figure>
    <img src="{{ '/static/fig_variants_squeezed.png' | relative_url }}" alt="Generated crown variants">
    <figcaption>
      Generated crown samples for the same input. CrownFusion captures expected axes of variation: fissure depth,
      secondary fossae detail, and distolingual cusp morphology vary, while marginal ridge height and overall crown
      outline remain largely stable.
    </figcaption>
  </figure>

  <h3>Expert evaluation</h3>
  <p>
    Two dental professionals assessed generated crowns across all methods. They noted that CrownFusion produces
    well-defined occlusal anatomy, rarely generating the featureless surfaces typical of DMC's overly smooth crowns
    with shallow fissures and blunt cusps. Across DMC, VBCD, and even the reference crowns, fissures occasionally
    appear as isolated incisions without corresponding cusp development, yielding anatomically incoherent surfaces;
    CrownFusion was less prone to this. It does, however, occasionally produce flattened proximal surfaces that
    conform too closely to adjacent teeth rather than forming convex contacts.
  </p>
</section>

<hr>

<section class="wrap">
  <h2>FDI 16 Crown Dataset</h2>
  <p>
    We release the <strong>FDI 16 Crown Dataset</strong>: 11,513 anonymized intraoral scans collected through the
    3Shape Dental System, with 1,000 scans held out for validation and testing respectively. Each scan is paired with
    the final crown restoration, designed by dental technicians in routine clinical workflows.
  </p>
  <p>
    We focus on the FDI 16 tooth (upper right first molar) as it is frequently restored and presents the most complex
    occlusal morphology of any tooth type — four to five cusps, an oblique ridge, and a detailed fissure pattern —
    making it a challenging benchmark. All scans are centered on the FDI 16 crown with the gingiva removed via
    segmentation. Where available, scans include adjacent teeth on the preparation side (FDI 15, 17) and opposing
    teeth on the antagonist side (FDI 45, 46, 47).
  </p>
  <figure>
    <img src="{{ '/static/fig_dataset.png' | relative_url }}" alt="FDI 16 Crown Dataset samples">
    <figcaption>Samples from the FDI 16 Crown Dataset.</figcaption>
  </figure>
</section>

<hr>

<section class="wrap">
  <h2>Limitations</h2>
  <p>
    Our evaluation focuses on FDI 16; generalization across all tooth types remains to be validated. The disk topology
    of geometry images currently restricts the framework to single-tooth restoration, and conditioning on absent
    neighbouring teeth is not yet addressed. Generation time (~5 min per 8 samples on an RTX 4090) is a practical
    constraint, though the extensive literature on diffusion sampling acceleration transfers directly to our setting.
  </p>
</section>

<hr>

<section class="wrap" id="bibtex">
  <h2>BibTeX</h2>
<pre><code>@inproceedings{ye2025crownfusion,
  title     = {CrownFusion: 3D Dental Crown Generation Using
               Geometry Images and Latent Diffusion},
  author    = {Ye, Johan Ziruo and Yan, Xingguang and Hauberg, S{\o}ren and
               Chang, Angel X. and Zhang, Hao and S{\o}ndergaard, Peter Lempel},
  booktitle = {Medical Image Computing and Computer Assisted Intervention (MICCAI)},
  year      = {2025}
}</code></pre>
</section>

</main>

<footer>
  <div class="wrap">
    <p>
      <strong>Acknowledgements.</strong> This work was partly funded by Innovation Fund Denmark (1044-00172B).
      SH was supported by the Novo Nordisk Foundation through the Center for Basic Machine Learning Research in Life
      Science (NNF20OC0062606), VILLUM FONDEN (42062), and the European Research Council (ERC) under the European
      Union's Horizon programme (grant agreement 101125993). AXC is supported by a CIFAR AI Chair and a NSERC
      Discovery Grant. HZ is supported by a NSERC Discovery Grant.
    </p>
    <p>
      <strong>Conflict of interest.</strong> J. Z. Ye and P. L. Søndergaard are employees of 3Shape A/S, and the
      dataset used in this work was collected through 3Shape software. The remaining authors have no competing
      interests to declare.
    </p>
  </div>
</footer>
