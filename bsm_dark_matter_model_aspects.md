# BSM Dark-Matter Theory Registry: Model Aspects

This note lists the major aspects of a beyond-the-Standard-Model (BSM) dark-matter model that a structured theory registry should track. The goal is to make each model understandable, comparable, and connectable to observables, likelihoods, emulators, and scientific assumptions.

The actual machine-readable schema can be defined separately after this conceptual structure is agreed upon.

---

## 1. Basic model identity

These fields identify the model and place it within the broader dark-matter landscape.

- Model name
- Model family
- Alternative names used in the literature
- Short scientific description
- Historical origin or motivation
- Canonical references
- Model status: canonical, speculative, emerging, benchmark, deprecated, or excluded
- Whether the model is intended as a complete theory, simplified model, or phenomenological parameterization

Examples of model families include:

- Cold dark matter
- Warm dark matter
- Fuzzy or ultralight dark matter
- Axion or axion-like dark matter
- Sterile-neutrino dark matter
- Self-interacting dark matter
- Asymmetric dark matter
- Freeze-in dark matter
- Hidden-sector dark matter
- Composite dark matter
- Primordial black holes
- Multi-component dark matter
- Decaying or annihilating dark matter
- Interacting dark radiation / dark acoustic oscillation models

---

## 2. Theory level and model type

This describes the theoretical status of the model.

- UV-complete theory
- Simplified model
- Effective field theory
- Phenomenological parameterization
- Benchmark mapping from another model
- Lagrangian-level description available or not
- Whether the model is renormalizable
- Whether the EFT has a known cutoff scale
- Whether the model is embedded in a larger framework

Possible parent frameworks include:

- Supersymmetry
- Extra dimensions
- Hidden valleys
- Axions and Peccei-Quinn symmetry
- Sterile-neutrino extensions
- Neutrino portal models
- Higgs portal models
- Vector portal models
- Dark photon models
- Twin-Higgs-like scenarios
- Composite dark sectors
- String-inspired axiverse scenarios

---

## 3. Particle content

These fields describe the particles or fields in the dark sector.

- Dark-matter candidate name
- Spin
- Statistics: boson, fermion, vector, scalar, etc.
- Whether the dark matter is elementary or composite
- Whether the model has one dark-matter species or multiple components
- Whether there are additional dark-sector particles
- Mediator particles
- Dark radiation species
- Excited states
- Nearly degenerate states
- Long-lived particles
- Unstable parent particles that produce dark matter
- Whether the Standard Model is extended minimally or substantially

Important particle-content distinctions:

- Scalar dark matter
- Fermionic dark matter
- Vector dark matter
- Axion-like field
- Sterile neutrino
- Primordial black hole
- Composite bound state
- Macroscopic dark-matter object
- Multi-state or inelastic dark matter

---

## 4. Symmetry structure

These fields specify why the dark matter is stable or long-lived and what symmetry principles define the theory.

- Stabilizing symmetry
- Gauge symmetry
- Global symmetry
- Approximate symmetry
- Discrete symmetry
- Shift symmetry
- R-parity-like symmetry
- Dark baryon or dark lepton number
- Accidental symmetry
- Symmetry-breaking scale
- Whether the symmetry is exact or approximate
- Whether the symmetry is spontaneously or explicitly broken
- Whether symmetry breaking creates topological defects

Examples:

- \(Z_2\) symmetry
- \(U(1)_D\) dark gauge symmetry
- Shift symmetry for axions
- Approximate lepton number
- R-parity
- Dark baryon number

---

## 5. Interaction structure

This describes how dark matter interacts with itself, with the Standard Model, and with other dark-sector particles.

- Couplings to Standard Model particles
- Couplings within the dark sector
- Mediator type
- Interaction operator
- Portal type
- Interaction strength
- Elastic versus inelastic scattering
- Annihilation channels
- Decay channels
- Self-scattering channels
- Momentum dependence
- Velocity dependence
- Spin dependence
- CP structure
- Flavor structure
- Parity violation
- Whether the interaction is tree-level or loop-level

Standard Model coupling targets may include:

