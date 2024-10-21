 # Git Commands Reference

## 1. Directory Operations
- **Create a directory**
  mkdir git-for-devops

- **Navigate into the directory**
  cd git-for-devops

## 2. File Operations
- **Create a file**
  echo "Hello, World!" > hello.txt

- **View file contents**
  cat hello.txt

- **Delete a file**
  rm hello.txt

## 3. Git Initialization
- **Initialize a Git repository**
  git init

## 4. File Renaming
- **Rename a file**
  mv hellp hello

## 5. Git Status
- **Check the status of the repository**
  git status

## 6. Staging and Committing
- **Add files to staging area**
  git add filename.txt

- **Commit changes**
  git commit -m "Commit message"

## 7. Branching
- **Create and switch to a new branch**
  git checkout -b branch-name

- **Switch back to the master branch**
  git checkout master

## 8. Logging
- **View commit logs**
  git log

- **View logs in one line**
  git log --oneline

- **View logs as a graph**
  git log --graph --oneline --decorate

## 9. Configuration
- **Set global Git user information**
  git config --global user.name "Your Name"
  git config --global user.email "youremail@example.com"

## 10. File Restoration
- **Restore a deleted file**
  git restore filename.txt

## 11. Viewing Branch Information
- **Show current branches**
  git branch -v
