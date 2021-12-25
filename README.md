### Estudando GIT

Aprendendo versionamento com a tecnologia GIT.

Para fazer o download do GIT [clique aqui](https://git-scm.com/downloads).

Depois da intalação, abra seu terminal para realizarmos as primeiras configurações.

O primeiro comando, determina o usuário local:

`git config --global user.name "NOME USUARIO"`  

O segundo comando, determina o email local:

`git config --global user.email "NOME EMAIL"`

O terceiro comando, determina o seu editor local, como exemplo utilizarei o VSCODE:

`git config --global core.editor code`

E para listar toda a configuração, basta utilizar o comando:

`git config --list`

A partir de agora, devemos utilizar os comandos para manipulação dos arquivos. `git status` server para verificar o status do repositório atual. Sempre após uma adição ou modificação de arquivo, deve utilizar o seguinte comando:

`git add -A`

Em seguida deve realizar o commit dos arquivos, com o seguinte comando:

`git commit -m "mensagem"`

Caso deseje fazer ambos juntos, utilize o comando:

`git commit -am "mensagem"`

E ao final de todo processo, você pode vizualizar todas as modificação atráves do arquivo de log, com o seguite comando:

`git log`