- Quarks
- Leptons
- Neutrinos
- Photons
- Gluons
- Higgs boson
- Electroweak gauge bosons
- Gravity only

Common portal types include:

- Higgs portal
- Vector portal
- Neutrino portal
- Axion portal
- Gravitational portal

Mediator types include:

- Scalar mediator
- Pseudoscalar mediator
- Vector mediator
- Axial-vector mediator
- Tensor mediator
- Graviton-like mediator
- Dark photon
- Heavy sterile state

---

## 6. Coupling and operator structure

This is a more detailed classification of the interaction terms.

- Renormalizable interaction terms
- Higher-dimensional EFT operators
- Contact interaction versus light mediator
- Scalar coupling
- Pseudoscalar coupling
- Vector coupling
- Axial-vector coupling
- Dipole interaction
- Anapole interaction
- Millicharge
- Magnetic or electric dipole moment
- Dark-matter-neutrino scattering
- Dark-matter-baryon scattering
- Dark-matter-photon coupling
- Dark-matter-dark-radiation coupling
- Dark-matter self-coupling

This category matters because different operators produce different experimental and astrophysical signatures even when the particle mass is similar.

---

## 7. Mass scales and hierarchies

The registry should track all relevant energy and mass scales, not only the dark-matter mass.

- Dark-matter mass
- Mediator mass
- Mass splittings
- Decay constant
- Symmetry-breaking scale
- Dark-sector confinement scale
- Cutoff scale
- Reheating temperature
- Kinetic-decoupling temperature
- Chemical-decoupling temperature
- Freeze-out temperature
- Free-streaming scale
- Jeans scale
- Half-mode mass
- Dark acoustic oscillation scale
- Soliton-core scale
- De Broglie wavelength for ultralight models

Important hierarchy questions:

- Is the mediator heavier or lighter than the dark matter?
- Is the dark sector colder or hotter than the visible sector?
- Is the mediator long-lived?
- Is there a small mass splitting enabling inelastic scattering?
- Is the model sensitive to the reheating temperature?
- Does the EFT cutoff sit safely above the relevant experimental or cosmological scale?

---

## 8. Production mechanism

This records how the dark matter is produced in the early Universe or through later processes.

- Thermal freeze-out
- Freeze-in
- Misalignment production
- Resonant production
- Non-resonant production
- Decay production
- Asymmetric dark matter
- SIMP mechanism
- ELDER mechanism
- Cannibal dark matter
- Gravitational production
- Production from topological defects
- Production from phase transitions
- Primordial black hole formation
- Non-standard cosmology production
- Multi-stage production
- Subdominant dark-matter production

Useful production questions:

- Was the dark matter ever in thermal equilibrium with the Standard Model?
- Was it in thermal equilibrium with a hidden sector?
- Does the abundance depend on reheating temperature?
- Is the final relic density set by annihilation, decay, misalignment, or asymmetry?
- Can the model produce all of dark matter, or only a fraction?
- Does the production mechanism imprint non-thermal momentum distributions?

---

## 9. Relic-density logic

This is distinct from production mechanism because it captures how the model obtains the observed dark-matter abundance.

- Target fraction of total dark matter
- Full dark-matter component versus subcomponent
- Thermal relic abundance calculation
- Non-thermal relic abundance calculation
- Dependence on annihilation cross section
- Dependence on decay rate
- Dependence on initial field displacement
- Dependence on lepton asymmetry or baryon asymmetry
- Dependence on reheating temperature
- Dependence on hidden-sector temperature
- Need for entropy dilution
- Overclosure constraints
- Underproduction regions

Important questions:

- Does the model naturally produce the observed abundance?
- Does it require tuning?
- Does it overproduce dark matter in much of parameter space?
- Does it require a non-standard expansion history?
- Can it be a subdominant component with distinctive signatures?

---

## 10. Cosmological history

These fields describe the early-Universe assumptions needed for the model.

