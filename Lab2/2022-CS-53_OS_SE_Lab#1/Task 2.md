### Task#2

For gcc and g++ installation we have to go ubuntu, click on leftmost below square dots and search terminal

![v15](C:\Users\Dulmi\Downloads\v15.PNG)

Open it and write the following command **sudo apt install gcc g++** and press enter

This will install gcc and g++ compilers.

![v10](C:\Users\Dulmi\Downloads\v10.PNG)

sudo apt update is just for check updates if any.

![v11](C:\Users\Dulmi\Downloads\v11.PNG)

The installation process will continue by Typing Y means Yes

![v12](C:\Users\Dulmi\Downloads\v12.PNG)

The installation is start, wait for 4 minutes to complete.

After that we have to create test.cpp file with Text Edition of Ubuntu, for this open the Main Menu

![v16](C:\Users\Dulmi\Downloads\v16.PNG)

Click on text Editor and write the following code

\#include<iostream>

using namespace std;

int main()

{

cout<< “Testing G++ Compiler!!!!!!!”;

cout<< “Yes, G++ Compiler working Perfectly!!!!!!!”;

return 0;

}

![v17](C:\Users\Dulmi\Downloads\v17.PNG)



The use of endl is for new line, now save it on Desktop

Create new file named test.c and write the below code and save it also on Desktop

![v18](C:\Users\Dulmi\Downloads\v18.PNG)

Now go to Terminal, before writing the following command to run c++ file named test.cpp

We have to change the directory to Desktop to locate our test.cpp file.

To change directory we use **cd ~/Desktop** command. And then write **g++ -o obj test.cpp** and press Enter

![v13](C:\Users\Dulmi\Downloads\v13.PNG)

As there is no error in code, the file is compiled successfully, now for output we write **./obj**

The output is shown above.



Now to run test.c file we use the command **gcc -o obj test.c**. as the program compiled successfully now we run it using **./obj**

![v14](C:\Users\Dulmi\Downloads\v14.PNG)

