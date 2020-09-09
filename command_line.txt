Terminal Command's

<!-- pwd(NO TAKE ANY ARGUMENT) -->
pwd -> (Print work directory) Display the current working directory. Example: /home/foobar

pwd --help -> how to work

<!-- CD (CHANGE DIRECTORY) -->
cd .. -> one directory back
cd ../.. -> two directory back

cd Desktop -> cd `folderName` to one up directory
cd Desktop/folderName -> up to this directory

<!-- my current director is /home/aman -->
cd ../aman -> out in current directory

<!-- LS (LIST) list the files in the current working directory. -->
ls -> LIST
ls home -> home is a argument, list the files in the home directory
ls --help -> how to work

echo hi -> print in terminal after echo text
which ls -> /bin/ls (ls program in bin directory)
cd /bin - to to binary directory
<!-- than -->
aman$aman:/bin$ ls -> list of bin directory

<!-- first goto the home directory -->
ls -l -> use a long listing format
ls -l -a ->
    .  ==> current directory
    .. ==> one directory up directory
    aman ==> current folder

<!-- first goto the aman directory -->
ls -l -a -> show all files (.hidden-file -> mean this is a hidden file)
<!-- ls -a OR ls --all are same -->
<!-- -a is sort hand -->


<!-- first goto the aman directory -->
<!-- both are equal -->
ls --ignore=snap -> ignore snap
ls --ignore snap -> ignore snap
ls -I snap -> sorthand

ls --ignore snap --ignore Home -> ignore snap and home

ls -lsah -> list of file size (human readable)
    l -> use a long listing format
    s -> print size of all files
    a -> all file
    h -> human readable

<!-- get list another directory -->
ls snap -> code  snap-store  vlc
ls -lsah snap -> list files whit full size(human readable)





<!-- ======== Search ========= -->
cd ~ -> take me to home directory
cd / -> take me to root directory

cd ~/snap -> take me to home directory than goto snap directory

<!-- AUTO COMPLETE -->
cd D -> press tab (auto complete to Desktop)
cd Desktop/p -> press tab (hint multiple options)


<!-- REVERSE SEARCH (CTRL+R) -->
cd lsa -> check your history to auto match

<!-- REVERSE SEARCH (CTRL+R) -->
<!-- SHOW SOME RESULT THAN LEFT OR RIGHT ARROW -->
cd l -> left and right arrow to modify result string

<!-- BASH HISTORY -->
tail ~/.bash_history -> show some history

<!-- bang band (!!) -->
!! -> what the last command and run last cmd (!! - this called :bang bang)

<!-- clear (CTRL + L) -->
clear -> clear you terminal OR

<!-- copy (CTRL + SHIFT + C) -->
<!-- PAST (CTRL + SHIFT + V) -->


<!-- SHORTCUT -->
CTRL + A – takes you to the beginning of the line
CTRL + E – takes you to the end of the line
CTRL + K – "yank" everything after the cursor
CTRL + U – "yank" everything before the cursor
CTRL + Y - "paste" (paste in quotes because it doesn't actually go into your system clipboard) everything you yanked
CTRL + L - clear the screen
CTRL + R – reverse search through history




<!-- Signal -->
<!-- CTRL + C – SIGINT ==> to end this line -->
tail -f .bash_history -> show all history and not end this code

<!-- CTRL + C – SIGINT ==> to end this line -->
yes -> CTRL + C

<!-- CTRL + D – SIGINT ==> to end this line -->
python -> CTRL + D  OR  CTRL + D

<!-- kill -l (list of signal list) -->
kill -SIGKILL 1467 -> BOTH ARE EQUAL
kill -9 1467 -> BOTH ARE EQUAL