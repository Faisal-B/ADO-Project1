# MyWebApp

This is a simple "Hello, Azure DevOps!" Python application.

## Getting Started

1.  Clone the repository: `git clone <your_github_repo_url>`
2.  Run the application: `python app.py`
3. Install the dependancies: `pip install -r requirements.txt`

## Azure DevOps Integration

This project is integrated with Azure DevOps for CI/CD.

### CI Pipeline

The CI pipeline is configured in `azure-pipelines.yml`. It performs the following steps:

1.  Uses Python 3.x.
2.  Installs dependencies from `requirements.txt`.
3.  Runs the `app.py` script.

### Azure Boards

Azure boards are used to track work items, user stories, and tasks related to this project.

## Azure Repos

This repository is hosted in Azure Repos and Github.

## Personal Access Token (PAT)

A Personal Access Token (PAT) was used to authenticate with Azure Repos.