# Initializing Project Locally

**Steps:**
- Create local repository;

        mkdir examplerepo
- Add necessary files, e.g README.md;

        touch README.md
- initialize new git repository;

        git init
- Create new remote repository
- Copy remote repository url;

        git@github.com:yourusername/examplerepo.git 
- On your local project terminal, add remote url;

        git remote add origin git@github.com:yourusername/examplerepo.git
- create main branch;

        git branch -M main
- pull remote files

        git pull
- Track files

        git add .
- Commit changes

        git commit
- Push to remote;

        git push origin main