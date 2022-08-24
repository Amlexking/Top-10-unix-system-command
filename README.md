# Top-10-unix-system-command
1. pwd command

Use the pwd command to find out the path of the current working directory (folder) you’re in. The command will return an absolute (full) path, which is basically a path of all the directories that starts with a forward slash (/). An example of an absolute path is /home/username.
2. cd command

To navigate through the Linux files and directories, use the cd command. It requires either the full path or the name of the directory, depending on the current working directory that you’re in.

Let’s say you’re in /home/username/Documents and you want to go to Photos, a subdirectory of Documents. To do so, simply type the following command: cd Photos.

Another scenario is if you want to switch to a completely new directory, for example,/home/username/Movies. In this case, you have to type cd followed by the directory’s absolute path: cd /home/username/Movies.

There are some shortcuts to help you navigate quickly:

    cd .. (with two dots) to move one directory up
    cd to go straight to the home folder
    cd- (with a hyphen) to move to your previous directory

On a side note, Linux’s shell is case sensitive. So, you have to type the name’s directory exactly as it is.
3. ls command

The ls command is used to view the contents of a directory. By default, this command will display the contents of your current working directory.

If you want to see the content of other directories, type ls and then the directory’s path. For example, enter ls /home/username/Documents to view the content of Documents.

There are variations you can use with the ls command:

    ls -R will list all the files in the sub-directories as well
    ls -a will show the hidden files
    ls -al will list the files and directories with detailed information like the permissions, size, owner, etc.

4. cat command

cat (short for concatenate) is one of the most frequently used commands in Linux. It is used to list the contents of a file on the standard output (sdout). To run this command, type cat followed by the file’s name and its extension. For instance: cat file.txt.

Here are other ways to use the cat command:

    cat > filename creates a new file
    cat filename1 filename2>filename3 joins two files (1 and 2) and stores the output of them in a new file (3)
    to convert a file to upper or lower case use, cat filename | tr a-z A-Z >output.txt

5. cp command

Use the cp command to copy files from the current directory to a different directory. For instance, the command cp scenery.jpg /home/username/Pictures would create a copy of scenery.jpg (from your current directory) into the Pictures directory.
6. mv command

The primary use of the mv command is to move files, although it can also be used to rename files.

The arguments in mv are similar to the cp command. You need to type mv, the file’s name, and the destination’s directory. For example: mv file.txt /home/username/Documents.

To rename files, the Linux command is mv oldname.ext newname.ext
7. mkdir command

Use mkdir command to make a new directory — if you type mkdir Music it will create a directory called Music.

There are extra mkdir commands as well:

    To generate a new directory inside another directory, use this Linux basic command mkdir Music/Newfile
    use the p (parents) option to create a directory in between two existing directories. For example, mkdir -p Music/2020/Newfile will create the new “2020” file.

8. rmdir command

If you need to delete a directory, use the rmdir command. However, rmdir only allows you to delete empty directories.
9. rm command

The rm command is used to delete directories and the contents within them. If you only want to delete the directory — as an alternative to rmdir — use rm -r.

Note: Be very careful with this command and double-check which directory you are in. This will delete everything and there is no undo.
10. touch command

The touch command allows you to create a blank new file through the Linux command line. As an example, enter touch /home/username/Documents/Web.html to create an HTML file entitled Web under the Documents directory.
