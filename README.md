<<<<<<< HEAD
# MY-PORTFOLIO-WEBSITE 2nd-SY - 2025


=======
# portfolio_2nd_sy
2nd portfolio, using HTML, CSS, JS


To push your local project to GitHub using Git CMD and GitHub (Git SW = Git Software), follow these step-by-step commands:

✅ 1. Create a GitHub Repository
Go to https://github.com

Click New Repository

Give it a name (e.g., my-project)

Keep it public or private as per your need

Don’t initialize with README (optional)

Click Create Repository

✅ 2. Open Git CMD in your Project Folder
Navigate to your project folder in File Explorer → Right-click → Git Bash Here or Git CMD.

✅ 3. Initialize Git (if not already done)
bash
Copy
Edit
git init
✅ 4a. Add Remote Origin (link to GitHub repo)
Replace your-username and repo-name:

bash
Copy
Edit
git remote add origin https://github.com/your-username/repo-name.git

or 

✅ 4b. Create and switch to a new branch (instead of default main)
bash
Copy
Edit
git checkout -b my-branch-name

✅ 5. Add All Files
bash
Copy
Edit
git add .
✅ 6. Commit with a Message
bash
Copy
Edit
git commit -m "Initial commit"
✅ 7a. Push to GitHub
If it's your first push, use:

bash
Copy
Edit
git push -u origin main
If your branch is called master, use master instead of main.

✅ 7b. Push to GitHub on that new branch
bash
Copy
Edit
git push -u origin my-branch-name

*****************************************
⚠️ Common Errors:
"fatal: remote origin already exists" → run:
git remote remove origin
Then re-add remote.

Authentication issue: GitHub may ask for username and personal access token (instead of password).
Generate token here: https://github.com/settings/tokens


************************************
Git Bash uses Linux-style paths, so:

F: becomes /f

Backslashes (\) become forward slashes (/)

If folder names have spaces, wrap the entire path in double quotes (")
ex- cd "/f/coding nts/ZZ courses/portfolio site"

**************************************
>>>>>>> e4c302b3c42c444f6d3e48e4510b20930e155ab1
