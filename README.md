# runGitCommand
get deep understanding of git hub
## configure git
 > git config --global user.name [name]
 > git config --global user.email [email]
## initialize your git repo (a project folder on you machine)
 > git init
## check if you have remote channel
 > git remote
## clone via HTTPS
 > git clone [Http link]
## clone via SSH
 > git clone [SSH link]
## adding remote stream
 > git remote add origin [SSH link]
## check git streams
 > git remote -v
## fetching and pulling
 > git fetch <stream: origin> [<Branch: Branch>]
 > git pull <stream: origin> [branch]
## switch form ssh keys
 > eval $(ssh-agent -s) ssh-add [path for key: ~/.ssh/json-key]
## creating new key when using ssh
 ### To create new key cd to ~/.ssh
 > ssh-keygen -t rsa  
 ### After creating this key cat it out to copy it to deploy key tab
 > cat ~/.ssh/filename.pub
 ### no extension just name only
## pushing your change to remote repo
 > git push -u <stream: origin> [branch]

## creating new git branching
 > git branch [branch_name]
## switch to git branch
 > git checkout [branch_name]
 
## version your development via tags
 > git tag <version: 1.1.0>
## pushing tags
 > git push <stream: origin> --tags
 ### pushing tag directly
 > git push <stream: origin> tag <version: 1.0.0>

