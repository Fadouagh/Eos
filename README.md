# Eos
Eos system
==========

To receive the packages of Eos, please write to fadouaghourabi@gmail.com. We would like to keep a list of Eos users and, hopefully, collect their feedback for future revisions.

Requirements
============
1. For running Eos
Mathematica 10 or 11
Mac Os, Linux, Windows

2. For reading only
CDF player

Installation
============
1. Change the path to the folder Eos in file Eos/init.nb.

***
Common`$eosSystemDirectory = FileNameJoin[{$HomeDirectory, <relative path to Eos from home directory>}];
***

Save. Source init.m is automatically generated.

2. Change the path to the folder Eos in the file Eos/install.nb.

***
fromDir = FileNameJoin[{$HomeDirectory ,  <relative path to Eos from home directory>}]
***

Run Install.nb (ctrl-a, shift-enter). The program will copy init.m to Mathematica/Kernel.

3. Open a Mathematica notebook, copy and run the following line to check that Eos/OrigamiBasics and Eos/ga/G3/math is in Mathematica's path.

$Path

How to use
==========
Check Tutorial.nb

Contact
=======
Fadoua Ghourabi, fadouaghourabi@gmail.com
