## 👋 Hi, I'm Sunjae (이선재)

I'm headed to **Columbia** this fall to start an M.S./Ph.D. in Applied Physics — plasma physics, specifically. Before that, a B.S. in Computer Science & Engineering and Physics at **Seoul National University** (2021–2026).

I work on magnetic-confinement fusion: why tokamak plasmas fall apart, and the software that makes studying them reproducible. These days that means kinetic MHD stability of oddly-shaped plasmas, and a fair amount of database plumbing.

## 🚀 What I'm building

<table>
<tr>
<td width="50%" valign="top">
<h3>🔬 <a href="https://github.com/VEST-Tokamak/vaft">VAFT</a></h3>
<img src="https://raw.githubusercontent.com/jaesun57/jaesun57/main/assets/vest_platform.png" width="100%" alt="VEST Data Analysis Platform" />
<p>Analysis toolkit for <b>VEST</b>, SNU's spherical tokamak — and the data platform around it. Diagnostics land in an OMAS-HSDS database as one file per shot; from there a couple of lines of Python pull a shot back out, and the same store feeds EFIT/CHEASE equilibria and DCON/RDCON stability runs.</p>
</td>
<td width="50%" valign="top">
<h3>🌀 GPEC reconstruction</h3>
<img src="https://raw.githubusercontent.com/jaesun57/jaesun57/main/assets/qvsc_n1.png" width="100%" alt="Normal effective current for Q vs C" />
<p>Energy-principle decomposition inside the <b>General Perturbed Equilibrium Code</b> — <a href="https://github.com/PrincetonUniversity/GPEC">Fortran</a> · <a href="https://github.com/OpenFUSIONToolkit/GPEC">Julia</a>. The effective field <b>C</b> = δ<b>B</b> + (ξ·n̂)(μ₀<b>j</b>×n̂) turns out not to be bookkeeping — it's the real field once you correct the frame to the perturbed surface. Test it by asking whether it pierces the flux surface: bare δ<b>B</b> does, <b>C</b> doesn't, and the gap is nine orders of magnitude.</p>
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
