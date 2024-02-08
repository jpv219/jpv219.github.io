---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

***
# Education
***

## Ph.D. in Chemical Engineering
*Imperial College London, London, U.K. (Expected 2024)*
  
## M.Sc. in Chemical Engineering Research
*Universidad de Los Andes, Bogotá, Colombia (March 2020)*

## B.Eng. in Chemical Engineering
*Universidad de Los Andes, Bogotá, Colombia (March 2018)*

***

# Projects and Research
***

## ❖ Hybrid Local-HPC automation package for parallel simulation run, monitoring, and post-processing
### Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K. (2023-2024)
* Spearheaded the creation of the HAMPPSterS Python repository from the ground up, in collaboration with two PhD colleagues, to enable parallelized orchestration of the entire CFD cycle for in-house DNS simulations in a hybrid remote HPC<->local PC environment. The repo fully automates and streamlines repetitive manual tasks carried out by fellow researchers, increasing the number of concurrent simulations five-fold and decreasing simulation run wait time by half. These tasks include: remote job setup, submission and status monitoring, scheduled convergence checks, dynamic re-submission based on custom, case-specific stopping criteria and data conversion, to local data download and subsequent PvPython post-processing.
* Developed a generic parametric run generator script using Python library psweep, with a physics-constrained DOE Latin Hypercube sampler embedded to initialize in parallel each simulation's run lifecycle for any type of set-up.
* Developed a communication system between the remote HPC server and local system using a SSHv2 protocol implementation through Paramiko, eliminating the need to keep a continuously active HPC user session, thus decreasing load in the HPC user-shared nodes.
* Successfully implemented HAMPPSterS in numerous projects in collaboration with Ph.D. researchers from my group, namely three parametric studies for mixing devices, as well as a fundamental investigation on interfacial oscillations, generating over 200 DNS runs per study within 2-4 months.
* GitHub Repository: [HAMPPSterS](https://github.com/jpv219/HAMPPSterS)

## ❖ Deep LSTM RNN framework for multivariate multistep time-series prediction
### Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K. (2023-2024)
* Co-wrote a novel multi-step PyTorch LSTM framework for mixing performance prediction, adept at handling multi-feature time-series inputs with varying feature dimensions per time-step. This capability circumvents the need for uniform feature dimensions, addressing traditional LSTM networks' limitations.
* Designed and constructed the framework's overall workflow, revamping the original code into separate object-oriented scripts for raw data pre-processing and clean-up, data augmentationm packaging and model training, hyperparameter tuning, and rollout predictions and visualization, enhancing its generalisation capability and improving overall code maintainability.
* Implemented L1/L2 regularisation methods, learning rate scheduling and early stopping algorithms to mitigate overfitting and guarantee high predictive accuracy with deviations under 20% on average.
* Co-wrote a parallelised hyperparameter tuning script with Ray Tune, exploring over 2000 possible configurations for different network architectures, finding best-performing models with a 75% lower MSE.
* GitHub Repository: [LSTMIX](https://github.com/jpv219/LSTMIX)
* Findings were disseminated orally at the 76th Annual meeting of the APS Division of Fluid Mechanics (2023) in Washington D.C., U.S..

## ❖ DNS of Surfactant-Laden Dispersions in Static Mixers
### Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K. (2021-2022)
* Set up and deployed high fidelity two-phase simulations of a SMX static mixer in a HPC environment using an in-house, massively parallelized DNS code. The results generated unveiled novel insights into the fundamental governing mechanisms and interfacial phenomena unfolding during the dispersion process.
* Executed comprehensive statistical data analysis with MATLAB to uncover novel functional relationships between the surfactant's physicochemical nature and different dispersion performance metrics.
* Modified and adapted pre-built Fortran and Shell scripts to generate the complex case studies explored throughout this project.
* Wrote and implemented PvPython scripts to automate the extraction of key temporal interfacial metrics (e.g., drop count and sizes), alongside computing and mapping relevant hydrodynamic features throughout the mixer, thus expediting data extraction and effectively tackling the challenge of post-processing significantly heavy datasets, commonly exceeding 0.5 TB per case.
* Published the results gathered in two papers in Chem. Eng. J. detailing two complex, industrially relavant scenarios: complex inlet morphologies and surfactant-laden systems.
* Results were presented orally at the AIChE annual meetings (2022-2023) in Phoenix and Orlando, U.S., respetively, the ECCOMAS Congress (2022) in Oslo, Norway, the 11th International Conference of Multiphase Flow (2023) in Kobe, Japan, and the 74th and 75th editions of the APS DFD in Phoenix and Indianapolis, U.S., respectively.

## ❖ Experimental and CFD Analysis of an ESP Handling Complex Liquid Flows
### Department of Chemical Engineering, Universidad de Los Andes, Colombia (2018-2020)
* Set-up and deployed non-Newtonian and two-phase CFD simulations of an Electrical Submersible Pump (ESP) using commercial software STAR-CCM+, carrying out the entire CFD lifecycle, from geometry construction and clean-up in Autodesk Inventor, to mesh generation, physics model and solver setup, and post-processing.
* Implemented newly released Population Balance Modelling (PBM) algorithms AMuSiG and S-Gamma to model drop breakup/coalescence, a first on ESPs handling complex emulsion flows. The framework's performance was compared against traditional Eulerian segregated flow and VOF approaches, outperforming such models in most cases with a <15\% deviation.
* Led, trained and managed a team of 4 students in the construction and operation of the experimental rig used for the project. Designed a 16 week work plan and coordinated shifts to efficiently collect rheological, drop size distribution, and Turbiscan Stability Index measurements for the emulsion systems tested throughout the project. 
* Published the results of this project in three papers in J. Pet. Sci. Eng. and Chem. Eng. Sci., revealing insights between hydraulic loss mechanisms and complex flow properties which can be leveraged for real-life geometry and operation optimsation.
* Findings were disseminated at the 10th International Conference of Multiphase Flow (2019) in Rio de Janeiro, Brazil.

*** 

# Work Experience
***

## ❖ Technical Writer and Sales Outreach
### Quaisr., London, U.K. (March-October 2023)
* Co-authored 4 technical blogs and developed practical Python-based examples on Smart Maintenance, Design of Experiments, and Active Learning, exploring links with AI, simulations, and streaming data.
* Led a targeted email outreach campaign to senior scientists in top pharma companies, strategically aligning Quaisr's platform capabilities with their research fields to generate leads for potential clients.

## ❖ Personal Care R&D Junior Engineer
### QUALA S.A., Bogota, Colombia (January-July 2017)
* Formulated and characterised lab-scale prototypes to accelerate industrial scale-up, reducing time to market by 6 months for several lines within the #1 grossing hair care brand in Latin America at the time.
* Conducted physicochemical characterization (e.g., rheology, pH, drop size distribution) and stability analysis of prototypes.
* Built product claim support portfolios through lab-scale experiments and scientific literature review, expediting marketing campaigns and improving customer product perception in subsequent field surveys.

***

# Academic Experience
***

## ❖ Visiting M.Sc. Researcher
### Departamento de Engenharia de Processos (DEPro), Universidade Estadual de Campinas, Brazil (May-July 2019)
* Conducted a coupled CFD-PBM study on two-phase gas-solid risers using commercial software STAR-CCM+ and ANSYS Fluent under Prof. Dr. Dirceu Noriler's supervision.
* Research findings were presented at the XXXIX Brazilian Congress of Particulate Systems, ENEMP 2019, Belem-Para, Brazil.

***

# Skills
***

* Coding skills
  * Python (including NumPy, Pandas, scikit-learn, Pytorch, Ray Tune, Seaborn, PvPython)
  * MATLAB
  * High Performance Computing (HPC) environment
  * Linux environment
  * Bash/Zsh/Shell
  * Git
  * LaTeX
* Software packages
  * Paraview
  * Siemens STAR-CCM+
  * Autodesk Inventor
  * Aspen ONE Suite (Plus, Hysys)
  * Excel
* Soft Skills
  * Leadership
  * Project management
  * Teamwork
  * Scientific communication
  * Critical thinking
  * Problem Solving
* Languages
  * Spanish (Native)
  * English (Fluent)

***

# Teaching experience
***

## ❖ Graduate Teaching Assistant
### Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia (2018-2019)
* Designed a 16-week complementary module for the undergraduate course *”Introduction to Modeling and Simulation in Chemical Engineering”*, which was set as the template for subsequent years. This included lecture delivery, coursework, assessments, and a final module project.
  * Designed and taught practical examples in MATLAB showcasing basic matrix operations, linear and non-linear multi-variable solving algorithms, optimization tools, and numerical modeling methods for ODE and PDE systems.
  * Developed practical coursework on CAD software Autodesk Inventor and on process simulator ASPEN ONE Suite.
  * Co-designed and constructed the final module project in CFD with commercial software STAR-CCM+, focusing on mixing systems, heat exchangers, and turbomachinery.
* Elevated student survey scores by around 18% compared to previous years and maintained them throughout my tenure: 2018-10 (4.7/5), 2018-20 (4.6/5), 2019-10 (4.91/5), and 2019-20 (4.8/5).
* Led, trained and managed a group of 4 undergraduate teaching assistants each semester to assist with mentoring, coursework grading and project guidance.
* Collaborated in re-structuring the main module through a Project-Based Learning (PBL) approach, achieving 85\% positive feedback from students and featuring a publication in *Edu. Chem. Eng.* [Ballesteros et al. (2018)](https://www.sciencedirect.com/science/article/pii/S1749772818300496)

## ❖ Graduate Teaching Assistant
### Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia (2018-2019)
* Assisted with lecture delivery, co-designed, and marked the final module project in CFD with commercial software STAR-CCM+ for the Master's course *"Computational Engineering”* offered by the Department of Chemical Engineering through the GDPP program.

## ❖ Summer 2018: Graduate Teaching Assistant
### Department of Mechanical Engineering, Universidad de Los Andes, Bogota, Colombia
* Assisted with tutoring and assessment marking for the course on *CFD applications for Renewable Energy Systems* offered by the School of Mechanical, Aerospace and Civil Engineering (MACE), The University of Manchester.

## ❖ Undergraduate Teaching Assistant
### Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia (2014-2017)
* Selected for outstanding academic performance in each module, assisted with tutoring, general coursework design, and marking for the following courses:
  - Thermodynamics (2014-2016)
  - Transport Phenomena I (2015)
  - Chemical Reaction Engineering (2016)
  - Modelling and Simulation in Chemical Engineering (2017)
* Introduced the first VBA-based mini-project in Thermodynamics (2014) to solve Real Gas Equations of State (EoS).

***

# Recognitions and Awards
***
## ❖ 2020-2024: PhD Scholarship from the Science and Innovation Ministry MINCIENCIAS
### MINCIENCIAS, Colombia
* Recipient of the "PhD Abroad Scholarship" awarded annually by the Colombian Government to 300 students nationwide. Funding totalling approximately £80,000.
## ❖ March 2022: STEM FOR BRITAIN 22' Finalist
### The Parliamentary & Scientific Committee, London, U.K.
* Shortlisted from hundreds of applicants throughout the UK to attend the prestigious poster event STEM FOR BRITAIN 22', held at the Houses of Parliament.

## ❖ March 2020: Cum Laude M.Sc. Graduation
### Universidad de Los Andes, Bogota, Colombia
* Overall GPA (4.92/5.00) in the top 3% of all Master graduates of the Engineering faculty during the past five years.

## ❖ April 2018: Best Paper Award
### 3rd World Congress on Momentum, Heat and Mass Transfer (MHMT´18), International ASET, Budapest, Hungary
* Paper titled: ”Experimental and CFD Modelling of the Drift Flux in Two-Phase Air (Non)-Newtonian Slug-Flow Pattern Flow along Horizontal and Inclined Pipelines”

## ❖ April 2018: Academic Excellence Distinction
### Universidad de Los Andes, Bogota, Colombia
* Highest undergraduate semestral GPA (4.89/5.00) during the 2017-2 period in the Chemical Engineering department.

## ❖ March 2018: Cum Laude B.Eng. Graduation
### Universidad de Los Andes, Bogota, Colombia
* Overall GPA (4.53/5.00) in the top 3% of all graduates of the Engineering faculty during the past five years.

## ❖ June 2013: Valedictorian Graduation
### The English School, Bogota, Colombia
* Academic Excellence recognition for the highest GPA in the International Baccalaureate (IB) programme (Final IB Score = 36/45).

# Extracurricular Activities
***
## ❖ Imperial College London Men's Squash 1st Team
### Imperial College London, U.K. (2022-2024)
* 3rd seeded player and Team Captain for the 23/24 season. 23' LUSL Cup Champions

## ❖ Uniandes Men's Squash Team
### Universidad de Los Andes, Colombia (2015-2019)
* Elite category squash player. 3X Bogota University League (CERROS) champions (2017-2019).