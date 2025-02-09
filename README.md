# COMP2156_Group20_Assignment

Project Title: COMP2156 Assignment
Group Members:
	1. 101469894 (Icy_Kellz)
	2. 101417110 (101417110)
	3. 101456851 (Teniola-dan)
	4. 101483707 (Fabio101483707)

Project Overview:
This is a group project for COMP2156 DevOps course that involves four members working collaboratively using Git and GitHub. The main goal is to demonstrate version control and collaboration practices in a DevOps environment.

Instructions: 
1. First clone the repository using HTTPS or SSH:

2. Navigate to the project directory:

3. Create your individual branch with your COMP2156 assignment code:

4. Create necessary files for your features

5. Git add, commit and push to your branch

6. Create pull request when your work is ready to merge

7. For any collaborative work, communicate with team members


CI/CD Details:

The DevOps pipeline implementation information is as follows:

- GitHub Actions workflow is used for continuous integration

- Pipeline triggers on push and pull request to main branch

- Builds and tests Node.js application

- Runs unit tests and ensures code quality

- Automated deployment to staging on successful build


Workflow Steps:

1. Checkout code

2. Setup Node.js environment

3. Install dependencies

4. Run tests

5. Build application

6. Deploy to staging


Branching Stragety:

- main: Production-ready code

- develop: Integration branch for features

- feature/*: Individual feature branches

- hotfix/*: Emergency production fixes

- release/*: Release preparation


Flow:

1. Create feature branches from develop

2. Merge features into develop

3. Create release branch when ready

4. After testing, merge release to main and develop

5. Hotfixes branch from main and merge to both main and develop
