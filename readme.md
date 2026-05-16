# this is new repo
<div>
PS D:\gitdemo\LocalRepo> git branch 
* main

PS D:\gitdemo\LocalRepo> git checkout -b feature1
Switched to a new branch 'feature1'
PS D:\gitdemo\LocalRepo> git branch 
* feature1
  main

PS D:\gitdemo\LocalRepo> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

PS D:\gitdemo\LocalRepo> git checkout -b xyz
Switched to a new branch 'xyz'
PS D:\gitdemo\LocalRepo> git branch 
  feature1
  main
* xyz

PS D:\gitdemo\LocalRepo> git branch -d feature1
Deleted branch feature1 (was e40e9e5).
PS D:\gitdemo\LocalRepo> git branch 
  main
* xyz
PS D:\gitdemo\LocalRepo> 

</div>