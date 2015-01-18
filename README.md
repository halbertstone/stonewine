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



...The package.json file created by the command: npm init
~/MEAN_STUFF/test-b/$ cat ../stonewine/package.json 
{
  "name": "stonewine",
  "version": "1.0.0",
  "description": "Stonewine application",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/halbertstone/stonewine.git"
  },
  "keywords": [
    "hapi",
    "node"
  ],
  "author": "HStone",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/halbertstone/stonewine/issues"
  },
  "homepage": "https://github.com/halbertstone/stonewine",
  "dependencies": {
    "hapi": "^8.0.0"
  }
}
~/MEAN_STUFF/test-b/$ Stonewine
  2 How to...
  3 Setup a hapi project within git
  4 
  5 Create a new repository at GitHub
  6 collect the URI for the repository:
  7      https://github.com/halbertstone/stonewine.git
  8 
  9 
 10 Create Your Local Repository
 11 mkdir stonewine
 12 cd stonewine
 13 git init  // creates .git directory, the local repository
 14 npm init  // wizard; answer questions, creates package.json
 15 npm install --save hapi // installs hapi and saves infor to package.json
 16 
 17 git add README.md
 18 git commit -m 'The initial commit'
 19 
 20 git remote add origin https://github.com/halbertstone/stonewine.git
 21     //origin is the traditional name of the Remote Repository main-line
 22 
 23 git push -u origin master
 24     username .....
 25     pwd .....
 26 
 27     // master is the traditional/default local repository branch name
 28     // this pushes the local branch 'master' to the remote branch 'origin'
 29 
 30 
 31 
 32 ...The package.json file created by the command: npm init
 33 ~/MEAN_STUFF/test-b/$ cat ../stonewine/package.json 
 34 {
 35   "name": "stonewine",
 36   "version": "1.0.0",
 37   "description": "Stonewine application",
 38   "main": "index.js",
 39   "scripts": {
 40     "test": "echo \"Error: no test specified\" && exit 1"
 41   },
 42   "repository": {
 43     "type": "git",
 44     "url": "https://github.com/halbertstone/stonewine.git"
 45   },
 46   "keywords": [
 47     "hapi",
 48     "node"
 49   ],
 50   "author": "HStone",
 51   "license": "ISC",
 52   "bugs": {
 53     "url": "https://github.com/halbertstone/stonewine/issues"
 54   },
 55   "homepage": "https://github.com/halbertstone/stonewine",
 56   "dependencies": {
 57     "hapi": "^8.0.0"
 58   }
 59 }
 60 ~/MEAN_STUFF/test-b/$ 
