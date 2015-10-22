# GitHub Tutorial

_by Ricardo Tlatelpa_

---
## Git vs. GitHub
* Both Git and Github are used to save code in order to get help, use it as a reference, debug, etc.

* Git is the actual code while github is the server in which supports git.

* The least complicated way to think of github is to think of it as a cloud. Githib is an easier way to access your code/data, it's an alternative to using a flash drive. It has the same concept as a flash drive, pulling or cloning to your local repository.

* Github is very useful because it opens a repository with version control, prevents crashes, and is open source(optional) so people can branch off your code or help with problems that you may have.


---
## Initial Setup
Create a [github](https://github.com/) account.

1. Make a repository in the website (Should be similar to the depository name,regardless of website or application using).

2. Inside of the terminal type **`git init`** which initializes git inside of the program.

3. `ssh -T git@github.com` by typing this you are basically setting up a connection between your local remote and github, it should also connect with your repository, in which you can [clone](#clone). You would like to have ssh because if you don't you would have to constantly type username and email with https.

4. You are almost done! you should feel very proud of yourself, now type in `git config --global user.name “Firstname-Last name”` then
`git config --global user.email “insert email”` so you can get the credit when you create something/save something.


---
## Repository Setup

**After you have setup github:**

 _Follow these steps to start your very own repo!_  

1. To make a repository just go to the github website and click on new repository and name it after your depository, so you can't get confused and be more organized.

2. **`git add`**; so github is for any kind of coder, so what ever line of code you used you can put up in the stage, think of this process like taking a photograph, you are adding people, removing them, and finally commiting them.   

3. **`git commit -m""`**; So what this does is basically take a snapshot and sends the data of code into the cloud.
 


---
## Workflow & Commands
**So now that you setup...**  

* You have to get used to this flow of work that consists of 3 commands:  
 * `git status`
 * `git add ` 
 * `git commit -m ""`

The importance of all these 3 lines of code are to both keep you aware of your progress and to save your code. You use these 3 lines of code the most because these are what you need the most in order to be the most productive you can be.
# Collaboration
--- 

## Clone
* Cloning is pretty self explanatory like the name, making a clone of the code onto your local repository. 

## Forking
* Forking confused with cloning because it may seem like they have the same concept but they are differet. Forking creates a copy into your github in which you can clone and request a pull. Pulling and pushing is how github gets code/files around, how the community stays open, pulling basically is getting a copy of code or idea and puttinng it into your depository. Pushing is basically applying the commits into the original copy of data.