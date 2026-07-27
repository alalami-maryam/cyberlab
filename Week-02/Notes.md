## Objectives
- Exploring Kali Linux and navigating the file system.
- Creating, copying, moving, renaming, and deleting files and folders.
- Navigating between directories using the terminal.


## Concepts Learned
In Linux, . represents the current directory, .. represents the parent directory, and ~ represents your home directory, no matter where you are.

The find command can search from any directory. Using . tells Linux to start searching from the current directory, while using ~ starts the search from your home directory. Empty directories can be deleted using the rmdir command. If a directory contains files or other directories, it must be deleted using rm -r directoryname.

## Hands On Work
I started by running the commands I learned last week: pwd, ls, ls -la, and touch.
I then used the commands cp and mv to copy and rename files. Then, I tried deleting a file using the rm command and verified that it had been deleted.

The most useful commands used in today's lab were find and grep. The find command is used to search for a specific file or for files with a particular extension. The grep command is used to search for specific words or phrases inside files.
I also practised searching from different directories using the find command.

Finally, I ended the lab by running the history command, which shows all the commands I have used in the terminal on my Kali VM.

## Commands
| Command | Description |
|---------|-------------|
| `find . -type f` | Finds all files in the current directory and its subdirectories. |
| `find . -type d` | Finds all directories. |
| `find . -empty` | Finds empty files and directories. |
| `find . -size +1M` | Finds files larger than 1 MB. |
| `find . -iname "*.txt"` | Finds `.txt` files without caring about uppercase or lowercase letters. |

## Challenges
Some of the challenges I have faced this week include: 
- Understanding why . is used when searching with the find command and how it tells Linux to begin searching from the current directory.
- Remembering the difference between the command used to delete files (rm) and the command used to delete directories (rmdir or rm -r).
