KLab AI Bootcamp - Day 1

This repository contains my work for Day 1 of the KLab AI Bootcamp.

Part1: Project Structure

klab-ai-lea/
    README.md
    requirements.txt
    .env.example
    .gitignore
    notebooks/
    src/
    data/
        raw/
        processed/
    reports/

Part 2: Environment Setup

1. Create the virtual environment

python -m venv .venv

2. Activate the environment on Windows PowerShell

.venv\Scripts\Activate.ps1

3. Install difference libraries
pip install numpy pandas scikit-learn matplotlib jupyter

4. Install the required libraries

pip install -r requirements.txt

5. I also enable extension for jupyter

5. Test the AI libraries
where i create test.py file under src to test if the libraries are working good


Part 3: Git and GitHub

This repository uses Git for version control and GitHub for storing and submitting the work.

Part 4: Security

Secrets such as API keys must not be committed to GitHub. The `.env` file and large or private datasets are excluded using `.gitignore`.
