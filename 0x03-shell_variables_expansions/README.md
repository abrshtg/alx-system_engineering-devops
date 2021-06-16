Script | Task |
-----------------|--------------|
alias ls='rm *'|script that creates an alias|
echo hello $USER|script that prints hello user, where user is the current Linux user|
export PATH=$PATH:/action|Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program|
echo $PATH|cut --output-delimiter=$'\n' -d":" -f 1-\|wc -l|script that counts the number of directories in the PATH|
printenv|script that lists environment variables|
set|script that lists all local variables and environment variables, and functions|
BETTY=Holberton|script that creates a new local variable.Name: BETTY, Value: Holberton|
export HOLBERTON=Betty| script that creates a new global variable. Name: HOLBERTON, Value: Betty|
echo $(($TRUEKNOWLEDGE+128))|script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line|
echo $(($POWER/$DIVIDE))|script that prints the result of POWER divided by DIVIDE, followed by a new line. POWER and DIVIDE are environment variables|
