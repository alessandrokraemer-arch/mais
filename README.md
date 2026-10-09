**Title:** Here a Virtual Machine can do ...

**Date:** 10/2026 

**Status:** Accepted 

**Owner:** Dr. Kraemer, Alessandro [sp.kraemer.alessandro@gmail.com](mailto:sp.kraemer.alessandro@gmail.com) 
O CV está disponível e com Direito Autoral ali no CNPq e autorizo para estudar. O repositório no CNPq é por via [https://lattes.cnpq.br](https://lattes.cnpq.br/) e ali marque DOUTOR. 

**Context:** Uma solução... 

**Decision:** Opta-se pelo VMware mas você deva converter...

Para obter o três arquivos aptos ao VMware baixe por via (o 1º é o disco...:

https://drive.google.com/file/d/1vaDOyb37X16Fu59NKGwfDKc4Jy7px-po/view?usp=drive_link
https://drive.google.com/file/d/1MgOXdTYaeY5xTTMsSbwd_oLct8H9_Str/view?usp=drive_link
https://drive.google.com/file/d/1hiGkfZowyT7ZO9UoMsgtKlapKRzXajdm/view?usp=drive_link

Aqueles trÊs arquivos ali são suficientes para execução da VM proposta. 

Converta se cabe indo pelo Windows

* A priori --> winget --install qemu-img
* Conversão para VDI ao Virtual Box --> qemu-img convert -O vdi Ubuntu_64-bit-disk1.vmdk Ubuntu-26.vdi
* Adiciono que em caso de erro ao Iniciar, opte por alterar o arquivo VMX, ali consta configuração e ajuste

Usuário de acesso o trivial: saas
Senha a mesma

Essa VM pode ser transferida para a AWS ...

**Consequences:** Em geral aluno é quem observa aqui...
