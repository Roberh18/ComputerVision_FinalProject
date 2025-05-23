# IKT452 Computer Vision Project: Facial Expression Recognition

This repository contains the code for a computer vision project focused on Facial Expression Recognition using the FER2013 and FERPlus datasets, implemented with PyTorch. 

## Project Structure

* `IKT452_ComputerVision_Project_v1.1.ipynb`: Main notebook for training.
* `IKT452_ComputerVision_Project_V1.0.ipynb`: An earlier version of the main training notebook.
* `IKT452_ComputerVision_Project_Experiments.ipynb`: Notebook containing various experiments.
* `Download_dataset.ipynb`: Utility notebook to download the FER2013 and FERPlus datasets using Kaggle Hub.
* `requirements.txt`: Lists all Python packages installed in the JupyterHub development environment.
* `outputs/`: (Generated by the script) This directory will contain subdirectories for each run, holding saved models, plots, and logs.

## Setup Instructions

Follow these steps to set up the environment and run the project.

### 1. Clone the Repository
```bash
git clone [https://github.com/Roberh18/ComputerVision_FinalProject.git](https://github.com/Roberh18/ComputerVision_FinalProject.git)
cd ComputerVision_FinalProject
```

### 2. Create and activate an environment
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Download the Dataset (FER2013)
* Run the provided Notebook `Download_dataset.ipynb`, which uses the kagglehub library.
* After the datasets have been downloaded, copy the printed paths for the datasets and paste them into the other Notebooks.

### 5. In each notebook, verify the data_dir variables at the top point to your downloaded datasets
### 6. Run the code
