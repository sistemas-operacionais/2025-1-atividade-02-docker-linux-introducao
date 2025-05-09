# Relato da atividade:
dnf install fish
warp

**2.2.1:** realizei o comando "docker run -it --name fedora-tutorial fedora:latest /bin/bash" e o pull foi realizado como esperado e o status da operação informado foi "Dowloaded newer image for fedora:latest"
**2.2.2:** 
- o comando pwd teve como saida o resultado "/"
- utilizei o comando "cd ~" e fui para o diretório home do usuário
- o comando "ls" não informou nenhum arquivo ou pasta no diretório home do usuário
- após utilizar o comando "mkdir atividades" o ls passou a informar uma pasta nomeada como "atividades"
- utilizei "cd atividades" e o prompt de comando informou que eu acessei o diretório atividades
**2.2.3:**
- entrei do diretório home do usuário com o cd ~
- conferi o diretório atual com pwd
- criei o arquivo1.txt com o touch
- listei os arquivos do diretório atual com o ls, que me informou que existia o arquivo1.txt e o diretorio atividades no diretório home
- renomeei o arquivo1.txt para documento.txt usando mv
- entrei no diretorio atividades com cd atividades
- criei um subdiretorio utilizando mkdir backup
- transferi documento.txt que estava no diretório home do usuário para o sub diretório criado (backup)
- voltei ao diretório home do usuário com cd ~ e usei um pwd para ver se realmente estava nele
- usei um rm document.txt para deletar o arquivo e usei um ls para conferir se a ação deu certo
- usei o comando ls atividades/backup/ para ver os arquivos dentro do novo subdiretório e ele informou que existia o arquivo documento.txt
