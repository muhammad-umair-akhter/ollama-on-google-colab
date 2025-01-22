# ollama-on-google-colab

## Running DeepSeek-R1 on Google Colab

To run DeepSeek-R1 on Google Colab, follow these steps:

1. Open the [DeepSeek_R1_Google_Colab.ipynb](DeepSeek_R1_Google_Colab.ipynb) file in Google Colab.
2. Follow the instructions in the notebook to install Ollama, download the DeepSeek-R1 model, and run it.

The notebook includes the following steps:
- Install Ollama using `!curl -fsSL https://ollama.com/install.sh | sh`
- Download the DeepSeek-R1 model using `!ollama pull deepseek-r1:7b`
- Run the DeepSeek-R1 model using `!ollama run deepseek-r1:7b`
