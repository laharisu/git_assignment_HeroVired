# git_assignment_HeroVired
This Repo is to perform the GIT graded Assignment 
**Question 1**
# Create a new repository on GitHub named "git_assignment_HeroVired"

b. Create a ‘dev’ branch and add the code:


# Clone the repository
git clone https://github.com/your-username/git_assignment_HeroVired.git
cd git_assignment_HeroVired

# Create and switch to the 'dev' branch
git checkout -b dev

# Add the provided code to the Calculator.py file

# Commit the changes
git add Calculator.py
git commit -m "Add initial code with dev branch"
c. Merge ‘dev’ branch with the main branch and make a release of version 1:
bash

# Switch to the main branch
git checkout main

# Merge the 'dev' branch into 'main'
git merge dev

# Create a tag for version 1
git tag -a v1.0 -m "Version 1.0 release"

# Push changes to the remote repository
git push origin main --tags
d. Add collaborators:
On GitHub, go to your repository.
Click on "Settings" > "Manage access" > "Invite a collaborator."
Add your classmates as collaborators.
e. Implement the square root feature:

# Create a new branch for the feature
git checkout -b feature/sqrt

# Uncomment and add the square root function in Calculator.py
# Commit the changes
git add Calculator.py
git commit -m "Add square root feature"
g. Fix the critical bug in the 'dev' branch:

# Switch back to the 'dev' branch
git checkout dev

# Update the divide function to fix the bug
# Commit the changes
git add Calculator.py
git commit -m "Fix divide function bug"
h. Create a pull request for the ‘feature/sqrt’ branch:
Push the 'feature/sqrt' branch to GitHub: git push origin feature/sqrt

Click on "Compare & pull request" for the 'feature/sqrt' branch.
Write a description for the pull request.
Request a code review.
i. Request code review and make improvements:
Collaborator reviews the pull request and suggests changes.
Make necessary changes, commit, and push them.
j. Merge 'feature/sqrt' into ‘dev’ branch:

# Switch to the 'dev' branch
git checkout dev

# Merge 'feature/sqrt' into 'dev'
git merge feature/sqrt

# Push changes to the remote repository
git push origin dev
k. Test and merge ‘dev’ into ‘main’ for version 2 release:

# Switch to the 'main' branch
git checkout main

# Merge 'dev' into 'main'
git merge dev

# Create a tag for version 2
git tag -a v2.0 -m "Version 2.0 release"

# Push changes to the remote repository
git push origin main --tags


**Question 2:**




Step 1: Initialize Git LFS in your Repository

git lfs install
.

Step 2: Track Binary Files with Git LFS

git lfs track "*.pdf"


Step 3: 
Add and Commit Binary Files
git add lfstry.pdf

Step 4: git commit -m "Add binary file using Git LFS"

Step 5: git push origin master

Step 6: git clone https://github.com/laharisu/git_assignment_HeroVired.git

Step 7: Verify Binary File Download
git lfs pull


**Question 3:**

Step 1: Create a New Branch for Circle Area Feature

git checkout main

# Create a new branch for the circle area feature
git checkout -b feature/circle-area

Step 2: Stash Changes for Circle Area Feature

# Stash changes
git stash

# Verify working directory is clean
git status

Step 3: Create a New Branch for Rectangle Area Feature

# Switch back to the main branch
git checkout main

# Create a new branch for the rectangle area feature
git checkout -b feature/rectangle-area

Step 4: Stash Changes for Rectangle Area Feature
bash
Copy code
# Stash changes
git stash

# Verify working directory is clean
git status
Step 5: Switch Back to Circle Area Branch and Retrieve Stashed Changes
bash
Copy code
# Switch back to the circle area branch
git checkout feature/circle-area

# Retrieve stashed changes
git stash apply
Step 6: Complete Circle Area Feature Implementation
Make the necessary changes to complete the circle area feature.

bash
Copy code
# Add changes to the staging area
git add .

# Commit changes
git commit -m "Complete circle area feature implementation"

# Push changes to remote repository
git push origin feature/circle-area
Step 7: Switch Back to Rectangle Area Branch and Retrieve Stashed Changes

# Switch back to the rectangle area branch
git checkout feature/rectangle-area

# Retrieve stashed changes
git stash apply

Step 8: Complete Rectangle Area Feature Implementation
Make the necessary changes to complete the rectangle area feature.


# Add changes to the staging area
git add .

# Commit changes
git commit -m "Complete rectangle area feature implementation"

# Push changes to remote repository
git push origin feature/rectangle-area
Step 9: Create Pull Requests
Create pull requests for both branches (feature/circle-area and feature/rectangle-area) into the dev branch.

Step 10: Review and Merge
Have another team member or reviewer review your pull requests.
After receiving approval, merge both pull requests into the main branch.
These steps provide a clear sequence of actions for updating the program and integrating new features into the main branch.

