# Week 2 Lab Report


`Installing VScode`: This is not my first time installing VScode. I went to the Visual Studio Code website to download the version for Windows. I opened VScode and it came up with a new file that is named untitled-1.

![image](Capture.JPG)

`Remotely Connecting`: My first time connecting to the server, I used my specific course username start with cs15lsp22 to connect with this new server. Once it estabilied, I re-entered my username and put in my password. Once it got connected, my computer(client) will welcome me and show my cluster status.

![image](Capture2.JPG)

`Trying Some Commands`: The command I have tried was ls -a. When I tried ls -a, it lists all the information. However, when I just put ls, it will only say perl5, because -a doesn’t ignore entries starting with period. 

![image](Capture3.JPG)

`Moving Files with scp`: When I run on the client device it shows Windows 10 cheri, which tells my personal device. And when the server runs it, it shows Linux cs15lsp22ajv. getProperty means get property of the system java file is on 

![image](Capture4.JPG)

`Setting an SSH Key`: Since it always ask me to put in my password and takes me a lot of time doing that, I set up an SSH Key. In order to do that, I used a program called ssh-keygen (first step: type ssh-keygen in command), it create a pair of key both on server(public key) and client(private key) (put my password in command two times to create keys). Both of the keys are stored in .ssh directory on my computer, so next time I don't need to re-enter my password to login in.

![image](Capture5.JPG)

`Optimizing Remote Running`: In order to directly run something on the remote server, this part I only need to put ssh+my username+"the code I want it to run on remote server". This helps me saving time on running something on the remote server

![image](Capture6.JPG)

# CSE 15L Spring 2022 Announcement
We will be using [Autograder]( https://autograder.ucsd.edu) as the student queue during TA/tutor office hours
Have a _nice_ week!