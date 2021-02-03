# Grievance

# Grievance

# Live Demo at: [here](https://gomega-pro.github.io/GOMEGA/)

### **Initial Local Setup**

git --version

### To configure your user name to be used by Git, type the following at the prompt:
git config --global user.name "Your Name"

### To configure your email to be used by Git, type the following at the prompt:
git config --global user.email <your email address>

### You can check your default Git global configuration, you can type the following at the prompt:
git config --list

`git clone https://github.com/Kmit-Greivance-Redressal-System/Grievance.git`

`git init`

### after modifying

### **Creating a Pull Request**

**Step 1:** Create a new branch from master

`git checkout -b <your branch-name>`

**Step 2:** Commit the changes to the newly created branch

`git add .`

`git commit -m "<commit message>"`

**Step 3:** Push the branch to the remote

`git push origin <your branch name>`

**Step 4:** Go to the URL generated the end of the push message

(OR)

` https://github.com/GOMEGA-PRO/GOMEGA/pull/new/<your branch name>`

**~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~**

### After the completion squash and merge process to update the local i.e in master branch with the current changes

`git checkout master`

`git pull`
