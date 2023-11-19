![Git commands](https://github.com/paulo-xavier/uc10-documentation/blob/main/assets/git.png)

# 📝 Git Commands

## Table of contents

- [Commands](#commands)  
  - [Setting commands](#%EF%B8%8F-settings-commands) 
  - [Creating Git and opening connection with GitHub](#%EF%B8%8F-creating-git-and-opening-connection-with-github)  
  - [Updating local repository](#%EF%B8%8F-updating-local-repository)
  - [Cloning repositories](#%EF%B8%8F-cloning-repositories)
  - [Working with branches](#%EF%B8%8F-working-with-branches)
  - [Extra commands](#%EF%B8%8F-extra-commands)
- [Author](#author)

## Commands

<div align="center"> 

### ⚙️ Settings commands

|  Command                                             | Description                                 |
| ------------                                         |  -----------                                |
|  `git config --global user.name "name-example" `     |  **Set the global user name**               |
|  `git config --global user.email "email-example"`    |  **Set the global user email**              |
|  `git config --global user.name unset`               | **Remove the global user name**             |
|  `git config --global user.email unset`              | **Remove the global user email**            |
|  `git config --global --list`                        | **List the global user and email registerd**| 
|  `git config --list`                                 | **Open a list of settings available**       |  
|  `git config`                                        | **Show all the configurations available**   |

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
|  `git status`                                                    | **Verify the current status of your local git repository**  |
 
</div>

<br><br>

<div align="center"> 

  ### ⚙️ Updating local repository 

|  Command                                                          | Description                                                        |
| ------------                                                      |    -----------                                                     |
|  `git pull`                                                       | **Pull the newest changes made in the remote repository on GitHub**|
| `git pull <https://github.com/user/repository.git> <branch-name>` | **Pull the newest changes of a specific branch**                   |
| `git pull origin master --allow-unrelated-histories`              | **Pull the newest changes**                                       |

</div>

<br><br>

<div align="center"> 

  ### ⚙️ Cloning repositories

|  Command                                              | Description                                                         |
| ------------                                          |  -----------                                                        |
|  `git clone <https://github.com/user/repository.git>` | **Create a copy of a remote repository in your local machine**      |      

</div>
<br><br>

<div align="center"> 

  ### ⚙️ Working with branches

|  Command                        | Description                        |
| ------------                    |  -----------                       |
| `git branch <branch-name>`      | **Create a new branch**            |
| `git checkout <branch-name>`    | **Switch to the branch**           |
| `git checkout -b <branch-name>` | **Create and switch to the branch**|
| `git branch -d <branch-name>`   | **Delete branch**                  |
| `git branch`                    | **Show all the branches available**|

</div>
<br><br>


<div align="center"> 

  ### ⚙️ Extra commands

|  Command                                                            | Description                                                       |
| ------------                                                        |  -----------                                                      |
| `git log`                                                           | **Show all the commits made**                                     |
| `git add --all`                                                     | **Add all files at the same time to the staging area**            |
| `git remote set-url origin <https://github.com/user/repository.git>`| **Set a new remote repository origin where you will commit files**| 
</div>
<br><br>

