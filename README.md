If you want to install the Cisco Foundation Model using Ollama with Google CoLab, use the T4 GPU with High-Ram for the runtime type

Sample Google Colab Jupyter instructions
sudo apt-get install zstd
curl -fsSL https://ollama.com/install.sh | sh
ollama serve &
#Navigate to where you have the Modelfile and Cisco Foundation Model stored (e.g., Google Drive for CoLab) - you can see my prior LinkedIn article for instructions on setting this up
ollama create foundation-sec-8b -f Modelfile
ollama run foundation-sec-8b

from terminal, install relevant packages

pip install llama-index llama-index-llms-ollama llama-index-embeddings-huggingface llm-guard
