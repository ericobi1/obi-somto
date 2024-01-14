# obi-somto
## what is version control
 Version Control is also known as source control, it is the practice of tracking and managing a file record changes to a file or set of files over time.
 ## Explain diffrences between git and github
 Git is a distributed version control system used for tracking changes in source code during software development. It enables collaboration among developers and helps manage different versions of a project.

GitHub, on the other hand, is a web-based platform that provides hosting for Git repositories. It adds a layer of collaboration features, like issue tracking, pull requests, and a web interface for managing repositories. GitHub is a service built on top of Git, making it easier to work with Git repositories, especially in a team setting.
## list 3 other github alternatives
 Azure DevOps:
   - Offers a suite of development tools, including version control, CI/CD, and project management.
   - Integrates well with Microsoft's development ecosystem.

2. AWS CodeCommit:
   - A fully managed source control service integrated with Amazon Web Services.
   - Supports Git repositories.

3 Gogs
   - A self-hosted Git service similar to Gitea, designed for simplicity and performance.
   ## Explain the diffrence between git fetch and git pull
   the key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.3 May 2023
   ## Explain in simple terms git rebase and the command for it
   From a content perspective, rebasing is changing the base of your branch from one commit to another making it appear as if you'd created your branch from a different commit. Internally, Git accomplishes this by creating new commits and applying them to the specified base.
  `` git rebase --keep-base <upstream> <branch>``
  ## Explain in simple terms git cherry-pick and the command for it
  git cherry-pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another. git cherry-pick can be useful for undoing changes.
  `git cherry-pick [--edit] [-n] [-m <parent-number>] [-s] [-x] [--ff]
		  [-S[<keyid>]]``

    
