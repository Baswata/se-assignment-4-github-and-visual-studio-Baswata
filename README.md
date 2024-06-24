[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15309352&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
GitHub is a version control system that host and manages code repositories.
its features and functions include;
commit history that allowa track of changes
Git Intergration that allows for efficient version control, branching and emerging
Forking crate personal copies of other users' repositories
Wikis allows creation and management of project documentation.
Github supports collaborative software development by allowing multiple people work on same project even fron different locations
Github allows developers to track changes in their project hence helps in managing tasks

Repositories on GitHub:
What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.A Github repository is a storage space where a developer can store and manage project files.
to create a github repository, you need to log in in your Github.
Click on your profile picture in the top-right corner and select 'your repositories' from the dropdown menu.
Click on the 'new' button to create a new repository.
Make sure you fill in repository details including repository name, Description of the project, choose whether it should be private or public and check the box 'intialize with a README'
Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers? 
Version control records changes to a file, allows multiple developers to work on a project. 
GitHub enhances version control for developers by providing a central repository aand backup which ensures project availability from anywhere
Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.
Branches are features in GitHub that allows developers to diverge from main codebase and work on changes independently.
Branches helps in maintaining a clean and organized history of project making it easier to track changes and revert if required
To create a branch; open your Gitbash terminal and navigate to your project directory. Create a new branch and switch to it  by using the command 'git checkout -b new-branch'
To make changes, edit the files in your code editor. Use the command 'git add .' to stage changes. commit changes using command 'git commit -m "description of the changes"'. Then use the command 'git push origin new-branch' to push the branch to GitHub.
Gnavigate to your repository on GitHub. Click on the button to 'compare and pull request' on the notification about recently pushed ranch. Provide a title and description for the pull request. Select 'main' brancd and 'new-branch' and click the 'create pull request' button.
Click on 'merge pull request' button on pull request page and confirm the merge by clicking 'confirm merge'

Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
pull request is an essential feature in GitHub that allows developers to notify team members about changes made in a branch repository. This allows team members to review code, sugest improvements and catch potential issues before intergration.
how to create a pull request;
After making changes in your branch, push the branch to the remote repository using the command 'git push origin your-branch-name'
Go to the repository where you pushed your branch and you will see a notification to create a pull request for the recently pushed branch. Click on 'compare & pull request'
make sure the main branch and compare branch are correct.
Provide a tittle for your pull request and add description on the changes made and why.
Click on 'create pull request'
GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.
GitHub actions is a feature that allows you to automate, customize and execute software development workflows in your repository. 
GitHub actions enables automation of various tasks such as; automatically building and testing code changes when pushed to the repository, deploying applications to various environments like stagging or production when code changes pass the required tests and sending notifications to team members when certain events occur in the repository.
Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Visual studio is an intergrated development environment(IDE) developed by Microsoft. Key features are; comprehensive IDE, Support for multiple programming languages, advanced programming language, advanced debugging and diagnostics, intelliSense 
Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
Make you have downloaded and install Visual Studio in your computer
open visual studio and go to file then click on account settings and sign in to your GitHub account
click on 'file' then choose 'open' and click on 'open from source control'
Select 'Git' from the gropdown men and choose 'clone Repository' and paste the URL of your GitHub repository
Select a local directory where you want to clone the repository
To create a new repository, go to 'File' then select 'New' and then choose 'Reository'
Select 'Git' as repository type and fill in the details of the new repository and select 'Create and Push'.
This intergration of Visual Stdio and GitHub enhances development workflow by allowing seamless version control as developers can perform version control operations without leaving the development environment, it also allows branch management as it makes it easy to create, switch and manage branches
This intergration allows collaboration from different developers who can work on same project from different location simultaneously. 
Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?
Key debugging tools in visual studio include;
Breakpoints: it allow developers to pause the execution of their program at specific line of code. A breakpoint is set by pressing 'F9' and when execution hits the breakpoint, the debugger pauses hence allow inspection of variables, the call stack and program state.
Watch Window: Allows developers to monitor values of specific variables or expressions as program execute. to add variables or expressions to watch window, right click a variable and select 'add to watch'
Call Stack: it shows the sequence of function calls that led to the current point of execution. This helps in understanding flow of execution and identifying where the program might have gone wrong. It accesed by clicking 'Debug' then choosing 'Windows' then selecting 'call stack'
Immediate window: It allows developers to evaluate expressions, execute commands and print variable values during debugging
Exception settings: it control how the debugger handles exceptions and developers can choose to break on specific exceptions
Edit and Continue: it allows to developer to make changes to their code during debugging session without stopping the debugger                     
Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.
Intergration of Visual Studio and GitHub allow teams to streamline their development workflow, improve collaboration and ensure high-quality code through automated testing and continous integration.
A real world example is when a team is working on aproject to build an app;
Team leader creates a new repository on GitHub and the team members clone it to their local machine using Visual Studio.
Each developer creates a new branch for their tasks.
Developers implement their fixes in their respective branches and commit their changes with meaningful messages.
Changes are pushed to the respective branches on GitHub.
After the feature is compelete, the developer opens a pull request on GitHub which includes description of changes and links to related issues.
Other team members review the pull request and provide feedback.
Once approved, the pull rquest is merged into the main branch.
GitHub actions then runs automated tests on the merged code. If tests pass, the application is automatically deployed to a staging environment


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
