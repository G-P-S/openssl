========================================================================
    MAKEFILE PROJECT : openssl_2013 Project Overview
========================================================================

This solution was created to build openssl for windows through visual studio.  
It uses nmake and customizes some of the commands to make win32 and x64 in the 
same directories and then copy the output to expected directories to avoid conflicts

When building, the include directory inc32 is created automatically.  This is not
directly checked in because it can contain different files depending on win32 or x64
build.  As a result the include files where checked in under inc_win32 and inc_x64.

/////////////////////////////////////////////////////////////////////////////
