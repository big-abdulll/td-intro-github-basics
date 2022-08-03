GIT is a version control system 
It is used to store codes because of the features it provide.
This basically means that GIT is content tracker, 

VERSION CONTROL SYSTEM, allows developers to revert and go back to an old version of their code

process of cmminting a project to git hub repository
there are two steps to do this

Type 1 involves creating a totally fresh repository on GitHub, 
cloning it to our computer, working on our project, and pushing it back.

-> create a new repository  
-> clone the repository to your computer 
    On the repository page, you need to get the “HTTPS” address.
        you need to get the “HTTPS” address.
-> Once you have the address of the repository, you need to use your terminal. 
    git clone [HTTPS ADDRESS]
-> be in the right directory or change directory 
    cd [NAME OF REPOSITORY]
-> There are 4 steps in a commit: ‘status’ , ‘add’ , ‘commit’ and ‘push’.
-> git status is use to check the status
->git add [file_name] --> git add sample.html
->git commit -m "Added sample HTML file that contain basic syntax"
    “push”: Now we can put our work on GitHub. To do that we have to ‘push’ our files to Remote. Remote is a duplicate instance of our repository that lives somewhere else on a remote server. To do this, we must know the remote’s name (Mostly remote is named origin). 
-> git remote
-> git push origin master
