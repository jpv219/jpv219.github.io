---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education
======
* **Ph.D. in Chemical Engineering**
  - *Imperial College London, London, U.K., 2024 (expected)*
* **M.Sc. in Chemical Engineering Research**
  - *Universidad de Los Andes, Bogotá, Colombia, March 2020*
* **B.Eng. in Chemical Engineering**
  - *Universidad de Los Andes, Bogotá, Colombia, March 2018*

***

# Projects and Research
***

## Hybrid Local-HPC Automation Package for Parallel Simulation
### Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K. (2023-2024)
* Developed Python scripts (HAMPPSterS Repo) to orchestrate the entire CFD cycle in parallel, from local PC setup to post-processing in a remote HPC server.
* Implemented parametric run generator using the psweep library with a DOE LHS sampler.
* Coded main scripts (local and HPC) for job setup, submission, monitoring, convergence checks, and dynamic re-submission.
* Established communication between the remote HPC server and local system using SSHv2 protocol implementation through Paramiko.
* Successfully implemented HAMPPSterS in three parametric studies for mixing devices, generating over 200 DNS runs per study within 4 months.
* Extended HAMPPSterS implementation to various fluid dynamics projects in collaboration with Ph.D. researchers.
* GitHub Repository: [HAMPPSterS](https://github.com/jpv219/HAMPPSterS)

## Deep LSTM RNN Framework for Dispersion Metrics Timeseries Prediction
### Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K. (2023-2024)
* Co-wrote a Python framework for preprocessing and augmenting multivariate timeseries data, training LSTM RNN architectures in PyTorch, and carrying out uncertainty quantification via ensemble perturbation.
* Designed and constructed the framework's overall workflow, recoding the original framework into separate object-oriented scripts.
* Coded raw data processing, cleanup, and packaging scripts for making DNS data suitable for the LSTM model.
* Implemented model hyperparameter tuning through Ray tune.
* GitHub Repository: [LSTMIX](https://github.com/jpv219/LSTMIX)

## DNS of Surfactant-Laden Dispersions in Static Mixers
### Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K. (2021-2022)
* Set up and deployed two-phase DNS simulations of a standard SMX static mixer in an HPC environment using in-house code BLUE.
* Modified pre-built Fortran scripts to generate case studies with complex dispersed phase inlet morphologies and alternative SMX element arrangements.
* Implemented PvPython scripts for automated temporal tracking of drop count, size distribution, interfacial surfactant concentration, and mapping of hydrodynamic features throughout the mixer.
* Authored two papers in Chem. Eng. J. detailing fundamental physical mechanisms and interfacial phenomena.

## Experimental and CFD Analysis of an ESP Handling Complex Liquid Flows
### Department of Chemical Engineering, Universidad de Los Andes, Colombia (2021-2022)
* Set up and deployed non-Newtonian and two-phase CFD simulations of an Electrical Submersible Pump (ESP) using STAR-CCM+.
* Implemented Population Balance Modelling (PBM) algorithms AMuSiG and S-Gamma for drop breakup/coalescence modeling.
* Authored three papers in J. Pet. Sci. Eng. and Chem. Eng. Sci. exploring ESP performance with non-Newtonian single phase and two-phase oil-water flows.
* Collaborated with undergraduate students to build the experimental rig and conducted rheological measurements and Turbiscan Stability Index tests for emulsion systems.

*** 

# Work experience
=======
* *March-October 2023:* **Freelance Technical Writer, Sales Outreach**
  - *Quaisr., London, U.K.*
  - Co-authored 4 technical blogs and developed practical Python-based examples on Smart Maintenance, Design of Experiments and Active Learning, exploring links with AI, simulations, and streaming data. Collaborated with the sales team on email campaigns to generate new business oportunities.

* *January-July 2017:* **Junior R&D Engineer Internship**
  - *QUALA S.A., Bogota, Colombia*
  - Formulated and developed hair mask, styling wax and conditioner prototypes at laboratory scale for commercial brands Nutribela and EGO. Carried out physicochemical characterization (i.e., rheology, pH, drop size distribution) and stability analysis of such prototypes, and assisted in the industrial scale-up tests and process development. 
  - Built product claim support portfolios through lab-scale experiments and scientific literature review.

***

# Academic experience
======
* *May-July 2019:* **Visiting M.Sc. Researcher**
  - *Departamento de Engenharia de Processos (DEPro), Universidade Estadual de Campinas, Brazil*
  - Research stay at UNICAMP Faculty of Chemical Engineering under Prof. Dr. Dirceu Noriler direction. Carried out a coupled CFD-PBM study on two-phase gas-solid risers with commercial softwares STAR-CCM+ and ANSYS Fluent, which was presented at the .

***

# Skills
======
* Coding skills
  * Python (including NumPy, Pandas, scikit-learn, Pytorch, Ray Tune, Seaborn, PvPython)
  * MATLAB
  * High Performance Computing (HPC)
  * Bash/Zsh/Shell
  * Git
  * LaTeX
* Software package
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
======
* *2018-2019:* **Graduate Teaching Assistant**
  * *Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia*
  - Designed a 16 week complementary module for the undergraduate course *”Introduction to Modeling and Simulation in Chemical Engineering”*, including lecture delivery, coursework, assessments and final module project:
    - Designed and taught practical examples in MATLAB showcasing basic matrix operations, linear and non-linear multi-variable solving algorithms, optimization tools and numerical modeling methods for ODE, DAE and PDE systems. 
    - Developed practical coursework on CAD software Autodesk Inventor and on process simulator ASPEN ONE Suite. 
    - Co-designed and constructed the final module project in CFD with commercial software STAR-CCM+, focusing on mixing systems, heat exchangers, and turbomachinery.
  - Students Official Evaluation of the course according to ABET Guidelines: 2018-10 (4.7/5), 2018-20 (4.6/5), 2019-10 (4.91/5), 2019-20 (4.8/5).

* *2018-2019:* **Graduate Teaching Assistant**
  - *Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia*
  - Assisted with lecture delivery, co-designed and marked final module project in CFD with commercial software STAR-CCM+ for the Master's course *"Computational Engineering”* offered by the Department of Chemical Engineering through the GDPP programme.

* *Summer 2018:* **Graduate Teaching Assistant**
  - *Department of Mechanical Engineering, Universidad de Los Andes, Bogota, Colombia*
  - Assisted with tutoring and assessment marking for the course on *CFD applications for Renewable Energy Systems* offered by the School of Mechanical, Aerospace and Civil Engineering (MACE), The University of Manchester.

* *2014-2017:* **Undergraduate Teaching Assistant**
  - *Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia*
  - Assisted with tutoring, assessment, general coursework design and marking for Thermodynamics (2014-2016), Transport Phenomena I (2015), Chemical Reaction Engineering (2016), and Modelling and Simulation in Chemical Engineering (2017).
  
***

# Recognitions and Awards
======
* *March 2020:* **Cum Laude M.Sc. Graduation**: Overall GPA (4.92/5.00) in the top 3% of all Master graduates of the Engineering faculty during the past five years.
**Universidad de Los Andes, Bogota, Colombia**

* *April 2018*: **Best Paper Award**: 3rd World Congress on Momentum, Heat and Mass Transfer (MHMT´18) for the paper titled: ”Experimental and CFD Modelling of the Drift Flux in Two-Phase Air (Non)-Newtonian Slug-Flow Pattern Flow along Horizontal and Inclined Pipelines”
**ICMFHT 18', International ASET, Budapest, Hungary**

* *April 2018*: **Academic Excellence Distinction**: Highest undergraduate semestral GPA (4.89/5.00) during the 2017-2 period in the Chemical Enginnering department.
**Universidad de Los Andes, Bogota, Colombia**

* *March 2018*: **Cum Laude B.Eng. Graduation**: Overall GPA (4.53/5.00) in the top 3% of all graduates of the Engineering faculty during the past five years.
**Universidad de Los Andes, Bogota, Colombia**

* *June 2013*: **Valedictorian Graduation**: Academic Excellence recognition for the highest GPA in the International Baccalaureate (IB) programme.
**The English School, Bogota, Colombia**
