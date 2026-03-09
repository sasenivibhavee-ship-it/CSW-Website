# Project Collaboration Guide

Welcome to the project!
This guide explains how to set up the repository on your computer and work on your **own branch**.

---

# 1. Accept the GitHub Invitation

1. Check your email for the GitHub collaboration invite.
2. Click **Accept Invitation**.
3. You should now see this repository in your GitHub account.

---

# 2. Install Git (If Not Installed)

Download Git from:

https://git-scm.com/downloads

Verify installation:

```bash
git --version
```

---

# 3. Clone the Repository

Copy the repository URL from GitHub.

Then run:

```bash
git clone https://github.com/REPO_OWNER/REPO_NAME.git
```

Example:

```bash
git clone https://github.com/username/project-name.git
```


```run
git clone https://github.com/sasenivibhavee-ship-it/CSW-Website.git
```
 

Move into the project folder:

```bash
cd project-name
```

---

# 4. Create Your Own Branch

Each collaborator should work in their **own branch**.
currently i have created branches for you guys just checkin to your branch by 


```bash
git checkout your-existing-branchname
```
Branch Names -
Student001
Student002
Student003
Student004
Developmet (testing will be done in this branch)
Main(do not work in this branch)

Create a branch if neccesary:

```bash
git checkout -b your-name-branch
```

Example:

```bash
git checkout -b john-feature
```

Verify branch:

```bash
git branch
```

---

# 5. Work on the Project

Make your changes to the project files.

Check changes:

```bash
git status
```

---

# 6. Add and Commit Changes

Stage your changes:

```bash
git add .
```

Commit your work:

```bash
git commit -m "Added new feature"
```

---

# 7. Push Your Branch to GitHub

Push your branch to GitHub:

```bash
git push origin your-name-branch
```

Example:

```bash
git push origin john-feature
```

---

# 8. Create a Pull Request

1. Go to the GitHub repository.
2. You will see **Compare & Pull Request**.
3. Click it.
4. Add a description of your changes.
5. Submit the pull request.

---

# 9. Keep Your Branch Updated

Before starting work each day:

```bash
git checkout main
git pull origin main
git checkout your-name-branch
git merge main
```

---

# 10. Important Rules

* Do **NOT commit directly to `main`**
* Always work in **your own branch**
* Write **clear commit messages**
* Test your code before pushing

---

# Example Workflow

```bash
git clone https://github.com/username/project-name.git
cd project-name
git checkout -b my-feature
# make changes
git add .
git commit -m "My feature update"
git push origin my-feature
```

Then create a **Pull Request on GitHub**.

---

