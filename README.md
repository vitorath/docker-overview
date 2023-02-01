# Docker

## Comando - **docker run hello-world**

O comando **docker run hello-world** tem como propósito executar uma imagem básica do docker que exibe uma mensagem na tela e finaliza a execução. Este comando também pode ser executado adicionando a versão da imagem **docker run hello-world:latest**, no caso **latest** que é a ultima versão disponível da imagem. 

Antes de iniciar a execução da imagem o docker verifica se a imagem existe em sua máquina local e caso não encontre ele tentará buscar esta imagem em um repositório online, no caso **docker hub**.

-t tty 

## Comando - **docker run -it --rm ubuntu bash**

O comando **docker run -it --rm ubuntu bash** tem como propósito executar a imagem do **ubuntu** e executar internamente o processo **bash**. Contudo, caso for executado sem os parametos **-i** e **-t** (**-it**) o docker irá criar um processo do **bash** e assim que terminar de executar o processo irá destruir o container. Isto é, o parametro **-i** permitir habilitar a iteração com o terminal e o parametro **-t** habilita o **tty**, ou seja, digitar no terminal. Já o comando **--rm** tem como objetivo remover o container após o processo executado internamente ser finalizado. 

Lembrando que os parametros **-it** e  **--rm** são opcionais.

## Comando - **docker start ubuntu**

O comando **docker start ubuntu** executa o ubuntu e consequentemente irá finaliza-lo, pois não existem processos a serem executados internamente nesta imagem.
