# GIT-Cheatsheet

<pre>

//Repository  
git init                              //Initialize a new Git repo  
git clone &lt;repo-url&gt;                  //Clone a repo from a URL   

//Basics  
git status                            //Show changes status   
git add &lt;file&gt;                        //Add change to staging  
git commit -m "Message"               //Commit changes with a message  
git log                               //View commit history  

//Branching  
git branch                            //List branches  
git branch &lt;branch-name&gt;              //Create a new branch  
git checkout &lt;branch-name&gt;            //Switch to a branch  
git merge &lt;branch-name&gt;               //Merge changes from a branch  
git branch -d &lt;branch-name&gt;           //Delete a branch  

//Remote repositories  
git remote                            //List remotes  
git remote add &lt;name&gt; &lt;url&gt;           //Add a remote  
git push &lt;remote&gt; &lt;branch&gt;            //Push changes to a remote  
git pull &lt;remote&gt; &lt;branch&gt;            //Pull changes from a remote  

//Undoing changes  
git pull                              //Fetch and merge changes  
git fetch                             //Fetch changes without merging  
git reset --hard HEAD                 //Discard changes  
git revert &lt;commit-hash&gt;              //Revert changes in a commit  

</pre>
