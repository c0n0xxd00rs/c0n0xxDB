

CH 5:



GIT WORKFLOW 1;

Computer (PC)----------->  Remote / Github(G)(Local Project not yet on GitHub)

RE; THIS IS WHEN YOU ALREADY HAVE A PROJECT/FOLDER ON YOUR COMPUTER AND WANT TO CREATE A GitHub REPO FOR IT.

STEPS: 

1. GET YOUR PROJECT FOLDER READY;

mkdir my_repo

cd my_repo


2. TURN THIS FOLDER INTO A GIT REPOSITORY | Initializing Git locally;

git init {Now the Folder is Git-enabled}.


3. WORKING FILES -----> MODIFICATIONS



4. ADD YOUR FILES (. = ALL)

git add . | git add filename1 filename2......and so on.

5. COMMIT (SAVE) PROJECT (-m = MESSAGE)

git commit -m "descriptions of what did"


6. CREATE A NEW REPO ON GITHUB

Re; Name it exactly thesame project(my_repo) or anything

don't initialize with README


7. CONNECT YOUR LOCAL FOLDER TO GITHUB

SSH:

git remote add origin
git@github.com:username/repo.git 


8. PUSH YOUR PROJECT TO GITHUB

git push -u origin main

{NOW YOUR PROJECT(MY-REPO) IS ONLINE ON GITHUB}



FLOW SUMMARY 

CREATE AND MOVE TO THE FOLDER
mkdir folder ------> making a folder

MOVE TO THE FOLDER
cd folder ------> moving to the folder

GIT INITIALIZE ; git init

WORKING FILES, CREATIONS AND MODIFICATIONS

FILES STATUS ; git status

TRACKING FILES | STAGING | INDEXING; git add .

COMMIT | SAVE ; git commit -m "a"

link of  SSH on GITHUB FROM YOUR NEW / EXISTING REPO FOR THE PROJECT USE; git remote aadd origin


UPLOAD TO GITHUB ; git push




