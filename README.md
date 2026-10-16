# 📊 U.S. Gun Violence Data Analysis: Lethality & Incident Characteristics

## 📌 Project Overview
This repository contains the data analysis and data cleaning workflows for our study on **U.S. Gun Violence**. 

Our primary objective was to analyze over **239,000 police incident reports** to understand what drives fatality rates across the United States and evaluate how lethality changes based on the number of firearms involved in an incident.

## 📂 Dataset Source & Structure
Due to GitHub's file size limits, the full raw dataset (239,677 incident records) is hosted on Kaggle:
* 📥 **[Download Dataset on Kaggle: Gun Violence Data (James Ko)](https://www.kaggle.com/datasets/jameslko/gun-violence-data)**

In our workflow, the raw data was structured into the following tables for analysis in Tableau:
* `gun_violence_cleaned.csv` — Main incident-level dataset containing dates, locations, victim counts (`N Killed`, `N Injured`), and `Incident Characteristics`.
* `guns_long_v3.csv` — Firearm-level breakdown (`Gun Type Clean`, `Gun Stolen`).
* `participants_v1.csv` — Demographic and status data for suspects and victims (`Age Group`, `Gender`, `Status`, `Relationship`).
* `gun_details_v2.csv` — Supplementary weapon metadata.
