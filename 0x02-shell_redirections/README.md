0. Hello World
Script-  echo "Hello, World" which prints “Hello, World”, followed by a new line to the standard output.

1. Confused smiley
File 1-confused_smiley:  script that displays a confused smiley "(Ôo)'.

2. Let's display a file
Script- cat /etc/passwd: Displays the content of the /etc/passwd file.

3. What about 2?
Script- tail -f /etc/passwd /etc/hosts: Displays the content of /etc/passwd and /etc/hosts.

4. Last lines of a file
Script- tail -10 /etc/passwd: Displays the last 10 lines of /etc/passwd.

5. I'd prefer the first ones actually
Script- head -10 /etc/passwd: Displays the first 10 lines of /etc/passwd/

6. Line #2
Script- awk 'FNR==3 {print}' iacta: Displays the third line of the file iacta

7. It is a good file that cuts iron without making a noise
Script printf "Best School\n" \*\\'"Best School"\'\\*$\?\*\*\*\*\*:): creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

8. Save current state of directory
Script ls -la > ls_cwd_content: writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, creates it.

9. Duplicate last line
Script tail -1f iacta: Duplicates the last line of the file iacta

10. No more javascript
Script rm *.js: Deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

11. Don't just count your directories, make your directories count
Script ls -l | grep -c ^d: Counts the number of directories and sub-directories in the current directory.