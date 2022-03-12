# Linux Workshop
- Unix filesystem
- Special folders and files
- File Perms

0. `man`
Shows usage manual of each command
`man ls`

1. `cd` 
"change directory"
`cd /home/`
2. `mkdir`
3. `ls`
Lists files in the specified directory
`ls -lah`
-l =  more details
-h = Human readable filesize
-a = shows all files (even hidden)
*-i = print Index number of file
*-R - list subdirs too

4. `pwd`
prints current working directory

5. `whoami` 
prints username which is logged in

6. `clear`
clears term

7. `reboot/shutdown`
self-explanatory

8. `df`
prints disk usage
`-h` for Mem usage of the filesystems

9. `uptime`
Shows uptime of the system

10. `chmod` 
Changes ownership of file
`chmod +x file`

11. `cat`
12. `head`
13. `tail`
14. `echo`

15. `free -h`
Used to display RAM stats

16. `mv`
Move file (but used to rename files too)
`mv old_file_name new_file_name`

17. `touch`
Make a file

18. `rm -rf`
Remove a file
-r = recursive (also delete subfolders if/any)
-f = force
19. `zip/unzip`
Self-explanatory
20. grep.
`grep [options] [flags] string filename`
grep -i = case insensitive
21. Deconstruct `find / -type d -name "impacket-scripts"  2>/dev/null` in VM
`find` - used to find files
`/` - specified directory to search (here it is /, entire filesystem)
`-type d` - Type of file : Directory
`-name "name"` - File name (supports patterns)
`-empty` - searches empty files/folders
2>/dev/null - special args.
22. Simpler version: `locate <name>`
locate options:
-n : limit number of results
-c : Just get number of results
-i : ignore case
23. `alias`
`alias text="command"`
24. `unalias`
25. `ifconfig`
26. `curl`
27. `ping`
28. `top` - Status screen
29. `ps` (-e = every, -u= for this user)
30. `uname -a`
31. `file <filename>`
Display type of file
32. `sudo`
33. `where`-
(alias doko)
34. `gcc` <filename> -o <ex filename>
35. `nano`

Piping two commands.
Redirect using > and append using >>
`wc`
`less`

