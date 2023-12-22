# GIT-Cheatsheet

//Repository  
git init                                         //Initialize a new Git repo  
git clone <repo-url>                             // Clone a repo from a URL   

//Basics  
git status                                       //Show changes status   
git add <file>                                   //Add change to staging  
git commit -m "Message"                          //Commit changes with a message  
git log                                          //View commit history  

//Branching  
git branch                                       //List branches  
git branch <branch-name>                         //Create a new branch  
git checkout <branch-name>                       //Switch to a branch  
git merge <branch-name>                          //Merge changes from a branch  
git branch -d <branch-name>                      //Delete a branch  

//Remote repositories  
git remote                                       //List remotes  
git remote add <name> <url>                      //Add a remote  
git push <remote> <branch>                       //Push changes to a remote  
git pull <remote> <branch>                       //Pull changes from a remote  

//Undoing changes  
git pull                                         //Fetch and merge changes  
git fetch                                        //Fetch changes without merging  
git reset --hard HEAD                            //Discard changes  
git revert <commit-hash>                         //Revert changes in a commit  
