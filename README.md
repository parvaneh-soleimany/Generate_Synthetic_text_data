# Generate_Synthetic_text_data

This project explores the generation of synthetic tabular data using Large Language Models (LLMs) on textual datasets. The primary goal is to leverage the generative capabilities of LLMs to create structured data while examining their handling of biases inherent in the original dataset. By training LLMs on this data, we aim to observe whether the models replicate or amplify existing biases when generating new data. In addition to understanding LLM behavior with biased data, the project also investigates techniques for bias mitigation, striving to reduce unintended bias propagation in the synthetic outputs. 

## Notebooks

This repository includes two Jupyter notebooks for generating synthetic tabular data using different approaches. Each notebook demonstrates a unique method and analyzes its effectiveness in synthetic data generation.

### 1. `Generate_synthetic_data_Tabula.ipynb`:
- **Approach**: This notebook uses [Tabula](https://github.com/zhao-zilong/Tabula) for generating synthetic tabular data.
- **Description**: The method focuses on leveraging LLM to create realistic tabular data. 

### 2. `Generate_synthetic_data_Langchain.ipynb`:
- **Approach**: In this notebook, we'll dive deep into generating synthetic records using the [LangChain](https://python.langchain.com/docs/introduction/) library. 
- **Description**: By applying this approach, we explore how to leverage LangChain’s SyntheticDataGenerator model for creating data based on prompt engineering and chaining LLM responses.

## Installation

Follow these steps to set up and run the project on your local machine:

1. **Clone the repository:**
   Begin by cloning the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/parvaneh-soleimany/Generate_Synthetic_text_data.git
2. **Install the dependencies:**
    Install the required packages
   ```bash
   pip install -r requirements.txt
3. **Install Ollama:**
   Follow these steps only for LangChain data generator.
   - As a first step, you should download Ollama to your machine from: https://ollama.com/download
   - Install a Llama3 model from the Ollama Library: https://ollama.com/library/llama3
   - You can verify that everything is correctly installed by running a basic command, such as:
     ```shell
     ollama list
     ```
## Usage

### Generate Synthetic Data using Tabula
- **Local**: Run `jupyter notebook` in your terminal, navigate to `Generate_synthetic_data_Tabula.ipynb`, and open it.
- **Colab**: You also can open and run the Jupyter notebook directly in Google Colab by clicking the button below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/parvaneh-soleimany/Generate_Synthetic_text_data/blob/main/Generate_synthetic_data_Tabula.ipynb)

### Generate Synthetic Data using LangChain
Run `jupyter notebook` in your terminal, navigate to `Generate_synthetic_data_Langchain.ipynb`, and open it.


