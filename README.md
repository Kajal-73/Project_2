# Project_2

# Fine-Tuning RoBERTa with LoRA for AG News Classification

ECE 7123- Deep Learning
Our team: (Kajal Gupta(kg3492), Jonathan Cvinar(jc12812), Devak Somaraj(ds8095))

## Repository Structure
**Code** : Our notebook for this project
**Dataset** : 
Raw - Original AG News data (auto-downloaded)
Processed- Tokenized datasets
submission.csv - Final predictions (8000 samples)
**Figures** : 
Loss_curves.png - Training vs validation loss

## Environemnt: 
Pytorch with default version in google colab

## Notes:
**Dataset:** AG News is auto-downloaded via Hugging Face datasets
**Custom Data:** Place test files (e.g., .pkl) in dataset/ and update paths in the notebook.
**Reproducibility:** Set seed=42 in the notebook for consistent shuffling.
