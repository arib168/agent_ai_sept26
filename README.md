Agentic AI 


RAG based systems and AI Agents


SETUP 
Install Antigravity 

SETUP TO CREATE venv

open terminal 
1. Create a virtual environment using below command:
python -m venv venv

2. Give PowerShell permission to run activation scripts:
Set-ExecutionPolicy Bypass -Scope CurrentUser -Force

3. Activate the virtual environment:
.\venv\Scripts\Activate.ps1


Inside the virtual environment run the following commands :

ollama pull qwen3:0.6b

ollama pull all-minim


pip install langchain langchain-core langchain-ollama langchain-community langchain-classic gradio python-dotenv pypdf faiss-cpu

