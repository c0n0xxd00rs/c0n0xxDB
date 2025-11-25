

WORKFLOW 2 -------------------> GITHUB ========> YOUR PC ===========> GITHUB

( THIS MEANS THE PROJECT IS ALREADY ON GITHUB )



STEPS:

1. CLONE THE PROJECT ( FIRST TIME ONLY) ----------------> THIS DOWNLOADS THE PROJECTS TO YOUR COMPUTER.
   
git clone git@github.com:username/repo.git 
      
IT CAN BE SSH | HTTPS


2. THEN  ENTER THE FOLDER/ DIRECTORY
  
cd repo
  
that's it. you now have the project




==================================================================================

 ALWAYS PULL UPDATES BEFORE YOU DO ANY WORK

WHY? : THIS MAKES SURE YOUR COMPUTER HAS THE LATEST CODE 

   
git pull origin main
   

THIS IS LIKE CLICKING -----------> Refresh



=====================================================================================

YOU CAN MAKE CHANGES ON BOTH YOUR EDITOR 

I.E; YOU EDIT FILES NORMALLY

=========================================================================================


CHECK WHAT YOU CHANGED

  
git status
  
: THIS SHOWS ; UNTRACKED FILES(NEW), MODIFIED FILES, STAGED FILES

===============================================================================================


TRACK THE FILES YOU CHANGED 
   
git add 
  
ADD ONE FILE
git add file.txt

ADD MULTIPLE FILES
git add file1 file2

ADD ALL FILES
git add .

======================================================================================

SAVE THE CHANGES (COMMIT)

  git commit -m "message describing the change"

======================================================================================

PUSH CHANGES BACK TO GITHUB
  
git push
  
THAT'S IT









======================================================================================

FLOW SUMMARY : GITHUB TO PC TO GITHUB

1. DOWNLOAD REPO 
  
git clone
  

2. GET THE LASTEST CODE
  
git pull
  

3. MAKE CHANGES ------------> modifying your files or code

4. TRACK CHANGES 
  
git add .
  

5. SAVE CHANGES
  
 git commit -m "meassage"
  

6. UPLOAD CHANGES
  
git push 
  


