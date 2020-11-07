# Remote-Host-Clion
Read to understand how to connect to lab computers in Ben Gurion University Through CLion

Choose requested computer in the lab from here: http://oldweb.cs.bgu.ac.il/facilities/labs.html

![](images/computerss.png)

First of all, you should be able to connect to a lab computer of your choice through putty/mobaxterm/any shell you like, as described in the following lesson: https://www.cs.bgu.ac.il/~spl211/PracticalSession01/Linux.

Install c++ using shell, as explained here: https://linuxconfig.org/how-to-install-g-the-c-compiler-on-ubuntu-18-04-bionic-beaver-linux.

After doing so, you are ready to begin:

1.	Go to CLion. 
2.	In Settings, go to “Build, Execution, Deployment”. 
3.	Go to “toolchains”
4.	Click the “+” sign, and choose “remote host”.

![](images/remote_host.png)

5.	In credentials, click on the wheel.

![](images/credentials.png)


6.	Click on the “+” sign.

7.	Put the computer address in “host”, [computer_name].bgu.ac.il

![](images/host.png)


8.	Put your Linux username and password.

9.	Press “test connection”.
Make sure you have VPN turned on (as explained here https://www.cs.bgu.ac.il/~spl211/PracticalSession01/Linux)

10.	Once you are connected, fill “Make” and “C++ Compiler” in the following manner.

![](images/paths.png)


11.	You are ready to go.

