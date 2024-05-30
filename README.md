# Net&Sys Assignment: Running Containers for Application Development

Group Name: __Fill your team name__. 

Team Mates:
1. Ahmad Sufian bin Azmi and 2111363
2. __Fill name__ and __matric no__
3. __Fill name__ and __matric no__

## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** https://github.com/Pianizx/NatSysProject.
2. How many files and folders are in this repository. ***(1 mark)*** 1.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** Ubuntu Linux.
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 2 cores, 8 GB RAM, and 32 GB storage, or 32 cores, 64 GB RAM, and 128 GB storage..
3. Why must we commit and sync our current work on source control? ***(1 mark)*** so that our work will not be lost when we want to submit our project.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
```
/workspaces/NatSysProject
```

2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
```
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
```

3. Run the command **df** . ***(1 mark)*** 
```
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 14451848  16701732  47% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 24400424   5881368  81% /vscode
/dev/sdb1       46127956      104  43752276   1% /tmp
/dev/loop4      32847680 14451848  16701732  47% /workspaces
```

4. Run the command **du** . ***(1 mark)*** 
```
1972    ./images
12      ./.git/objects/60
12      ./.git/objects/ff
8       ./.git/objects/c6
8       ./.git/objects/4b
8       ./.git/objects/41
12      ./.git/objects/d2
8       ./.git/objects/d8
8       ./.git/objects/e7
12      ./.git/objects/2e
8       ./.git/objects/4a
8       ./.git/objects/7b
16      ./.git/objects/fb
8       ./.git/objects/fe
12      ./.git/objects/6e
8       ./.git/objects/fa
12      ./.git/objects/1c
8       ./.git/objects/f2
1820    ./.git/objects/pack
12      ./.git/objects/70
12      ./.git/objects/64
12      ./.git/objects/44
8       ./.git/objects/74
8       ./.git/objects/0d
8       ./.git/objects/cb
8       ./.git/objects/58
12      ./.git/objects/14
8       ./.git/objects/3f
12      ./.git/objects/3d
12      ./.git/objects/af
8       ./.git/objects/f6
8       ./.git/objects/83
8       ./.git/objects/91
8       ./.git/objects/b2
8       ./.git/objects/3a
12      ./.git/objects/73
8       ./.git/objects/93
8       ./.git/objects/b6
8       ./.git/objects/a6
8       ./.git/objects/71
8       ./.git/objects/a3
8       ./.git/objects/04
8       ./.git/objects/eb
8       ./.git/objects/fc
8       ./.git/objects/49
8       ./.git/objects/4f
8       ./.git/objects/c3
8       ./.git/objects/81
12      ./.git/objects/72
8       ./.git/objects/0b
8       ./.git/objects/1b
4       ./.git/objects/info
8       ./.git/objects/52
12      ./.git/objects/89
8       ./.git/objects/27
8       ./.git/objects/20
8       ./.git/objects/86
8       ./.git/objects/fd
8       ./.git/objects/cd
12      ./.git/objects/62
12      ./.git/objects/b5
12      ./.git/objects/e5
12      ./.git/objects/17
8       ./.git/objects/e9
8       ./.git/objects/47
8       ./.git/objects/24
8       ./.git/objects/96
8       ./.git/objects/b9
8       ./.git/objects/ab
2440    ./.git/objects
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/refs/tags
8       ./.git/refs/heads
8       ./.git/refs/remotes/origin
12      ./.git/refs/remotes
28      ./.git/refs
8       ./.git/info
8       ./.git/logs/refs/heads
8       ./.git/logs/refs/remotes/origin
12      ./.git/logs/refs/remotes
24      ./.git/logs/refs
32      ./.git/logs
64      ./.git/hooks
4       ./.git/branches
2616    ./.git
4608    .
```

5. Run the command **ls** . ***(1 mark)*** 
```
README.md  images
```

6. Run the command **ls -asl** . ***(1 mark)*** 
```
total 36
 4 drwxrwxrwx+ 4 codespace root  4096 May 23 01:07 .
 4 drwxr-xrwx+ 5 codespace root  4096 May 23 01:07 ..
 4 drwxrwxrwx+ 9 codespace root  4096 May 23 01:23 .git
20 -rw-rw-rw-  1 codespace root 16739 May 23 01:41 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 May 23 01:07 images
```

7. Run the command **free -h** . ***(1 mark)*** 
```
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.5Gi       281Mi       1.0Mi       6.0Gi       5.9Gi
Swap:            0B          0B          0B
```

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)***
```
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.898
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.893
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```

9. Run the command **top** and type **q** to quit. ***(1 mark)***
```
top - 01:44:17 up  4:36,  0 users,  load average: 0.20, 0.22, 0.20
Tasks:  17 total,   1 running,  16 sleeping,   0 stopped,   0 zombie
%Cpu(s):  4.4 us,  4.5 sy,  0.0 ni, 90.9 id,  0.2 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    277.1 free,   1538.3 used,   6114.2 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6075.2 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                             
   2687 codespa+  20   0   21.1g 344832  46464 S   2.3   4.2   0:55.30 node                                                                
   2619 codespa+  20   0  962676 103384  42112 S   1.0   1.3   0:07.29 node
```

10. Run the command **uname -a**. ***(1 mark)*** 
```
Linux codespaces-250421 6.5.0-1019-azure #20~22.04.1-Ubuntu SMP Wed Apr  3 03:28:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```

