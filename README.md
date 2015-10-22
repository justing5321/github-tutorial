# GitHub Tutorial

_by Justin Garcia_

---
## Git vs. Github
* Git   
 * Version control: Git keeps your lastest bits of code or snapshots to refer back to later  
 * *Note: GIT DOES NOT REQUIRE GITHUB!
* Github
  * space where all your code is saved
  * Saves for work to the "Cloud"
  * Easily lets multiple people work on files
  * *Note: REQUIRES GIT!

---
## Initial Setup
##1. First go to [github.com](https://github.com)  
  2.Once you're there you should use your HSTAT user email/password to sign up.  
  3.Now that you're signed up you should look at the icon on the top right corner, click on the icon and direct yourself to settings.  
  4.You should see on your screen a column called _Personal settings_, scroll down until you get to ssh keys, click, and wait for instructions.  
  5.Click on the top right, _Add SSH key_, and you should add an appropriate title and copy your ssh key from your *IDE  
  6. Type ssh -T git@github.com (then type yes)
 


---
## Repository setup
###Creating a repository:  
* Go to your command line on the bottom of the screen and you should make a new repository(Make an appropriate title)  
* To do that you will type mkdir(making your directory), space, (whatever your repo is named) and then press enter.  
* Then you should type cd (whatever your file is called) because you want to be in that file so you can keep all of your work in one place.  
*  Now you should do a one time setup which gets saved in order to know who did this beautiful work.
  * type git `init`, enter, then `git config  --global user.name "first name"`,enter, then `git config --global user.email "hstat email"`

  




---
## Workflow & Commands
Now lets go into your directory if you are already not in there.  
`cd` (whatever the name of your directory)  
To save your work press command+s  
now that your work is saved, type `git add` (the name of your directory).  
If you want to check your added files use `git status` which lets you know the file is ready to be committed.  
Once you see your saved work then you want to type git comit -m "message describing what you did to the file).  
If you are wondering what the -m is, it is just reminding you to make a message.  
Go to github.com and go go to the top right and click new repository.  
CREATE REPOSITORY!!(If you are asked to verify your emial...JUST DO IT!!)  
oh snap, you have to now push your work up to github! Make sure you have ssh selected and you should type `git remote add origin git@github.com:bmuellerhstat/(name or your repo), press enter.`
Then type `git push -u origin master`. You are down!! Refresh the page to see your repo!