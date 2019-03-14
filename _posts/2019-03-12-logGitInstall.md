---
layout: post
title: Bash Log
categories: documentation
published: true
---
## Bash log

```
johnbolan@JohnBolan-Gazelle-Professional:~$ sudo  add-apt-repository ppa:git-core/ppa
[sudo] password for johnbolan:
Sorry, try again.
[sudo] password for johnbolan:
 The most current stable version of Git for Ubuntu.

For release candidates, go to https://launchpad.net/~git-core/+archive/candidate .
 More info: https://launchpad.net/~git-core/+archive/ubuntu/ppa
Press [ENTER] to continue or Ctrl-c to cancel adding it.

Ign:1 http://dl.google.com/linux/chrome/deb stable InRelease
Hit:2 http://dl.google.com/linux/chrome/deb stable Release                                                                        
Hit:3 http://us.archive.ubuntu.com/ubuntu bionic InRelease                                                                        
Get:5 https://brave-browser-apt-release.s3.brave.com bionic InRelease [2,825 B]                                                   
Get:6 http://us.archive.ubuntu.com/ubuntu bionic-updates InRelease [88.7 kB]                                                     
Hit:7 http://ppa.launchpad.net/aasche/cutemarked/ubuntu bionic InRelease                                 
Err:5 https://brave-browser-apt-release.s3.brave.com bionic InRelease                                                             
  The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 4FE13824E3FFC656
Get:8 http://us.archive.ubuntu.com/ubuntu bionic-backports InRelease [74.6 kB]                                                    
Get:9 http://ppa.launchpad.net/git-core/ppa/ubuntu bionic InRelease [20.7 kB]                              
Get:10 http://security.ubuntu.com/ubuntu bionic-security InRelease [88.7 kB]        
Get:11 http://ppa.launchpad.net/git-core/ppa/ubuntu bionic/main i386 Packages [3,036 B]          
Get:12 http://ppa.launchpad.net/git-core/ppa/ubuntu bionic/main amd64 Packages [3,024 B]
Get:13 http://ppa.launchpad.net/git-core/ppa/ubuntu bionic/main Translation-en [2,248 B]
Reading package lists... Done                       
W: GPG error: https://brave-browser-apt-release.s3.brave.com bionic InRelease: The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 4FE13824E3FFC656
E: The repository 'https://brave-browser-apt-release.s3.brave.com bionic InRelease' is not signed.
N: Updating from such a repository can't be done securely, and is therefore disabled by default.
N: See apt-secure(8) manpage for repository creation and user configuration details.
johnbolan@JohnBolan-Gazelle-Professional:~$ sudo apt-get update
Ign:1 http://dl.google.com/linux/chrome/deb stable InRelease
Hit:2 http://dl.google.com/linux/chrome/deb stable Release                                                                        
Get:3 https://brave-browser-apt-release.s3.brave.com bionic InRelease [2,825 B]                                                   
Hit:4 http://us.archive.ubuntu.com/ubuntu bionic InRelease                                                                        
Get:5 http://security.ubuntu.com/ubuntu bionic-security InRelease [88.7 kB]                  
Get:7 http://us.archive.ubuntu.com/ubuntu bionic-updates InRelease [88.7 kB]                               
Hit:8 http://ppa.launchpad.net/aasche/cutemarked/ubuntu bionic InRelease                                              
Err:3 https://brave-browser-apt-release.s3.brave.com bionic InRelease                                                 
  The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 4FE13824E3FFC656
Get:9 http://us.archive.ubuntu.com/ubuntu bionic-backports InRelease [74.6 kB]                                                    
Hit:10 http://ppa.launchpad.net/git-core/ppa/ubuntu bionic InRelease                
Reading package lists... Done                                                       
W: GPG error: https://brave-browser-apt-release.s3.brave.com bionic InRelease: The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 4FE13824E3FFC656
E: The repository 'https://brave-browser-apt-release.s3.brave.com bionic InRelease' is not signed.
N: Updating from such a repository can't be done securely, and is therefore disabled by default.
N: See apt-secure(8) manpage for repository creation and user configuration details.
johnbolan@JohnBolan-Gazelle-Professional:~$ sudo apt-get install git
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libavahi-gobject0 libavahi-ui-gtk3-0 libfreerdp2-2 libvte-2.91-0 libvte-2.91-common libwinpr2-2 stunnel4
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  git-man libpcre2-8-0
Suggested packages:
  git-daemon-run | git-daemon-sysvinit git-doc git-el git-email git-gui gitk gitweb git-cvs git-mediawiki git-svn
The following NEW packages will be installed:
  libpcre2-8-0
The following packages will be upgraded:
  git git-man
2 upgraded, 1 newly installed, 0 to remove and 35 not upgraded.
Need to get 7,550 kB of archives.
After this operation, 5,757 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us.archive.ubuntu.com/ubuntu bionic/universe amd64 libpcre2-8-0 amd64 10.31-2 [179 kB]
Get:2 http://ppa.launchpad.net/git-core/ppa/ubuntu bionic/main amd64 git amd64 1:2.21.0-0ppa1~ubuntu18.04.1 [5,748 kB]
Get:3 http://ppa.launchpad.net/git-core/ppa/ubuntu bionic/main amd64 git-man all 1:2.21.0-0ppa1~ubuntu18.04.1 [1,622 kB]
Fetched 7,550 kB in 6s (1,304 kB/s)  
(Reading database ... 289663 files and directories currently installed.)
Preparing to unpack .../git_1%3a2.21.0-0ppa1~ubuntu18.04.1_amd64.deb ...
Unpacking git (1:2.21.0-0ppa1~ubuntu18.04.1) over (1:2.17.1-1ubuntu0.4) ...
Preparing to unpack .../git-man_1%3a2.21.0-0ppa1~ubuntu18.04.1_all.deb ...
Unpacking git-man (1:2.21.0-0ppa1~ubuntu18.04.1) over (1:2.17.1-1ubuntu0.4) ...
Selecting previously unselected package libpcre2-8-0:amd64.
Preparing to unpack .../libpcre2-8-0_10.31-2_amd64.deb ...
Unpacking libpcre2-8-0:amd64 (10.31-2) ...
Setting up git-man (1:2.21.0-0ppa1~ubuntu18.04.1) ...
Processing triggers for libc-bin (2.27-3ubuntu1) ...
Processing triggers for man-db (2.8.3-2ubuntu0.1) ...
Setting up libpcre2-8-0:amd64 (10.31-2) ...
Setting up git (1:2.21.0-0ppa1~ubuntu18.04.1) ...
Processing triggers for libc-bin (2.27-3ubuntu1) ...
johnbolan@JohnBolan-Gazelle-Professional:~$
johnbolan@JohnBolan-Gazelle-Professional:~$ git config --global user.name "BolanBuilders"
johnbolan@JohnBolan-Gazelle-Professional:~$ git config --global user.email "JBRedacted@pm.com"
johnbolan@JohnBolan-Gazelle-Professional:~$ ^C
johnbolan@JohnBolan-Gazelle-Professional:~$ git init Mytest
Initialized empty Git repository in /home/johnbolan/Mytest/.git/
johnbolan@JohnBolan-Gazelle-Professional:~$ git add README
fatal: not a git repository (or any of the parent directories): .git
johnbolan@JohnBolan-Gazelle-Professional:~$ git add ReadMe.md
fatal: not a git repository (or any of the parent directories): .git
johnbolan@JohnBolan-Gazelle-Professional:~$ ^C
johnbolan@JohnBolan-Gazelle-Professional:~$ git add smaple.c
fatal: not a git repository (or any of the parent directories): .git
johnbolan@JohnBolan-Gazelle-Professional:~$ ls
Desktop  Documents  Downloads  Dropbox  gems  Music  Mytest  Pictures  Public  Templates  Videos
johnbolan@JohnBolan-Gazelle-Professional:~$ cd Mytest
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$ ls
ReadMe.md  sample.c
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$ git add ReadME.md
fatal: pathspec 'ReadME.md' did not match any files
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$ git add ReadMe.md
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$ git add sample.c
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$ git commit -m "FirstCommitReadmeSample.c"
[master (root-commit) 9b5593b] FirstCommitReadmeSample.c
 2 files changed, 11 insertions(+)
 create mode 100644 ReadMe.md
 create mode 100644 sample.c
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$ git remote add origin https://github.com/BolanBuilders/Mytest.git
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$ git push origin master
Username for 'https://github.com': BolanBuilders
Password for 'https://BolanBuilders@github.com':
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 452 bytes | 452.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/BolanBuilders/Mytest.git
 * [new branch]      master -> master
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$ ^C
johnbolan@JohnBolan-Gazelle-Professional:~/Mytest$


```
