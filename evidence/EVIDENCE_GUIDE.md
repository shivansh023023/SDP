# Evidence Directory - Git & GitHub Execution Records

This folder contains authentic terminal session recordings and visual terminal snapshots captured directly on the local machine during the execution of this assignment.

## Generated Terminal Evidence Files

| Step | Terminal Log File | Screenshot PNG | Description |
|------|-------------------|----------------|-------------|
| 1 | `01_git_init_status.txt` | `01_git_init_status.png` | `git --version`, `git config`, `git init`, `git branch -M main`, `git status` |
| 2 | `02_initial_commit.txt` | `02_initial_commit.png` | `git add index.html about.html`, `git commit` (hash: `5f7d64f`) |
| 3 | `03_second_commit.txt` | `03_second_commit.png` | Adding welcome section to `index.html`, `git commit` (hash: `df0ad2b`) |
| 4 | `04_feature_branch.txt` | `04_feature_branch.png` | `git branch feature`, `git switch feature`, `git branch` active verification |
| 5 | `05_feature_commit.txt` | `05_feature_commit.png` | Adding features list to `about.html`, `git commit` (hash: `81ef279`) |
| 6 | `06_merge_operation.txt` | `06_merge_operation.png` | `git switch main`, `git merge feature` (fast-forward merge) |
| 7 | `07_commit_history.txt` | `07_commit_history.png` | `git log --oneline --graph --all --decorate`, `git branch -a` |
| 8 | `08_gitignore_verification.txt` | `08_gitignore_verification.png` | Verifying `debug.log` and `temp/` exclusion via `git status --ignored` |
| 9 | `09_gitignore_commit.txt` | `09_gitignore_commit.png` | Committing `.gitignore` into `main` (hash: `a4a1a1f`) |
| 10 | `10_git_revert_operation.txt` | `10_git_revert_operation.png` | Temporary commit (`69ddbb8`) and non-destructive `git revert` (`239e2df`) |

---

## Instructions for GitHub Web Browser Screenshots (Optional Submission Evidence)

Once you complete the push to your remote GitHub repository (`https://github.com/shivansh023023/SDP`), you can capture two browser screenshots:

1. **GitHub Repository Landing Page**:
   - Navigate in your browser to: `https://github.com/shivansh023023/SDP`
   - Ensure the repository visibility says **Public**.
   - Take a screenshot of the main file list (`index.html`, `about.html`, `.gitignore`, `git_commands.txt`, `README.md`).
   - Save as: `GitHub_Assignment/evidence/11_github_public_repo.png`

2. **GitHub Commits History Page**:
   - Navigate in your browser to: `https://github.com/shivansh023023/SDP/commits/main`
   - Verify all commits are displayed chronologically:
     - *Add project documentation, git commands reference, and execution evidence*
     - *Revert "Add temporary demonstration content"*
     - *Add temporary demonstration content*
     - *Add gitignore rules for logs and temporary files*
     - *Add website features to about page*
     - *Update homepage content*
     - *Initial commit: Add homepage and about page*
   - Take a screenshot of this commit timeline.
   - Save as: `GitHub_Assignment/evidence/12_github_commit_history.png`
