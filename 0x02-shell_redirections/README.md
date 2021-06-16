Script | Task |
-----------------|--------------|
echo Hello, World|prints “Hello, World”, followed by a new line to the standard output|
echo "\"(Ôo)'"|displays a confused smiley "(Ôo)'|
cat /etc/passwd|display the content of the /etc/passwd file|
cat /etc/passwd /etc/hosts|display the content of /etc/passwd and /etc/hosts|
tail -n 10 /etc/passwd|Display the last 10 lines of /etc/passwd|
head -n 10 /etc/passwd|Display the first 10 lines of /etc/passwd|
head iacta --lines=3|tail --lines=1|displays the third line of the file iacta|
echo "Holberton School" > \\\*\\\\\'\"Holberton\ School\"\\\'\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*:\)|creates a file named exactly \*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:) containing the text Holberton School ending by a new line|
ls -la > ls_cwd_content|script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.|
tail iacta --lines=1 >> iacta|script that duplicates the last line of the file iacta|
find . -name "*.js" -type f -delete|deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders|
find -mindepth 1 -type d \| wc -l|script that counts the number of directories and sub-directories in the current directory|
ls -t|head -n 10|displays the 10 newest files in the current directory|
