# git-practice

# git  Fetch

this is used to fetch the changes made by other developer in the same branch where your are working and it will only show the chnages and it will not merge the chnages with your chnages  in the same branch , and you you want you can merge after words 

it only shoes the difference between your ad other developpers in the same branch

# git restore 
git restore 
    command : 
        when file is in working directory ( before add command )   ---      git restore <file name>
    
        when file is in staging directory ( after add and commit command )   ---      git restore --staged <file name>

            here first the file will move to working area from stgaed area and then we have to run the git restore <file name> and then file content will chang
# git pull


this will pull and merge the chnages made by other developer in the same repo/branch where your working 

this is combination of fetch + merge 

# git rebase

this is used to put your commit on top of the other commit,  

suppose you are working in Feature branch and there are some commit s done in main branch , then switch to feature branch  run the below command 

    in main branch 

    git log --oneline

    in feature branch 

    git add <file name>
    git commit -m <messgae>
    git rebase <branch name>
    git log --oneline 

you can see that your latest commit in feature branch is at the top of the commit in the main branch 

