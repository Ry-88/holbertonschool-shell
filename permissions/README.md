su  username this command switch user
whoami this command to print current user
groups this commsnd print the groups is current user part of
chown this command change the owner of file
touch this command create new file
chmod u+x filename this command to adds execute permission to the owner of the file
chmod 754 filename this command adds execute permission to the owner and the group owner, and read permission to other users
chmod a+x filename this command adds execution permission to the owner, the group owner and the other useris
chmod 007 filename this comand adds full permission to user only
chmod 753 filename this command adds full permission to user and read,execute for group and write,execute to others
chmod ug=rw,o=r this command adds read,write for user and group, read only for others
chmod --refernce=filename filename this command copy permission form first file to secound file
find . -type d -exec chmod a+x {} + this command adds execute on all subdirectory
mkdir -m 751 directory this command create directory with permission
chgrp school filename this command change group owner
chown vincent:staff * this command change owner and group owner of all contant in current directory
chown -h vincent:staff _hello this command change the owner and group owner of symbolic file only
chown --from=guillaume vincent hello this command change the owner if the owner file like condation
