# ELEVATELAB_Day4
Version-Controlled DevOps Project with Git

Project Objective

Manage a DevOps project using Git best practices.  


Tools:

Git and GitHub

   Repository Structure:
   
ELEVATELAB_Day4/
├─ README.md
├─ main/
│ └─ .gitignore
│ └─ main files
├─ feature/
│ └─ feature-task files
└─ dev/
└─ development branch files



   Implementation Workflow

1. Initialize Repository

        git init
        git remote add origin <your-repo-URL>
   
2. Create Branches

        git checkout -b dev          # Development branch
        git checkout -b feature-task1  # Feature branch
        git checkout -b main         # Main branch
   
3. Make Changes and Commit

        git add <files>
        git commit -m "Your commit message"
   
4. Push Branches to GitHub

        git push origin feature-task1
   
5. Pull Requests (PR)
Push your feature branch to GitHub.

Open a PR from feature-task1 → main 

Review changes, merge via GitHub UI.

6. Use .gitignore
Ignore unnecessary files (e.g., i have created vidumukhi.txt to check working of .gitignore file)


7. Tagging Releases

        git tag -a v1.0 -m "commit msg"
        git push origin v1.0
   
8. Document Tasks
Keep all tasks documented in Markdown files inside the repository.

Include clear commit messages, branch usage, and PR workflow.

Output

By following this workflow,

I Understand Git branching strategies

Learned commit and push best practices

Got familiar with pull requests and code review

Used tags and .gitignore effectively



