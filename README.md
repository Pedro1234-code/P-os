# P-os
Operating System based on Windows 11, but better and without Microsoft's garbage

Some of removed things: A lot of UWP Apps, Microsoft Account Sign-In, TPM 2.0 Requisite and Secure Boot requisite.

Added Features: WSL and Microsoft .NET 4.5

# Performance Tests
The system was tested on a virtual machine using VMWare Workstation Player 16, with 1.6 gb of RAM, on a host with 4 gb of RAM, Intel(R) Core(TM) i3-10110U CPU @ 2.10GHz   2.59 GHz, Dual-Boot Windows 10 and Windows 11, and the system was running better than a lot of real PCs, without freezes.

The system, with GitHub Web running on Microsoft Edge, was spending 5% of the CPU, 59% of the RAM and 1% of the disk, surpassing the Windows 10 host

Pos Task Manager: 

![TaskmgrPos](https://user-images.githubusercontent.com/78425126/133113160-d595fbb0-c76b-47dc-8aef-cbfc322fdb0d.PNG)


# Known issues

The Windows 11's license screen on setup may appear in another language

Windows shows an error saying that you don't have the requirements to install Windows 11. This happens because its setup program is based on leaked Windows 11 21996.1, which has many bugs, and this happens even if you have all the requirements of Windows 11, TPM, Secure Boot and others. We already have an ISO based on the Windows 10 setup, but it's still being tested and takes a long time to upload to Google Drive.

Fix: On next update

# Important information

If you don't have virtualization, please disable Virtual Machine Plataform and Windows Subsystem for Linux. 

Download: https://drive.google.com/file/d/1jqlRBWlvm8CqHmZczq8vsOEnp3dyoP24/view?usp=sharing

# Images

![Pos-1](https://user-images.githubusercontent.com/78425126/133007541-928567ce-7bd4-433f-ad41-15025eaad197.PNG)

![Pos-2](https://user-images.githubusercontent.com/78425126/133007555-9d951a22-5c55-4aec-9251-7e33468bce5b.PNG)

![Pos-3](https://user-images.githubusercontent.com/78425126/133007567-0b9ef443-58e1-48a4-bde9-7609417acf83.PNG)

![Pos-4](https://user-images.githubusercontent.com/78425126/133007576-e82e02a4-c5e9-4e47-a36b-b8d8c4a7b2eb.PNG)

![Pos-5](https://user-images.githubusercontent.com/78425126/133007586-af417c5f-db2a-45c6-bf0c-cbed83376284.PNG)

![Pos-6](https://user-images.githubusercontent.com/78425126/133007592-9ba71ce8-9387-4468-ae8f-65e8429d9a0f.PNG)

![Pos-nomsa](https://user-images.githubusercontent.com/78425126/133007609-1e7e2791-6220-4a22-8af3-76756e77dc8e.PNG)

You can't login with Microsoft Account, as you can see in the image.

Why I didn't put the ISO file directly on the GitHub releases page?

Because the ISO has sizes of 4 gb, and the GitHub version only accepts files smaller than 2 gb, so it is impossible to upload.
