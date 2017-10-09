---
layout: default
title: Installation Guide
---

* * *

## The use of FLAME requires a C compiler (GCC)

This can be easily installed under the following operations systems:
 
### **Windows**
> 1. Install MinGW following the Getting Started guide at [Getting Started](http://www.mingw.org/wiki/Getting_Started "Getting Started")
> 2. Remember to change the Environment Settings to add MinGW to the *path*
> 3. Change the name of **C:\MinGW\bin\mingw32-make.exe** to just **make.exe**

### **Mac OSX**
> 1. Install Xcode
>> 1. From the Mac App Store
>> 2. Newer versions might require you to download the Command Line Tools from the preferences panel.

### **Linux**
> 1. Should already be installed or use your distributions Package Manager to install GCC

* * *

## Obtain Xparser

Xparser is the program that parses a model file and produces source code for a simulation program.

1. Download [Xparser](../download)
2. Unzip the package
3. On the command line change to the xparser directory and run **make**
4. This creates the xparser executable

* * *

## Obtain libmboard

Libmboard is the communication library used by simulation programs.
It can be compiled or a compiled (binary) version is available for Windows:

1. Download [libmboard](../download)
2. Untar the package
3. Follow the instructions within **README** to compile and install

If you have installed to your own *location* then when compiling models using **make** on the command line append the *location* as a parameter by using **LIBMBOARD_DIR=**

or

1. Download the Windows binary version [here](http://ccpforge.cse.rl.ac.uk/gf/download/frsrelease/107/224/libmboard-0.2.1-WinBinaries.zip)
2. Unzip the package
3. Rename the folder from **libmboard-0.2.1** to just **libmboard** and copy the folder to folders that contain models


* * *

Viewing model state graphs requires:

* Dotty
> 1. Install [Graphviz](http://www.graphviz.org "Graphviz")


