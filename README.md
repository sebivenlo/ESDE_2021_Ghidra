# ESDE_2021_Ghidra

##Reverse Engineering with Ghidra

**Reverse Engineering:**  
From assembled product to lose materials, in our world also known as <u>Decompiling</u>. A decompiler reads the assembly code and tries to interpret it, to vaguely recreate the original code. 

**Ghidra:**  
Ghidra, a program created and published by the National Security Agency, is a reverse engineering tool, that lets you analyze one or more compiled files, to be able to view the original code with all its imports, methods, fields etc.

**Practical Part:**  
To be able to run and analyze a file with Ghidra, do the following:  
1. Go to https://github.com/NationalSecurityAgency/ghidra/releases
2. Download Version 10.0.3 (Assets -> ghidra_10.0.3). There is also an Installation Guide, that might help you with setting up Ghidra.
3. Extract the Zip-File to your desired location.
4. Download JDK 11 LTS from wherever you want. An option could be https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html
5. Now <u>either</u>: Add the the \bin directory to your system variables and make it the active one <u>or</u>: Go to your_ghidra_folder\support, open launch.properties with any editor, locate JAVA_HOME_OVERRIDE and write the complete path to your JDK 11 folder behind it. (\bin not necessary)
6. You should be pretty much set now. Open CMD and type "ghidraRun", which should open Ghidra.
7. Now create a new Active Project and after that you can drag the crackme files into that project.
8. Double click one of the files and Ghidra should open a new window.

