# Automated-EEG-Analysis-HMS
Project and research paper on Automated EEG analysis for harmful brain activity classification.
# Harmful Brain Activity Classification

## Overview
This project aims to detect and classify seizures and other types of harmful brain activity using EEG signals recorded from critically ill patients. The project is based on the Kaggle competition ["HMS - Harmful Brain Activity Classification"](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification).

## Project Structure
- `data/`: Contains the EEG signal data.
- `notebooks/`: Jupyter notebooks for data analysis and model development.
- `scripts/`: Python scripts for data preprocessing and model training.
- `models/`: Trained models.
- `docs/`: Research paper and other documentation.


## Usage

### Data Preprocessing
Run the preprocessing script to prepare the EEG data for model training:

python scripts/preprocess.py

## Model Training
Train the model using the prepared data:
python scripts/train_model.py

## Model Evaluation
Evaluate the trained model on the test dataset
python scripts/evaluate_model.py


## Competition Details
The goal of this competition is to detect and classify seizures and other types of harmful brain activity. You will develop a model trained on electroencephalography (EEG) signals recorded from critically ill hospital patients.

## Patterns of Interest
There are six patterns of interest for this competition:

    Seizure (SZ)
    Generalized Periodic Discharges (GPD)
    Lateralized Periodic Discharges (LPD)
    Lateralized Rhythmic Delta Activity (LRDA)
    Generalized Rhythmic Delta Activity (GRDA)
    Other
Detailed explanations of these patterns are available in the competition overview.

## Contributors
- **Nandani Daga** - [GitHub](https://github.com/Nandanidaga)

## Evaluation

Submissions are evaluated on the Kullback Liebler divergence between the predicted probability and the observed target.

## Acknowledgements

We gratefully acknowledge the contributions of the experts from the Critical Care EEG Monitoring Research Consortium (CCEMRC), who provided the labels for model training and evaluation, and to others who contributed to the scientific work that enabled this competition.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## References

    [Kaggle Competition](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification). 

    EEG Talk - ACNS Critical Care EEG Terminology 2021

