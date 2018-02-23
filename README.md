# px

px.rsrc is the resource directory of the program px.

The program px is a virtual machine that emulates an http server and is a front-
end to databases. Its application language shows much resemblance to the once
very famous fourth generation language Omnis published by Blyth Software. With
px you can, just as with Omnis, setup your own information system.

It is Linux/Unix oriented. By convention it should be at ~/px/.

px.rsrc contains information for the program to run. It holds for example the
translation tables (for words and statements).

It also contains:

1-a datadictionary with definitions of tables, fields and fieldgroups
2-c++ source files
3-gnu makefiles
4-tools and stuff
5-documentation

An overview of all subdirectories:

px.css - legacy
px.db - MySQL databases with base applications
px.dd - The data dictionary
px.default - Default files to setup a new environment from scratch
px.doc - Misc documentation
px.js - Javascript files
px.language - Translation tables
px.pict - Pictures for the user interface (legacy)
px.sdk - Misc other tools and programs
px.src - C++ source files
px.test - Data files used for testing
px.xcod - The Xcode project file for compiling and linking under MacOSX
px.xgnu - The Makefiles for compiling and linking under Linux/Unix

The resource directory contains all to understand and modify px. For technical
reasons this is desirable because servers has the information to apply
changes and a server has access to its own source code.

This version may be copied and modified. Serious users, or commercial users of
px (or products derived from it) are strongly advised to contact us at
www.zenopx.nl to stay in tune with future releases.

See the readme.txt file in the subdirectories for more techincal details
