# Generate_Synthetic_text_data

This project explores the generation of synthetic tabular data using Large Language Models (LLMs) on textual datasets. The primary goal is to leverage the generative capabilities of LLMs to create structured data while examining their handling of biases inherent in the original dataset. By training LLMs on this data, we aim to observe whether the models replicate or amplify existing biases when generating new data. In addition to understanding LLM behavior with biased data, the project also investigates techniques for bias mitigation, striving to reduce unintended bias propagation in the synthetic outputs. 

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

## Notebooks

This repository includes two Jupyter notebooks for generating synthetic tabular data using different approaches. Each notebook demonstrates a unique method and analyzes its effectiveness in synthetic data generation.

### 1. `Generate_synthetic_data_Tabula.ipynb`:
- **Approach**: This notebook uses Tabula for generating synthetic tabular data.
- **Description**: The method focuses on leveraging LLM to create realistic tabular data. 

### 2. `Generate_synthetic_data_Langchain.ipynb`:
- **Approach**: This notebook implements Langchain.
- **Description**: By applying this approach, 
