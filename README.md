# Sleep Stage Classification Using EEG (CNN)

## Project Overview

This project focuses on classifying human sleep stages using Electroencephalography (EEG) signals and a Convolutional Neural Network (CNN). The model is designed to automatically identify different sleep stages such as Wake, REM, and NREM from raw EEG recordings.

The goal of this project is to demonstrate how machine learning and deep learning techniques can be applied to neuroscience and sleep research.

---

## Dataset

This project relies on publicly available EEG sleep data from OpenNeuro:

**Dataset Name:** Sleep EEG Dataset (ds005555)
**Source:** OpenNeuro
**Link:** [https://openneuro.org/datasets/ds005555/versions/1.0.0](https://openneuro.org/datasets/ds005555/versions/1.0.0)

Please download the dataset directly from OpenNeuro before running the code. Due to size limitations, the dataset is not included in this repository.

---
## Published Poster
<img width="2500" height="2142" alt="Classifying Sleep Stages Final Poster  (1)" src="https://github.com/user-attachments/assets/f3d72d1a-f28c-4065-a56e-9db380e1ce3c" />

---
## Project Features

* Preprocessing of raw EEG signals
* Feature extraction and normalization
* CNN-based sleep stage classification
* Model training and evaluation
* Performance visualization (e.g., accuracy metrics, confusion matrix)

---

## Technologies Used

* Python
* NumPy
* Pandas
* PyTorch / TensorFlow (depending on implementation)
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Project Structure

```
project-folder/
│
├── SleepClassificationProject.ipynb   # Main notebook
├── data/                              # Dataset directory (not included)
├── README.md                          # Project documentation
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-repo-link>
cd <your-repo-name>
```

### 2. Download the Dataset

Download the dataset from OpenNeuro:
[https://openneuro.org/datasets/ds005555/versions/1.0.0](https://openneuro.org/datasets/ds005555/versions/1.0.0)

Place the extracted files inside the `data/` directory.

### 3. Install Dependencies

(Optional but recommended)

```bash
pip install -r requirements.txt
```

Or manually install required libraries:

```bash
pip install numpy pandas torch scikit-learn matplotlib jupyter
```

### 4. Run the Notebook

```bash
jupyter notebook
```

Open `SleepClassificationProject.ipynb` and run all cells.

---

## Results

The model demonstrates strong performance in classifying sleep stages from EEG data. Evaluation metrics such as accuracy and confusion matrices are used to assess model reliability.

Detailed results can be found within the notebook.

---

## Notes

* Large datasets are excluded from this repository.
* Make sure file paths in the notebook match your local dataset location.
* GPU acceleration is recommended for faster training.

---

## License & Data Usage

Please follow OpenNeuro’s data usage and citation guidelines when using the dataset.

If you use this project or dataset in academic work, make sure to properly cite the original data source.

---

## Author:

**Andres Quintanar**
Neuroscience & Data Science Student

---

## Acknowledgments

* OpenNeuro for providing open-access neuroimaging datasets
* Researchers who contributed to dataset ds005555
* Open-source ML and neuroscience communities
