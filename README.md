<p align="center">
  <img src="./banner.svg" width="100%" alt="Antonio Sánchez Doña, Biomedical Engineering and Bioinformatics undergraduate, University of Málaga">
</p>

### Hi, I'm Antonio 👋

I'm a Biomedical Engineering and Bioinformatics undergraduate at the University of Málaga (Spain). I've completed the Biomedical Engineering track of the Health Engineering degree and I'm now finishing the Bioinformatics track too, so most of my work lives where medicine, data and software meet: clinical data analysis, machine learning, RNA-seq pipelines and models of physiological systems.

I like projects where the method can be checked: repeated cross-validation instead of a single split, simple baselines to compare against, and results that anyone can reproduce from the repository.

- 📊 Current average grade 8.81/10, with 22 honours grades (*matrícula de honor*) so far.
- 🔬 Working on my final degree project: predicting molecular alterations in lung adenocarcinoma from H&E histology images with pathology foundation models (2026-27, in progress).
- 🎓 Mentor in the ETSI Informática mentoring plan at UMA since 2024, helping new students with maths and with the degree.
- 📜 NVIDIA Deep Learning Institute certificate: *Fundamentals of Accelerated Computing with Modern CUDA C++*.
- 🎹 Outside engineering I'm a pianist: I studied at the conservatory from age 8 to 20, completed the Professional Piano Degree and the first year of the Higher Degree, and received the Extraordinary Award in piano from the Junta de Andalucía, an honours grade (*matrícula de honor*) and the Santa Cecilia award.

---

## 🧬 Projects

### Clinical data and machine learning

| Project | What it does | Tools |
|---|---|---|
| [**Oncology notes classification**](https://github.com/antoniodoa9/clasificacion-notas-oncologicas-pln) | Classifies real anonymised Spanish oncology notes (one neoplasm or several). The best model raises the AUC from 0.733 to 0.827, evaluated with 30-seed repeated cross-validation, permutation tests and nested cross-validation. | Python, spaCy, NLTK, scikit-learn |
| [**Antibiotics and breast cancer response**](https://github.com/antoniodoa9/cancer-mama-respuesta-neoadyuvante) | Studies whether antibiotic use during neoadjuvant chemotherapy affects pathological complete response, from multiple imputation to a predictive model deployed as a web app ([BioCalc](https://antonio-sanchez-uma.shinyapps.io/biocalc/)). | R, Quarto, Shiny |
| [**Diabetes risk screening**](https://github.com/antoniodoa9/diabetes-riesgo-ml) | Screening model on the CDC BRFSS 2015 survey with class imbalance handling, model comparison, interpretability and threshold analysis (ROC-AUC 0.83, recall 0.77). | Python, scikit-learn |
| [**RAG over clinical guidelines**](https://github.com/antoniodoa9/pab-proyecto) | Retrieval-Augmented Generation prototype over a clinical practice guideline with a local LLM, so answers cite the pages they come from and no data leaves the computer. | LangChain, ChromaDB, Ollama |

### Bioinformatics

| Project | What it does | Tools |
|---|---|---|
| [**RNA-seq of *Arabidopsis*: Ler vs C24**](https://github.com/antoniodoa9/arabidopsis-rnaseq-ler-c24) | Full RNA-seq workflow, from raw reads to differentially expressed genes and their functional interpretation ([reports](https://antoniodoa9.github.io/arabidopsis-rnaseq-ler-c24/)). | Galaxy, fastp, kallisto, edgeR, limma-voom, g:Profiler |
| [**Dexamethasone functional analysis**](https://github.com/antoniodoa9/dexametasona-analisis-funcional) | Functional interpretation of the dexamethasone response in airway smooth muscle cells, comparing ORA with GSEA preranked on the MSigDB Hallmark collection. | Python, gseapy |
| [**Aortic dissection network analysis**](https://github.com/antoniodoa9/project_template) | Systems biology group project: from an HPO phenotype to a STRING protein interaction network, its topology, Louvain modules and functional enrichment (in progress). | R, STRINGdb, igraph, clusterProfiler |

### Databases, software and modelling

| Project | What it does | Tools |
|---|---|---|
| [**ChronoHealthDB**](https://github.com/antoniodoa9/ChronoHealthDB) | Longitudinal health record database with privacy by design, where clinical and personal data live apart. Indexing made the patient history query 62 times faster. | MySQL, XML/XQuery, MongoDB, Python |
| [**PK-PD model of propofol anaesthesia**](https://github.com/antoniodoa9/modelo-pkpd-propofol) | Three-compartment pharmacokinetic model with effect site and Hill equation, simulating the BIS of different patients and dosing strategies. | MATLAB, Simulink |
| [**MindVibe**](https://github.com/antoniodoa9/mindvibe) | Concept of an EEG headset that adapts music to the user's emotional state, taken through the whole software engineering lifecycle, with a Spring Boot prototype and a [project website](https://antoniodoa9.github.io/mindvibe/). | Java, Spring Boot, UML |
| [**HealthCalc**](https://github.com/antoniodoa9/healthcalc_ISAgrupo03-Antonio) | Health metrics calculator built step by step with unit testing, BDD, a GUI with MVC, design patterns and refactoring. | Java, Maven, JUnit, Cucumber |

Most repositories are documented in Spanish, with a short English summary at the top.

---

## 🛠 Tools

**Languages**

![Python](https://img.shields.io/badge/Python-5e1f2c?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-5e1f2c?style=flat&logo=r&logoColor=white)
![Java](https://img.shields.io/badge/Java-5e1f2c?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-5e1f2c?style=flat&logo=mysql&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB%20%26%20Simulink-5e1f2c?style=flat&logo=mathworks&logoColor=white)
![C++](https://img.shields.io/badge/C++%20%26%20CUDA-5e1f2c?style=flat&logo=nvidia&logoColor=white)

**Data science and bioinformatics**

![scikit-learn](https://img.shields.io/badge/scikit--learn-5e1f2c?style=flat&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-5e1f2c?style=flat&logo=pandas&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-5e1f2c?style=flat&logo=spacy&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-5e1f2c?style=flat&logo=langchain&logoColor=white)
![Bioconductor](https://img.shields.io/badge/Bioconductor-5e1f2c?style=flat&logo=r&logoColor=white)
![Shiny](https://img.shields.io/badge/Shiny-5e1f2c?style=flat&logo=rstudioide&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-5e1f2c?style=flat&logo=quarto&logoColor=white)
![Galaxy](https://img.shields.io/badge/Galaxy-5e1f2c?style=flat&logo=galaxy&logoColor=white)

**Databases and software**

![MySQL](https://img.shields.io/badge/MySQL-5e1f2c?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-5e1f2c?style=flat&logo=mongodb&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-5e1f2c?style=flat)
![Oracle](https://img.shields.io/badge/Oracle%20SQL-5e1f2c?style=flat&logo=oracle&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-5e1f2c?style=flat&logo=springboot&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-5e1f2c?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-5e1f2c?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-5e1f2c?style=flat&logo=linux&logoColor=white)

---

## 📬 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-antoniodoa9-5e1f2c?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antoniodoa9)
