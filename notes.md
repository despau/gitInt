raugustin1049@gmail.com
romane

#GIT BASICS
* Git init
* Git status
* Git add
        - to add any files or folders you want git to track
        - git add filename.ext
        --- rm --cached filename.ext, to ustage the file
    + git add . (to add all the files on your directory)
* Git Commit
        - right after you add the files/folders, you can commit to git
        - git commit -m "message goes here", because every commit needs a message with it


* git add, creates a new file in your git folder
* git commit, send it to git


git --version ==> to get the version of your installed git
git init ==> to initialize git on your curr_dir. i-e, creates .git folder
git status ==> tells about the status of your git, masters, commits, tracked files, etc..


#GIT Checkout
* Git Log:
        Display all your commits in a log
* Git Checkout
        Used for a lot of things like: go checkout a branch or a master or something
            -git checkout :id, will take you back on time to that particular id
        HEAD
            0 -> 0 -> 0 -> 0 -> 0
                                MASTER
       # whenever you git checkout :id, you need to rmember to git checkout master again

the long commit string id Git gives you is important to see your files and changes you made

* Git Remove
        To remove a file from the staging area ( 'git reset HEAD filename.ext')

* 'git revert --no-commit 294be68b565bdfd72d9a410da19b6aeef1956c3e..HEAD'
         (--no-commit) to bypass git individual prompting messages
    --apartently you can use this to revert your change to that particular state
    --even if you revert on time, you still havent loss your changes. 'git log'



# IGNORE FILES WITH .gitignore
    *create file name .gitignore
        -- add all the filesname you wanna ignore in that .gitignore file