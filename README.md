# git_assignment_HeroVired
This Repo is to perform the GIT graded Assignment 
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
