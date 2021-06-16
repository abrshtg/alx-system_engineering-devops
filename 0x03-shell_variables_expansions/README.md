Script | Task |
-----------------|--------------|
alias ls='rm *'|script that creates an alias|
echo hello $USER|script that prints hello user, where user is the current Linux user|
export PATH=$PATH:/action|Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program|
echo $PATH|cut --output-delimiter=$'\n' -d":" -f 1-\|wc -l|script that counts the number of directories in the PATH|
printenv|script that lists environment variables|
