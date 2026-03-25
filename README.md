# GitHub-Pracatice

Step 1: 
Make a GitHub Repository and add a Collaborator.

Step 2:
Suppose two Person working on a same project-
Shikhar - main
Ansh -  collaborator

Ansh will clone the whole Repo and pass the following commands~

1. Clone the Repo:
```bash
git clone https://github.com/TheShikharr/GitHub-Pracatice.git
```
2. move to the same repo as of GitHub Repo:
```bash
cd .\GitHub-Pracatice\
```
3. Make its own branch first:
```bash
git switch -C feature/Frontend
```
4. To view in which branch itself is:
```bash
git branch
```
5. After adding changes in the new branch i.e feature/Frontend:
```bash
git add .
```
6. commit:
```bash
git commit -m "Frontend Added"
```
7. push to github:
```bash
git push -u origin feature/Frontend
```

After this the code will be saved in the branch-feature/Frontend.

Step 3:
Shikhar will see the whole code in the branch-feature/Frontend and verify it, if it is right or wrong. Then he can merge the branch code with the main code.

Shikhar will use the following git commands~

-git fetch
-git branch
-git switch feature/Frontend         [code in that branch will be visible in vscode editor]
-git switch main
-git merge feature/Frontend
-git push origin main

After this we will reload the GitHub and the merged code will be visible in the main branch.

Step 4:
Now, Ansh will fetch the whole code in the main branch, so he can work further with the project.

-git switch main
-git fetch
-git pull
