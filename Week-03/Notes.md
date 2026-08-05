## Objectives
- Understand Linux file permissions.
- Learn who can access files and folders.
- Change permissions using terminal commands.

## Concepts Learned
- Users, groups, and others.
- Read (r), write (w), and execute (x) permissions.
- What ls -l means.
- Difference between chmod and chown.

## Hands On Work

I started the lab by creating a new directory to try testing the permissions on. I then created 2 files named file1 and file2. Then I used the ls -l command to view permissions. Then I used the chmod 600 command to change the file permissions. This gave the owner read and write permissions while removing all permissions from the group and others. Linux permissions are divided into three groups: the owner, the group, and others. The owner refers to the user who owns the file, the group refers to users who belong to the same group as the owner, and others refers to everyone else on the system.
Each position has a meaning, r means read, w means write, and x is execute. If there is a dash then it means that permission is not given. I finally ended my lab by trying different commands to add and remove permission from different groups. Since I am the only user of this virtual machine, I was researching commands and found the chown command. This command is used to change the owner of a file or directory. It can also be used to change the group associated with the file, helping control who is responsible for and has access to it. Some of the other commands I learned were whoami and id. whoami is used to display the username of the currently logged-in user. id is used to display detailed information about the current user, including the user ID (UID), group ID (GID), and the groups the user belongs to.

## Permission Commands Learned

| Command | Meaning |
|---------|---------|
| `chmod u+r file` | Give the owner read permission. |
| `chmod u-r file` | Remove read permission from the owner. |
| `chmod u+w file` | Give the owner write permission. |
| `chmod u-w file` | Remove write permission from the owner. |
| `chmod u+x file` | Give the owner execute permission. |
| `chmod u-x file` | Remove execute permission from the owner. |
| `chmod g+r file` | Give the group read permission. |
| `chmod g-r file` | Remove read permission from the group. |
| `chmod g+w file` | Give the group write permission. |
| `chmod g-w file` | Remove write permission from the group. |
| `chmod g+x file` | Give the group execute permission. |
| `chmod g-x file` | Remove execute permission from the group. |
| `chmod o+r file` | Give others read permission. |
| `chmod o-r file` | Remove read permission from others. |
| `chmod o+w file` | Give others write permission. |
| `chmod o-w file` | Remove write permission from others. |
| `chmod o+x file` | Give others execute permission. |
| `chmod o-x file` | Remove execute permission from others. |
| `chmod a+r file` | Give everyone read permission. |
| `chmod a-r file` | Remove read permission from everyone. |
| `chmod a+w file` | Give everyone write permission. |
| `chmod a-w file` | Remove write permission from everyone. |
| `chmod a+x file` | Give everyone execute permission. |
| `chmod a-x file` | Remove execute permission from everyone. |

## Permission Symbols

| Symbol | Meaning |
|--------|---------|
| `u` | User (Owner) |
| `g` | Group |
| `o` | Others |
| `a` | All (Owner, Group, and Others) |
| `+` | Add a permission |
| `-` | Remove a permission |
| `=` | Set permissions exactly |
| `r` | Read |
| `w` | Write |
| `x` | Execute |


## Challenges
Some of the challenges I have faced this week include: 
- Understanding the meaning of the permission symbols (`r`, `w`, and `x`).
- Understanding how Linux groups permissions into owner, group, and others.