- Standard radiation domination
- Early matter domination
- Late entropy injection
- Low reheating temperature
- Modified expansion history
- Dark-sector temperature
- Dark radiation contribution
- Effective number of relativistic species, \(\Delta N_{\rm eff}\)
- Kinetic decoupling
- Chemical decoupling
- Dark recombination
- Dark acoustic oscillations
- Cannibalization
- Phase transitions
- Topological defects
- Isocurvature perturbations
- BBN constraints
- CMB constraints
- Reionization dependence

Important questions:

- Does the model assume standard cosmology?
- Does the model require a non-standard thermal history?
- Does it alter BBN or CMB observables?
- Does it produce dark radiation?
- Does it create isocurvature modes?
- Does it change the time or nature of matter-radiation equality?

---

## 11. Momentum distribution and phase-space structure

This is especially important for non-cold models.

- Thermal momentum distribution
- Non-thermal momentum distribution
- Distribution function \(f(p)\) or \(f(q)\)
- Average momentum relative to thermal relic
- Free-streaming length
- Phase-space density
- Tremaine-Gunn-like bounds
- Warmness parameter
- Cold plus warm mixed distribution
- Resonantly produced distribution
- Distribution inherited from decay kinematics
- Velocity dispersion today
- Redshift evolution of velocity dispersion

This category matters because two models with the same particle mass can have different structure-formation effects if their momentum distributions differ.

---

## 12. Linear structure-formation impact

This connects the particle model to the linear matter power spectrum.

- Linear transfer function
- Suppression of small-scale power
- Enhancement of small-scale power
- Cutoff scale
- Oscillatory features
- Dark acoustic oscillations
- Step-like suppression
- Mixed cold/warm suppression
- Scale-dependent growth
- Redshift-dependent suppression
- Impact on \(\sigma_8\), \(S_8\), or small-scale variance
- Half-mode scale
- Half-mode mass
- Mapping to thermal relic warm dark matter, if applicable

Important questions:

- Does the model behave like CDM at linear scales?
- Is the transfer-function shape smooth, oscillatory, sharp, or mixed?
- Can the model be summarized by a half-mode mass, or is that insufficient?
- Is the mapping to thermal WDM valid or misleading?

---

## 13. Nonlinear structure-formation impact

These fields describe how the model affects halos, subhalos, and nonlinear cosmic structure.

- Halo mass function
- Subhalo mass function
- Infall subhalo mass function
- Present-day bound subhalo mass function
- Concentration-mass relation
- Halo density profiles
- Core formation
- Cusps versus cores
- Subhalo survival
- Tidal stripping
- Subhalo evaporation
- Merger histories
- Delay of halo formation
- Suppression of low-mass halos
- Changes in halo assembly bias
- Wave interference effects
- Soliton cores
- Quantum pressure effects
- Dark-sector drag or scattering
- Impact on the smallest galaxies

Important questions:

- Does the model reduce the abundance of low-mass halos?
- Does it change the internal structure of halos?
- Does it change subhalo survival after infall?
- Does it create cores in dwarf galaxies or clusters?
- Are the nonlinear effects calibrated by simulations?

---

## 14. Astrophysical environment dependence

Some dark-matter signatures depend strongly on environment.

- Host-halo mass dependence
- Redshift dependence
- Velocity-dispersion dependence
- Local-density dependence
- Cluster versus dwarf versus Milky Way behavior
- Strong-lens host-halo environment
- Satellite-galaxy environment
- Stellar-stream orbital environment
- Disk-shocking dependence
- Baryonic-feedback degeneracy
- Reionization-history dependence
- IGM thermal-history dependence
- Dependence on host-halo concentration
- Dependence on tidal history

This is important because a model may affect Lyman-alpha, satellites, streams, strong lenses, dwarfs, and clusters in different ways.

---

## 15. Observable signatures

The registry should organize signatures by observational channel.

### Cosmological observables

- CMB anisotropies
- CMB lensing
- Matter power spectrum
- Large-scale structure
- Lyman-alpha forest
- 21 cm cosmology
- Spectral distortions
- \(N_{\rm eff}\)
- Isocurvature
- Reionization history

### Small-scale structure observables

