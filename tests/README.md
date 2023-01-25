As a consequence, be careful not to push any c file containing a main function in the root directory of your project (you could have a test folder containing all your tests files including main functions)
Our main files will include your main header file (main.h): #include main.h
You might want to look at the gcc flag -Wno-format when testing with your _printf and the standard printf

Authors:
        Victor Ayodeji Olatunde https://github.com/Re1gns
        Robiat Adeshewa https://github.com/Crownbeauty01
