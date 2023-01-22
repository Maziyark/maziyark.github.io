---
layout: default
title: Cardiac & Vascular Biomechanics
parent: Projects
nav_order: 2
---

# Cardiac & Vascular Biomechanics
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

### CMA
[CMA](https://github.com/mzyrke/CMA): Cardiac Mechanics Analyzer (CMA) is a set of python & MATLAB libraries for image-based analysis of cardiac contractile function through motion analysis, strain calculation, and resolution enhancement: 
- Manuscripts: [Paper 01](https://link.springer.com/chapter/10.1007/978-3-030-78710-3_27)

<p align="center" style="text-align: center;"> 
    Motion of mouse left <a href="https://en.wikipedia.org/wiki/Ventricle_(heart)">ventriclular</a> <a href="https://en.wikipedia.org/wiki/Endocardium">endocardium</a> estimated by deformable image registration of cine-MRI scans
</p> 

<p align="center" style="text-align: center;"> 
    <img src="https://github.com/Maziyark/maziyark.github.io/blob/gh-pages/assets/cine_mri_overlay_displacement_2d.gif?raw=true" alt="Mouse Left Ventricle." class="center"  width="350">
    <img src="https://github.com/Maziyark/maziyark.github.io/blob/gh-pages/assets/Mouse_Left_Ventricle_Endocardium_03.gif?raw=true" alt="Mouse Left Ventricle." class="center"  width="350"> 
    <img src="https://github.com/Maziyark/maziyark.github.io/blob/gh-pages/assets/cine_mri_strains_mouse_lv_3d.gif?raw=true" alt="LV Strains." class="center" width ="800"> 
</p> 

---

### Echo
Toolbox for STE (2D ultrasound) in MATLAB 
<p align="center" style="text-align: center;"> 
    <img src="https://github.com/Maziyark/maziyark.github.io/blob/gh-pages/assets/mk_papers_6_1.png?raw=true" alt="Echo." class="center"  width="600"> 
</p>

- Manuscripts: 

     | [Abstract 01](https://www.ahajournals.org/doi/abs/10.1161/circ.144.suppl_1.14317)  | [Abstract 02](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=59WprqwAAAAJ&sortby=pubdate&citation_for_view=59WprqwAAAAJ:Wp0gIr-vW9MC) | [Abstract 03](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=59WprqwAAAAJ&citation_for_view=59WprqwAAAAJ:YOwf2qJgpHMC) |

---

### AB-FEA 
{: .note-title }
> APhy
>
> The first 3D fully coupled Agent Based - Finite Element Analysis (AB-FEA) modeling framework to study progression of cardiovascular diseases and growth and remodeling in blood vessels:

{: .note-title }
> My note title
>
> A paragraph with a custom title callout

- Packages/software used: Java, REPAST Simphony, ANSYS (APDL), and MATLAB
- Received the [American Heart Association Predoctoral Fellowship](https://professional.heart.org/idc/groups/ahamah-public/@wcm/@sop/@rsch/documents/downloadable/ucm_433355.pdf) + ~ $2 million funding from [NIH](https://projectreporter.nih.gov/project_info_details.cfm?aid=9618585&icde=46505989&ddparam=&ddvalue=&ddsub=&cr=1&csb=default&cs=ASC&pball=) & AHA
- [Project page](https://maziyark.github.io/InSilico_TEVG/) 
- Manuscripts: 

        [Paper 01](https://www.liebertpub.com/doi/full/10.1089/ten.tec.2019.0103) | [Paper 02](https://link.springer.com/article/10.1007/s10237-017-0946-y)  | [Abstract 01](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=59WprqwAAAAJ&citation_for_view=59WprqwAAAAJ:3fE2CSJIrl8C) | [Abstract 02](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=59WprqwAAAAJ&citation_for_view=59WprqwAAAAJ:kNdYIx-mwKoC) | [Abstract 03](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=59WprqwAAAAJ&citation_for_view=59WprqwAAAAJ:Zph67rFs4hoC) | [Abstract 04](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=59WprqwAAAAJ&citation_for_view=59WprqwAAAAJ:ULOm3_A8WrAC)
 
<p align="center" style="text-align: center;">   
    <img src="https://maziyark.github.io/assets/mk_papers_3_1.jpg?raw=true" alt="Schema of Modeling Framework." class="center" style="width: 35vw; min-width: 300px;"> 
</p>
{: .new-title }
> In-Silico Tissue Engineering using AB-FEA
>
> Predicted collagen fiber orientations & stress distributions in a [Tissue Engineered Vascular Graft](https://pubmed.ncbi.nlm.nih.gov/27108525/) under biaxial cyclic loading during 12 weeks of culture. The simulations were prformed using the [AB-FEA](https://maziyark.github.io/docs/Projects/cardiovascular.html#ab-fea) modeling framework.

<p align="center" style="text-align: center;">  
    <img src="https://github.com/Maziyark/InSilico_TEVG/blob/main/BA8C2CF.gif?raw=true" alt="Fiber Orientations" class="center" style="width: 45vw; min-width: 400px;"> 
    <img src="https://github.com/Maziyark/InSilico_TEVG/blob/main/assets/BA8C2StressMP.gif?raw=true" alt="MaxPStress" class="center" style="width: 45vw; min-width: 400px;"> 
</p> 

---

### [DeepIVUS](https://maziyark.github.io/DeepIVUS/) 
A toolbox for analysing VH-IVUS images & comparing baseline & followup images.

- Packages/software used: MATLAB, python

<p align="center" style="text-align: center;">   
    <img src="https://maziyark.github.io/DeepIVUS/assets/B2F.gif?raw=true" alt="VH-IVUS" class="center" style="width: 45vw; min-width: 400px;"> 
</p>

---

### TFM-FEA
[TFM-FEA](https://github.com/mzyrke/TFM_FEA): MATLAB-ANSYS library for calculating the forces that cells exert on their env. using Traction Force Microscopy (TFM)
    - Manuscripts: [Paper 01](https://link.springer.com/article/10.1007/s10439-021-02881-1)
<p align="center" style="text-align: center;">   
    <img src="https://maziyark.github.io/assets/mk_papers_4_1.jpg?raw=true" alt="sample result." class="center" style="width: 35vw; min-width: 200px;"> 
</p>
    
