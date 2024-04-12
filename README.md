# Virtual Machine for Vulnerabilities

![image](https://github.com/Ashraf-In-Tech/Virtual-Machine-for-Vulnerabilities-/assets/165876025/a1e263ff-5153-4492-bcbd-701e81563880)

## Intro

Now that I created the virtual machine for the OpenVAS software, I need to create a 2nd virutal machine. This is important for the lab because it will host all of the insecure/outdated software. I did the following when created the 2nd virtual machine:

- It will go to the same Resource group called "Vulneraiblity Management"
- It will be in the same region as the other virtual machine
- I named the virutal machine "Win10-Vulnerable"
- For the image, I made it Windows 10 Pro

![VL 10](https://github.com/Ashraf-In-Tech/Virtual-Machine-for-Vulnerabilities-/assets/165876025/e7b25532-dcf2-4b15-82bb-01bafbf25ec7)

It's very important that the 2nd virtual machine is placed in the same virtual network as the virtual machine that has OpenVAS. The virtual network is OpenVAS-vnet.

![VL 11](https://github.com/Ashraf-In-Tech/Virtual-Machine-for-Vulnerabilities-/assets/165876025/bf0087ac-caf8-4657-8a4f-dcced85480be)

After that, I clicked create.  After the new virtual machine has been made, I will log into it remotely and download outdated software. 

![VL 12](https://github.com/Ashraf-In-Tech/Virtual-Machine-for-Vulnerabilities-/assets/165876025/eea0f892-ff3b-43d1-b678-0a86d107bcc3)

I will then copy the public IP address of Wind10-Vulnerable.

![VL 13](https://github.com/Ashraf-In-Tech/Virtual-Machine-for-Vulnerabilities-/assets/165876025/87cd4bf3-3967-4c87-8067-f4378082ad82)

Then I will open up the Remote Desktop Connection in my Windows computer in order to log into the virtual machine I just created.
* Put the MACos version here

I pasted the public IP address. After that, I put in the username and password to log in the virtual machine. 

![VL 14](https://github.com/Ashraf-In-Tech/Virtual-Machine-for-Vulnerabilities-/assets/165876025/61ebb535-b0a1-4f25-9f7b-99fdb2748aea)
![VL 15](https://github.com/Ashraf-In-Tech/Virtual-Machine-for-Vulnerabilities-/assets/165876025/f994900f-2921-443e-acfa-b21303d550da)

## Step 2 is done. I have just created a separate virtual machine where outdated software will be downloaded. 
