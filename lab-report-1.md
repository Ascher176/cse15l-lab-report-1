## CSE15L Account
First, you need to look up your course-specific CSE 15L account on this website:
[https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php):    
![Image](image1.jpg) 
   
Under additional accounts you should click the one that starts with "cs15l":  
![Image](image3.jpg)  
   
In the new window copy your username and click "Global Password Change Tool":  
![Image](image2.jpg)  
   
Click "Proceed to the Password Change Tool".   
When you are asked to enter your username make sure to put your cs15l username you have just copied.       
Follow the instructions. After you click the "Finish password setup" button you are done with the password reset.       
It might take a few minutes to take effect.     

## Visual Studio Code
I had VScode installed on my laptop since I have been using it before this class (for CSE 8B).   
However, I will include the instructions on how I installed it (I am working on Windows).  
The link where it can be installed: [https://code.visualstudio.com/](https://code.visualstudio.com/).  
After opening the website you should click this:  
![Image](image4.jpg)  
  
The window will pop up. You should click "Save"  
(but keep in mind where you are saving the file so you can easily find it. I am saving it on my Desktop):  
![Image](image5.jpg)  
   
Open the installer you have just downloaded and follow the instructions.  
When it is installed you should be able to open this window:  
![Image](image6.jpg) 

## Remotely Connecting
First, you need to install git. Here is the link for Windows: [https://gitforwindows.org/](https://gitforwindows.org/).  
Then open VScode and open a new terminal:  
Image 3  
In the terminal type this command `$ ssh username@ieng6.ucsd.edu` where username is your cs15l username.  
(The dollar sign is used to indicate that what follows is a command, it should not be typed in.)  
Type in "yes" when asked if you are sure you want to connect.  
Then you will be asked for password. Type in the password you have created in the first step.   
You cannot see what are you typing in the command line for security reasons.  
After that you will see something like this:   
Image 4

## Run Some Commands
Your terminal is now remotely connected to the server and you can run different commands.  
Here is a list of command I tried:  
* cd ~
* cd
* ls -lat
* ls -a
* ls /home/linux/ieng6/cs15lsp23/cs15lsp23ly (cs15lsp23ly - username of one of my groupmates)  
* cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/
* cat /home/linux/ieng6/cs15lsp23/public/hello.txt
The result:  
Image 5  

You can run the command _exit_ to log out of the remote server or create a new terminal and try the same commands on your computer.  
My result:   
Image 6  




