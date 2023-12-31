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
 


<br>

<details open> 
  <summary> <h3> Creating a remote repository using Git step-by-step 📌</h3> </summary>

<h4> Creating a folder </h4>

- 💻 Create a folder in your computer where you wil upload the files to GitHub.

<img width="70" height="70" alt="example" src="https://github.com/paulo-xavier/uc10-documentation/assets/133855530/0234dead-3761-48c5-bb8f-feac78d91b34">

<br><br>

<h4> Open this folder on terminal </h4>
                                    
<img width="400" height="300" alt="gitbash-screen" src="https://github.com/paulo-xavier/uc10-documentation/assets/133855530/b0e4ec98-e9f6-4370-952a-ba64031fe248">

<br><br>

<h4>Git init</h4>

<code>git init</code>

- 💻 This command will initialize a local git repository in your machine. It's the first command that you will always use. You cannot use other commands before initialize the git command.   

<br><br>
After that, you can create some files or code something inside this folder that you want to send to your remote repository on Github. The next steps are related to uploading files from your local repository to the remote repository on Github. 

![image](https://github.com/paulo-xavier/uc10-documentation/assets/133855530/83aa0ae4-21bc-49b1-9ebc-ab25cac32de0)

<br>

<h4> Git add </h4>

<code> git add file-example.md </code>

- 💻 After you finished to edit your file, it's time to add it to Github. The first command is the `git add` that will send these files to the local staging area. The staging area is a temporary location where your file will stay.

<br><br>

<h4> Git commit </h4>

<code> git commit -m "my first commit" </code>

-  💻 This command works as an agreement or confirmation of the changes in your code. It confirms the state of the code at that point in time.  

<br><br> 

Now, we are going to configurate the repository on Github where we are going to upload the file. Basically, we need to create a repository on Github and copy the URL of this repository adding `.git` in the end of the url.  
The next step is to use the following command: 

<br>








</details>


 

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

 ### ⚙️ Editing a commit 

| Command                                       | Description                        |
|--------                                       |  ---------                         |
| `git commit --amend -m "new commit message"`  | **Edit the last commit message**   |
| `git push origin main --force`                | **Push the new commit to GitHub**  |

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
