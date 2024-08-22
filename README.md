# PLPBasicGitAssignment

**Basic Git and GitHub Workflow Assignment**

**Objective:**
The objective is to familiarize with creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

**Requirements:**
- A GitHub account
- Git installed on your local machine
- A code editor of your choice

**Task 1: Repository Setup**

1. **GitHub Repository Creation:**
   - Logged in to GitHub account.
   - Created a new repository named `PLPBasicGitAssignment`.
   - Initialized it with a README file.

**Task 2: Local Setup**

2. **Local Folder Setup:**
   - Created a folder named `PLPBasicGitAssignment` on the local machine.
   - Opened terminal and navigated to the folder with the command: `cd path/to/PLPBasicGitAssignment`.

3. **Git Initialization:**
   - Initialized a new Git repository in the local folder with: `git init`.

4. **Connecting to GitHub:**
   - Linked the local repository to the GitHub repository with: `git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git`.
   - Replaced `your-username` with GitHub username.

**Task 3: Making Changes**

5. **Create a File:**
   - Created a new text file named `hello.txt`.
   - Added the text "Hello, Git!" to the file.

6. **Committing Changes:**
   - Staged the changes with: `git add hello.txt`.
   - Committed the changes with: `git commit -m "Add hello.txt with a greeting"`.

**Task 4: Pushing to GitHub**

7. **Push to GitHub:**
   - Attempted to push committed changes to GitHub with: `git push -u origin master`.
   - Encountered a rejection due to non-fast-forward error.
   - Pulled changes from the remote repository with unrelated histories allowed using: `git pull origin master --allow-unrelated-histories`.
   - Resolved merge conflicts and committed the resolved changes with: `git add <file-with-conflict>` and `git commit -m "Resolve merge conflicts"`.
   - Successfully pushed changes with: `git push origin master`.

**Task 5: Verification**

8. **Verify on GitHub:**
   - Visited the GitHub repository in a web browser.
   - Confirmed that the `hello.txt` file and commit message ("Add hello.txt with a greeting") were visible.

**Submission:**
- Ensured all changes were pushed to GitHub.
- Shared the link to the GitHub repository as per class instructions.

