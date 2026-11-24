# Superdiffusive-Stochastic-Fermi-Acceleration-in-Space-and-energy

A lattice scatterer model for stochastic second-order Fermi acceleration,
applied to solar-wind and laboratory magnetized plasmas.
M1 internship project, LUX/Observatoire de Paris (2025–2026).

## Key results
- Using the total relativistic energy (instead of the kinetic energy) in the
  per-collision energy update recovers the correct transport exponents and
  the Weibull energy spectrum.
- The model reproduces published solar-wind spectra, showing that power-law
  energy growth and the Weibull spectral shape are independent.

## Contents
- `fig1b_energy_distribution.ipynb` – energy distributions from Gaussian and Maxwellian initial conditions
- `generalized eq4.ipynb` – generalized (relativistic) per-collision energy equation
- `lorentz+rejection.ipynb` – collisions via Lorentz transformation and rejection sampling
- `weibull0612.ipynb` – Weibull fit to solar-wind spectra and comparison with simulations
- `data from article.txt` – digitized data from articles used for comparison
