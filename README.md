# Drug Discovery Demo: Binding Affinity + ADMET (DeepPurpose + Gradio)

## Overview
This project uses the DeepPurpose library to predict **drug–target binding affinity (Kd)** and a set of **ADMET properties**. It also includes a **Gradio UI** (MolDesigner-style) that takes a protein sequence and a SMILES string and returns predicted affinity and ADMET outputs.

## What’s inside
- Dataset preprocessing for DTI (BindingDB workflow)
- Training multiple CNN/CNN DTI models (10/50/100 epochs)
- Inference using pretrained + custom-trained models
- ADMET prediction suite (multiple endpoints)
- Gradio web app for interactive predictions

## Data
The notebook expects a BindingDB TSV file path (not included in this repo due to size/licensing).
Update the BINDINGDB_TSV variable in the notebook to point to your local file.

## Tech Stack
Python, DeepPurpose, PyTorch, RDKit, Gradio, pandas/numpy
