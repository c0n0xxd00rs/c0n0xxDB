
CH:6


BRANCHING :


A Branch is like making a copy of your project so you can work without touching main

Reasons / Why?; Because you don't want to ruin/spoil min

---------------------------------------------------------------------


TO CREATE A BRANCH; 
  
git checkout -b  "your branch-name" 
  
THIS MEANS; CREATE A COPY OF THE PROJECT AND CALL IT "YOUR BRNCH-NAME" 

----------------------------------------------------------------------------------

TO CHECK WHAT BRNCH YOU'RE ON
  
git branch
  
The one with * is where you're.


-------------------------------------------------------------------------------

TO SWITCH BETWEEN BRANCH
  
git switch main 

or

git checkout "your branch name"

""-------> is not included

----------------------------------------------------------------------

DELETING LOCAL BRANCH
  
git branch -d branchname
  

--------------------------------------------------------
FORCE DELETE
   
git branch -D branchname


-==================================================================

 DELETE A REMOTE BRANCH 

  
git push origin --delete branchname

git push origin :branchname

----------------------------------------------------------------------------


TO CHECK BRANCH DELETION

  
git branch

git branch -r
  
