# BeRoot Project 

BeRoot Project is a post exploitation tool to check common misconfigurations to find a way to escalate our privilege. \
It has been added to the [pupy](https://github.com/n1nj4sec/pupy/) project as a post exploitation module (so it will be executed in memory without touching the disk). 

This tool does not realize any exploitation. It mains goal is not to realize a configuration assessment of the host (listing all services, all processes, all network connection, etc.) but to print only information that have been found as potential way to escalate our privilege. 

This project works on Windows, Linux and Mac OS. You could find the Windows version [here](https://github.com/AlessandroZ/BeRoot/tree/master/Windows) and the Linux and Mac OS [here](https://github.com/AlessandroZ/BeRoot/tree/master/Linux)

I recommend reading the README depending on the targeted OS, to better understand what's happening. 

I tried to implement most technics described in this picture:

<p align="center"><img src="./pictures/privilege_escalation_workflow.jpeg" alt="BeRoot"></p>


Enjoy ;)


Interesting projects
----
* [Windows / Linux Local Privilege Escalation Workshop](https://github.com/sagishahar/lpeworkshop)
* [Linux tools](https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Privilege%20Escalation%20%26%20Post-Exploitation.md#linpriv)
* [Windows tools](https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Privilege%20Escalation%20%26%20Post-Exploitation.md#privescwin)


