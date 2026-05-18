# CCMI CDT Training Course - Deep Learning Theory & Practice 2026

![Build Status](https://github.com/Deep-Learning-Theory-Practice-2026/Course-Materials-Public/workflows/Build%20LaTeX%20Documents/badge.svg)

## Overview

These are the course materials for the one-week CCMI CDT training course on 'Deep Learning Theory & Practice 2026'.

This course provides a comprehensive overview of deep learning theory and its application to inverse problems. The week begins with the fundamentals, covering everything from perceptrons and CNNs to modern training dynamics and the mechanics of backpropagation. It then critically examines the pitfalls of applying these models naively to inverse problems, highlighting issues of stability and data consistency. The curriculum progresses to principled, physics-informed architectures, exploring algorithm unrolling (LISTA, LPD) and bilevel optimisation. The latter half of the course focuses on modularity and advanced generative techniques, including Plug-and-Play (PnP) priors, score-based diffusion models, and the theory connecting them. The week concludes by pushing the concept of network depth to its limits, reframing deep learning as continuous dynamical systems (Neural ODEs) and introducing Deep Equilibrium Models (DEQs) that achieve infinite depth with constant memory.

This repository contains the presentation slides for the course, which are automatically compiled to PDF via GitHub Actions. For more information, please visit the [training week website](https://github.com/CCMI-CDT/deep-learning).

## Contents

- **Slides/**: Presentation slides organised by day
- **Common_Images/**: Shared images and figures for slides

## Getting Started

### Latest Compiled PDFs

Download the latest compiled PDFs from:
- **Actions tab**: [GitHub Actions](https://github.com/Deep-Learning-Theory-Practice-2026/Course-Materials-Public/actions) → Latest workflow run → Artifacts
- **Releases**: [Release section](https://github.com/Deep-Learning-Theory-Practice-2026/Course-Materials-Public/releases)

### Local Compilation

To compile locally, you'll need a LaTeX installation (TeX Live, MacTeX, or MiKTeX).

```bash
# Compile slides
cd Slides/
pdflatex monday.tex 
``` 
 
## License 
 
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](https://creativecommons.org/licenses/by-nc-sa/3.0/). 
 
**In brief**: You are free to share and adapt this material for non-commercial purposes, as long as you provide attribution and distribute your contributions under the same license. See [LICENSE](LICENSE) for full details. 
 
## Contact 
 
For questions, please use the Discord forum or contact the course instructors.