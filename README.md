Stonewine 
How to...
Setup a hapi project within git

Create a new repository at GitHub
collect the URI for the repository:
     https://github.com/halbertstone/stonewine.git


Create Your Local Repository 
mkdir stonewine
cd stonewine
git init  // creates .git directory, the local repository
npm init  // wizard; answer questions, creates package.json
npm install --save hapi // installs hapi and saves infor to package.json

git add README.md
git commit -m 'The initial commit'

git remote add origin https://github.com/halbertstone/stonewine.git
    //origin is the traditional name of the Remote Repository main-line

git push -u origin master
    username .....
    pwd .....

    // master is the traditional/default local repository branch name
    // this pushes the local branch 'master' to the remote branch 'origin'




