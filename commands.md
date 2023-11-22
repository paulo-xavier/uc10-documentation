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
- [Author](#-author--)

<br>

## Commands

<br>


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

<br>

<details open> 
  <summary> <h3> Example using <code>Git config</code> 📌 </h3> </summary>

<h4> Setting a username </h4>

<code> git config --global user.name "paulo-xavier"</code>
- 💻 This command will define the global user name for your projects. It's recommended to be the same username that you use in your Github.

<br>

<h4> Setting a email </h4>

<code> git config --global user.email "pauloxavier@gmail.com"</code>
- 💻 This command will define the global email for your project. This email must be the same that you use on Github, because you will connect in your remote repository to commit the files.  

<br>

<h4> Checking the global username and email </h4>

<code> git config --global --list</code>
- 💻 This command shows the username and email registered. You can use it to check which email and username is defined as the global in your machine. If some of them be wrong, you can change using the commands on top. 
</details>

<br><br>

 

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
 


<br><br>
 

  ### ⚙️ Updating local repository 

|  Command                                                          | Description                                                        |
| ------------                                                      |    -----------                                                     |
|  `git pull`                                                       | **Pull the newest changes made in the remote repository on GitHub**|
| `git pull <https://github.com/user/repository.git> <branch-name>` | **Pull the newest changes of a specific branch**                   |
| `git pull origin master --allow-unrelated-histories`              | **Pull the newest changes of unrelated branches**                  |


<br><br>

 

  ### ⚙️ Cloning repositories

|  Command                                              | Description                                                         |
| ------------                                          |  -----------                                                        |
|  `git clone <https://github.com/user/repository.git>` | **Create a copy of a remote repository in your local machine**      |      


<br><br>

 

  ### ⚙️ Working with branches

|  Command                        | Description                        |
| ------------                    |  -----------                       |
| `git branch <branch-name>`      | **Create a new branch**            |
| `git checkout <branch-name>`    | **Switch to the branch**           |
| `git checkout -b <branch-name>` | **Create and switch to the branch**|
| `git branch -d <branch-name>`   | **Delete branch**                  |
| `git branch`                    | **Show all the branches available**|


<br><br>

 

  ### ⚙️ Extra commands

|  Command                                                            | Description                                                       |
| ------------                                                        |  -----------                                                      |
| `git log`                                                           | **Show all the commits made**                                     |
| `git add --all`                                                     | **Add all files at the same time to the staging area**            |
| `git remote set-url origin <https://github.com/user/repository.git>`| **Set a new remote repository origin where you will commit files**| 

<br><br>

<h2> Author 💻 </h2>

- Frontend Mentor - [@paulo-xavier](https://www.frontendmentor.io/profile/paulo-xavier)
- Instagram - [@oxavierpaulo](https://www.instagram.com/oxavierpaulo/)
- GitHub - [@paulo-xavier](https://github.com/paulo-xavier)
- Linkedin - [@Paulo Roberto Xavier da Silva](https://www.linkedin.com/in/paulo-xavier-15bb6924a/)
