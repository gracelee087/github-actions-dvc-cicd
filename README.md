# Github Actions and CI/CD

In this repository you will learn about Github Actions and CI/CD. CI/CD stands for Continuous Integration and Continuous Delivery/Deployment. It is a set of practices that automates the process of building, testing and deploying software. It is a way to automate the software development process. And can also be used in Machine Learning. 

## What is Github Actions?

GitHub Actions is a powerful CI/CD tool provided by GitHub. It allows you to define custom workflows using YAML syntax, which can be triggered by various events in your GitHub repository such as code pushes, pull requests or scheduled intervals. It provides a wide range of pre-built actions and allows you to create your own custom actions to automate specific tasks.

## Learning Objectives

- Learn about Github Actions
- Learn about CI/CD in Machine Learning
- Learn about CML (Continuous Machine Learning)
- Learn about DVC (Data Version Control)

## Environment

You need the google cloud sdk installed and configured. If you don't have it installed follow the instructions here or use homebrew on mac:
```bash
brew install --cask google-cloud-sdk
```

## Pyhton Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

### **`macOS`**
```BASH
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/bin/activate
  pip install --upgrade pip
  pip install -r requirements.txt
  ```
### **`WindowsOS`**
 For `PowerShell` CLI :

  ```PowerShell
  pyenv local 3.11.3
  python -m venv .venv
  .venv\Scripts\Activate.ps1
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```

  For `Git-Bash` CLI :

  ```
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/Scripts/activate
  python -m pip install --upgrade pip
  pip install -r requirements.txt
  ```

