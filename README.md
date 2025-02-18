# Kinetic Modeling in PET Imaging 
## Overview:
This project implements kinetic modeling of PET imaging data, focusing on:
1. Processing time-activity curves (TACs) to quantify radiotracer uptake in different regions.
2. Fitting kinetic models to estimate rate constants and clearance values.
3. Performing statistical analysis to assess the reliability of extracted parameters.
## Introduction
Adenosine A2A and dopamine D2 receptors in the basal ganglia form heterotetrameric complexes, which play a crucial role in motor control and neuropsychiatric functions. Dysregulation of these receptor interactions is implicated in disorders such as Parkinson’s disease and schizophrenia.

This study investigates how A2A receptor activation affects D2 receptor binding in vivo, using positron emission tomography (PET) imaging with [11C]raclopride, a selective D2 receptor antagonist tracer.

Study Design
Animal Model: Healthy male Wistar rats (n = 8).
PET Imaging: Dynamic [11C]raclopride PET scans (60 min) at baseline and post-treatment.
Pharmacological Intervention: Acute administration of the A2A receptor agonist CGS21680 (1 mg/kg).
Kinetic Modeling Approaches:
Simplified Reference Tissue Model (SRTM): Used cerebellum as the reference tissue to calculate nondisplaceable binding potential (BPND).
Two-Tissue Compartment Model (2TCM): Estimated BPND from k3/k4 ratio and striatum/cerebellum volume of distribution ratio (DVR).
Key Findings
1. No significant changes in BPND were observed using SRTM (p = 0.102).
2. CGS21680 increased the parent fraction of [11C]raclopride in plasma (p = 0.0001).
3. Compartment modeling showed a significant reduction in the k3/k4 ratio (p < 0.01) after CGS21680 treatment, suggesting altered receptor availability.
4. The A2A antagonist KW6002 had no significant effect on D2 receptor binding.
This analysis demonstrates that A2A receptor activation may reduce D2 receptor availability, providing insight into the complex A2A-D2 receptor interactions in the striatum.
## Data & Methods
🔹 Data Description
Source: PET imaging time-activity curve (TAC) data from different brain regions.
Processing: Extracted TACs were analyzed to calculate radiotracer kinetics and clearance rates.
🔹 Analysis Methods
Time-Activity Curve Processing – Extracted TAC data to track radiotracer kinetics over time.
Kinetic Modeling – Applied compartmental modeling to estimate rate constants for tracer distribution.
## Results
1. ![image](https://github.com/user-attachments/assets/8cbb9c39-ec1a-4f2d-a65f-7a92aaf15f8e)
2. 

Statistical Analysis – Performed correlation analysis and curve fitting to validate kinetic parameters.
Visualization – Generated line plots, scatter plots, and residual analysis using Matplotlib & Seaborn.
