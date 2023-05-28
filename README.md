# dio-linux-project-2
Módulo Linux
Desafio 01: Infraestrutura como Código: Script de Criação de Estrutura de Usuários, Diretórios e Permissões

PASSO A PASSO:

Excluir diretórios, arquivos, grupos e usuários criados anteriormente no curso;✅
Todo provisionamento deve ser feito em um arquivo do tipo Bash Script;✅
O dono de todos os diretórios criados será o usuário root;✅
Todos os usuários terão permissão total dentro do diretório público;✅
Os usuários de cada grupo terão total permissão dentro de seu diretório respectivo;✅
Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem.✅
Comentários:

Além do passo a passo pedido no desafio, adicionei códigos para a expiração da senha padrão criada para cada usuário, para que alterem a senha em seu primeiro acesso.
Adicionei um simples comentário na criação do usuário identificando a qual setor pertence.
Informações
Alterações para execução do script.

Alterar as permissões do script iac.sh, dando permissão de execução.

Necessário ter privilégios de usuário root para realizar uma alteração.
# Adicionando permissão de execução
$ chmod +x iac.sh
