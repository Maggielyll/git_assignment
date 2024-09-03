# Git Assignment - <Maggielyll>

a. What is an issue?
- It is a feature on Github that allows us to track requested changes and features in a software project.

b. What is a pull request?
- A pull request is a way of submitting contributions to a project. It will notify changes to be reviewed and merged into another branch, typically the main branch, of the repository.

c. Describe the steps to open a pull request?
- Fork the repository: Create a copy of the repository under the GitHub account.
- Clone the forked repository: Download the repository to the local computer using $ git clone
- Create a new branch: Create a new branch for the changes using $ git checkout -b branch-name.
- Make your changes: Edit, add, or delete files
- Commit your changes: Save changes with a commit message using $ git commit -m
- Push the changes: Upload changes to GitHub using $ git push
- Open a pull request: Go to the original repository on GitHub and click the New pull request button. Select the branch and submit the pull request.
- Select Branches: Choose the branch with changes as the source branch and main branch where to merge the changes.
- Review and Create: Add a title and description for the pull request and click Create pull request

d. Describe the steps to add a collaborator to a repository (share write permissions)
- Go to the repository on GitHub
- Click on the Settings tab
- Click the "Collaborators & teams"
- Click the "Invite a collaborator" button
- Enter GitHub username and Email
- Click "Add collaborator"

e. What is the difference between git and GitHub?
- Git: It is a version control system that allows to track changes in code and collaborate with others' work
- GitHub: An online platform that uses Git for version control. It provides an environment for developers to host and review code, manage projects together

f. What does git diff do?
- git diff shows the differences between various states of the repository. git diff compares what is in our working directory to what is in our staging area. If we've made changes to our files without running git add, we'll see the comparison. If there are no differences, nothing will be shown

g. What is the main branch?
- The main branch is sometimes called the master branch. It is the default branch in a Git repository.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
- No. Using feature branches is better than pushing directly to the main branch. To ensure the stability and quality of the codebase.
