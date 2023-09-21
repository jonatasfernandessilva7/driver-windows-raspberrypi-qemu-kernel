# driver-windows-raspberrypi-qemu-kernel

## Resumo 

Este é um projeto da disciplina de sitemas embarcados ministrada pelo professor <a href="https://github.com/jstoquica">Juan Sebastian Toquicas</a>. Este projeto simula o sistema raspberrypi por meio do qemu kernel. Para ver o projeto em execução siga os passos a seguir.:

## Passo a passo

- Clone o projeto.:

```bash
git clone https://github.com/jonatasfernandessilva7/driver-windows-raspberrypi-qemu-kernel.git
```

- Baixe a imagem do raspberrypi disponível no link abaixo.:

```bash
https://downloads.raspberrypi.org/raspios_armhf/images/raspios_armhf-2023-05-03/
```

- Baixe o qemu-kernel disponível no link abaixo.:

```bash
https://qemu.weilnetz.de/w64/
```

<strong>Atenção para não baixar a versão errada do qemu. Baixe o arquivo com o seguinte nome: <em>qemu-w64-setup-20230822.exe</em></strong>

Após ter feito tudo isso, <strong>NÃO INSTALE O EXECUTÁVEL DO QEMU</strong>. Ao invés de executálo você deve extraí-lo. Depois de extrair o executável, coloque o arquivo *start.bat* e o arquivo *2023-05-03-raspios-bullseye-armhf.img* dentro da pasta gerada na extração do .exe do qemu. Feito isso também extraia a imagem do raspberry que você baixou e também a coloque dentro da pasta que foi gerada na extração do executável do qemu.


## Executando o projeto

Para executar o projeto, abra dentro da pasta gerada ao extrair o executável, uma guia do CMD/PowerShell e, execute.:

```bash
./start.bat 
```
