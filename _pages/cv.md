---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D.** in Chemical Engineering, <i>Imperial College London, London, U.K.<i>, 2024 (expected)
* **M.Sc.** in Chemical Engineering Research, <i>Universidad de Los Andes, Bogotá, Colombia<i>, March 2020
* **B.Eng.** in Chemical Engineering, <i>Universidad de Los Andes, Bogotá, Colombia<i>, March 2018


Work experience
======
* <i>March-October 2023<i>: Freelance Technical Writer, Sales Outreach
  * **Quaisr., U.K.**
  Co-authored 4 technical blogs and developed practical Python-based examples on Smart Maintenance, Design of Experiments and Active Learning, exploring links with AI, simulations, and streaming data. Collaborated with the sales team on email campaigns to generate new business oportunities.

* <i>January-July 2017<i>: Junior R&D Engineer Internship
  * **QUALA S.A., Colombia**
  * Formulated and developed hair mask, styling wax and conditioner prototypes at laboratory scale for commercial brands Nutribela and EGO. Carried out physicochemical characterization (i.e., rheology, pH, drop size distribution) and stability analysis of such prototypes, and assisted in the industrial scale-up tests and process development. 
  * Built product claim support portfolios through lab-scale experiments and scientific literature review.

Academic experience
======
* <i>May-July 2019<i>: Visiting M.Sc. researcher
  * **Departamento de Engenharia de Processos (DEPro), Universidade Estadual de Campinas, Brazil**
  Research stay at UNICAMP Faculty of Chemical Engineering under Prof. Dr. Dirceu Noriler direction. Carried out a coupled CFD-PBM study on two-phase gas-solid risers with commercial softwares STAR-CCM+ and ANSYS Fluent, which was presented at the .

Projects and Research
======
* <i>2023-2024<i>: Hybrid Local-HPC automation package for parallel simulation run, monitoring, and post-processing
  * **Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K.**
  Developed a set of Python scripts (HAMPPSterS Repo) from the ground up to orchestrate in parallel, from a local PC, the entire CFD cycle: from setup, submission, monitoring, re-submission and conversion of DNS simulations in a remote HPC server, to download and post-processing in a local PC.
   * Wrote a parametric run generator using library psweep with a DOE LHS sampler embedded to initialize in parallel each simulation run lifecycle.
   * Coded two main scripts (local and HPC) to handle all essential procedures, such as job set-up and submission, status monitoring, convergence checks and dynamic re-submission when needed based on customizable stopping criteria, file conversion and download to local PC and PvPython post-processing. 
   * Developed a communication system between the remote HPC server and local system using a SSHv2 protocol implementation through Paramiko without the need to keep an HPC user session active.
   * Successfully implemented HAMPPSterS in three parametric studies for mixing devices, generating over 200 DNS runs per study within 4 months.
   * Successfully extended the implementation of HAMPPSterS to various fluid dynamics projects in collaboration with Ph.D. researchers from Matar Fluid's Group.
   * GitHub Repository HAMPPSterS is available here.

* <i>2023-2024<i>: Deep LSTM RNN framework for dispersion metrics timeseries prediction
  * **Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K.**
  Co-wrote a Python framework to pre-process and augment multivariate timeseries data, train and carry out predictions with different Long Short Term Memory (LSTM) Recurrent Neural Network (RNN) architectures in PyTorch, and carry out uncertainty quantification via ensemble perturbation.
    * Designed and constructed the framework's overall workflow, re-coding the original framework into separate object-oriented scripts for data pre-processing, data augmentation and model training, hyperparameter tuning, and rollout predictions and visualization.
    * Coded from scratch raw data processing, clean-up and packaging scripts to make DNS data suitable for the LSTM model, as well as model hyperparameter tuning through Ray tune.
    * GitHub Repository LSTMIX is available here.

* <i>2021-2022<i>: DNS of surfactant-laden dispersions in static mixers
  * **Matar Fluids Group, Department of Chemical Engineering, Imperial College London, U.K.**
  Set up and deployed two-phase DNS simulations of a standard SMX static mixer in a High Performance Computing (HPC) environment. Simulations were carried out using in-house code BLUE developed by collaborators from LISN-CNRS, France and Hongik University, South Korea.
    * Modified pre-built Fortran scripts to generate all case studies considered throughout the project: complex dispersed phase inlet morphologies (i.e., multi-drop or jet inlet) and alternative SMX element arrangements.
    * Wrote and implemented PvPython scripts to automate temporal tracking of drop count, size distribution and interfacial surfactant concentration, as well as map spatially key hydrodynamic features throughout the mixer (i.e., velocity, pressure, flow topology, stretching efficiency).
    * Authored two papers in Chem. Eng. J. detailing the fundamental physical mechanisms and interfacial phenomena governing the dispersion dynamics of SMX mixers when handling complex inlet morphologies and surfactant-laden systems.

