# GitHub Tutorial

_by Anthony Chen _

---
## Git vs. GitHub
**Git** and **Github** are very similar but they aren't the same. **Git** is version control which is keeping 
snapshots of your code and _**doesn't**_ require **Github**. **Github** keeps code in the cloud which allows you
to collaborate and also keeps track of changes in your code or other peoples code. _**Github** requires **git**_. 



---
## Initial Setup
Creating a github account will allow you to keep track of changes in your code, share your files easily, 
and also collaborate with other people on Github. Github also allows you to transfer your local repository 
to your remote repository meaning that you can transfer your code into the cloud.
An SSH key is a password that allows you to clone a remote repository to your local repository and every 
key is different. 
Git config is basically setting up your user.name and user.email. This will mark the file as yours 
and you will never have to enter the information again. 


###To make a Github account
1. [Click](www.github.com)
2. Plug in information such as username and password
3. Select the **free** plan
4. _**Enjoy**_


###To find your SSH key
1. Log into [Github](www.github.com)
2. Select SSH key in _settings_
3. Click 'Add'
4. Add a title and copy the key
5. Open your IDE and type in 'ssh -T git@github.com' 
6. Type 'yes'

---
## Repository Setup
###The repository setup is basically setting up a local repository which is your file. 
To do this, you need to


1. Type in mkdir (file name) in order to make a file
2. 'cd' or go inside that file
3. Type 'git init' which initializes and creates your first repository
4. By using git config explained in _**Initial Setup**_, put in your login information
5. add a new file called **readme.md**

### In order to make a new repository on Github
1. click 'create a new repository'
2. Press 'New Repository' and add information
###You should always 

- Save changes
- use 'git add .' to add changed files
- user 'git commit -m"(message" to display a message about your changes


###A remote is used to link the repository to Github but presented.

---
## Workflow & Commands
* 'Git Status' allows you to check what you have done to your work 
so you can easily pick out mistakes and fix them.

* 'Git add' adds any file

* 'Git commit' to explain what changes you have made
'push' to push the file into a remote repository

## Collaboration
_Forking_ and _cloning_ is when you take someone elses uploaded file
and make as many edits to it as you want. This allows people
to _**collaborate**_ with each other on projects because the leader
of the file gets to decide what changes to choose from.
Pulling is when you pull a file into your own repository to edit.

## Error Handling
Error Handling is when you initialize the _**wrong**_ directory. 
