# Active-Directory-Lab
In this lab I will be creating an active directory lab. The lab will have two servers, a switch, router, kali Linux machine, and a windows 10 machine.

First I will begin the lab by creating a diagram to display what network I intend to create. I will be using draw.io to create the diagram. Since this is an active directory lab I will have two servers on the network. The first server will be used as a splunk server to have logs, events, and metrics. The second server will be used used as an actve directory sever which is used for authentication, group policies, and computer management. I will then have a Windows 10 machine that is connected to the splunk server to forward data to the server as well as be connected to the switch. Then I will have a kali linux machine that is connected to the switch and used to simulate attacks. Then all of these devices will be connected to a switch and then to a router. Which will allow our system to connect to the internet while keeping information confidental through a switch.

<img width="770" height="703" alt="image" src="https://github.com/user-attachments/assets/398b3e22-4576-46c5-9ebe-7878abc7d0a4" />

Since I have the kali linux machine downloaded I will create the windows server. To do this search windows server 2022 iso and download the 64-bit version of the iso. 

<img width="1680" height="727" alt="image" src="https://github.com/user-attachments/assets/bee7de2c-7211-4da7-a243-570e8804c331" />

After it has finished downloading we are going to import it into VirtualBox. Then we are going to select create new machine and then select the iso image that we previously installed. We will check the unintended install box and then select finish.

<img width="947" height="728" alt="image" src="https://github.com/user-attachments/assets/5ee1016a-2a95-47e2-811f-d3898db6bb91" />

Then we will boot up the virtual machine and then select the defalut settings and select the operating system as shown below.

<img width="1025" height="847" alt="image" src="https://github.com/user-attachments/assets/fd5a5c99-92c2-4d95-9eb9-21f677832a18" />

Then when asked which installation we will like select custom installation and then wait for it to finish installing. 