- Milky Way satellite counts
- Satellite luminosity function
- Stellar-stream gaps
- Stellar-stream density perturbations
- Strong-lensing flux-ratio anomalies
- Strong-lensing astrometric anomalies
- Strong-lensing arc perturbations
- Dwarf-galaxy density profiles
- Cluster halo shapes
- Cluster offsets
- Subhalo abundance
- Halo concentration

### Direct-detection observables

- Nuclear recoils
- Electron recoils
- Absorption signals
- Annual modulation
- Directional detection
- Migdal effect
- Bremsstrahlung signatures
- Low-threshold detector signals
- Superconducting detector signals
- Superfluid helium signals

### Indirect-detection observables

- Gamma rays
- X-rays
- Cosmic rays
- Neutrinos
- Radio synchrotron
- CMB energy injection
- 21 cm heating or cooling
- Spectral lines
- Continuum emission
- Signals from dwarfs, Galactic center, clusters, or extragalactic background

### Collider observables

- Missing transverse energy
- Monojet signatures
- Monophoton signatures
- Invisible Higgs decays
- Invisible Z decays
- Displaced vertices
- Long-lived particles
- Emerging jets
- Dark showers
- Heavy mediator resonance searches
- Exotic Higgs decays

### Precision and laboratory observables

- Axion haloscopes
- Axion helioscopes
- Light-shining-through-wall experiments
- Atomic clocks
- Magnetometers
- Interferometers
- Fifth-force searches
- Equivalence-principle tests
- Neutron-star or black-hole constraints
- Black-hole superradiance

---

## 16. Existing constraints

The registry should track which constraints apply and how robust they are.

- Excluded regions
- Allowed regions
- Benchmark points
- Controversial parameter regions
- Prior-dependent constraints
- Likelihood availability
- Public data availability
- Public code availability
- Whether recasting is required
- Whether constraints are model-specific or mapped from another model
- Whether constraints depend on astrophysical assumptions
- Whether constraints depend on cosmological assumptions
- Whether constraints are robust, approximate, or disputed

Constraint categories include:

- Relic-density constraints
- BBN constraints
- CMB constraints
- Lyman-alpha constraints
- Satellite-count constraints
- Stellar-stream constraints
- Strong-lensing constraints
- Dwarf-galaxy constraints
- Cluster constraints
- Direct-detection constraints
- Indirect-detection constraints
- Collider constraints
- Laboratory constraints
- Black-hole constraints
- Neutron-star constraints

---

## 17. Allowed parameter ranges and priors

The registry should record both physically allowed ranges and analysis priors.

- Particle mass ranges
- Mediator mass ranges
- Coupling ranges
- Cross-section ranges
- Decay-rate ranges
- Lifetime ranges
- Mixing parameters
- Decay constants
- Temperature ratios
- Relic fraction
- Half-mode mass
- Self-interaction cross section per unit mass
- EFT cutoff scale
- Reheating temperature
- Nuisance parameters

Priors should specify:

- Linear prior
- Log prior
- Literature-informed prior
- Theoretical prior
- Experimentally motivated prior
- Astrophysically motivated prior
- Benchmark grid
- Prior inherited from a previous analysis

---

## 18. Theoretical consistency conditions

These fields prevent the registry from including parameter regions that are theoretically inconsistent.

- Perturbativity
- Unitarity
- Vacuum stability
- Gauge anomaly cancellation
- Absence of ghosts
- Absence of tachyonic instabilities
- EFT validity
- Correct relic abundance or allowed subcomponent abundance
- Cosmological stability
- Lifetime longer than the age of the Universe, if required
- Consistency with BBN
- Consistency with CMB energy injection
- Consistency with structure-formation bounds
- Naturalness or tuning considerations
- Radiative stability
- Validity of classical versus quantum scattering limits

---

## 19. Validity domain

The registry should define where each model description, approximation, emulator, or likelihood is valid.

