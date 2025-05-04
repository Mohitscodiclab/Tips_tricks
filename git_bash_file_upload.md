### 📘 How to upload files on Github using Git bash

````markdown
# Uploading Files to GitHub Using Git Bash

This guide provides step-by-step instructions on how to upload (push) your project files to a GitHub repository using Git Bash.

---

## ✅ Prerequisites

- Git installed on your system
- A GitHub account
- A GitHub repository (public or private)
- Git Bash installed

---

## 🚀 Steps to Upload Files

### 1. Open Git Bash
Launch Git Bash on your computer.

### 2. Navigate to Your Project Directory
Use the `cd` command to go to the folder containing your project files.

```bash
cd path/to/your/folder
````

### 3. Initialize Git (if not already initialized)

```bash
git init
```

### 4. Add Remote Repository

Copy the repository URL from GitHub and add it as a remote.

* For HTTPS:

```bash
git remote add origin https://github.com/yourusername/repo-name.git
```

* For SSH:

```bash
git remote add origin git@github.com:yourusername/repo-name.git
```

Verify the remote:

```bash
git remote -v
```

### 5. Add Files to Staging Area

```bash
git add .
```

### 6. Commit the Files

```bash
git commit -m "Initial commit"
```

### 7. Push to GitHub

If this is your first push and the branch is not yet set to `main`:

```bash
git branch -M main
```

Then push:

```bash
git push -u origin main
```

> 🔐 Note: If using HTTPS, GitHub will ask for your username and a **personal access token** (not your password).

---

## ✅ Success!

Your files are now uploaded to your GitHub repository.
