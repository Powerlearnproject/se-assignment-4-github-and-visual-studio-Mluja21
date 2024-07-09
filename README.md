[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15367368&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
# Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
Github is a platform that is for software developers allowing them to create,manage,and share code with other developers. It's primary function is to allow developers to collaborate on different projects irrespective of where they are, or if they even know each other. If a developer's repository is public,with no license, it'll allow anyone to make changes and Git will keep track of changes made.
# Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.
A Github repository is like a folder in your file system. It allows the developer to store their code, upload files and keeps track of all changes made to files within it. To create a repository, navigate to the github website and log in. Once logged in, on the home page,under the tab "Top repositories", there'll be a green button labeled new.When clicked on it'll take the user to a page to create a name for the repository. They can decide whether it'll be public/private, whether it'll have a license and security measures.
# Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?
Version control in the context of Git is a system/software that keeps track of every change made within a file/files. This would allow a developer to see the original code/file and track every change made and be able to pinpoint where everything went wrong. Github enhances version control because it's a public platform, it allows every developer who wants to collab and help on any project to access the relevant repository and see all the previous changes made and be able to assist. 
# Branching and Merging in GitHub:
What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.
Branches are like creating a copy of the original code/file and it allows you to make changes and test out different feautures without risking breaking the original code. It's important to allow different members of a team to work on the same code at the sametime, yet whatever changes are made are personal to the branch they created. they have no effect on each other. Go to desired repository, then while in Gitbash use the command, git branch new_branch,then title it.Use git checkout new_branch to switch to that branch. You can make relevant changes and commit to that branch. Then use git merge (the name of new branch), then the branch will be merged with the main one.
# Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to  create and review a pull request.
A pull request is a process by which, a developer proposes certain code changes, bug fixes to be made to the main branch of code.Then it allows other developers within the team to discuss and review the changes suggested by the initial developer. It facilitates code reviews and great collaboration amognst the developers, as it ensures they engage the code and discuss whether they actually agree with the suggested changes,and this fosters great teamwork. To create a pull request, start-off by forking the main repository.Then proceed to create a branch, implement the desired changes to the forked repo, then proceed to commit the changes made. Then push the changes to the forked repository. Then open GitHub website,navigate to the branch created by you, then click on the Pull Request option. This will promptly open a new pull request allowing you to compare your changes to the main original code.Then provide a title and description for the pull request, then proceed to assign one or more reviewers.Then proceed to discuss the changes,after discussing and finalising the changes.Proceed to get approval from all the reviewers then merge the pull request.
# GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.
Github actions are automation tools that allow the user to directly automate workflows within the Github repository.It allows the user to build, test adn run code from within the website itself. Workflows can be automated by using YML files that can be activated by certain commands such as a push to the repository. Using Github actions, you can create a YML file containing all the instructions for the workflow. It'l contain a Trigger,jobs, within the jobs, it'll checkout the code,install dependencies(Node.js), run tests, If statement(if it passes). Then it'll be deployed to Github pages,create a temporary copy then proceeed to commit the changes and push them through.
# Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Visual studio is an intergrated development environment, primary use is creation of web applications. It has broad language support(Python, Java...etc),it works seamlessly with many different frameworks and libraries. It differs from visual studio code, as visual studio code is a source-code editor.So it's focus is code editing flexibility and experience.
# Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
Ensure that Git is installed. Then go to extensions option within the Visual studio,install Github extension for visual studio, check its verified. Use the Team explorer option, click on Clone, "under local repositories". Copy & paste the Github URL,and click the local path option, click clone. As soon as you prompt the cloning a popup requiring you to authenticate and login to your Github account will come up. After authentication, then you're done and can start working. Intergration allows the development workflow to work seamlessly due to Unified environment preventing the confusion of utilising multiple different platforms and tools.
# Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?
There is a wide assortment of debugging tools such as Breakpoints,this allows developers to be able to pause the execution of their code at specific lines of code. Another tool to be utilised is the Debugging toolbar this contains the most commonly used debugging commands such as "Start, Pause". It even allows the developer to control the execution of code.Exception settings- these help the developer be able to identify issues within the code in early development,as they can configure the settings to break execution when an exception is found.
# Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.
GitHub and Visual Studio together provide a robust ecosystem for collaborative development. By leveraging Git for version control, GitHub for repository management and collaboration, and Visual Studio for development and debugging tools, teams can streamline their workflows, improve code quality, and facilitate effective communication and collaboration across projects. This integration helps teams deliver high-quality software efficiently while fostering a collaborative and productive development environment. In a real-world scenario, where there may be Open-source project, this would allow different members of the team to be simulteanously working on the project, making continuos improvements and changes while, still having the safety of being able to return to previously saved code before the changes were made.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
