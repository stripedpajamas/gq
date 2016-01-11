# quickCommit
A shell script that quickly adds all changes to git, commits, and pushes in one command

**Setup:**
enter command in terminal in directory of file: *chmod +x quickCommit* (or *chmod 0777 quickCommit*)

**To run:**
if script is in same directory as repo: *./quickCommit upstream branch* (ex: *./quickCommit "commit message" origin master*)
if script is in home directory: *~./quickCommit upstream branch* (ex: *~./quickCommit "commit message" origin master*)

If you want to be able to run script universally in all directories:

1) Copy script into /usr/local/bin/ 
  - cd into /usr/local/bin/
  - *sudo cp -p /Path/To/quickCommit/Script ./*
  - restart terminal
  - you can now run using quickCommit from any repo directory (ex: *quickCommit "commit message" origin master*)
  
2) Add Path into .bash_profile
  - *open ~/.bash_profile* (if you don't have a bash profile, http://apple.stackexchange.com/questions/99835/how-to-create-bash-profile-and-profile)
  - in bash_profile, type *export PATH="$PATH:$HOME/path/to/quickCommit/script"*
  - save bash_profile
  - in terminal, type *. ./.bash_profile*
  - in terminal, type *source ~/.bash_profile*
  - restart terminal
  - you can now run using quickCommit from any repo directory (ex: *quickCommit "commit message" origin master*)
  

