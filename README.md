 # DigitalNoteWallet
The GUI DigitalNoteWallet
 # Contributing to the DigitalNoteXDN Project
 
 Always check the latest README.md at https://github.com/DigitalNoteXDN/digitalnotewallet/blob/master/README.md for updated instructions.

The new dev team are continually looking for skilled blockchain developers in the Cryptonight space. Not everyone is able to do this so do not dispair,
as a start, we encourage you to help test the software, and report bugs to the team. Please see below for some guidelines. 

Things will be a bit slow to start off, so do not get impatient if your pull request is not initiated right away, in some cases it will require extensive testing before it is released or merged.

## General guidelines

The "DigitalNoteXDN core Team" is defined as the following GitHub users:

 	AuCRHI
 	DrCryptoToad
	rainmanp7
  
At the moment we are using preferred builds to develop and test software.
These are based on Mac OS Sierra, Mac OS High Sierra, Windows 10 64bit and Linux (Lubuntu ver 17.1).

Qt Creator is used on Macs and Microsoft Visual Studio community 2017 for Windows.

All patches are to be sent via a Github pull request. 

Patches should be self-contained and well documented. 
One patch per separate issue, feature, or logical change. Also, please follow the code style of the code you are 
modifying. 

Please be carful when submitting and select
what changes you wish to commit using git add the -p switch. This 
walks you through all the changes and asks whether or not to
include a particular change creating clean patches. 

      git diff will show you the changes in your tree.
      git diff --cached will show what is currently staged for commit. 

When you add hunks with git using -p as a switch, those hunks will
"move" from the git diff output to the git diff --cached output,
so you can see clearly what your commit is going to look like.

## Commits and pull requests

Please document all commits and pull requests in detail.

When submitting a pull request on Github, make sure your branch is
rebased. No merge commits nor stray commits from other people in
your submitted branch. You may be asked to rebase if there
are conflicts which is a pain.

# Code of Conduct (42/C4)

Please adhere to the following principles when contributing to the project.

Please see https://rfc.zeromq.org/spec:42/C4

## License

Copyright (c) 2018 The DigitalNote Project 

This is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.

It is supplied WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

Please see GNU General Public License along with this program -  <http://www.gnu.org/licenses>.
