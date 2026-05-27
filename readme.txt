Tech Stack
-------------------------------
Python
LLM Groq
Langchain Framework
Pinecode Vector DB
Flask For Front end / Backend Developement
AWS Deployment
CI/CD Pipeline ( use Github Repo)

Plan Of Action
--------------------------------
1) Github Repo
2) Project Template ( Folder Structure)
3) Project Setup ( All dependenices)
4) Jupiter Notebook
5) Modular Code
6) Create Web App
7) Deployment

Tools
-------
git bash
vs code

Create Folder using Bash Script
-------------------------------------

template.sh
    mkdir -p src
    mkdir -p research
    touch src/__init__.py
    touch src/helper.py
    touch src/prmopt.py
    touch src/prmopt.py
    touch .env
    touch setup.py
    touch app.py
    touch research/trials.ipynb
    touch requirements.txt

run template.sh using git cmd

now commit and push files in git


requirements.txt
langchain==0.3.26
flask==3.1.1
sentence-transformers = 4.1.0
pypdf==5.6.1
python-dotenv==1.1.0
langchain-pinecone==0.2.8


pip install -r requirements.txt