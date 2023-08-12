Iniciar novo packet com GIT na máquina 
### git init

Definir as configurações do usuário
### git config --local user.name Cesar
### git config --local user.email cesar@celke.com.br

Baixar os arquivos do Git
### git clone --branch <branch_name> <repository_url>
### git clone --branch 1.0 https://github.com/celkecursos/celke_como_usar.git

Adicionar o arquivo criado, adicionar arquivo ao índice de preparação (staging area). 
O índice de preparação é uma área intermediária entre o diretório de trabalho (working directory) e o repositório Git
### git add <file>
### git add README.md