11. What is the available free memory in the system. ***(1 mark)*** **281 Mi**.

12. What is the available disk space mounted on /workspace. ***(1 mark)*** **16GB**.

13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** **version: 6.5.0-1019-azure, hardware architecture: x86_64 GNU/Linux**.

14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** **ls is a command that gives a simple list of files and directory while ls -asl provided more detailed listing of the file such as permissions, owner, and timestamp.**

15. What is the TLB size of the Virtual CPU. ***(1 mark)*** **2560 4K pages**.

16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** **3243.893MHz**.

17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** **PID 2687 USER codespa+ is consumes the most CPU cycles which is 2.3%**.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
My Terminal:
```
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker pull debian
Using default tag: latest
latest: Pulling from library/debian
Digest: sha256:fac2c0fd33e88dfd3bc88a872cfb78dcb167e74af6162d31724df69e482f886c
Status: Image is up to date for debian:latest
docker.io/library/debian:latest
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker run --detach -it debian
75fbc0cb62389856b35ca84e5aba881bc7db5364b969fdc34d86c94be28c97cd
```


2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```
My Terminal:
```
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                      PORTS     NAMES
75fbc0cb6238   debian    "bash"    9 minutes ago   Up 9 minutes                          quizzical_taussig
```


3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```
My Terminal:
```
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker exec -i -t quizzical_taussig /bin/bash
```


4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```
My Terminal:
```
root@75fbc0cb6238:/# apt-get update 
Get:1 http://deb.debian.org/debian bookworm InRelease [151 kB]
Get:2 http://deb.debian.org/debian bookworm-updates InRelease [55.4 kB]
Get:3 http://deb.debian.org/debian-security bookworm-security InRelease [48.0 kB]
Get:4 http://deb.debian.org/debian bookworm/main amd64 Packages [8786 kB]
Get:5 http://deb.debian.org/debian bookworm-updates/main amd64 Packages [13.8 kB]
Get:6 http://deb.debian.org/debian-security bookworm-security/main amd64 Packages [157 kB]
Fetched 9212 kB in 1s (7924 kB/s)
Reading package lists... Done
root@75fbc0cb6238:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 0 not upgraded.
Need to get 837 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1 [689 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 837 kB in 0s (33.4 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6090 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../archives/nano_7.2-1_amd64.deb ...
Unpacking nano (7.2-1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u7) ...
root@75fbc0cb6238:/# cd /root
root@75fbc0cb6238:~# nano helloworld.txt
```


5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.
My Terminal:
```
root@75fbc0cb6238:~# exit
exit
@Pianizx ➜ /workspaces/NatSysProject (main) $ 
```

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available? **Yes, it still available**
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```
My Terminal:
```
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker stop quizzical_taussig
quizzical_taussig
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
75fbc0cb6238   debian    "bash"    17 minutes ago   Exited (137) 11 seconds ago             quizzical_taussig
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker restart quizzical_taussig
quizzical_taussig
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker exec -i -t quizzical_taussig /bin/bash
root@75fbc0cb6238:/# cd root
root@75fbc0cb6238:~# ls
helloworld.txt
```


7. Stop the container and delete the container. What happened to your helloworld.txt? **The helloworld.txt file is deleted because the container have been deleted**

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```
My Terminal:
```
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker stop quizzical_taussig
quizzical_taussig
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                       PORTS     NAMES
75fbc0cb6238   debian    "bash"    25 minutes ago   Exited (137) 4 seconds ago             quizzical_taussig
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker rm quizzical_taussig
quizzical_taussig
@Pianizx ➜ /workspaces/NatSysProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED      STATUS                      PORTS     NAMES
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** **No because the container are designed to be ephemeral and stateless which means they can be created, started, stopped, and destroyed quickly and easily**.

2. Can we run two, or three instances of debian linux? . ***(1 mark)*** **Yes, Debian Linux containers can run multiple instance simultaneously using Docker. Each container runs independently and can be configured to have its own environment**.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```
My Terminal:
```
@Pianizx ➜ /workspaces/NatSysProject (main) $ mkdir myroot
@Pianizx ➜ /workspaces/NatSysProject (main) $ cd myroot/
@Pianizx ➜ /workspaces/NatSysProject/myroot (main) $ pwd
/workspaces/NatSysProject/myroot
@Pianizx ➜ /workspaces/NatSysProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
16dbf27c2bf9c6828f68ade45b33267209a9acd48035340f187f3f4539ff2033
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** **The permission of the folder /workspaces/NetSysProject is -rw-rw-rw, and it is owned by the user root and the group root**.
```
@Pianizx ➜ /workspaces/NatSysProject/myroot (main) $ ls -l -a
total 16
drwxrwxrwx+ 3 codespace codespace 4096 May 27 08:25 .
drwxrwxrwx+ 5 codespace root      4096 May 27 07:50 ..
drwxrwxrwx+ 3 root      root      4096 May 27 08:22 .local
-rw-rw-rw-  1 root      root        12 May 27 08:22 file1.txt
```

2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Fill answer here__.***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** __Fill answer here__.
2. What port is the apache web server running. ***(1 mark)***
3. What port is open for http protocol on the host machine? ***(1 mark)***

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** __Fill answer here__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
4. What is the network address for the running container c1 and c2.
5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
