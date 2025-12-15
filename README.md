# Roberto's GitHub repositories
Here's an overview of the repos I worked on during my PhD in the group :D 

Structuring GitHub repositories: 
+ [projthis](https://ijlyttle.github.io/projthis/articles/projthis.html) (R).
+ projthis-inspired setups (python)

The **StressRegNet** consortium includes the following people:   
+ me
+ Christian L. Müller
+ Martin K. Amstalden
+ Annamaria Zannoni
+ Cynthia Sharma
+ Ana Rita Brochado.   


## **MolE**

📝 **Manuscript:** [Pre-trained molecular representations enable antimicrobial discovery](https://www.nature.com/articles/s41467-025-58804-4)

🤝 **Collaborators:** The StressRegNet consortium, and Mina Rezaei

🔹 Contains necessary code and data to pre-train a molecular representation using the MolE framework.  
🔹 Fine-tune the pre-trained weights on a specific benchmark molecular property prediction task.  
🔹 Train a Machine Learning model (XGBoost or Random Forest) using the static pre-trained representation on a specific benchmark task.  
🔹 Gather the static pre-trained representation for any set of molecules.  

📊 **Available at:**
+ https://github.com/bio-datascience/MolE
+ https://huggingface.co/collections/virtual-human-chc/mole

## **MolE - Antimicrobial Potential**

📝 **Manuscript:** [Pre-trained molecular representations enable antimicrobial discovery](https://www.nature.com/articles/s41467-025-58804-4)

🤝 **Collaborators:** The StressRegNet consortium, and Mina Rezaei

🔹 We use MolE's pre-trained representation to train XGBoost models to predict the antimicrobial activity of compounds based on their molecular structure. This repository contains all of the scripts and data used to obtain the results presented in our paper.  
🔹 You can obtain MolE's pre-trained representation for your own set of molecules using the `mole_representation.py` script.  
🔹 You can make predictions of the antimicrobial activity for your collection of molecules using the `mole_antimicrobial_prediction.py` script.    

📊 **Available at:**
+ https://github.com/bio-datascience/mole_antimicrobial_potential
+ https://huggingface.co/collections/virtual-human-chc/mole

## DGrowthR  

📝 **Manuscript:** [Statistical end-to-end analysis of large-scale microbial growth data with DGrowthR](https://www.biorxiv.org/content/10.1101/2025.03.25.645164v2)

🤝 **Collaborators:** Medina Feldl (co-first author), Stefanie Peschel, The StressRegNet consortium  

🔹 This repository contains the code for the DGrowthR package.  
🔹 It also contains the workflow followed for the analysis of public datasets. 

📊 **Available at:**  
+ https://github.com/bio-datascience/DGrowthR

## Modeling a chemical-genetic screen in _Escherichia coli_  

📝 **Manuscript:** [Systematic screen uncovers regulator contributions to chemical cues in Escherichia coli](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3003260)

🤝 **Collaborators:** Mara Stadler, Christoph Binsfeld, Ana Rita Brochado

🔹 Code for analyzing data from publication Binsfeld et al, PLOS Biology, 2025.  
🔹 Our contribution starts at pre-processing CPI scores up to modeling with HierNet.

📊 **Available at:**  
+ https://github.com/bio-datascience/ecoli_regulator_screen_binsfeld25
+ https://zenodo.org/records/15600688

## Exploring Pathogenex the dataset (Shiny App)  

🤝 **Collaborators:** The StressRegNet consortium, Susanne Brenzinger  

🔹 This dashboard enables the user to explore differential expression patterns for _Campylobacter jejuni_ and _Salmonella enterica_ Typhimurium in the Pathogenex dataset.

📊 **Available at:**  
+ https://github.com/rolayoalarcon/reporter_app_de

## StressRegNet (Private)  

📝 **Manuscript(s):** In preparation

🤝 **Collaborators:** The StressRegNet consortium (of course)

🔹 These repositories contain the workflow followed to analyse the data from the StressRegNet screening.
🔹 These steps include pre-processing, quality control, expression estimation, and hit detection.

📊 **Available at:**  
+ https://github.com/rolayoalarcon/salmonella_stressregnet
+ https://github.com/rolayoalarcon/campylobacter_stressregnet

**Shiny apps:**
+ https://github.com/rolayoalarcon/salmonella_srn_dashboard
+ https://github.com/rolayoalarcon/campylobacter_srn_dashboard

## MolE + Microbial representations (Private)

📝 **Manuscript(s):** In preparation

🤝 **Collaborators:** Daniele Pugno

🔹 Code to obtain microbial representations for species in the Maier dataset.  
🔹 Testing different combinations of molecular and microbial representations for their predictive benefit.

📊 **Available at:**  
+ https://github.com/rolayoalarcon/maier_udl

## **Host - microbiome interactions** (Private)

📝 **Manuscript:** [RNF43 is a gatekeeper for colitis-associated cancer](https://www.biorxiv.org/content/10.1101/2024.01.30.577936v1)

🤝 **Collaborators:** Alisa Dietl, Mara Stadler

🔹 Analyzes microbiome (16S), RNA-seq, histological, and clinical data from a mouse study on CRC and IBD.  
🔹 Methods include DA testing, DE analysis, MDS, mixedCCA, log-contrast regression, and latent correlation.

📊 **Available at:**  
+ https://github.com/bio-datascience/host_microbiome

## Metric learning on molecular representations (Private)

🤝 **Collaborators:** Christoph Binsfeld, Ana Rita Brochado

🔹 Code applying different metric learning techniques to ECFP4 representations on the Binsfeld dataset.  
🔹 Imputation of out-of-sample compound's effect on gene expression.

📊 **Available at:**  
+ https://github.com/rolayoalarcon/chemical_analysis
