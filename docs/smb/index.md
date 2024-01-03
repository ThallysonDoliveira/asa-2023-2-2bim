# SMB

## Instalação

$apk update

$apk add samba-dc krb5

## Configuração

foi criado um arquivo de configuração no diretorio /etc/samba/ usando o comando:

$nano /etc/samba/smb.conf

então colocar essas configurações dentro do arquivo

[![docprova1](https://i.im.ge/2024/01/03/3MiXcm.docprova1.png)](https://im.ge/i/3MiXcm)

[![docsprova2](https://i.im.ge/2024/01/03/3MjTP0.docsprova2.png)](https://im.ge/i/3MjTP0)

na vm do windosn em (Usuários e Computadores do Active Directory)

dentro do dominio pernambuco.lab foi criado duas OU norte e sul clicando com o botão direito do mouse em pernambuco.lab

[![docsprova3](https://i.im.ge/2024/01/03/3MCEYC.docsprova3.png)](https://im.ge/i/3MCEYC)

dentro da OU norte foi criado dois grupos (Oliveira e Silvestre) e 4 usuários para cada grupo, para criar os grupos é só cliar com o botão direito do mouse em norte e criar o grupo e os usuários

[![docsprova4](https://i.im.ge/2024/01/03/3MEpe4.docsprova4.png)](https://im.ge/i/3MEpe4)


[![docsprova5](https://i.im.ge/2024/01/03/3MxOJL.docsprova5.png)](https://im.ge/i/3MxOJL)

então joga os usários para seus respectivos grupos

[![docsprova6](https://i.im.ge/2024/01/03/3Mx5PX.docsprova6.png)](https://im.ge/i/3Mx5PX)

[![docsprova7](https://i.im.ge/2024/01/03/3Mxmuh.docsprova7.png)](https://im.ge/i/3Mxmuh)


#Incluir o(s) nome(s) e o conteúdo do(s) arquivo(s) de #configuração.

#1. Criar 2 grupos para dois de seus sobrenomes;

#2. Criar 4 usuários, dois para cada um dos sobrenomes;

#3. Compartilhar duas pastas com dois de seus #sobrenome, compartilhado para o grupo com o sobrenome correspondente.

## Teste

usuário Thai Oliveira entrando na pasta compartilhada oliveira

[![docsprova8](https://i.im.ge/2024/01/03/3MxgRr.docsprova8.png)](https://im.ge/i/3MxgRr)

usuário Thai Oliveira tentando entrar na pasta compartilhada silvestre

[![docsprova9](https://i.im.ge/2024/01/03/3M3lF8.docsprova9.png)](https://im.ge/i/3M3lF8)




