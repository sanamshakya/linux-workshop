# Lab 1
* Find out which version of kernel your coumputer is using.
* Use man and related resources to find out how to change the date and time of your computer

# Lab 2
* Create the directory structure /tmp/files/pictures, /tmp/files/videos, /tmp/files/photos
* Copy all the files starting from a, b and c from /etc to /tmp/files
* From /tmp/files, move all the the files that have a name starting with a or b to /tmp/files/photos, and with name starting with a c  to /tmp/files/videos
* Find all files in /etc with size greater than 1000 bytes and copy those into /tmp/files/pictures
* In /tmp/files, create a symbolic link to /var

# Lab 4
* Use head and tail to display the fifth line of the file /etc/passwd
* Use sed to display the fifth line of the file /etc/passwd
* Use awk in a pipe to filter column out of the results of the command ps aux
* Use grep to show the names of all files in /etc that have lines starting with the text 'root'
* Use grep to show all lines from all files in /etc that exactly contains 3 characters
* Use grep to find all files that contain the string "alex", but make sure "alexander" is not included in the result

# Lab 5
* Log in to your server using a text only console
* Also log in from SSH session
* Find out which terminal names are used for both logins

# Lab 6
* Create 4 users: Linda, Laura, anna and anouk
* Set their passwords to expire after 60 days
* Create group sales and make linda and laura members of that group
* Create group accounts and add anna and anouk member of this group
* Also create a group users, and make all four users members of that group as secondary group
* Use input redirection to set password for this users as "password"
* Ensure all these users get a directory in home
* Make sure that members from group sales cannot start more than 25 simultaneous process from the shell


