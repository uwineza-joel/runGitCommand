# runGitCommand
get deep understanding of git hub
## initialize your git repo (a project folder on you machine)
 > git init
## check if you have remote channel
 > git remote
## clone via HTTPS
 > git clone [Http link]
## clone via SSH
 > git clone [SSH link]
## check git streams
 > git remote -v
## fetching and pulling
 > git fetch <stream: origin>
 > git pull <stream: origin> [branch]
## switch form ssh keys
 > eval $(ssh-agent -s) ssh-add [path for key: ~/.ssh/json-key]
## creating new key when using ssh
 To create new key cd to ~/.ssh
 > ssh-keygen -t rsa
 After creating this key cat it out to copy it to deploy key tab
 > cat [~/.ssh/filename *no extension*]
## pushing your change to remote repo
 > git push -u <stream: origin> [branch]


