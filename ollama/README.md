## Ollama with LLaMA 3.2

### Overview
This project demonstrates how to set up and test the Ollama framework with the LLaMA 3.2 model. It includes installation instructions, server setup, and running the model.

## Prerequesites
- Ubuntu OS (Tested on Ubuntu Jammy)
- Python 3 installed
- Internet connection for downloading dependencies

## Installation
- Install required system libraries:
sudo apt-get install -y pciutils
- Install Ollama:
curl https://ollama.ai/install.sh | sh

## Enviroment Setup
import os
import threading
import requests
import subprocess
import json

# Configure Ollama environment
os.environ["OLLAMA_HOST"] = "0.0.0.0:11434"
os.environ["OLLAMA_ORIGINS"] = '*'

# Start Ollama Server
subprocess.Popen(['ollama', "serve"])

## Output
- The server will pull and load the required model data.
- Logs will display the model loading process.
- After completion, the server will be available at http://127.0.0.1:11434.
