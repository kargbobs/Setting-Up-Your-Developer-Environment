[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281680&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
Objective: Choose and install an operating system that best suits your preferences and project requirements.
Instructions:
Choose an OS: For this assignment, we'll go with Windows 11.
Download and Install: Go to the Windows 11 Download Page.
Follow the installation instructions: This typically involves creating a bootable USB drive and installing Windows 11 on your machine.
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Objective: Install Visual Studio Code, a powerful and popular code editor.
Instructions:
Download: Go to the Visual Studio Code Download Page.
Install: Follow the instructions to install VS Code on your machine.
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
Objective: Install Git, set up a GitHub account, and initialize a Git repository.
Instructions:
Install Git:
Go to the Git Download Page.
Download and install Git for Windows.
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git init
echo "# My Project" >> README.md
git add README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo.git
git push -u origin main

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
Objective: Install Python and ensure it works correctly.
Instructions:
Download and Install Python:
Go to the Python Download Page.
Download the installer and follow the installation instructions. Make sure to check the option to add Python to your PATH.
python --version
pip --version

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Objective: Ensure that you have package managers like pip installed.
Instructions:
Pip is usually installed with Python. Verify it using the command pip --version. If it's not installed, you can install it by following instructions on the pip documentation.
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Objective: Install and configure MySQL database.
Instructions:
Download MySQL: Go to the MySQL Installer Page.
Install MySQL: Follow the installation instructions and configure the root user password.
Verify Installation:
mysql -u root -p

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Objective: Consider using Docker or virtual machines for isolated environments.
Instructions:
Install Docker: Go to the Docker Desktop Download Page and install Docker.
Verify Installation:
docker --version

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Objective: Enhance your IDE with extensions and plugins.
Instructions:
Open VS Code and go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+X.
Install Extensions:
Python
GitLens — Git supercharged
Docker
Prettier — Code formatter
Any other extensions that fit your workflow.
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
Document Your Setup
Objective: Create a document detailing the setup process.
Instructions:
Document Steps: Write a comprehensive document that includes:
Step-by-step instructions for each task.
Screenshots of key steps.
Any configurations or customizations.
Troubleshooting steps.
#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
