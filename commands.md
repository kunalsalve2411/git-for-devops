
### Essential Git Commands

### 1. Initialize a New Git Repository
```bash
git init
```
This command initializes a new, empty Git repository in the current directory.

### 2. Configure Username in Git
```bash
git config --global user.name "Your Name"
```
This sets your Git username for all repositories.

### 3. Configure Email in Git
```bash
git config --global user.email "your-email@example.com"
```
This sets your Git email address for all repositories.

### 4. Add Files to the Staging Area
```bash
git add <file-name>
```
This command stages the specified file for the next commit.

To stage all files in the current directory:
```bash
git add .
```

### 5. Commit Changes with a Message
```bash
git commit -m "Your commit message"
```
This command saves your changes to the local repository with a descriptive commit message.

### 6. View Commit History
```bash
git log
```
This shows the commit history, including commit hashes, author information, and commit messages.

### 7. Create and Switch to a New Branch
```bash
git checkout -b <branch-name>
```
This command creates a new branch and immediately switches to it.

### 8. View All Branches
```bash
git branch
```
This lists all branches in your repository, with an asterisk (`*`) marking the current branch.

### 9. Restore a File to Its Previous State
```bash
git restore <file-name>
```
This command restores a file from the most recent commit, discarding any local changes made to the file.

For staged files:
```bash
git restore --staged <file-name>
```

