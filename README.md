### 202434774 Park Juyoung
---

## 1. Git Overview

Git is a **distributed version control system (DVCS)** used to track changes and collaborate in software development. Each developer has a full copy of the repository, enabling independent work.

### Key Concepts:
- **Version Control**: Manages the history of changes to your codebase.
- **Distributed System**: Every developer has a clone of the entire repository.

### Three Git States:
- **Modified**: Files have been changed but not yet staged.
- **Staged**: Files are marked to be committed.
- **Committed**: Changes are safely stored in the repository.

---

## 2. Git Configuration

Git can be configured at three levels:
1. **System Level**: Affects all users and repositories on the system (`/etc/gitconfig`).
2. **Global Level**: Affects all repositories of the current user (`~/.config/git/config`).
3. **Local Level**: Affects only the current repository (`.git/config`).

Each level overrides values in the previous level (system -> global -> local).

---

## 3. Basic Git Workflow

### Core Commands:
- **git init**: Initialize a new Git repository.
- **git status**: Check the working directory and staging area.
- **git add \<file>**: Stage files for commit.
- **git commit -m "message"**: Commit changes to the repository.
- **git log**: View commit history.
- **git push origin main**: Push commits to a remote repository.

### Branch Management:
- **git branch \<branch>**: Create a new branch.
- **git checkout \<branch>**: Switch between branches.
- **git merge \<branch>**: Merge a branch into the current branch.

---

## 4. Common Git Issues & Best Practices

- **Merge Conflicts**: Occur when changes to the same code conflict.
  - **Resolution**: Edit the conflicted file, stage the changes, and commit.

### Best Practices:
- Commit frequently and write clear commit messages.
- Use branches to maintain stability in the main branch.
- Utilize pull requests for code reviews.
