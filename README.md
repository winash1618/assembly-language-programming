# assembly-language-programming
This repo contain assembly programs of simpleRISC, ARM, x86, masm32
1 masm32
  * installation link http://masm32.com/download.htm
  * running hello world
      * open cmd
      * cd file location for example: cd C:\Users\admin\Documents
      * now we need to first create object file for our assembly program 
      * \masm32\bin\ml \c \coff FILENAME.asm
      * next we are going to create executable(.exe) file of our .obj file
      * \masm32\bin\link /SUBSYSTEM:CONSOLE FILENAME.obj
      * finally run the executable by typing FILENAME.exe
          