- Valid mass range
- Valid coupling range
- Valid redshift range
- Valid wavenumber range
- Valid halo-mass range
- Valid host-mass range
- Valid velocity range
- Valid cross-section range
- Linear-regime validity
- Nonlinear-regime calibration
- Simulation calibration domain
- Emulator training domain
- EFT cutoff validity
- Nonrelativistic approximation validity
- Fluid approximation validity
- Classical scattering approximation validity
- Born-regime validity
- Resonant-regime validity

Important questions:

- Is the model being extrapolated beyond its calibration range?
- Is the likelihood valid for this transfer-function shape?
- Is the emulator trained on this parameter space?
- Is the EFT description valid at the relevant energy?
- Is the model mapping only approximate?

---

## 20. Degeneracies and confounders

This is essential for trustworthy scientific inference.

- Baryonic feedback
- Reionization history
- IGM thermal history
- Milky Way mass
- Host-halo mass
- Halo concentration
- Subhalo concentration
- Tidal stripping model
- Disk disruption
- Satellite occupation model
- Star-formation efficiency
- Stellar-stream progenitor properties
- Strong-lens macro-model uncertainty
- Line-of-sight structure
- Detector backgrounds
- Astrophysical foregrounds
- Neutrino mass
- Dark radiation
- Primordial power-spectrum features
- Running of the spectral index
- Warm IGM temperature
- Selection functions
- Survey incompleteness

The registry should explicitly identify which astrophysical or experimental effects could mimic or hide the dark-matter signal.

---

## 21. Computational representation

This describes how the model is evaluated by the system.

- Analytic formula available
- Boltzmann solver required
- Modified CLASS or CAMB required
- N-body simulations required
- Hydrodynamical simulations required
- Semi-analytic model available
- Emulator available
- Likelihood available
- Recasting pipeline available
- Public code available
- Custom initial conditions required
- Custom halo model required
- Custom subhalo model required
- Custom detector response required
- Custom production calculation required

Useful computational questions:

- Can the model be mapped to a small number of effective parameters?
- Can the model use existing CDM simulations with reweighting?
- Does it require new simulations?
- Does it require a transfer-function calculation?
- Does it require a phase-space distribution calculation?
- Does it require expensive likelihood evaluation?
- Is a fast emulator available?

---

## 22. Theory-to-observable routing

This is one of the most important agentic components of the registry. It defines which tools, emulators, likelihoods, or datasets should be invoked for a given model.

Possible routing targets:

- Linear Boltzmann solver
- Transfer-function emulator
- Matter-power-spectrum emulator
- Halo-mass-function emulator
- Subhalo-mass-function emulator
- Concentration-mass relation model
- Lyman-alpha likelihood
- Satellite-count likelihood
- Stellar-stream likelihood
- Strong-lensing substructure likelihood
- CMB likelihood
- Direct-detection rate calculator
- Indirect-detection flux calculator
- Collider recasting module
- Relic-density calculator
- Self-interaction cross-section calculator
- Axion haloscope sensitivity calculator

The registry should specify which routes are mandatory, optional, irrelevant, or invalid for each model.

---

## 23. Assumptions

Every model entry should explicitly record its assumptions.

Examples include:

- Standard cosmological history
- Standard radiation domination
- No late entropy injection
- Dark matter is all of the observed abundance
- Dark matter is only a subcomponent
- Single-component dark matter
- No significant baryonic effects
- Specific reionization model
- Specific IGM thermal history
- Specific Milky Way mass prior
- Specific host-halo mass prior
- Specific halo profile
- Specific subhalo concentration model
- Specific stellar-to-halo mass relation
- Specific direct-detection velocity distribution
- Specific local dark-matter density
- Specific mediator decay assumptions
- Specific branching ratios

This is particularly important because many dark-matter constraints are only valid under specific assumptions.

---

## 24. Provenance and literature status

The registry should track where every claim came from.

- Original model papers
- Review papers
- Main constraint papers
- Public datasets
- Public likelihoods
- Public codes
- Simulation suites
- Benchmark points
- Known disputed interpretations
- Expert-reviewed status
- Last updated date
- Person or agent responsible for update
- Confidence level
- Evidence quality
- Whether the entry has been validated by a domain expert

Provenance fields should make it possible to audit why the agent believes a given model is allowed, excluded, or testable.

