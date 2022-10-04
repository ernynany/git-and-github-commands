# git-and-github-commands
Practice Git

 nosa-ubuntu@DESKTOP-ND8EM2D:~$ ssh -T git@github.com

# create a repository on github
  227  ssh-keygen  --- generate ssh keys
  228  cd /root/.ssh
  230  cat id_rsa.pub ---  add the pub key to repo created on github
  233  mkdir Git  ----- create your project directory
  234  cd Git/
  235  git init  ----- initiate the git project folder 
  

***********************************************************
Authentication
************************************************************
  238  git config --global user.email=doct2wise@gmail.com
  240  git config --global user.name "ernynany"  ------ enter password if asked
  
  
  241  git clone git@github.com:ernynany/Demo.git   --- clone the ssh path
  242  ls
  243  cd Demo/
  248  vim Demo.md  --- create a file with markdown extendion
  250  git add Demo.md  ----- use "git add <file>..." to update what will be committed
  251  git status    --- check git status
  252  git commit -m "Demo"  --- include a commit message to your commit (-m "the commit messaeg"
  253  git status
  254  git remote set-url origin git@github.com:ernynany/Demo.git   ---- set the origin of your repo
  255  git push  --- push the file to this origin
 

The SSH keys and GPG keys are established and synchronised between my server and the github account. The GIT commands used thereby are:

git init
git config --global user.name "John Doe"
git config --global user.email "John Doe@gmail.com"
GIT PUSH: Navigate inside the folder (could be the cloned repo too)
which has the new updates to be pushed to GIT git add . -->in case of adding the whole folder or 
git add <Folder_Name> git status ---> to check the updates git commit -m "Message"
git remote set-url origin <SSH_Link_of Git_repo> git push GIT PULL: 
mkdir git clone <ssh_repo_link> PS: OpenSSh server could be installed on the machine beforehand because the 
latest GIT operations hold right only either via SSH or Authentication apps like Twilio Authy etc.

