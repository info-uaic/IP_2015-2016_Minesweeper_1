# IP_2015-2016_Minesweeper_1
This repo will hold one of the Minesweeper projects


Project made on Code::Blocks 13.12. 


Running the source code may fail on some versions of Visual Studio because of one or more of the followings:

-the security put by Microsoft on ‘char’ functions(like strcpy, strcat, etc) from <string.h> library. Can be repaired by removing this security (or rewriting the code to follow this security);
-kbhit() function may have an underscore ('_') in front of it (_kbhit());
-_sleep(number_of_seconds_to_sleep) function may not have the underscore ('_') in front of it.
 
