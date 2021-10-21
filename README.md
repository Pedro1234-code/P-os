# P-os
Sistema Operacional baseado no Windows 11, mas melhor e sem o lixo da Microsoft.

Algumas coisas removidas: Muitos apps UWP, Login com Conta da Microsoft, Requisitos de TPM 2.0, Secure Boot e UEFI.

Recursos adicionados: WSL e Microsoft .NET 4.5 completo

# Performance Tests
O sistema foi testado numa virtual machine usando VMWare Workstation Player 16, com 1.6 gb of RAM, em um host com 4 gb of RAM, Intel(R) Core(TM) i3-10110U CPU @ 2.10GHz   2.59 GHz, Dual-Boot Windows 10 e Windows 11, e o sistema estava rodando melhor que muitas of máquinas reais, sem travamentos.

O sistema, com GitHub Web rodando no Microsoft Edge, estava gastando 5% da CPU, 59% da RAM e 1% do disco, passando o host Windows 10.

Pos Task Manager: 

![TaskmgrPos](https://user-images.githubusercontent.com/78425126/133113160-d595fbb0-c76b-47dc-8aef-cbfc322fdb0d.PNG)


# Known issues

O nome P os pode desaparecer e voltar a ser Windows em alguns lugares, como winver.exe no P os 40.13

Fix: On next update

# Important information

If you don't have virtualization, por favor desabilite Virtual Machine Plattaform.

Download: https://drive.google.com/file/d/1kk0W56caLigyzEEZUKt9upmYKPUQVUk5/view?usp=sharing
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


# What I am working for now:

Build an ISO with an ESD image, not WIM. | Launch P os 40.13.
