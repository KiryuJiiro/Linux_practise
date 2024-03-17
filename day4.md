
##  Files permissons: 
###  r:
    -readable
###  w:
    -writable
###  x:
    -executable
###  users:
    use:normal user
    group:specific group
    others:other than normal or group 
###  checking premissions:
    ls -l
    shows list of files and folders with permission
###  format:
    --rwx--rwx--rwx: first shows permission of user, second group and third of others.
    can also be denoted in octal from 000-111.
    all permissions for all 3 users can be denoted by 111
###  Changing permissions:
    chmod u+x file.txt
    u:signifies change on user 
    +:signifies addition of permission(use - tp
	x:signifies which permission is being added
	syntax: chmod users:add/remove:permission [file_name]
	chmod 777 [file_name]:adds all permission to all user 