---

## 25. Model-comparison metadata

These fields help prioritize models for follow-up.

- Theoretical motivation
- Naturalness
- Minimality
- Explanatory power
- Whether it solves another problem, such as strong CP, neutrino masses, baryogenesis, or hierarchy
- Observational distinctiveness
- Near-term testability
- Compatibility with current data
- Number of independent signatures
- Complementarity across probes
- Degree of tuning
- Degree of novelty
- Community interest
- Availability of public tools
- Suitability for benchmark studies

This allows the system to rank models not only by whether they are allowed, but by whether they are scientifically promising and testable.

---

## 26. Robustness and uncertainty metadata

This tracks how much confidence the system should have in a model assessment.

- Robust constraints
- Approximate constraints
- Recast constraints
- Simulation-dependent constraints
- Prior-dependent constraints
- Astrophysics-dependent constraints
- Cosmology-dependent constraints
- Experiment-background-dependent constraints
- Uncertainty in mapping from model parameters to observables
- Uncertainty in emulator predictions
- Uncertainty in likelihood implementation
- Uncertainty from missing baryonic physics
- Uncertainty from selection functions
- Uncertainty from incomplete literature coverage

This is particularly important for a trustworthy AI system because it prevents the agent from treating weak or assumption-dependent constraints as definitive.

---

## 27. Benchmark points and use cases

Each model should eventually include benchmark parameter points or benchmark regimes.

- Canonical benchmark points
- Allowed benchmark points
- Excluded benchmark points
- Near-future testable benchmark points
- High-priority discovery regimes
- Degenerate benchmark points
- Stress-test benchmark points
- Simulation benchmark points
- Emulator-training benchmark points
- Likelihood-validation benchmark points

Benchmarks are useful for:

- Testing the registry
- Validating agent behavior
- Comparing probes
- Running emulators
- Building demonstrations
- Creating reproducible examples

---

## 28. Failure modes for an agent

The registry should explicitly warn the agent about scientifically dangerous mistakes.

Examples:

- Mapping every suppressed-power model to thermal WDM without checking transfer-function shape
- Treating half-mode mass as sufficient when oscillatory features matter
- Applying Lyman-alpha constraints outside their validity domain
- Ignoring the model dependence of sterile-neutrino momentum distributions
- Combining constraints that assume incompatible cosmologies
- Ignoring whether dark matter is a subcomponent
- Treating direct-detection null results as applicable when the model has no relevant coupling
- Ignoring velocity dependence in self-interacting dark matter
- Applying dwarf-scale constraints to cluster scales without checking velocity dependence
- Confusing decay and annihilation signals
- Ignoring baryonic-feedback degeneracies
- Ignoring Milky Way mass dependence in satellite constraints
- Ignoring line-of-sight halos in strong-lensing analyses
- Ignoring emulator training limits
- Confusing a phenomenological parameterization with a UV-complete theory

This category is crucial for building a trustworthy scientific agent rather than a simple literature summarizer.

---

## 29. Minimal high-priority fields for a first version

For an initial version of the BSM dark-matter theory registry, the most important fields are:

1. Model family
2. Theory level: UV-complete, simplified model, EFT, or phenomenological
3. Particle content
4. Symmetry or stability mechanism
5. Mediator and portal structure
6. Core model parameters
7. Production mechanism
8. Relic-density logic
9. Cosmological-history assumptions
10. Linear matter-power effect
11. Nonlinear halo/subhalo effect
12. Observable signatures
13. Existing constraints
14. Validity domain
15. Degeneracies and confounders
16. Theory-to-observable routing
17. Computational requirements
18. Provenance
19. Robustness/confidence metadata
20. Agent failure-mode warnings

---

## 30. Guiding principle

The registry should not only answer:

> What is this dark-matter model?

It should answer:

> Given this model, what parameters define it, what assumptions make it valid, what observables does it affect, what tools should be run, what constraints apply, and where could an agent make a scientifically dangerous mistake?

This turns the registry from a static taxonomy into the backbone of an agentic dark-matter discovery system.
