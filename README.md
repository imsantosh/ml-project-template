This repository can be used to create a modular and well-managed structure for ML/DL projects. Here's a step-by-step guide to setting up and using this template:

## Steps:
1) clone this repo.
2) Create a virtual enviroment
- Create virtual enviroment: python -m venv tutorial-env
- Activate virtual enviroment: 
  - On Windows, run: tutorial-env\Scripts\activate
  - On Unix or MacOS, run: source tutorial-env/bin/activate    
3) Run 'python template.py'. This script will create all required files and folders as part of the template. You can review and update 'template.py' to customize the project structure according to your needs.
4) Update the setup.py file with resepect to project name and your email id & name.
5) Add or remove Python libraries as needed. Ensure the last line of the file includes '-e .' to enable the project as a package.
6) Install requirements.txt file by running 'pip install -r requirements.txt'. This command will install the required libraries and enable your project as a package using setup.py

## Use of different files:
# Template.py:
- This script is used to create the initial project structure and files. Modify it to fit the specific needs of your project.
# Setup.py:
- This file is used to enable your project as a package. It includes metadata about your project and its dependencies.
# Requirements.txt:
- This file lists the libraries required for your project. By including '-e .' at the end, While running the 'pip install -r requirements.txt' will also look for setup.py and will enable your project as a package.

# Note:- 
- This script will set up a basic folder structure for your project. You can expand it based on your requirements.
- By following these steps, you can ensure a modular and well-organized ML/DL project, making it easier to manage and scale your code.