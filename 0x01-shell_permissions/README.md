**0x01-shell_permissions**
Script | Task | Command used |                    
----------------------------- | -----------| ---------------|
0-iam_betty|this changes the user id to betty by making the current user betty| su betty
1-who_am_i|prints the effective user id as a name|whoami
2-groups|prints all group Ids not only the effective one| groups
3-new_owner|change ownership of file hello to betty| chown betty hello
4-empty|creats an empty file named hello| touch hello
5-execute|addes excute permion to the owner over the hello file|chmod u+x hello
6-multiple_permissions|adds execute permission to the owner and the group owner, and read permission to other users, to the file hello|chmod ug+x,o+r hello
7-everybody|adds execution permission to the owner, the group owner and the other users, to the file hello|chmod ugo+x hello
8-James_Bond|set the owner and group permission to none and all permission|chomd 007 hello
9-John_Doe|sets the mode of the file hello to 753|chmod 753 hello
10-mirror_permissions|copy permissions form olleh to hello|chmod --reference=olleh hello
11-directories_permissions|adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.|chmod -R a+x ./*/
12-directory_permissions|creates a dirctory with a 751 permission|mkdir -m 751 dir_holberton
13-change_group|change the group of the hello file|chgrp holberton hello
103-Star_Wars|Plays the star wars move on the command line using the telnet protocol|telnet towel.blinkenlights.nl
100-change_owner_and_group|changes the owner to betty and the group owner to holberton for all the files and directories in the working directory.|chown betty:holberton ./*
101-symbolic_link_permissions|changes the owner and the group owner of the file _hello to betty and holberton respectively.|chown -h betty:holberton _hello
102-if_only| changes the owner of the file hello to betty only if it is owned by the user guillaume|chown --from=guillaume betty hello
