Creating a New Repository
Create a README file:

bash
Copy code
echo "# se-assignment-day-3-environment-setup-0796776478" >> README.md
Initialize a new Git repository:

bash
Copy code
git init
Add the README file to the staging area:

bash
Copy code
git add README.md
Commit the file to the repository:

bash
Copy code
git commit -m "first commit"
Rename the default branch to main (if necessary):

bash
Copy code
git branch -M main
Add the remote repository:

bash
Copy code
git remote add origin https://github.com/Powerlearnproject/se-assignment-day-3-environment-setup-0796776478.git
Push your local repository to GitHub:

bash
Copy code
git push -u origin main
Pushing an Existing Repository
If you already have a local repository and you just want to push it to a new GitHub repository:

Add the remote repository:

bash
Copy code
git remote add origin https://github.com/Powerlearnproject/se-assignment-day-3-environment-setup-0796776478.git
Rename the default branch to main (if necessary):

bash
Copy code
git branch -M main
Push the existing repository to GitHub:

bash
Copy code
git push -u origin main
