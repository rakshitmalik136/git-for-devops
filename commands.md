# Git Commands Cheat Sheet


## 1. Initialization

### `git init`
- Initializes a new Git repository in the current directory.

---

## 2. File Operations and Staging

### `git status`
- Displays the status of the working directory and staging area, showing tracked, untracked, and staged files.

### `git add .`
- Stages all changes (new, modified, and deleted files) in the repository for the next commit.

### `git add <file>`
- Stages a specific file for commit.

### `git rm --cached <file>`
- Removes a file from the staging area but keeps it in the working directory (untracked).

---

## 3. Committing Changes

### `git commit -m "<message>"`
- Commits the staged changes with a commit message.

### `git log`
- Displays the commit history, including the commit hash, author, date, and message.

### `git log --oneline`
- Shows a simplified, one-line-per-commit view of the commit history.

---

## 4. Configuration

### `git config --global user.name "<name>"`
- Sets the user name for all Git repositories globally.

### `git config --global user.email "<email>"`
- Sets the user email for all Git repositories globally.

---

## 5. Branching

### `git branch`
- Lists all branches in the current repository.

### `git checkout -b <branch>`
- Creates a new branch and switches to it.

### `git checkout <branch>`
- Switches to an existing branch.

---

## 6. Additional Commands

### `history`
- Shows the list of all previously executed commands in the terminal session.

---

## 7. Common Workflows Example

- **Initialize a Git repository:**
  - `git init`

- **Create and modify files:**
  - `touch hello.txt`
  - `vim hello.txt`

- **Check the status of the repository:**
  - `git status`

- **Stage and commit changes:**
  - `git add hello.txt`
  - `git commit -m "say hello"`

- **Create a new branch and switch to it:**
  - `git checkout -b dev`

- **View the commit history in a simplified format:**
  - `git log --oneline`
