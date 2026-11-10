---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<script>
window.MathJax = {
  tex: {
    inlineMath: {'[+]': [['$', '$']]}
  }
};
</script>
<script defer src="https://cdn.jsdelivr.net/npm/mathjax@4/tex-chtml.js"></script>

<p align="center">
<!-- <img style="float: left; margin-right: 24px; margin-bottom: 16px;" src="files/eth.JPG?v=2" width="200"> -->
<img style="float: left; margin-right: 24px; margin-bottom: 16px;" src="files/260930_317 copy 2.jpg" width="200">
</p>

I'm a fifth-year PhD candidate at the [MIT Department of Mathematics](https://math.mit.edu/directory/profile.html?pid=2448), working on problems in differential geometry, geometric analysis, and partial differential equations. I am advised by Prof. William Minicozzi.

I grew up in Hong Kong. Before coming to MIT, I obtained my BSc at the University of Melbourne and completed an Honors year at the Australian National University.

I am fortunate to be supported by a [Simons Dissertation Fellowship](https://www.simonsfoundation.org/news/first-class-of-simons-dissertation-fellows-in-mathematics-announced/) (2025-2027), as well as a [Croucher Scholarship](https://croucher.org.hk/en/fellows-and-scholars/michael-law) (2023-2025).

<div style="height: 1.3em;"></div>

<p style="text-align: center;">
    <a href="mailto:{{ site.email }}">
    ✉ {{ site.email }}
    </a>
    &nbsp; • &nbsp;

    <a href="https://scholar.google.com/citations?user=fyboKJcAAAAJ&hl=en">
    <img
        src="https://scholar.google.com/favicon.ico"
        style="width:16px; height:16px; vertical-align:text-bottom;"
        alt="">
    Google Scholar
    </a>
    &nbsp; • &nbsp;

    <a href="https://www.linkedin.com/in/mikeblaw/">
    <svg class="svg-icon">
        <use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use>
    </svg>
    LinkedIn
    </a>
</p>


# Research

1. Uniqueness and stability of Appleton's solitons.
<span style="font-size: 0.8em;">[[arXiv preprint]](https://arxiv.org/abs/2611.10444)</span>
    <button type="button"
    aria-expanded="false"
    aria-controls="abstract-appleton"
    style="border: 0; background: none; padding: 0; font-size: 0.8em; color: inherit; cursor: pointer;"
    onclick="const a = document.getElementById(this.getAttribute('aria-controls')); a.hidden = !a.hidden; this.setAttribute('aria-expanded', String(!a.hidden)); this.querySelector('span').style.transform = a.hidden ? 'rotate(0deg)' : 'rotate(90deg)';">
    <span aria-hidden="true" style="display: inline-block; transition: transform 0.15s ease;">▶</span> abstract
    </button>
    <p id="abstract-appleton" hidden style="font-size: 0.8em; line-height: 1.5; margin-top: 0.5em;">
    We prove that Appleton's noncollapsed steady gradient Ricci solitons on complex line bundles over positive Kähler–Einstein manifolds are the unique such solitons arising from his metric ansatz. We then show that the four-dimensional examples on $\mathcal{O}_{\mathbb{CP}^1}(-k)$, $k \geq 3$, are strictly linearly stable. By a result of Deruelle, this implies dynamical stability under the Ricci flow.
    </p>
    <div style="height: 0.4em;"></div>

2. An analytical characterization of Eguchi-Hanson space and its higher-dimensional analogs.
<span style="font-size: 0.8em;">[[arXiv preprint]](https://arxiv.org/abs/2604.23410)</span>
    <button type="button"
    aria-expanded="false"
    aria-controls="abstract-ale"
    style="border: 0; background: none; padding: 0; font-size: 0.8em; color: inherit; cursor: pointer;"
    onclick="const a = document.getElementById(this.getAttribute('aria-controls')); a.hidden = !a.hidden; this.setAttribute('aria-expanded', String(!a.hidden)); this.querySelector('span').style.transform = a.hidden ? 'rotate(0deg)' : 'rotate(90deg)';">
    <span aria-hidden="true" style="display: inline-block; transition: transform 0.15s ease;">▶</span> abstract
    </button>
    <p id="abstract-ale" hidden style="font-size: 0.8em; line-height: 1.5; margin-top: 0.5em;">
    Let $(M,g)$ be a complete $4$-dimensional Ricci-flat ALE orbifold with finitely many orbifold points and group at infinity $\mathbb{Z}_2$. We prove that if the $L^2$ kernel of its Lichnerowicz Laplacian has dimension at most $3$, then $(M,g)$ is either the Eguchi–Hanson space or the flat orbifold $\mathbb{R}^4/\mathbb{Z}_2$. A similar uniqueness result is proved for Calabi's higher-dimensional analogs of the Eguchi-Hanson space among Ricci-flat Kähler ALE orbifolds with group at infinity $\mathbb{Z}_m$.
    </p>
    <div style="height: 0.4em;"></div>

3. On steady and expanding Ricci solitons with asymptotic symmetries.
<span style="font-size: 0.8em;">[[arXiv preprint]](https://arxiv.org/abs/2505.20576)</span>
    <button type="button"
    aria-expanded="false"
    aria-controls="abstract-acyl"
    style="border: 0; background: none; padding: 0; font-size: 0.8em; color: inherit; cursor: pointer;"
    onclick="const a = document.getElementById(this.getAttribute('aria-controls')); a.hidden = !a.hidden; this.setAttribute('aria-expanded', String(!a.hidden)); this.querySelector('span').style.transform = a.hidden ? 'rotate(0deg)' : 'rotate(90deg)';">
    <span aria-hidden="true" style="display: inline-block; transition: transform 0.15s ease;">▶</span> abstract
    </button>
    <div id="abstract-acyl" hidden style="font-size: 0.8em; line-height: 1.5; margin-top: 0.5em;">
    <p>We establish a symmetry principle for asymptotically cylindrical steady gradient Ricci solitons and asymptotically conical expanding gradient Ricci solitons. Our symmetry principle bounds the loss of symmetry from the asymptotic link to the interior by the dimension of the weighted $L^2$ kernel of the stability operator. For homogeneous links, suitable kernel bounds imply that the soliton has an isometric action of cohomogeneity one. The results apply in particular to strictly linear stable solitons, require no curvature sign assumptions, and allow orbifold singular sets of codimension at least four.</p>
    <p>Applications include characterizations of Bryant solitons and global $U(m)$-symmetry results for solitons with quotient-Berger asymptotic links. In dimension four, we classify asymptotically $SU(2)/\Gamma$-cylindrical steady gradient Ricci solitons with trivial weighted kernel as finite quotients of Bryant or Appleton solitons. Under the same kernel condition, we also establish toric symmetry for asymptotically lens-cylindrical steady solitons.</p>
    </div>
    <div style="height: 0.4em;"></div>

4. Drift-harmonic functions with polynomial growth on asymptotically paraboloidal manifolds.
<span style="font-size: 0.8em;">[[arXiv preprint]](https://arxiv.org/abs/2501.05119)</span>
    <button type="button"
    aria-expanded="false"
    aria-controls="abstract-ap"
    style="border: 0; background: none; padding: 0; font-size: 0.8em; color: inherit; cursor: pointer;"
    onclick="const a = document.getElementById(this.getAttribute('aria-controls')); a.hidden = !a.hidden; this.setAttribute('aria-expanded', String(!a.hidden)); this.querySelector('span').style.transform = a.hidden ? 'rotate(0deg)' : 'rotate(90deg)';">
    <span aria-hidden="true" style="display: inline-block; transition: transform 0.15s ease;">▶</span> abstract
    </button>
    <p id="abstract-ap" hidden style="font-size: 0.8em; line-height: 1.5; margin-top: 0.5em;">
    We construct and classify all polynomial growth solutions to certain drift-harmonic equations on complete manifolds with paraboloidal asymptotics. These encompass the natural drift-harmonic equations on certain steady gradient Ricci solitons. Specifically, we show that all drift-harmonic functions with polynomial growth asymptotically separate variables, and compute the dimensions of spaces of drift-harmonic functions with a given polynomial growth rate. The proof uses an inductive argument that alternates between constructing and asymptotically controlling drift-harmonic functions.
    </p>
    <div style="height: 0.4em;"></div>

5. Concavity for elliptic and parabolic equations in locally symmetric spaces with nonnegative curvature (with Shrey Aryan). <em>Calc. Var. Partial Differential Equations.</em> Vol. 64, No. 202, 2025.
<span style="font-size: 0.8em;">[[published version]](https://link.springer.com/article/10.1007/s00526-025-03049-8) [[arXiv preprint]](https://arxiv.org/abs/2403.16783)</span>
    <button type="button"
    aria-expanded="false"
    aria-controls="abstract-cpn"
    style="border: 0; background: none; padding: 0; font-size: 0.8em; color: inherit; cursor: pointer;"
    onclick="const a = document.getElementById(this.getAttribute('aria-controls')); a.hidden = !a.hidden; this.setAttribute('aria-expanded', String(!a.hidden)); this.querySelector('span').style.transform = a.hidden ? 'rotate(0deg)' : 'rotate(90deg)';">
    <span aria-hidden="true" style="display: inline-block; transition: transform 0.15s ease;">▶</span> abstract
    </button>
    <p id="abstract-cpn" hidden style="font-size: 0.8em; line-height: 1.5; margin-top: 0.5em;">
    We establish a concavity principle for solutions to elliptic and parabolic equations on locally symmetric spaces with nonnegative sectional curvature, extending the results of Langford and Scheuer. To the best of our knowledge, this is the first general concavity principle established on spaces with non-constant sectional curvature.
    </p>
    <div style="height: 0.4em;"></div>

6. Positive mass and Dirac operators on weighted manifolds and smooth metric measure spaces (with Isaac M. Lopez and Daniel Santiago). <em>J. Geom. Phys.</em> Vol. 209, No. 105386, 2025.
<span style="font-size: 0.8em;">[[published version]](https://www.sciencedirect.com/science/article/abs/pii/S0393044024002870) [[arXiv preprint]](https://arxiv.org/abs/2312.15441)</span>
    <button type="button"
    aria-expanded="false"
    aria-controls="abstract-dirac"
    style="border: 0; background: none; padding: 0; font-size: 0.8em; color: inherit; cursor: pointer;"
    onclick="const a = document.getElementById(this.getAttribute('aria-controls')); a.hidden = !a.hidden; this.setAttribute('aria-expanded', String(!a.hidden)); this.querySelector('span').style.transform = a.hidden ? 'rotate(0deg)' : 'rotate(90deg)';">
    <span aria-hidden="true" style="display: inline-block; transition: transform 0.15s ease;">▶</span> abstract
    </button>
    <p id="abstract-dirac" hidden style="font-size: 0.8em; line-height: 1.5; margin-top: 0.5em;">
    We establish a weighted positive mass theorem which unifies and generalizes results of Baldauf–Ozuch and Chu–Zhu. Our result is in fact equivalent to the usual positive mass theorem, and can be regarded as a positive mass theorem for smooth metric measure spaces. We also study Dirac operators on certain warped product manifolds associated to smooth metric measure spaces. Applications of this include, among others, an alternative proof for a special case of our positive mass theorem, eigenvalue bounds for the Dirac operator on closed spin manifolds, and a new way to understand the weighted Dirac operator using warped products.
    </p>
    <div style="height: 0.4em;"></div>


# Other writing

1. [Uniqueness of tangent flows in mean curvature flow](https://mike-law.github.io/files/ThesisMCF.pdf). Undergraduate honors thesis, ANU. Advised by [Prof. Ben Andrews](https://maths-people.anu.edu.au/~andrews/).
2. [Characteristic classes for the differential geometer](https://mike-law.github.io/files/char_classes.pdf). Term paper for <em>Gauge Theory and Symplectic Geometry</em>, ANU.
3. [The No Wandering Domains theorem](https://mike-law.github.io/files/NWD_Theorem.pdf). Term paper for <em>Riemann Surfaces</em>, ANU.
4. [Jacobi fields, conjugate points and some applications](https://mike-law.github.io/files/jacobi_fields.pdf). Term paper for <em>Differential Geometry</em>, ANU.
5. [Topological phases in quantum systems with quantum group symmetries](https://vrs.amsi.org.au/wp-content/uploads/sites/84/2021/01/law_michael_vrs-report.pdf.pdf). AMSI VRS research report, Australian Mathematical Sciences Institute/University of Melbourne. Advised by [Dr. Thomas Quella](https://sites.google.com/view/thomas-quella/home/).
6. [Label-noise robust twin auxiliary classifier GANs](https://mike-law.github.io/files/TACGAN_with_label_noise.pdf). Research report for SCIE30001, University of Melbourne. Advised by [Dr. Mingming Gong](https://mingming-gong.github.io/index.html).


<script>
document.addEventListener('DOMContentLoaded', () => {
  document.querySelectorAll('a[href]').forEach(link => {
    const href = link.getAttribute('href');

    if (href.startsWith('#') || href.startsWith('mailto:')) return;

    link.target = '_blank';
    link.rel = 'noopener noreferrer';
  });
});
</script>