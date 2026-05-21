| `.md` concept                | Schema module                   | Purpose                                                              |
| ---------------------------- | ------------------------------- | -------------------------------------------------------------------- |
| Basic identity               | `identity`                      | Names, aliases, family, status, references                           |
| Theory level and model type  | `theory`                        | UV-complete, EFT, simplified, phenomenological                       |
| Particle content             | `particle_content`              | DM candidate, spin, mediator, dark radiation, excited states         |
| Symmetry structure           | `symmetries`                    | Stability mechanism, gauge/global/discrete symmetries                |
| Interaction structure        | `interactions`                  | Portals, mediators, SM couplings, annihilation/decay/scattering      |
| Coupling/operator structure  | `operators`                     | EFT operators, scalar/vector/axial/dipole/anapole terms              |
| Mass scales and hierarchies  | `mass_scales`                   | DM mass, mediator mass, cutoff, reheating, half-mode mass            |
| Production mechanism         | `production`                    | Freeze-out, freeze-in, misalignment, resonant, decay, PBH, etc.      |
| Relic-density logic          | `relic_density`                 | Full DM vs subcomponent, abundance calculation, overclosure          |
| Cosmological history         | `cosmological_history`          | Standard/nonstandard history, entropy injection, dark radiation      |
| Momentum distribution        | `phase_space`                   | Distribution function, warmness, free-streaming, velocity dispersion |
| Linear structure             | `structure_formation.linear`    | Transfer function, cutoff, oscillations, half-mode mapping           |
| Nonlinear structure          | `structure_formation.nonlinear` | HMF, SHMF, concentrations, cores, subhalo survival                   |
| Environment dependence       | `environment_dependence`        | Host mass, redshift, velocity, baryonic degeneracies                 |
| Observable signatures        | `observables`                   | Cosmology, small-scale structure, direct, indirect, collider, lab    |
| Existing constraints         | `constraints`                   | Bounds, likelihoods, public data/code, robustness                    |
| Allowed ranges and priors    | `parameters` / `priors`         | Physical ranges and analysis priors                                  |
| Consistency conditions       | `consistency_conditions`        | Perturbativity, unitarity, EFT validity, BBN/CMB consistency         |
| Validity domain              | `validity_domain`               | Where model, emulator, likelihood, or approximation is valid         |
| Degeneracies/confounders     | `degeneracies`                  | Baryons, IGM, MW mass, line-of-sight structure, selection            |
| Computational representation | `computational_representation`  | CLASS/CAMB, simulations, emulators, likelihoods                      |
| Routing                      | `theory_to_observable_routing`  | Which tool/likelihood/emulator should be called                      |
| Assumptions                  | `assumptions`                   | Explicit assumptions required for constraints or predictions         |
| Provenance                   | `provenance`                    | Claim sources, expert review, confidence, update history             |
| Model comparison             | `model_comparison`              | Motivation, testability, distinctiveness, complementarity            |
| Robustness                   | `robustness`                    | Prior dependence, recast status, emulator uncertainty                |
| Benchmarks                   | `benchmarks`                    | Allowed, excluded, stress-test, emulator-training points             |
| Agent failure modes          | `agent_failure_modes`           | Warnings against common scientific mistakes                          |
