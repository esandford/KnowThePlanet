# KnowThePlanet

This repository contains posterior distributions for the target KOIs of "Know the Planet, Know the Star: Precise Stellar Densities from *Kepler* Transit Light Curves (Sandford  & Kipping, 2017).

In the root folder are three target lists containing median and +/- 1sigma values for the ten transit parameters fit to each planet-star system (transit epoch t0 in barycentric Kepler Julian days; transit period P in days; impact parameter b; stellar density rhostar, parametrized as log10(rhostar [kg/m^3]); ratio-of-radii Rp/Rstar; eccentricity and argument of periastron, reparametrized as sqrt(e)cos(omega) and sqrt(e)sin(omega); and three reparametrized coefficients of a modified nonlinear limb-darkening law, alpha\_r, alpha\_h, and alpha\_theta (see Kipping 2016, MNRAS, 455, 1680).

In each directory are files containing posterior samples of these 10 transit parameters for each KOI. We have downsampled the full MCMC chains for each KOI such that these files are of manageable size; each contains of order 10^4-10^5 samples.
