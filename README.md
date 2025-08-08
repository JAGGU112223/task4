🚀 Task 4 - Version-Controlled DevOps Project with Git 📌 Overview This project demonstrates the use of Git and GitHub for version control in a DevOps workflow. It includes proper branching, commits, pull requests, tagging, and documentation to simulate a real-world collaborative development environment.

🛠 Tools & Technologies Git – Version control system

GitHub – Remote repository hosting

Markdown – For documentation (README.md)

📂 Project Workflow Repository Setup & Initialization

Created a new local Git repository and connected it to a GitHub remote.

Added .gitignore to exclude unnecessary files.

Added initial commit with project structure.

Branching Strategy

Created three main branches:

main → Stable production-ready branch

dev → Development branch

feature-* → Temporary feature branches for new functionality (e.g., feature-homepage, feature-about)

Followed a feature-branch workflow to isolate changes.

Development & Commits

Each feature branch contained relevant code changes.

Used meaningful commit messages for clarity.

Merged completed features into dev using Pull Requests (PRs) on GitHub.

Once stable, dev was merged into main.

Version Tagging

Used Git tags to mark important releases (e.g., v1.0).

Merge & Conflict Resolution

Practiced merging branches and resolving any merge conflicts.

Used git stash to temporarily save changes when switching branches.

Final Push & Cleanup

Pushed final code to GitHub.

Deleted unused feature branches after merging.

📁 Project Structure bash Copy Edit task4/ │── src/ # Source code │── README.md # Documentation │── .gitignore # Ignored files config │── screenshots/ # Screenshots if applicable 📝 Key Git Commands Used bash Copy Edit git init git branch dev git branch feature-homepage git checkout feature-homepage git add . git commit -m "Added homepage feature" git push origin feature-homepage git checkout dev git merge feature-homepage git push origin dev git checkout main git merge dev git push origin main git tag v1.0 git push origin v1.0
