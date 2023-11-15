![Git commands](https://github.com/paulo-xavier/uc10-documentation/blob/main/assets/git.png)

# 📝 Git Commands

## Table of contents

- [Commands](#commands)  
  - [Setting commands](#settings-commands) 
  - [Opening a local git repository](#creating-git-and-oppening-connection-with-github)  
  - [Links](#links) 
- [My process](#my-process) 
  - [Built with](#built-with) 
  - [What I learned](#what-i-learned) 
  - [Useful resources](#useful-resources)
- [Author](#author)

## Commands

<div align="center"> 

### ⚙️ Settings commands

|  Command                                             | Description                     |
| ------------                                         |  -----------                    |
|  `git config --global user.name "name-example" `     |  **Set the global user name**   |
|  `git config --global user.email "email-example"`    |  **Set the global user email**  |
|  `git config --global user.name unset`               | **Remove the global user name** |
|  `git config --global user.email unset`              | **Remove the global user email**|
</div>
<br><br>

<div align="center"> 

  ### ⚙️ Creating git and opening connection with GitHub

|  Command                                                         | Description                                                   |
| ------------                                                     |  -----------                                                  |
|  `git init`                                                      | **Initialize a local git repository**                         |      
|  `git add <file-name>`                                           |  **Add files to the staging area**                            |
|  `git commit -m "your-message"`                                  | **Commit/confirm the changes**                                |
|  `git branch -m master main`                                     | **Change the name of your branch(master) to main**            |
|  `git remote add origin <https://github.com/user/repository.git>`| **Set the repository origin where you will add the files**    |
|  `git remote -v`                                                 | **Verify if the connection to the repository is correct**     |
|  `git push -u origin <branch-name>`                              | **Send the branch files to the remote repository on GitHub**  |

</div>

<br><br>

<div align="center"> 

  ### ⚙️ Updating local repository 

|  Command                                                         | Description                                                         |
| ------------                                                     |  -----------                                                        |
|  `git pull`                                                      | **Pull the newest changes made in the remote repository on GitHub** |      


</div>
