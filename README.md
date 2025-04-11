# 🚀 Internship Task 4 — Version-Controlled DevOps Project

> **Submitted for:** Elevate Lab — DevOps Internship  
> **Author:** Raj Kumar Mourya

---

## 📌 Project Description

This repository contains my solution for **Task 4** of the DevOps Internship provided by **Elevate Lab**.  
The objective of the task is to manage a DevOps project using Git best practices including proper branching, pull requests, commit tracking, tagging, and documentation.

---

## 🛠️ Tools Used

- Git (Command Line)
- GitHub (Remote Repository)

---

## ⚙️ Setup Instructions

No special tools or frameworks are required. This project uses basic Git and GitHub features. Here's what I did step-by-step:

1. ✅ Created a new GitHub repository.
2. ✅ Initialized a local repository using `git init`.
3. ✅ Added some sample files to track.
4. ✅ Linked the local repo to GitHub using `git remote add origin`.
5. ✅ Created and switched between branches:
   - `main`
   - `dev`
   - `feature/<feature-name>`
6. ✅ Made individual commits to each branch.
7. ✅ Created a **Pull Request** from the `feature` branch to `main`.
8. ✅ Pushed all branches to GitHub with `git push -u origin <branch-name>`.

---

## 🌿 Branching Strategy

| Branch        | Purpose                                 |
|---------------|------------------------------------------|
| `main`        | Final stable code                        |
| `dev`         | Integration and testing                  |
| `feature/*`   | Individual features or task development  |

---

## 📸 Screenshots

Here are a few snapshots of my Git workflow:

<img src="https://github.com/user-attachments/assets/21995381-7d0d-41cb-9420-17979790fa75" width="600" alt="Branching Strategy"/>

<img src="https://github.com/user-attachments/assets/0d921b89-1c17-42b4-818c-317882196b99" width="600" alt="Pull Request"/>

<img src="https://github.com/user-attachments/assets/e3491fac-296f-43ca-92c3-7f4aa1d2454a" width="600" alt="Commits and Pushes"/>

---

## 🏷️ Git Tags

Tags can be used for versioning.  
Example:
```bash
git tag -a v1.0 -m "Initial stable version"
git push origin v1.0



