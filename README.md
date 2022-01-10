### Estudando GIT

Aprendendo versionamento de código com a tecnologia GIT.

Para fazer o download do GIT [clique aqui](https://git-scm.com/downloads).

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

Verificar status do repositório:  
`git status` 

Adiciona as alteraçãos:  
`git add -A` ou `git add .` 

Comfirma as alterações:  
`git commit -m "mensagem"`

Caso deseje fazer ambos juntos, utilize o comando:  
`git commit -am "mensagem"`

Visualizar todas modificações:  
`git log`

Verificar os branchs existentes:  
`git branch`

Criar um novo branch:  
Obs.: como exemplo, o nome do brach irá ser "teste".  
`git branch teste`

Acessar outro branch:  
`git checkout teste`