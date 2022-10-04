# git-and-github-commands
Practice Git

 nosa-ubuntu@DESKTOP-ND8EM2D:~$ ssh -T git@github.com

# Authentication
git config --global user.email=doct2wise@gmail.com
git config --global user.name "ernynany"

# create a repository on github
ssh-keygen  #generate ssh keys
git clone git@github.com:ernynany/git-and-github-commands.git
cd  git-and-github-commands #cd into the project folder
git init     #initiate the git project folder 

git status
git add
git commit #save changes or snapshot to your branch
git remote set-url origin git@github.com:ernynany/git-and-github-commands.git #set origin to the preferred branch
git push  #push the file
 

The SSH keys and GPG keys are established and synchronised between my server and the github account. The GIT commands used thereby are:

