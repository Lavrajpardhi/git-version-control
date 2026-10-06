DevOps Internship Task 4 – Build a Version-Controlled DevOps Project with Git

Objective
Manage a DevOps project using Git best practices, including branching strategies, pull requests, merging, and tagging.

Tools Used
Git
GitHub
VS Code

Project Description
In this task, Git version control was used to manage a DevOps project workflow locally and remotely on GitHub. 
The project involved creating multiple branches (`main`, `dev`, `feature/update-project`), performing pull request-based merges, and setting up release tags.

Workflow Steps Followed
1. Repository Initialization:
   - Initialized a local Git repository and connected it to the remote GitHub repository (`git-version-control`).
   - Configured `.gitignore` and added an initial `README.md` file.

2. Branching Strategy:
   - Created and managed a secondary development branch (`dev`) from `main`.
   - Created a dedicated feature branch (`feature/update-project`) from `dev` to handle project updates safely.

3. Pull Requests & Merging:
   - Raised and merged a Pull Request from `feature/update-project` into `dev`.
   - Raised and merged a Pull Request from `dev` into `main`.

4. Tagging & Release:
   - Created and pushed a Git release tag (`v1.0.0`) on the stable `main` branch.

Git Commands Used
git init
git checkout -b dev
git checkout -b feature/update-project
git add .
git commit -m "commit message"
git push -u origin <branch-name>
git tag v1.0.0
git push origin v1.0.0

Verification
The repository branches and merge history were verified using GitHub UI and documented via screenshots:
- Closed Pull Requests 
- Git Tags 
- Merge Dev to Main 
- Branches 

Outcome
This task provided practical experience with professional Git branching workflows, pull request management, and version tagging for collaborative DevOps projects.