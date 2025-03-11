# Various scripts for analysing lab data

This repo contains various scripts and notebooks I use when analysing lab data and is intended mainly for members of the [Albanese Lab](https://www.albaneselab.com) but anyone is welcome to use it. 

Note most of this is optimised to work with a specific file output for specific lab set ups. I denote the hardware and software I use to generate data. You're welcome to use any of this code but note it might need to be tweaked for other setups.

This repo is in active developmen and highly subject to change. 

## Circular Dichroism

This CD code enables the uploading of JASCO CD data. I have tested it with TXT files from both J810/5 and J1500. Features:
    - Transform data from CD (mdeg) to Mean residue ellipticity.
    - Plot CD spectra
    - Fit a simple sigmoid function to melting curves to get a prediction of transition temperature should the data allow for it. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chubbj/lab_scripts/blob/main/notebooks/circular_dichroisim_analysis.ipynb)
