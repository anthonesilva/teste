# Github
#
# Repositório git-course
#
#Arquivo da aula de iniciantes para Git e Github
#
#----------------CONFIGURAÇÕES INICIAIS--------------------
#
#git config --global user.name "Nome de Usuário"
#git config --global user.email "Email do usuário"
#
#----------------OPERANDO----------------------------------
#
#git init - inicia repositório na pasta atual
#
#untracked - não está visível para o git
#unmodified - arquivo comitado sem alterações
#modified - arquivo que foi alterado que ainda não foi adicionado para commit
#staged - arquivo adicionado para commit
#
#git add "nome do arquivo" - adicionar arquivo para commit
#
#git commit -m "Comentário ao subir arquivo" - envia arquivo para o repositório
#git commit -am "Edit tal arquivo" - opção a em um arquivo que já existiu
#
#
#git status - verifica o status do repositório
#
#git log
#git log --graph
#git shortlog
#git shortlog -sn
#git log --author="Autor"
#git show "número da transação"
#
#git diff - vê o que alterou antes de comitar
#
#git diff --name-only - para ver só o nome do arquivo que foi alterado
#
#git checkout "Nome do arquivo" - retorna um arquivo para antes da alterando, enquanto ainda aparece no git diff, ou seja, status modified
#
#git reset HEAD "Nome do arquivo" - retira o arquivo da fila do staged
#
#git reset --soft(volta para o stage) --mixed (volta para o modified) --hard (volta ao estado zedo, desconsidera totalmente as alterações) "Número da transação"
#escolhe sempre o commit anterior ao que se quer excluir, ou seja, para qual estado se deseja voltar
#
