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
echo $(($BREATH**$LOVE))|script that displays the result of BREATH to the power LOVE, BREATH and LOVE are environment variables, The script should display the result, followed by a new line|
echo $((2#$BINARY))|script that converts a number from base 2 to base 10., The number in base 2 is stored in the environment variable BINARY, The script should display the number in base 10, followed by a new line|
echo {a..z}{a..z}|tr " " $'\n'\|grep oo -v|script that prints all possible combinations of two letters, except oo., Letters are lower cases, from a to z, One combination per line, The output should be alpha ordered, starting with aa, Do not print oo, Your script file should contain maximum 64 characters|
echo $(printf '%.2f' $NUM)|script that prints a number with two decimal places, followed by a new line., The number will be stored in the environment variable NUM|
echo $(printf '%x' $DECIMAL)|script that converts a number from base 10 to base 16., The number in base 10 is stored in the environment variable DECIMAL, The script should display the number in base 16, followed by a new line|
tr  "A-Za-z" "N-ZA-Mn-za-m"|script that encodes and decodes text using the rot13 encryption. Assume ASCII|
ls -1\|xargs\|cut -s -d" " -f $(seq 1 2 $(ls -1\|wc -l)\|xargs\|cut -s -d" " --output-delimiter="," -f1-)\|cut -s -d" " --output-delimiter=$'\n' -f 1-|script that prints every other line from the input, starting with the first line|
printf "%o\n" $((5#$(echo $WATER | tr water 01234) + 5#$(echo $STIR | tr stir. 01234))) | tr 01234567 behlnort|shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result., WATER is in base water, STIR is in base stir., The result should be in base behlnort|




