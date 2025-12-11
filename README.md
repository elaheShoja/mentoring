# How to Start an Exercise

This guide will show you how to work on exercises using your own fork of the repository.

---

## 1️⃣ Fork the Repository
1. Click the **Fork** button at the top-right of this page.  
2. This will create a copy of this repository in your GitHub account.

---

## 2️⃣ Clone Your Fork
Open a terminal and run:

git clone <your-fork-URL>
cd <repository-name>


---

## 3️⃣ Sync with the Original Repository (Upstream)
This keeps your fork updated with the mentor's repository.

git remote add upstream https://github.com/YOUR-USERNAME/mentoring-repo.git

git fetch upstream
git checkout main
git merge upstream/main

---

## 4️⃣ Create a New Branch for the Exercise
git checkout -b exercise1
> Always create a new branch for each exercise.

---

## 5️⃣ Complete the Exercise
- Open the folder for this exercise: `exercises/exercise1`  
- Add or edit files as instructed in the exercise README:
  - `index.html` → HTML file  
  - `style.css` → CSS file  
  - `script.js` → JavaScript file (if needed)  

---

## 6️⃣ Commit and Push Your Changes
git add .
git commit -m "Complete Exercise 1"
git push origin exercise1

---

## 7️⃣ Create a Pull Request
1. Go to your fork on GitHub.  
2. Click **Compare & pull request**.  
3. Make sure the **base repository** is the original mentoring repo and the **base branch** is `main`.  
4. Add a short description of your work and click **Create pull request**.

---

💡 Notes:
- **Fork** = your personal copy of the repo  
- **Upstream** = the mentor's original repo  
- **Branch** = a separate line of work for each exercise  
- **PR (Pull Request)** = request to merge your changes into the mentor's repo
