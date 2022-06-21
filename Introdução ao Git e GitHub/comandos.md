# Lista de Comandos utilizados no Git



## Criar uma chave SSH

Criar link entre o GitHub e a máquina de trabalho.

### **ssh-keygen -t ed25519 -C** _digitarEmail_

### cat id_ed25519.pub

### eval $(ssh-agent -s)

### ssh-add id_25519





## Commit

Comandos utilizados para realizar commits.

### git init

Marca o início do repositório na máquina.



### git config --global user.email "_digitarEmail_"

### git config --global user.name "_digitarNickname_"



### git add *

Prepara todos os arquivos criados/modificados para o commit.

### git commit -m "_digitarComentário_"

Realiza o commit na máqiuina.

### mv _nomeArquivo_ ./_nomePasta_/

Move um arquivo para uma pasta.

### git status

Mostra o status dos arquivo modificados.

### git remote add origin _digitarLinkRepositorioGithub_

Faz a ponte entre o repositório da máquina com o repositório remoto (GitHub).

### git push origin master/mais

Enviar as alterações para o GitHub.

### git pulll origin master/main

Puxar o repositório do GitHub para a máquina.

### git clone _linkRepositorio_

Copia o repositório do GitHub para a máquina.









 
