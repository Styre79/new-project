1. Install the Git client;
2. Create a new repository new-project on GitHub;
3. Create a new new-project folder in your environment;
4. Go to the new-project folder;
5. Initialize the new repository in the new-project folder using the command: git init
6. Link the local repository to your GitHub repository using the command: git remote add origin https://github.com/<your_account>/new-project.git;
7. Create a README.md file and add the first instructions to it;
8. Create the development branch and switch to it using: git checkout -b development;
9. Create a README.md file and add appropriate instructions to it;
10. Add the contents of the folder to the commit using: git add .;
11. Add a commit to the repository using: git commit -m "Created README.md";
12. Switch to the main branch using: git chekout main;
13. Merge changes in the development branch with the main branch using: git merge development;
14. Push the local repository to GitHub with: git push -u origin main