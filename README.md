# IT: Analisi del livello di stress durante le sessioni d'esami

## Descrizione
Questo progetto raccoglie i file e le cartelle di un lavoro universitario (corso di Econometria) che esplora la relazione tra il livello di stress percepito dagli studenti e alcune variabili come numero di esami sostenuti in una sessione e genere.  
È stata applicata una regressione lineare multipla utilizzando Excel e Python su dati raccolti tramite questionario sottoposto a un campione di 29 studenti.

## Obiettivo
Costruire un modello di regressione lineare multipla per individuare i fattori che influenzano lo stress accademico.  

**Nota**: Il dataset è stato ottenuto tramite questionario, il che può introdurre distorsioni statistiche. Le analisi analisi e le interpretazioni nel report hanno dunque una validità limitata ai fini di eventuali decisioni o policy accademiche.

## Contenuto del repo
- [Report finale (PDF)](https://github.com/krssclaire/regression-model-exams-stress-study/blob/main/report/report_reg_stress-esami.pdf)
- [Notebook Python](https://github.com/krssclaire/regression-model-exams-stress-study/blob/main/notebook/reg-py-stress.ipynb) per visualizzazioni e modelli
- [Grafici generati](https://github.com/krssclaire/regression-model-exams-stress-study/tree/main/img) tramite librerie Python
- [Dataset CSV](https://github.com/krssclaire/regression-model-exams-stress-study/blob/main/dataset/dati-sondaggio-stress.csv) ricavato da un file Excel contenente:
    - i dati completi del questionario
    - i dati filtrati per l'analisi 
    - il modello di regressione lineare multiplo già eseguito per confronto

## Come riprodurre l'analisi
1. Clona il repo
2. Apri lo script `reg-py-stress.py`
3. Esegui il notebook per ottenere grafici e modelli


# ENG: Stress levels during uiversity exam sessions — Regression analysis

## Overview
This repository contains all the materials of a university project (Econometrics course), exploring the relationship between perceived stress levels among students and variables such as the number of exams taken during an exam session and gender.  
A multiple linear regression model was applied using both Excel and Python, based on data collected through a survey submitted to a sample of 29 university students.

## Objective
To build and interpret a multiple linear regression model aimed at identifying the main factors influencing academic stress levels.  

**Disclaimer**: Since the dataset was collected through a survey, a method that can introduce statistical distortions, the analysis and interpretations should be considered **limited statistical reliable** for decision-making or policy implementation.

## Repository content
- [Final Report (PDF)](https://github.com/krssclaire/regression-model-exams-stress-study/blob/main/report/report_reg_stress-esami.pdf)
- [Python Notebook](https://github.com/krssclaire/regression-model-exams-stress-study/blob/main/notebook/reg-py-stress.ipynb) with visualizations and regression modeling
- [Generated graphs](https://github.com/krssclaire/regression-model-exams-stress-study/tree/main/img) using Python libraries
- [CSV Dataset](https://github.com/krssclaire/regression-model-exams-stress-study/tree/main/dataset), exported from Excel and includes:
  - Full raw data from the survey
  - Cleaned and filtered data for analysis
  - A worksheet with the Excel regression model for comparison

## How to reproduce the analysis
1. Clone the repository
2. Open the `reg-py-stress.ipynb` notebook
3. Run all cells to generate visualizations and model outputs