# PLP BASIC GIT ASSIGNMENT

## Hands-On Assignment: Basic Git And GitHub Workflow.

## Objective:
The objective of this assignment is to familiarize students with the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

## Description
This assignment is a basic introduction to the Git and GitHub workflow, emphasizing repository creation, local setup, making changes, committing, and pushing to GitHub.

## STEP ONE: 
* Repository Setup: Log in to Github account and create a new repository on GitHub. To create a new repository, check the plus sign which has a drop down icon, then click to open a New repository.
 - on the text box, type your repository name ie "PLPBasicGitAssignment"
 - type a brief description in the description dialog box.
 - click on Add a README file = this part is to anable one to write a long description of about the project.
 - then Click "Create repository" at the bottom to create a repository.
 - A repository with a name "PLPBasicGitAssignment" will be created, and a URL link will be available in the section <> Code- which has a drop down icon. copy the URL with a fomart HTTPS.

## STEP TWO:
* Local Setup: Creating a local folder setup where we shall save our project for.
 - Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").
 - Open a terminal or command prompt and navigate to the created folder. e.g cd Users/USER/github-classroom/PLPBasicGitAssignment/

* Initialize the Git repository: Run the following command to initialize a new Git repository in your current directory: 
 <git init>
 
* Connecting to GitHub: Link your local repository to the GitHub repository you created
bash
   ```
git remote add origin <repository-url>

   ```
   Replace `<repository-url>` with the actual URL of your GitHub repository we copied.

## STEP THREE:
* Creating a file with a text "hello.txt"
 - a text file can created with different routes e.g using the terminal or command prompt or a text editor ( Notepad, VS Code, Sublime Text, etc.)
- Using VS Code: open a VS Code and Open the folder "PLPBasicGitAssignment"
- create a file with the name "hello.txt"
- Type a message: "Hello, Git!" in the new file.
- Save the file: Save the file in your project directory.
* Create another file with the name: README.md
- Document the steps and commands used for this project and save.

## STEP FOUR: 
* Committing Changes:
  - Stage the changes.

   ```bash
   git add hello.txt

   ```
  - Commit the changes.

   ```bash
   git commit -m "Add hello.txt with a greeting, Hello, Git!"

   ```
* Pushing to GitHub
  - Push the committed changes to your GitHub repository.

   ```bash
   git push -u origin main

   ```

Task 5: Verification

8. Verify on GitHub:

  - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.

## Summary
The above steps initialize a new Git repository in your project folder and create a text file named `hello.txt` with the content "Hello, Git!".