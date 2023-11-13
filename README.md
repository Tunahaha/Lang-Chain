# Lang-Chain Application

## Introduction
This is an application developed using Lang-Chain. The application includes several Jupyter notebooks that demonstrate different uses of the GPT model for various tasks such as document generation, YouTube comment generation, and data manipulation in CSV files.

## Structure
The repository consists of the following key files:

1. **DocGPT.ipynb**: A Jupyter notebook for document generation using the GPT model.

2. **YoutubeGPT.ipynb**: A Jupyter notebook for generating YouTube comments using the GPT model.

3. **csvGPT.ipynb**: A Jupyter notebook for manipulating data in CSV files using the GPT model.

4. **langchain.ipynb**: The main Jupyter notebook that uses Lang-Chain for the application.

5. **pokemon.csv**: A CSV file containing Pokemon data used in the csvGPT notebook.

## Quick Start

1. First, you need to install Jupyter notebook if you haven't installed it yet. Please refer to the following link:
   - [Install Jupyter](https://jupyter.org/install)

2. Clone this repository to your local machine:
    ```
    git clone https://github.com/Tunahaha/Lang-Chain.git
    ```

3. Switch to the directory of the repository you just cloned:
    ```
    cd Lang-Chain
    ```

4. Start Jupyter Notebook:
    ```
    jupyter notebook
    ```

5. Navigate to the desired notebook file (`.ipynb`) in the Jupyter Notebook web interface and click to open.

6. Run the notebook cells using the Jupyter interface.

## Features

- **Document Generation**: The DocGPT notebook demonstrates how to generate documents using the GPT model.

- **YouTube Comment Generation**: The YoutubeGPT notebook shows how to generate YouTube comments using the GPT model.

- **CSV Data Manipulation**: The csvGPT notebook demonstrates how to manipulate data in CSV files using the GPT model.

## Note
Please ensure you have the necessary Python libraries installed before running the notebooks. You can install the requirements via pip:
```
pip install -r requirements.txt
```
Replace `requirements.txt` with the actual requirements file if it has a different name. If there is no requirements file, you may need to install the libraries individually based on the import statements in the notebooks.
