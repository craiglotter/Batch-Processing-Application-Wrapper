Batch Processing Application Wrapper
====================================

Batch Processing Application Wrapper is used to provide batch support for folder or input text processing when a desired application does not provide the necessary functionality. As long as a desired application can be run from the command line and exits once processing is complete, Batch Processing Application Wrapper can be used to emulate a 'batch processing' mode for the application. The user can specify whether Batch Processing Application Wrapper needs to process a folder's contents (recursive or non-recursive) or needs to parse a text file containg the desired program inputs.

The special term #inputtext# is used to indicate where the variable term is to be used in the application to run's argument list. (e.g. ->"c:\Program Files\fileobfuscater.exe" -f #inputtext#)

Created by Craig Lotter, February 2006

*********************************

Project Details:

Coded in Visual Basic .NET using Visual Studio .NET 2003
Implements concepts such as threading, file manipulation and recursive programming.
Level of Complexity: simple
