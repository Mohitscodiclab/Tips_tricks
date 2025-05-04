### 📘 README.md (Git Clone Instructions)

# Cloning a GitHub Repository Using Git Bash

This guide explains how to clone a GitHub repository to your local machine using Git Bash.

---

## ✅ Prerequisites

- Git installed on your system
- Git Bash installed
- A GitHub repository you want to clone (public or private)

---

## 🔁 What is `git clone`?

`git clone` is used to create a local copy of a GitHub repository. This allows you to work on the project locally and push changes when needed.

---

## 🚀 Steps to Clone a Repository

### 1. Open GitHub Repository

Go to the repository page on GitHub that you want to clone.

Click the green **Code** button and copy the repository URL:

- HTTPS: `https://github.com/username/repo-name.git`
- SSH: `git@github.com:username/repo-name.git`

---

### 2. Open Git Bash

Launch Git Bash on your computer.

---

### 3. Navigate to the Folder Where You Want to Clone

Use the `cd` command to go to your desired directory:

```bash
cd path/to/your/folder
````

---

### 4. Clone the Repository

Use the following command (replace with your copied URL):

* For HTTPS:

```bash
git clone https://github.com/username/repo-name.git
```

* For SSH:

```bash
git clone git@github.com:username/repo-name.git
```

---

### 5. Enter the Project Directory

After cloning, move into the project folder:

```bash
cd repo-name
```

---

## ✅ Done!

You now have a local copy of the GitHub repository and can start working on it using Git commands.

