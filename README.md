# A02 

- This is a tutorial that will show you how to create a GitHub account, make a repository named **A02**, edit your README file, and submit your repository link to Canvas.

# A02 – Git, WebStorm, and GitHub Tutorial

This tutorial provides instructions on using **Git**, **WebStorm**, and **GitHub** for version control and collaboration. It is written so that a beginner can follow it step by step.

---

## Part 1: Directions on Using WebStorm

### Step 1: Download and Install WebStorm
- Download WebStorm from JetBrains: [https://www.jetbrains.com/webstorm/download/](https://www.jetbrains.com/webstorm/download/)
- Follow the installation guide: [https://www.jetbrains.com/help/webstorm/installation-guide.html](https://www.jetbrains.com/help/webstorm/installation-guide.html)
- Launch WebStorm after installation.

### Step 2: Install Git
- Download Git from the official website: [https://git-scm.com/downloads](https://git-scm.com/downloads)
- Follow the installation instructions for your operating system.
- Verify installation by opening a terminal/command prompt and typing:
    ```bash
  git --version

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Task: Create Repository

## Step 4: Create a GitHub Account and Repository
1. Sign up for an account at https://github.com
2. Click the + in the top-right corner → New repository
3. Name it A02 (make sure to use a capital A)
4. Check Add a README file and click Create repository

## Step 5: Clone Repository into WebStorm
1. In GitHub, copy the HTTPS URL for your repository (e.g., https://github.com/<username>/A02.git)
2. In WebStorm, go to File → New → Project from Version Control → Git
3. Paste the repository URL and click Clone

## Step 6: Make Changes and Commit
1. Open your README.md file in WebStorm.
2. Edit the content as needed.
3. Go to VCS → Commit (or open the Commit tool window).
4. Write a clear commit message such as:
Task: Create Repository
5. Click Commit or Commit and Push.

## Step 7: Push Changes to GitHub
- If you committed locally, push your changes to GitHub:
- In WebStorm, go to VCS then Git then Push
- This sends your local changes to the remote repository

## Step 8: Pull or Fetch Updates
If collaborating with others:
- Use Pull to download and merge updates from the remote repository
- Use Fetch to check for changes without merging immediately

## PART 2: 
Glossary: 
- **Branch** – A separate line of development within a project, allowing you to work on features independently from the main code.
- **Clone** – The process of creating a local copy of a remote repository on your computer.
- **Commit** – A snapshot of your changes that records modifications in your local repository along with a message describing them.
- **Fetch** – The process of downloading information about changes from a remote repository without merging them into your local files.
- **GIT** – A distributed version control system that tracks and manages changes in source code.
- **Github** – A cloud-based hosting service for Git repositories that provides tools for collaboration and version management.
- **Merge** – The act of combining changes from one branch into another, typically to integrate updates into the main project.
- **Merge Conflict** – An event that occurs when Git cannot automatically merge changes because two branches have modified the same part of a file.
- **Push** – The process of sending committed changes from your local repository to a remote repository, such as GitHub.
- **Pull** – A command that retrieves changes from a remote repository and merges them into your local branch.
- **Remote** – A version of your repository that is stored on a server, such as GitHub, enabling collaboration between developers.
- **Repository** – A storage location for a project that includes all files, history, and version tracking.

## References
- Atlassian. (2024). Git tutorials and training. Retrieved September 30, 2025, from https://www.atlassian.com/git/tutorials
- GitHub Docs. (2024). Creating and managing repositories. Retrieved September 30, 2025, from https://docs.github.com/en/repositories
- Git-SCM. (2024). Pro Git Book: What is Git? Retrieved September 30, 2025, from https://git-scm.com/book/en/v2
- JetBrains. (2024). WebStorm documentation – Using Git integration. Retrieved September 30, 2025, from https://www.jetbrains.com/help/webstorm/using-git-integration.html
- OpenAI. (2025). Generated educational content on Git, GitHub, and WebStorm tutorial formatting.
- Instructor PowerPoint Presentations. (2025). Git, GitHub, and WebStorm Overview. Classroom materials.
