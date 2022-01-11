### Estudando GIT

Aprendendo versionamento de código com a tecnologia GIT.

Para fazer o download do GIT [clique aqui](https://git-scm.com/downloads).

Para realizar todos os comandos abra o terminal.

Comandos de configuração.

Determina o usuário local:  
`git config --global user.name "NOME USUARIO"`  

Determina o email local:  
`git config --global user.email "NOME EMAIL"`

Determina o seu editor de código, como exemplo utilizarei o VSCODE:  
`git config --global core.editor code`

Lista toda a configuração:  
`git config --list`

Para a manipulação dos arquivos.

Para inicializar o repositório local:  
`git init`

Verificar status do repositório:  
`git status` 

Mostrar o que está sendo adicionado, modificado ou removido (antes de realizar o commit):  
`git diff`

Adiciona as alteraçãos:  
`git add -A` ou `git add .` 

Confirma as alterações:  
`git commit -m "mensagem"`

Caso deseje fazer ambos juntos, utilize o comando:  
`git commit -am "mensagem"`

Visualizar todos os commits:  
`git log`

Para reverter um commit:  
`git revert commit`

Para reverter um commit sem apagar:  
`git revert --no-edit hash_do_commit`


Verificar os branchs existentes:  
`git branch`

Criar um novo branch:  
Obs.: como exemplo, o nome do branch irá ser "teste".  
`git branch teste`

Acessar outro branch:  
`git checkout teste`

Para remover um branch localmente:  
`git branch -D teste`   

Para adicionar um repositório remoto:  
`git remote add origin link_do_repositorio`

Exibir os repositórios remotos:  
`git remote -v`

Para enviar arquivos para o repositório remoto:  
`git push -u origin nome_do_branch`