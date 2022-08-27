# CS3013_A01_2022_KP_Project0

Krish Patel
8/27/2022

STEP 1:
- Virtual Machine Manager: AWS EC2 (Ubuntu 22.04)
- No tutorials consulted (I have prior work experience with AWS EC2)
- No issues along the way

STEP 2: View project0_s2.txt

STEP3:
strncpy: #include <string.h>
exit: #include <stdlib.h>
printf: #include <stdio.h>

-g Produces debugging information in the operating system's native format (stabs, COFF, XCOFF, or DWARF). GDB can work with this debugging information

View Script on project0_s3.txt

STEP 4:

after running the gdb, the debugger determined that the error was in line 7
strncpy(buffer, "Hello World!", 14);
This line caused an issue with the code because the buffer is of the char pointer type (char*) and strncpy would use strings rather than chars.
