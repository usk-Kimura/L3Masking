# L3Masking
New Masked Language Modeling for Auxiliary tasks

## Overview

`L3Masking` is a new mlm as auxiliary task for effective multi-task fine-tuning. This project is based on the following paper:

**Paper Title**: [L3Masking: Multi-task Fine-tuning for Language Models by Leveraging Lessons Learned from Vanilla Models](https://openreview.net/forum?id=XBlgA9S6sN#discussion)  
**Presented at**: [Customizable NLP Workshop @ EMNLP 2024](https://customnlp4u-24.github.io/)  
**Workshop Date**: November 16, 2024  
**Location**: [Hyatt Regency Miami Hotel, Miami, Florida](https://www.hyatt.com/hyatt-regency/en-US/miarm-hyatt-regency-miami?src=adm_sem_crp_chico_crp_ppc_NAM-UnitedStates-FL-Miami-HR-MIARM_google_Evergreen2022_e_hyatt%20regency%20miami&gad_source=1&gclid=CjwKCAjwmaO4BhAhEiwA5p4YL10TTpJ3DTZo0a_XzENdBLPyE-4bbi81RFDWYGmgaK0MH8RcPaV4nxoCyNYQAvD_BwE)

## Features

- Task and domain adaptation-specific masking
- Masked Token selection based on pseudo-likelihood.

## Installation and Usage

1. Clone the repository:

    ```bash
    git clone git@github.com:usk-Kimura/L3Masking.git
    ```

2. Install the required dependencies:

    ```bash
    cd L3Masking 
    pip install -r requirements.txt
    ```

   CUDA 11.8, Ubuntu 20.04.4 LTS 

3. Run the application:

    ```bash
    bash run_meta_multiple.sh
    ```

## LICENSE
This software includes modifications made by usk-Kimura. 
Original repository: [TARTAN](https://github.com/ldery/TARTAN/tree/main)
Modification date: 12/10/2024

