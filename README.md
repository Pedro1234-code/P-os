# P os 40.14

P os 40.14 | Estamos trabalhando na última versão Release do P os. O que isso significa? Significa que estaremos introduzindo o P-os-As-a-Service, logo após o lançamento do P os 40.14. Esta versão será chamada de apenas P os, e será atualizada com novos recursos e novos nomes, assim como imagens de 4 em 4 meses. As atualizações ocorreram no app já incluido com o P os 40.13 e 40.14, o P os Update.

Novidades no nosso próximo release (P os 40.14):

Wallpaper atualizado para combinar com o tema dark padrão; Desabilitado todos os serviços de telemetria; Restaurado Visualizador de Fotos do Windows; Botões pequenos na barra de tarefas; Menu de contexto clássico e responsivo; Removido navegador Firefox para deixar apenas o mais otimizado (Edge); Logo do P os no winver.exe

O P os 40.14 está em processo de testes. Decidimos reconstruir nosso trabalho já feito e refazer com base no P os 40.13. Isso se dá pois os testes com a implementação do shell do Windows 10 na base do Windows 11 falhou, nos deixando sem opção a não ser rebootar o trabalho. Agora nós já concluimos e estamos confiantes de que irá funcionar.

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

Se você não tiver virtualização, por favor desabilite Virtual Machine Plattaform.

Download: https://drive.google.com/file/d/1IyJvRmFpVYqpvPrMucofESBfufPzlngW/view?usp=sharing (P os 40.13)
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

Shell do Windows 10 e base do Windows 11

Empacotar apps Win32 para MSIX e implantar no lugar de instaladores MSI
