Here are typical gitHub commands:


preconditions:: You have to have github aplicayion isntalled your computer !

if not ... get it from 

MAC:: https://mac.github.com/
windows ::  https://windows.github.com/


To get release from github to your computer
============================================
1. Open github from web  https://github.com/ and login 

2. Go NinjaMaid front page and chooce wanted release.

3. Clone release right down there is small window HTTPS clone url .. press copy to clipboard button.

4. open terminal and go place where you want to install NinjaMaid unity project

5. in that directory give git command :: git clone ****
   ****  copy paste your  clipboard  addres and press enter


To get modified file back to github
====================================

1. check what has been changed by command ::: git status

2. First you must comment your changes by command ::: git commit -a -m "esim.c added new moving funtion"

3.  then you must push file in into github with command ::: git push 

4.  you can verify from web that chnges has been done 


To get newer version of file from github 
========================================

1. in your directory give command ::: git pull 
--> you will get  files what are newer. by command 
git pull xxxx

where xxxx is your projects hithub adderess 


to add new file in github
===========================

1. ::: git add file.cs
2. ::: git commit -a -m "file lisatty"
3. ::: git push 
4 verify that fie has been added to github  from  web


If there are problmes with your config try 
===========================================

1. git config --global user.email "xxxx"

xxxx == your github email address

