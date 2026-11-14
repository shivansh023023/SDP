# Git & GitHub Workflow Demonstration

An academic assignment project demonstrating comprehensive Git version control workflows, branching and merging strategies, undo operations using `git revert`, `.gitignore` configurations, and software testing test case design.

## Project Structure

```text
GitHub_Assignment/
│
├── index.html          # Semantic HTML5 homepage with navigation & welcoming section
├── about.html          # Semantic HTML5 about page detailing project features
├── .gitignore          # Rules ignoring *.log files and the temp/ directory
├── git_commands.txt    # Complete reference log of all Git commands executed
├── README.md           # Project documentation and assignment overview
│
├── temp/               # Excluded folder for temporary build/runtime files
│   └── temporary.txt   # Sample temporary file (ignored by Git)
│
└── evidence/           # Terminal session outputs captured during execution
```

## Git Workflow Highlights

1. **Repository Initialization**: Initialized Git repository and set primary branch to `main`.
2. **Commit Progression**: Created initial and subsequent feature commits following professional commit messages.
3. **Feature Branching**: Created and switched to `feature` branch to develop feature enhancements independently.
4. **Fast-Forward Merge**: Merged `feature` back into `main` cleanly.
5. **Gitignore Rules**: Configured `.gitignore` to safely exclude log files (`*.log`) and temporary directories (`temp/`).
6. **Non-Destructive Undo**: Demonstrated `git revert` to reverse an unwanted commit safely while preserving historical integrity.
7. **Remote Publishing**: Connected to remote repository `https://github.com/shivansh023023/SDP` and synchronized branch history.

## Software Testing Overview

This project includes a comprehensive 10-scenario test suite for a user login system covering:
- Positive functional paths
- Negative validation checks
- Boundary value analysis (password length constraints)
- Security brute-force account lockout mechanisms (3-strike policy)

---
*Created as part of Software Development / Software Testing coursework.*
