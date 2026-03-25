# GitHub-Collaboration

Step 1: <br>
Make a GitHub Repository and add a Collaborator.<br><br>

Step 2: <br>
Suppose two Person working on a same project-<br>
Shikhar - main<br>
Ansh -  collaborator<br>

Ansh will clone the whole Repo and pass the following commands~<br>

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
<br>

After this the code will be saved in the branch-feature/Frontend.<br><br>

  
Step 3:<br>
Shikhar will see the whole code in the branch-feature/Frontend and verify it, if it is right or wrong. Then he can merge the branch code with the main code.<br>

Shikhar will use the following git commands~<br><br>

1. fetching the whole Repo:
```bash
git fetch
```
2. View branch
```bash
git branch
```
3. After this the code in that branch will be visible in vscode editor:
```bash
git switch feature/Frontend
```
4. Switch to main:
```bash        
git switch main
```
5. Merge branch code with main code:
```bash
git merge feature/Frontend
```
6. push:
```bash
git push origin main
```
<br>

After this we will reload the GitHub and the merged code will be visible in the main branch.<br><br>

  
Step 4:<br>
Now, Ansh will fetch the whole code in the main branch, so he can work further with the project.<br><br>

1. switch to main:
```bash
git switch main
```
2. fetch the main branch:
```bash
git fetch
```
3. pull:
```bash
git pull
```
<br><br>
