# Git-and-Github-Workshop-DRESTEIN-24
```
NAME: Mallireddy Venkata Nithin Reddy 
REGISTER NUMBER : 212221060158 
DEPARTMENT : B.E. (ECE) 
YEAR :  IV
```
## 1. Setup and Initialize:
```
What command do you use to create a new directory named git-workshop and navigate into it?
Answer : mkdir git-workshop
cd git-workshop
```
## 2. Initialize a Git Repository:
```
What command initializes a Git repository in your directory?
Answer: git init
```
## 3.Create and Modify Files:
```
How do you create a new file named hello.txt and add the content 'Hello, Git Workshop!' to it using a single command?
Answer : echo "Hello, Git Workshop!" > hello.txt
```
## 4. Check the Status of Your Repository:
```
What command displays the status of your repository?
Answer: git status
```
## 5. Stage and Commit Changes:
```
What command stages the file hello.txt?
Answer: git add hello.txt
What command commits the staged file with the message 'Add hello.txt with welcome message'?
Answer: git commit -m "Add hello.txt with welcome message"
```
## 6. Branching:
```
What command creates a new branch named update-content?
Answer: git branch update-content
How do you switch to the update-content branch?
Answer: git checkout update-content
```
## 7. Make Changes on the Branch:
```
What command would you use to append the text 'This is a simple Git assignment.' to hello.txt?
Answer: echo "This is a simple Git assignment." >> hello.txt
What command stages and commits the changes with the message 'Update hello.txt with additional message'?
answer: git add hello.txt
git commit -m "Update hello.txt with additional message"
```
## 8. Merge Changes:
```
What command switches you back to the main branch?
Answer: git checkout main
How do you merge the update-content branch into main?
Answer: git merge update-content
```
## 9. View Commit History:
```
What command shows the commit history?
Answer : git log
```
## 10. Undo and Reset (Practice Safely):
```
If you make a change to hello.txt that you want to revert before committing, what command would you use?
Answer : git restore hello.txt
How can you reset your branch to a previous commit (optional, for advanced practice)?
Answer : git reset --hard
```
## 11. Push to a Remote Repository (Optional):
```
What command adds a remote repository named origin?
Answer: git remote add origin
What command pushes your local main branch to the remote repository?
Answer : git push origin main
```
