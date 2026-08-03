<img src="https://readme-typing-svg.demolab.com?font=Nanum+Gothic&weight=700&size=26&duration=2800&pause=700&color=2F81F7&vCenter=true&width=620&height=60&lines=Hi%2C%20I%27m%20Sunjae%21;%EC%95%88%EB%85%95%ED%95%98%EC%84%B8%EC%9A%94%2C%20%EC%A0%80%EB%8A%94%20%EC%9D%B4%EC%84%A0%EC%9E%AC%EC%9E%85%EB%8B%88%EB%8B%A4.;I%20study%20why%20fusion%20plasmas%20fall%20apart.;%ED%95%B5%EC%9C%B5%ED%95%A9%EC%9D%80%20%EB%8A%98%2030%EB%85%84%20%EB%82%A8%EC%95%98%EC%8A%B5%EB%8B%88%EB%8B%A4." alt="👋 Hi, I'm Sunjae — 안녕하세요, 저는 이선재입니다." />

I'm headed to **Columbia** this fall to start an M.S./Ph.D. in Applied Physics — plasma physics, specifically. Before that, a B.S. in Computer Science & Engineering and Physics at **Seoul National University** (2021–2026).

I work on magnetic-confinement fusion: why tokamak plasmas fall apart, and the software that makes studying them reproducible. These days that means kinetic MHD stability of oddly-shaped plasmas, and a fair amount of database plumbing.

## 🚀 What I've built and am building

<table>
<tr>
<td width="50%" valign="top">
<h3>🔬 <a href="https://github.com/VEST-Tokamak/vaft">VAFT</a></h3>
<img src="https://raw.githubusercontent.com/jaesun57/jaesun57/main/assets/vest_platform.png" width="100%" alt="VEST Data Analysis Platform" />
<p>Analysis toolkit for <b>VEST</b>, SNU's spherical tokamak — and the data platform around it. Diagnostics land in an OMAS-HSDS database, and from there the modelling runs itself: EFIT/CHEASE equilibria and DCON/RDCON stability, automated across the shot archive. Running it end to end turned up something I liked — VEST tends to be limited by current-driven instabilities rather than by pressure.</p>
</td>
<td width="50%" valign="top">
<h3>🌀 GPEC reconstruction</h3>
<img src="https://raw.githubusercontent.com/jaesun57/jaesun57/main/assets/qvsc_n1.png" width="100%" alt="Normal effective current for Q vs C" />
<p>Energy-principle decomposition inside the <b>General Perturbed Equilibrium Code</b> — <a href="https://github.com/PrincetonUniversity/GPEC">Fortran</a> · <a href="https://github.com/OpenFUSIONToolkit/GPEC">Julia</a>. A tokamak holds plasma on nested magnetic surfaces, and the field is supposed to stay on them. Measure a wobbling plasma the obvious way and the field looks like it leaks straight out through the surface — which would be alarming, if it were real. It isn't: you measured on the surface the plasma <i>used</i> to have. The effective field <b>C</b> = δ<b>B</b> + (ξ·n̂)(μ₀<b>j</b>×n̂) is that same field read off the surface the plasma actually moved to, and the leak drops by nine orders of magnitude.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>🏎️ <a href="https://github.com/jaesun57/F1Apex">F1Apex</a></h3>
<img src="https://raw.githubusercontent.com/jaesun57/F1Apex/main/docs/img/car01/streamlines_hero.png" width="100%" alt="F1Apex streamlines" />
<p>CFD-backed F1 front wing aerodynamics — parametric geometry, OpenFOAM RANS, and an interactive aero map. Turns out tokamaks aren't the only thing where the shape decides whether it works.</p>
</td>
<td width="50%" valign="top"></td>
</tr>
</table>
