# TASK-4-Version-Controlled-DevOps-Project-with-Git
## Git:
- Git is a distributed version control system used to track changes in source code during software 
development. It helps teams collaborate, manage code versions, and keep a history of every change made to a 
project.
```sh
Git can tracks the every changes from work directory to remote repository. 
1. Working directory 
2. Stagging area  
3. Local repository 
4. Remote repository
```
## Git Flow
![Image](https://github.com/user-attachments/assets/7fde12db-c42e-427c-a9ed-5490c508eeb2)
## Git connection:

- SSH keypair
- HTTPS
- PAT
## GIT WORKFLOW COMMON CMDS
- Create a folder in local ------git init  #.git is hidden file
![Image](https://github.com/user-attachments/assets/d15dc7f3-78f6-4d0a-800e-dc6a7057624f)
- git config  --global user.name “username”
- git config  --global user.email “email id”
- git clone  -- This cmd use for a clone the repo from remote to local
- mkdir file-1
- git status
![Image](https://github.com/user-attachments/assets/14a86b98-4324-4995-b1fd-8ceb8555191a)
- git add file-1
![Image](https://github.com/user-attachments/assets/815913fe-1526-493c-a146-573bc921f66a)
- git commit -m “message”
![Image](https://github.com/user-attachments/assets/520aba46-3431-4be5-b6c9-6c5b113874c0)
- git log
![Image](https://github.com/user-attachments/assets/d71ff6a9-fee4-4535-accc-f476614acba5)
- git branch -M main
![Image](https://github.com/user-attachments/assets/1a74edba-4c25-41cb-8d06-5d824d96740e)
- Git remote add origin <git repo url>
- Git push -u origin main
![Image](https://github.com/user-attachments/assets/5a58cc3c-b043-4606-b9c1-b3f2d0bc06f7)
![Image](https://github.com/user-attachments/assets/0ee829d3-e1af-4596-ae72-c86ae7546a5a)
- Git remote -v # if we get an error: remote origin already exists
![Image](https://github.com/user-attachments/assets/16401aa4-2ed4-4fdf-9b7f-044ea84a704d)
- Git remote set-url <git hub repo url> #remove existing origin map and add git remote url
![image](https://github.com/user-attachments/assets/e9b586e4-e187-4181-bd2a-6c201d969a17)
- Git branch # checking the branches are available
![image](https://github.com/user-attachments/assets/1ef39fb1-4cda-46ca-8899-07f414008a12)
- Git branch dev # create a sub-branch comes under main branch
![image](https://github.com/user-attachments/assets/522974b8-9be9-4edd-a13f-0fa29e892c95)
- Git checkout <branch-name> (or) git switch <branch-name> #move from one branch to other branch
![image](https://github.com/user-attachments/assets/2356f849-011b-49b3-8cfb-10e3c658ff97)
- Git checkout -b <sub-branch-name> # this cmd use for create branch and switch to branch
![image](https://github.com/user-attachments/assets/5d3ce067-3f0c-46c7-8e82-b0fb5bc7223b)
- git branch -m oldname new name -------> to rename a branch
![image](https://github.com/user-attachments/assets/2255c8b6-a0ce-45f6-925c-0d66d0c4118f)
- Git branch -D <branch name> ----- to delete a branch
![image](https://github.com/user-attachments/assets/f9473e09-d902-4160-94b4-87c306d4e68e)
## Git logs cmds:
- Git log # check the logs
![image](https://github.com/user-attachments/assets/29f75a46-9b54-4ad9-9eb0-3cf15c9e0aeb)
- Git log –oneline # it give in one line log
  ![image](https://github.com/user-attachments/assets/4f984b48-5251-4e2a-a117-c5b0c7c5efac)
- Git pull #solve the merger conflicts and different commit ids 
