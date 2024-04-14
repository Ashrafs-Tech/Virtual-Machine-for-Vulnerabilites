# Virtual Machine for Vulnerabilities

![image](https://github.com/Ashrafs-Tech/Virtual-Machine-for-Vulnerabilites/assets/166546026/d5e02213-3611-4d2a-a922-018946df844d)


## Intro

Now that I created the virtual machine for the OpenVAS software, I need to create a 2nd virutal machine. This is important for the lab because it will host all of the insecure/outdated software. I did the following when created the 2nd virtual machine:

- It will go to the same Resource group called "Vulneraiblity Management"
- It will be in the same region as the other virtual machine
- I named the virutal machine "Win10-Vulnerable"
- For the image, I made it Windows 10 Pro

![VL 10](https://github.com/Ashrafs-Tech/Virtual-Machine-for-Vulnerabilites/assets/166546026/e9be1ba9-0bb4-41a8-acba-4718d0f5de54)


- It's very important that the 2nd virtual machine is placed in the same virtual network as the virtual machine that has OpenVAS. The virtual network is OpenVAS-vnet.

![VL 11](https://github.com/Ashrafs-Tech/Virtual-Machine-for-Vulnerabilites/assets/166546026/fc5ce72d-35de-483f-a377-28f0050aa913)


- After that, I clicked create.  After the new virtual machine has been made, I will log into it remotely and download outdated software. 

![VL 12](https://github.com/Ashrafs-Tech/Virtual-Machine-for-Vulnerabilites/assets/166546026/49806d18-c912-4109-9611-380ea4c7d085)


- I will then copy the public IP address of Wind10-Vulnerable.

![VL 13](https://github.com/Ashrafs-Tech/Virtual-Machine-for-Vulnerabilites/assets/166546026/153fa4ab-804f-41d1-b433-501a596de654)


- Then I will open up the Remote Desktop Connection in my Windows computer in order to log into the virtual machine I just created.


- I pasted the public IP address. After that, I put in the username and password to log in the virtual machine. 

![VL 14](https://github.com/Ashrafs-Tech/Virtual-Machine-for-Vulnerabilites/assets/166546026/ff43d99b-c4b0-420a-ad0f-960bd0c8698c)

![VL 15](https://github.com/Ashrafs-Tech/Virtual-Machine-for-Vulnerabilites/assets/166546026/d463fe90-bcc1-409b-a16f-b6c91683305b)


## Step 2 is done. 
I have just created a separate virtual machine where outdated software will be downloaded. 
