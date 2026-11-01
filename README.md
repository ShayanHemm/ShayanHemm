<h1 align="center">Shayan Hemmatyar</h1>

<p align="center">
  PhD in theoretical physics, Universität Heidelberg &middot; MSc in theoretical physics, ETH Zürich<br>
  <b>Heading into quantitative finance</b>
</p>

<p align="center">
  <a href="mailto:shayanhemm@gmail.com">shayanhemm@gmail.com</a> &nbsp;&middot;&nbsp;
  <a href="https://www.linkedin.com/in/shayan-hemmatyar">LinkedIn</a> &nbsp;&middot;&nbsp;
  <a href="https://shayanhemm.github.io/second-brain/">Live demo of my latest project</a>
</p>

I build research code that other people can run and check: statistics on noisy time series, numerical simulation, and AI tools whose every output can be traced back to its evidence. The four projects below show how I work. Each comes with figures, a reproducible setup, and a section on what the result does not show.

## Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ShayanHemm/second-brain"><img src="https://raw.githubusercontent.com/ShayanHemm/second-brain/main/docs/screenshots/network.png" alt="Second Brain concept network" width="100%"></a>
      <br><b><a href="https://github.com/ShayanHemm/second-brain">Second Brain</a></b> &nbsp;<a href="https://shayanhemm.github.io/second-brain/">live demo</a><br>
      A local-first journal that files itself with Claude, links entries into a concept network, and reports patterns with their sample sizes. Every model output is a fixed form checked against the text in code, and nothing leaves the machine except the entry being filed.<br>
      <sub>Python &middot; FastAPI &middot; SQLite FTS5 &middot; d3-force &middot; Claude API &middot; tests in CI</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ShayanHemm/yield-curve-spread-analysis"><img src="https://raw.githubusercontent.com/ShayanHemm/yield-curve-spread-analysis/main/figures/spreads_recessions.png" alt="2s10s spread with recessions" width="100%"></a>
      <br><b><a href="https://github.com/ShayanHemm/yield-curve-spread-analysis">US yield curve and spreads</a></b><br>
      The Treasury curve from FRED, 1990 to today: 2s10s and 3m10y spreads against NBER recessions and inflation, with every inversion episode tabulated. Key-free data pull that refreshes on each run.<br>
      <sub>pandas &middot; pandas-datareader &middot; matplotlib</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ShayanHemm/inflation-pressure-signals"><img src="https://raw.githubusercontent.com/ShayanHemm/inflation-pressure-signals/main/figures/pressure_regime.png" alt="Core inflation pressure regime" width="100%"></a>
      <br><b><a href="https://github.com/ShayanHemm/inflation-pressure-signals">US inflation pressure signals</a></b><br>
      Level, momentum and persistence of core inflation combined into a rule-based regime call of the kind macro desks use, with the thresholds and their weaknesses spelled out.<br>
      <sub>pandas &middot; fredapi &middot; matplotlib</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ShayanHemm/gw-noisy-cnn-classification"><img src="https://raw.githubusercontent.com/ShayanHemm/gw-noisy-cnn-classification/main/figures/overview.png" alt="Gravitational-wave classification pipeline" width="100%"></a>
      <br><b><a href="https://github.com/ShayanHemm/gw-noisy-cnn-classification">GR vs beyond-GR gravitational-wave signals with a 1D CNN</a></b><br>
      Waveforms from 121 catalogued black-hole mergers, a controlled beyond-GR phase deformation, coloured detector noise, and a convolutional baseline, with the evaluation caveats stated up front.<br>
      <sub>PyCBC &middot; LALSuite &middot; TensorFlow &middot; scikit-learn</sub>
    </td>
  </tr>
</table>

## How I work

- **Reproducible by default.** Pinned environments, one-command setup, outputs stored so results can be read without running anything, and tests in CI where there is code to test.
- **Statistics before stories.** Sample sizes on every statement, judgement calls named as such, and the known weaknesses of each result listed in its README.
- **AI as an inspectable tool, not an oracle.** Structured outputs, quoted evidence verified in code, a human override at every step.

## Background

- **PhD in theoretical physics, Universität Heidelberg (2025).** Thesis: [*Theoretical and Machine Learning Approaches to Beyond General Relativity: Stability of Generalized Proca Theories and Multi-Method Classification of Gravitational Wave Observables*](https://doi.org/10.11588/heidok.00036791). Gravitational-wave physics, tests of general relativity, and neural-network classification of noisy signals.
- **MSc in theoretical physics, ETH Zürich.** Thesis work on kinetic field theory of cosmic structure formation, published in Physical Review D as an Editors' Suggestion.
- Python (NumPy, pandas, SciPy, scikit-learn, TensorFlow, FastAPI), C, Mathematica.
- Currently building a portfolio project on AI-assisted quantitative research, designed around transparency, backtesting and explicit rubrics.

## Publications

- L. Heisenberg, S. Hemmatyar. *Identifiability Limits of Gravitational Wave Phase Deviations: Multiclass Classification with a Multihead Neural Network.* [arXiv:2609.31993](https://arxiv.org/abs/2609.31993) (2026).
- L. Heisenberg, S. Hemmatyar, H. Villarrubia-Rojo. *Testing General Relativity Through Gravitational Wave Classification: A Convolutional Neural Network Framework.* [arXiv:2605.02453](https://arxiv.org/abs/2605.02453) (2026).
- L. Heisenberg, S. Hemmatyar, N. Nussbaumer. *A non-renormalization theorem for local functionals in ghost-free vector field theories coupled to dynamical geometry.* [JHEP 09 (2026) 042](https://doi.org/10.1007/JHEP09(2026)042), [arXiv:2601.08081](https://arxiv.org/abs/2601.08081).
- L. Heisenberg, S. Hemmatyar, S. Zentarra. *Kinetic field theory: Higher-order perturbation theory.* [Phys. Rev. D 106, 063513 (2022)](https://doi.org/10.1103/PhysRevD.106.063513), Editors' Suggestion. [arXiv:2207.10504](https://arxiv.org/abs/2207.10504).
