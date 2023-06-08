## Shell permissions basics

### What do the commands (chmod, sudo, su, chown, chgrp) do in linux file permission
- 0-iam_betty : The script changes the current user to the user 'betty'
- 0-who_am_i : The script prints the effective username of the current user
- 2-groups : The script prints all the groups the current user is part of
- 3-new_owner : The script changes the owner of the file hello to the user betty.
- 4-empty : The script creates an empty file called hello.
- 5-execute : The script adds execute permission to the owner of the file hello.
- 6-multiple_permissions : The script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
- 7-everybody : The script adds execution permission to the owner, the group owner and the other users, to the file hello
- 8-James-Bond : The script sets the permission to the file 'hello' as (Owner = no perms, Group = No perms, Other users = all the perms)
- 9-John_doe : The script sets the mode of the file hello to this (-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello)
