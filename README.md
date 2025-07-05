Note: This tutorial is no longer updated, and is superseded by the iris-hep repository: https://github.com/iris-hep/NSBI-workflow-tutorial
--

# Neural Simulation-Based Inference Workflow demonstration

The notebooks presented here aim to serve as a scaled-down and simplified tutorial for the workflow building related to the NSBI analysis recently published by ATLAS:

<br/>

- An implementation of neural simulation-based inference for parameter estimation in ATLAS (https://arxiv.org/pdf/2412.01600)
  
<br/>

- Measurement of off-shell Higgs boson production in the $H\to ZZ \to 4\ell$ decay channel using a neural simulation-based inference technique in 13 TeV p-p collisions with the ATLAS detector (https://arxiv.org/pdf/2412.01548)

<br/>
<br/>

![NLL_PE_ExpOnly_PEHist_Comp](https://github.com/user-attachments/assets/5aba909b-efc5-4a66-b171-9aa2c8c4d6f4) ![NLL_PE_ObsExp_StatSyst_Comp](https://github.com/user-attachments/assets/3c518b0b-90cb-4bcc-8830-a2783777010f)

<br/>
<br/>

The aim is to demonstrate the workflow associated with a full-scale LHC analysis. The physics results presented in the notebooks only serve as examples of the workflow.

**Note: The tutorial is a significantly scaled down and incomplete version of the original workflow. More complete versions will follow!**

The workflow currently uses the ttbar open data released by CMS, more open datasets will be added in the future. A more complete version with systematic uncertainties and ensemble training will also be added.

## Building a general toolkit for NSBI at the LHC (Work in Progress)

Workflow bluprint (**tentative**):

![NSBI_flowchart](https://github.com/user-attachments/assets/98c6ebbe-c9d2-49fb-bc98-2b8f3b27b1e1)

## Acknowledgements

[![NSF-1836650](https://img.shields.io/badge/NSF-1836650-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1836650)
[![PHY-2323298](https://img.shields.io/badge/PHY-2323298-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=2323298)

This work is being supported by the U.S. National Science Foundation (NSF) cooperative agreements [OAC-1836650](https://nsf.gov/awardsearch/showAward?AWD_ID=1836650) and [PHY-2323298](https://nsf.gov/awardsearch/showAward?AWD_ID=2323298) (IRIS-HEP).


