# Usage of Desktop PCs

The Desktop PCs in the student office have the Ubunutu 18.04 operating system. You can log in to each PC with you *UU/Solis* account name (all lower casse letters) and pass word.

# Home directory

When you log in to a PC, you home directory from the central UU facilities will be automatically 'mounted', and you should see your files there (using 'ls' in a terminal).
Settings for software such as the Firefox web browser and the graphical environment on the desktops are also stored in your home directory and should therefore be the same on all PCs.
Note that your home directory has only **2 Gb storage space**, which can quickly fill up if you download and compile software or store large output files from analysis code. If you need more disk space, it is normally more convenient to run on the [quark cluster](quark.md).
To check the disk usage in your home directory, do:
```
cd
du -sh
```
This will take a minute to collect all the information, but will show your total disk usage. If it is growing, make sure to check that the trash can is emptied after you remove files. There may be a directory 'Recycle_bin' that you also need to remove.


# Software packages

Import packages, such as ROOT, AliRoot and several event generators are available from the the shared file system cvmfs. 
To use a software package, you first need to set up the environment, which tells the system (shell) which version of the software you want to use. There is simple shortcut that allows you to do this:
```
ali
```
after which you can for example start up root:
```
root
```
