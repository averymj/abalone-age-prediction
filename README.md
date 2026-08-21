# Abalone Age Prediction

**Status:** In progress

## Overview

The age of abalone is traditionally determined by cutting through the shell, staining it, and counting the number of rings under a microscope - a process that is slow, costly, and destructive, since cutting an abalone shell kills the abalone.\ 
Physical measurements, by contrast, can be taken quickly and without harming the animal, raising the question of whether they could serve as a reliable proxy for age. If a model can predict age accurately from these measurements, it could save fisheries and marine researchers significant time and cost, while avoiding the need to sacrifice an abalone for routine sampling. 

## Goal

Build a regression model in R to predict abalone age from physical measurements, using the UCI Abalone dataset.

## Data

Source: https://www.kaggle.com/datasets/rodolfomendes/abalone-dataset 

## Project Structure

- `data/` — raw and processed data
- `analysis/` — Quarto/R Markdown analysis files
- `output/` — figures and saved model objects
- `report/` — final rendered report

## Status / Roadmap

- [x] Project framing & problem definition
- [x] Environment & project setup
- [ ] Exploratory data analysis
- [ ] Model building
- [ ] Model evaluation
- [ ] Final report

## Reproducing this project

This project uses `renv` for package management. To reproduce:

\`\`\`r
renv::restore()
\`\`\`