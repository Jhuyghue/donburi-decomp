# 1. Overview 
This repository documents the software archaeology project on *TwinBee PARADISE in Donburi Shima* (ツインビーPARADISE in どんぶり島), a 1998
Windows 95 multimedia CD-ROM by Konami that was built with **Macromedia/Adobe Director**. 

The goal is to understand how the software is structured and why it behaves differently on modern systems. 
For example, some CD-ROM software made in a certain version of Director will run very well on Windows 10/11 without much of an issue while other have issues. 
From my observation of working with Director in the past, some games may run faster based on the type of processor you have, the game will crash on runtime, 
or will have unsupported/outdated external tools that make some of the software work.  Most Director games are either emulated with ScummVM or Virtual Machines
to fully run them since it's a easier setup to work with. 

The project covers the Lingo scripts, file formats, Japanese text encoding, and media and path handling in the original. While that all of the research is being documented,
the game is going to be recompiled to work on Windows 10/11. Most of the internal and external filenames are going to be renamed for better readability.