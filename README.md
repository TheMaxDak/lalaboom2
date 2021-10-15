# lalaboom2

  root@bd16a44759bf:/# ls
	
	
  bin  boot  dev  docker-entrypoint.d  docker-entrypoint.sh  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
	
  root@bd16a44759bf:/# ls -F --color
	
  bin/  boot/  dev/  docker-entrypoint.d/  docker-entrypoint.sh*  etc/  home/  lib/  lib64/  media/  mnt/  opt/  proc/  root/  run/  sbin/  srv/  sys/  tmp/  usr/  var/
	
  root@bd16a44759bf:/# ls -F --color ~
	
  root@bd16a44759bf:/# ls -F --color~
	
  ls: unrecognized option '--color~'
	
  Try 'ls --help' for more information.
	
  root@bd16a44759bf:~# pwd
	
/root

root@bd16a44759bf:~# ls

root@bd16a44759bf:~# pwd

/root

root@bd16a44759bf:~# ?

bash: ?: command not found

root@bd16a44759bf:~# /

bash: /: Is a directory

root@bd16a44759bf:~# pwd/home/user/

bash: pwd/home/user/: No such file or directory

root@bd16a44759bf:~# cd

root@bd16a44759bf:~# mkdir test

root@bd16a44759bf:~# "mkdir test"

bash: mkdir test: command not found

root@bd16a44759bf:~# mkdir "test"

mkdir: cannot create directory 'test': File exists

root@bd16a44759bf:~# mkdir "test1"

root@bd16a44759bf:~# ls -F --color test1 

root@bd16a44759bf:~# ls -F --color test1/

root@bd16a44759bf:~# ls -F --color "test1/"

root@bd16a44759bf:~# ls -F --color  


test/  test1/

root@bd16a44759bf:~# ls\           
> ls 
> 
bash: lsls: command not found

root@bd16a44759bf:~# ls 

test  test1

root@bd16a44759bf:~# ls test1

root@bd16a44759bf:~# mkdir "test2"

root@bd16a44759bf:~# ls

test  test1  test2root@bd16a44759bf:/# cd

12

root@bd16a44759bf:~# ^C

13

root@bd16a44759bf:~# ^C

14

root@bd16a44759bf:~# ^C

15

root@bd16a44759bf:~# ^C

root@bd16a44759bf:~# mkdir test1/223

root@bd16a44759bf:~# ls

test  test1  test2

root@bd16a44759bf:~# ls/test1

bash: ls/test1: No such file or directory

root@bd16a44759bf:~# ls test1  

223

root@bd16a44759bf:~# mkdir classics 

root@bd16a44759bf:~# ls

classics  test  test1  test2

root@bd16a44759bf:~# rmd classics

bash: rmd: command not found

root@bd16a44759bf:~# rmdir classics

root@bd16a44759bf:~# ls

test  test1  test2

root@bd16a44759bf:~# your name

bash: your: command not found

root@bd16a44759bf:~# uname

Linux

root@bd16a44759bf:~# uname-s

bash: uname-s: command not found

root@bd16a44759bf:~# uname-r\

> uname-r 
> 
bash: uname-runame-r: command not found

root@bd16a44759bf:~# uname-runame -s

bash: uname-runame: command not found

root@bd16a44759bf:~# runame -s

bash: runame: command not found

root@bd16a44759bf:~# uname -r

4.19.0-16-amd64

root@bd16a44759bf:~# date

Fri Oct 15 12:48:42 UTC 2021

root@bd16a44759bf:~# date

Fri Oct 15 12:48:48 UTC 2021

root@bd16a44759bf:~# &

bash: syntax error near unexpected token `&'

root@bd16a44759bf:~# apt install cal

Reading package lists... Done

Building dependency tree        

Reading state information... Done

E: Unable to locate package cal

root@bd16a44759bf:~# cal 

bash: cal: command not found

root@bd16a44759bf:~# date

Fri Oct 15 12:51:06 UTC 2021

root@bd16a44759bf:~# apt list

Listing... Done

root@bd16a44759bf:~# clear

root@bd16a44759bf:~# ls

test  test1  test2

root@bd16a44759bf:~# cd ~

root@bd16a44759bf:~# ls

test  test1  test2

root@bd16a44759bf:~# ls -R

.:

test  test1  test2

./test:

./test1:

223

./test1/223:

./test2:

root@bd16a44759bf:~# type

root@bd16a44759bf:~# ls type

ls: cannot access 'type': No such file or directory

root@bd16a44759bf:~# -F

bash: -F: command not found

root@bd16a44759bf:~# - F

bash: -: command not found

root@bd16a44759bf:~# type -F

bash: type: -F: invalid option

type: usage: type [-afptP] name [name ...]

root@bd16a44759bf:~# ls/ect/X11

bash: ls/ect/X11: No such file or directory

root@bd16a44759bf:~# cd/ect/X11

bash: cd/ect/X11: No such file or directory

root@bd16a44759bf:~# mkdir "x11"

root@bd16a44759bf:~# cd/ect/X11

bash: cd/ect/X11: No such file or directory

root@bd16a44759bf:~# mkdir "ect"

root@bd16a44759bf:~# mkdir ect "x11"

mkdir: cannot create directory 'ect': File exists

mkdir: cannot create directory 'x11': File exists

root@bd16a44759bf:~# mkdir "ect"\

> mkdir "ect"\
> 
> mkdir "ect"mkdir "ect" 
> 
mkdir: cannot create directory 'ectmkdir': File exists

mkdir: cannot create directory 'ectmkdir': File exists

mkdir: cannot create directory 'ect': File exists

root@bd16a44759bf:~# mkdir "ect"

mkdir: cannot create directory 'ect': File exists

root@bd16a44759bf:~# cd ect     

root@bd16a44759bf:~/ect# mkdir "x11"

root@bd16a44759bf:~/ect# cd ect x11

bash: cd: too many arguments

root@bd16a44759bf:~/ect# cd x11

root@bd16a44759bf:~/ect/x11# cd ~

root@bd16a44759bf:~# cd ect

root@bd16a44759bf:~/ect# mkdir group

root@bd16a44759bf:~/ect# cd group

root@bd16a44759bf:~/ect/group# cd ~

root@bd16a44759bf:~# cd ect

root@bd16a44759bf:~/ect# mkdir passwd

root@bd16a44759bf:~/ect# cat

ls 

ls

^C

root@bd16a44759bf:~/ect# toucg group

bash: toucg: command not found

root@bd16a44759bf:~/ect# touch group

root@bd16a44759bf:~/ect# touch passwd

root@bd16a44759bf:~/ect# cat group

cat: group: Is a directory

root@bd16a44759bf:~/ect# head passwd

head: error reading 'passwd': Is a directory

root@bd16a44759bf:~/ect# 
