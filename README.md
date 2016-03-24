# sudoku

C:\Users\Dobri_Stefanov\Downloads\maestro-cli\bin>or2run -p PERSONAL -r EPAM-MSQ3 -s small -i CentOS6_64-bit -c 1
Response:


================================================================================================================
 instanceID | dnsName | privateIP | state    | guestOS               | owner          | image          | shape |
================================================================================================================
 i-d5b1fd15 |         |           | starting | Linux CentOS 6 64-bit | Dobri Stefanov | CentOS6_64-bit | SMALL |
----------------------------------------------------------------------------------------------------------------

C:\Users\Dobri_Stefanov\Downloads\maestro-cli\bin>or2start --project PERSONAL --region EPAM-MSQ3 --instance i-726deb23
Response:


========================
 instanceID | state    |
========================
 i-726deb23 | starting |
------------------------


C:\Users\Dobri_Stefanov\Downloads\maestro-cli\bin>ping ecsc00104334

Pinging ecsc00104334.epam.com [10.6.193.119] with 32 bytes of data:
Reply from 10.6.193.119: bytes=32 time=88ms TTL=61


172.16.247.58


ecsc00104334

[dobri_stefanov@epam.com@ecsc00104334 sudoku]$ history
    1  w
    2  sudo -s
    3  ls
    4  ls -al
    5  sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkins-ci.org/redhat/jenkins.repo
    6  sudo rpm --import https://jenkins-ci.org/redhat/jenkins-ci.org.key
    7  sudo yum install jenkins
    8  history
    9  sudo yum install java
   10  sudo service jenkins start
   11  jar
   12  sudo yum provides */jar
   13  sudo yum install java-1.8.0-openjdk-devel-1.8.0.45-35.b13.el6.x86_64
   14  sudo yum search java-1.8.0-openjdk-devel
   15  sudo yum install java-1.8.0-openjdk-devel.x86_64

/home/dobri_stefanov@epam.com/com/derletztekick/games/sudoku

sudo yum install ant.x86_64

[dobri_stefanov@epam.com@ecsc00104334 sudoku]$ ant -version
Apache Ant version 1.7.1 compiled on August 24 2010


Currently the server is located in our cloud: hostname - ecsc00104334

Os version is : 
[root@ecsc00104334 dobri_stefanov@epam.com]# more /etc/redhat-release
CentOS release 6.7 (Final)


Please find below installed packages:
[root@ecsc00104334 dobri_stefanov@epam.com]# rpm -qa |grep ant
ant-1.7.1-13.el6.x86_64
[root@ecsc00104334 dobri_stefanov@epam.com]# rpm -qa |grep jenk
jenkins-1.653-1.1.noarch

Sudoku project is situated in my home dir 
/home/dobri_stefanov@epam.com/sudoku
[root@ecsc00104334 sudoku]# ls -al
total 32
drwxr-xr-x 6 dobri_stefanov@epam.com users 4096 Mar 18 18:13 .
drwx------ 6 dobri_stefanov@epam.com users 4096 Mar 21 16:58 ..
drwxr-xr-x 2 dobri_stefanov@epam.com users 4096 Mar 26  2011 generator
drwxr-xr-x 8 dobri_stefanov@epam.com users 4096 Mar 21 12:53 .git
drwxr-xr-x 2 dobri_stefanov@epam.com users 4096 Mar 26  2011 gui
drwxr-xr-x 2 dobri_stefanov@epam.com users 4096 Mar 26  2011 icon
-rw-r--r-- 1 dobri_stefanov@epam.com users 5840 Mar 28  2011 JSudoku.java


sudo yum install git.x86_64
[dobri_stefanov@epam.com@ecsc00104334 ant_test]$ git config --global user.email "dobris@gmail.com"
[dobri_stefanov@epam.com@ecsc00104334 ant_test]$ git config --global user.name "astor2015"
git init
git add .
git commit -m "First commit"


I am using my free account in github 
[dobri_stefanov@epam.com@ecsc00104334 ~]$ git remote add origin git@github.com:astor2015/sudoku.git



[dobri_stefanov@epam.com@ecsc00104334 sudoku]$ git remote -v
origin  git@github.com:astor2015/sudoku.git (fetch)
origin  git@github.com:astor2015/sudoku.git (push)

For more information you could read README.md document on the following location -> https://github.com/astor2015/sudoku  - to add more info with help of MarkDown ?!


Jenkins is availbe on the following address -> http://ecsc00104334:8080/ with user/pass - > to add ?!

4. to work on build.xml integration with git 
5. It will be highly appreciated if you also add Checkstyle










