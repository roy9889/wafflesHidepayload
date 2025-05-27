This is a modified version of 
https://github.com/WafflesExploits/hide-payload-in-images/blob/main/code/payload-extractor/payload-extractor-from-file/payload-extractor-from-file.cpp

This runs silently and persistently 

Edit the Size and location of the image 

and compile as below (or similar):

x86_64-w64-mingw32-g++ Read-IMG-BACKUP.cpp -mwindows -static-libgcc -static-libstdc++ -luser32 -lkernel32 -static -lwinmm -o OUTPUT.exe