* <i>2021-2022<i>: Experimental and CFD analysis of an ESP handling complex liquid flows
  * **Department of Chemical Engineering, Universidad de Los Andes, Colombia**
  Set-up and deployed non-Newtonian and two-phase CFD simulations of an Electrical Submersible Pump (ESP) using commercial software STAR-CCM+. Carried out the entire CFD lifecycle, from geometry construction and clean-up in Autodesk Inventor, to mesh generation, physics model setup, and post-processing.
    * Implemented newly released Population Balance Modelling (PBM) algorithms AMuSiG and S-Gamma to model drop breakup/coalescence, and compared them against Eulerian multiphase segregated flow and VOF frameworks.
    * Authored three papers in J. Pet. Sci. Eng. and Chem. Eng. Sci. exploring the performance and internal flow dynamics of the ESP when handling non-Newtonian single phase flows and two-phase oil-water flows, comparing it with experimental measurements.
    * Collaborated with undergraduate students to build the experimental rig used for the project. Carried out rheological, drop size distribution and Turbiscan Stability Index measurements for the emulsion systems tested in the ESP. 


Skills
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

Teaching experience
======
* <i>2018-2019 <i>: Graduate Teaching Assistant
  * **Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia**
  Designed a 16 week complementary module for the undergraduate course <i>”Introduction to Modeling and Simulation in Chemical Engineering”<i>, including lecture delivery, coursework, assessments and final module project:
    * Designed and taught practical examples in MATLAB showcasing basic matrix operations, linear and non-linear multi-variable solving algorithms, optimization tools and numerical modeling methods for ODE, DAE and PDE systems. 
    * Developed practical coursework on CAD software Autodesk Inventor and on process simulator ASPEN ONE Suite. 
    * Co-designed and constructed the final module project in CFD with commercial software STAR-CCM+, focusing on mixing systems, heat exchangers, and turbomachinery.
  Students Official Evaluation of the course according to ABET Guidelines: 2018-10 (4.7/5), 2018-20 (4.6/5), 2019-10 (4.91/5), 2019-20 (4.8/5).

* <i>2018-2019 <i>: Graduate Teaching Assistant
  * **Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia**
  Assisted with lecture delivery, co-designed and marked final module project in CFD with commercial software STAR-CCM+ for the Master's course <i> "Computational Engineering” <i> offered by the Department of Chemical Engineering through the GDPP programme.

* <i>Summer 2018 <i>: Graduate Teaching Assistant
  * **Department of Mechanical Engineering, Universidad de Los Andes, Bogota, Colombia**
  Assisted with tutoring and assessment marking for the course on <i> CFD applications for Renewable Energy Systems <i> offered by the School of Mechanical, Aerospace and Civil Engineering (MACE), The University of Manchester.

* <i>2014-2017<i>: Undergraduate Teaching Assistant
  * **Department of Chemical Engineering, Universidad de Los Andes, Bogota, Colombia**
  Assisted with tutoring, assessment, general coursework design and marking for Thermodynamics (2014-2016), Transport Phenomena I (2015), Chemical Reaction Engineering (2016), and Modelling and Simulation in Chemical Engineering (2017).
  
Recognitions and Awards
======
* <i>March 2020<i>: Cum Laude M.Sc. Graduation: Overall GPA (4.92/5.00) in the top 3% of all Master graduates of the Engineering faculty during the past five years.
**Universidad de Los Andes, Bogota, Colombia**

* <i>April 2018<i>: Best Paper Award: 3rd World Congress on Momentum, Heat and Mass Transfer (MHMT´18) for the paper titled: ”Experimental and CFD Modelling of the Drift Flux in Two-Phase Air (Non)-Newtonian Slug-Flow Pattern Flow along Horizontal and Inclined Pipelines”
**ICMFHT 18', International ASET, Budapest, Hungary**

* <i>April 2018<i>: Academic Excellence Distinction: Highest undergraduate semestral GPA (4.89/5.00) during the 2017-2 period in the Chemical Enginnering department.
**Universidad de Los Andes, Bogota, Colombia**

* <i>March 2018<i>: Cum Laude B.Eng. Graduation: Overall GPA (4.53/5.00) in the top 3% of all graduates of the Engineering faculty during the past five years.
**Universidad de Los Andes, Bogota, Colombia**

* <i>June 2013<i>: Valedictorian Graduation: Academic Excellence recognition for the highest GPA in the International Baccalaureate (IB) programme.
**The English School, Bogota, Colombia**
