# Bone Segmentation Assignment

This repository contains the implementation and analysis for the second assignment- bone segmentation. 

## Setup Instructions

To ensure the Jupyter Notebook runs perfectly with all the correct dependencies, please follow these steps to set up the Conda environment.

### Prerequisites
Ensure you have [Miniconda] or Anaconda installed on your system.

### Installation

1. Open your Anaconda Prompt (Windows) or Terminal (Mac/Linux).
2. Navigate to the root folder of this project:
   ```bash
   cd path/to/assignment/folder
   ```
3. Create environment from setup
    ```bash
   conda env create -f setup/environment.yml
    ```
4. Activate the newly created environment:
    ```bash
    conda activate boneseg-env 
    ```
5. Install ipykernel so Jupyter can see this environment:
    ```bash
    pip install ipykernel
    ```
6. Register the environment as a Jupyter kernel:
    ```bash
    python -m ipykernel install --user --name boneseg-env --display-name "Python (boneseg-env)"

    ```

After this, open VSCode or another Jupyter environment and select the created kernel. All should be working fine.
## Disclaimer
Due to the Windows compatibility issues with importing the library torch on one of our teammate's laptops, we needed to add the first cell in the notebook06.py. It should not affect running the code on other devices, however if it does, please remove the first cell in notebook06.py (the one that starts with the comment:  Windows-only compatibility fix for Conda/PyTorch DLL loading). Thank you!
