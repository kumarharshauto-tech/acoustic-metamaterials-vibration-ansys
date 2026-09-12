# Acoustic Metamaterials for Vibration Reduction using ANSYS

Fundamental study of acoustic metamaterials for low-frequency vibration reduction in homogeneous rectangular plates using ANSYS-based finite element modelling.

The project investigates whether locally resonant mass-spring structures and dynamic vibration absorbers can reduce vibration in lightweight plate and beam structures, with particular relevance to automotive floor panels and other NVH-sensitive components.

## Project Aim

To investigate fundamental acoustic metamaterial concepts and evaluate their effectiveness in reducing structural vibration in uniform, homogeneous flat plates using simplified modelling techniques and finite element simulation.

## Research Objectives

- Review acoustic metamaterial concepts for low-frequency vibration attenuation
- Investigate simple plate-type and locally resonant designs
- Develop mass-spring and finite element models
- Compare structural behaviour with and without metamaterial inclusions
- Assess changes in natural frequencies and mode shapes
- Investigate the influence of resonator mass, stiffness, spacing and location
- Evaluate vibration attenuation over the low-frequency range of approximately 50–1000 Hz

## Engineering Context

Low-frequency vibration is a major challenge in lightweight engineering structures.

Thin automotive panels, particularly floor and body panels, can transmit vibration from road and powertrain excitation into the passenger compartment. Conventional damping methods can require additional mass and may be less effective at low frequencies.

Acoustic metamaterials offer an alternative approach by using locally resonant structures to modify the dynamic behaviour of the host structure and potentially create attenuation bands.

## Scope of Study

The study focuses on modal and harmonic analysis of:

- Homogeneous aluminium beams
- Thin rectangular aluminium plates
- Structures enhanced with acoustic metamaterial concepts
- Dynamic vibration absorber configurations

The work is simulation-based and does not include physical testing.

## Geometry and Material Definition

### Beam

- Length: 1000 mm
- Width: 20 mm
- Thickness: 2 mm
- Boundary condition: cantilever

### Plate

- Dimensions: 1000 mm × 1000 mm
- Thickness: 2 mm
- Boundary condition: simply supported on all four edges

### Material

Aluminium was used for the baseline structures:

- Young’s modulus: 70 GPa
- Density: 2700 kg/m³
- Poisson’s ratio: 0.33

## Finite Element Modelling

The finite element models were developed in ANSYS Workbench.

The modelling workflow included:

- Geometry definition
- Material-property assignment
- Mesh generation
- Boundary-condition definition
- Modal analysis
- Harmonic-response analysis
- Mesh-refinement studies
- Analytical comparison
- Parameter sensitivity studies

Higher-order solid and shell element formulations were considered for accurate bending-mode prediction in beams and thin plates.

## Model Validation

The finite element model was assessed using:

- Mesh-independence checks
- Boundary-condition verification
- Comparison with analytical vibration theory
- Correlation with published literature

For the simply supported plate, the first-mode natural frequency was reported to agree with the analytical solution within approximately 3%.

## Modal Analysis

Modal analysis was used to determine:

- Natural frequencies
- Mode shapes
- Resonant behaviour of the baseline structures
- Changes introduced by locally resonant structures

For the beam, the analysis considered a frequency range of approximately 1–1000 Hz.

For the plate, the study focused on the first bending modes in the 1–500 Hz range.

## Harmonic Response Analysis

Harmonic-response analysis was used to evaluate forced vibration behaviour across a broad frequency range.

The simulation methodology included:

- A 1 N off-centre harmonic point load
- Frequency sweeps across the low-frequency range
- Frequency-response-function evaluation
- Identification of resonance peaks and anti-resonance regions
- Comparison between baseline and vibration-control configurations

## Parameter Study

The study considered the effect of varying:

- Resonator mass
- Resonator stiffness
- Resonator spacing
- Resonator position
- Spatial distribution

Representative parameter ranges included:

- Resonator mass: 5–50 g
- Resonator stiffness: 100–5000 N/m
- Resonator spacing: 50–200 mm

These parameters were intended to investigate their influence on vibration attenuation, modal behaviour and possible band-gap formation.

## Dynamic Vibration Absorbers

Dynamic vibration absorbers were also considered as mass-spring systems tuned to selected resonant frequencies.

Their placement was based on regions of high modal displacement, with the aim of reducing vibration amplitude at critical frequencies and comparing their behaviour with acoustic metamaterial-based approaches.

## Data Analysis

Simulation data was extracted from ANSYS for comparison and post-processing.

The principal evaluation criteria were:

- Reduction in peak displacement amplitude
- Changes in natural frequencies
- Width and depth of attenuation regions
- Suppression of selected vibration modes
- Comparison of baseline and modified configurations

Frequency-response data was intended to be processed further using Excel for plotting and comparison.

## Automotive Relevance

The work is directly relevant to lightweight automotive structures such as:

- Vehicle floor panels
- Body panels
- Cabin structural panels
- Lightweight NVH-sensitive components

The study explores whether locally resonant structures could offer low-frequency vibration control without relying entirely on conventional mass-based damping treatments.

## Limitations

The dissertation is simulation-based and therefore depends on idealised material properties, boundary conditions and geometric assumptions.

No experimental validation was conducted, so practical implementation would require further physical testing.

## Tools and Methods

- ANSYS Workbench
- Finite Element Analysis
- Modal Analysis
- Harmonic Response Analysis
- Structural Dynamics
- Vibration Analysis
- Acoustic Metamaterials
- Dynamic Vibration Absorbers
- Mass-Spring Modelling
- Mesh Convergence
- Frequency Response Functions
- NVH Engineering

## Project Type

Individual MSc Automotive Engineering dissertation project.
