# Eos
Eos system
==========

This tutorial explain how to use the Eos system to solve origami geometrical problem. 
To receive the packages of Eos, please write to fadouaghourabi@gmail.com.

Reference about Eos system:
1. Tutorial.nb

2. Tetsuo Ida, An Introduction to Computational Origami, Springer 2020
https://www.springer.com/gp/book/9783319591889

3. Conference/Journal publications
https://dblp.org/pid/i/TetsuoIda.html

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
