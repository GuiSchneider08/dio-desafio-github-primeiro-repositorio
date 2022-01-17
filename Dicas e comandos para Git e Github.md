# Git e Github(dicas basicas)

Comandas para resetar User email e Nickname no Git Bash

- git config --global --unset user.email
- git config --global --unset user.nickname

Comando para adicionar um email ao Git 

- git config --global user.email ‘[guilhermelactodama@gmail.com](mailto:guilhermelactodama@gmail.com)’
- git config --global user.nickname ‘GuiSchneider08’

Comando para listar as configurações no Git 

- git config --list

Comando para criar pastas no Git 

- Mkdir

Comando para deletar pastas no Git

- del/rmdir

Comando para abrir uma pasta 

- cd e o enderesamento da pagina
- para voltar um nivel(uma pasta) digitar: cd ..

Comando para listar todo o conteudo da pasta

- LS

Para iniciar o repositorio do Git na pasta - Git init

Para mover arquivos - Git add *

Para criar um Commit usamos Git commit

FLAGS 

- ‘’ls -a’’ serve para listar tudo, inclusive com arquivos ocultos

Para enviar do Git para o Github

- git remote add origin “”
- git status Para saber se deu certo
- git push origin master : para empurrar para o Github
- git pull origin master : para puxar do Github quando tem alguma modificação

Como baixar o repositorio

- git clone “” (o site a ser clonado do github)

Localizar as origens dos repositorios 

- git remote -v // fazer esse comando dentro da pasta
