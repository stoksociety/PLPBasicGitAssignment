# PLPBasicGitAssignment

Git Initialization:

Initialize a new Git repository in your local folder:
bash
git init

Connecting to GitHub:

Link your local repository to the GitHub repository you created earlier:
bash
git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git
Replace your-username with your GitHub username.

Making Changes
Create a File:
Inside your local folder, create a new text file called hello.txt.
Add a simple text message like "Hello, Git!" inside hello.txt.

Committing Changes:
Stage the changes:
bash
git add hello.txt

Commit the changes:
bash
git commit -m "Add hello.txt with a greeting"

Pushing to GitHub
Pushing to GitHub:
Push the committed changes to your GitHub repository:
bash
git push -u origin main

 Verification
Verify on GitHub:
Visit your GitHub repository in a web browser.
Confirm that the hello.txt file and the commit message "Add hello.txt with a greeting" are visible.
