GitHub Repository Creation:
  - Logged in to your GitHub account.
  - Created a new repository on GitHub ("PLPBasicGitAssignment")
Local Folder Setup:
  - Created a new folder on your local machine ("PLPBasicGitAssignment").
  - Open a terminal or command prompt and navigate to the created folder.
Git Initialization:
  - Initialize a new Git repository in your local folder.
Connecting to GitHub:
  - Linking local repository to the created GitHub repository
Create a File:
  - Inside your local folder, create a new text file (e.g., `hello.txt`).
  - Add a simple text message (e.g., "Hello, Git!").
Committing Changes:
  - Stage the changes.
   ```bash
   git add hello.txt
   ```
  - Commit the changes.
   ```bash
   git commit -m "Add hello.txt with a greeting"
   ```
Pushing to GitHub:
  - Push the committed changes to your GitHub repository.
   ```bash
   git push -u origin main
```
Verify on GitHub:
  - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.
Otherwise from Github you can push the file like this
Click create repository and type the name of your repository
Open your git bash on the specific folder where your file is stored and follow the below steps
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https:"your url"
git push -u origin main
