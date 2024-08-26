# Git Códigos

git init

git status

git add .

git commit -m "mensagem"

git push

git push -u origin main

git reset       //consegue remover do stage, no caso do add .

git clean -df  //remove as modificacoes que não foram pro stage
git checkout -- .  //quando removido as modificacoes garante que esteja no ultimo commit realizado

git log --oneline //verifica os commits que o projeto tem

**ERRO DE EDITOR VIM //aquele editor azul quando tu esquece a mensagem do commit**
- Digite "i" para escrever a mensagem do commit esquecido, após escrever a mensagem aperte "ESC" e digite ":wq" e aperte "ENTER" para salvar

**DELETANDO O ULTIMO COMMIT SEM REMOVER AS MODIFICACOES REALIZADAS**
- git reset --soft HEAD~1 //ele vai voltar para o último penultimo commit sem remover as alterações que você realizou no projeto

**DELETANDO O ULTIMO E DELETANDO AS MODIFICACOES REALIZADAS**
- git reset --hard HEAD~1 //deleta tudo até o penultimo commit

**ATUALIZAR O REPOSITÓRIO LOCAL EM RELAÇÃO AO GITHUB**
- git pull origin main //traz do remoto até o local

**ERRO DE PUSH QUANDO O LOCAL ESTA DESATUALIZADO DO GITHUB E VOCE TEM COMMITS PARA DAR PUSH**
- git pull origin main //vai abrir o editor VIM para realizar um merge (união) dos commit que você realizou com os commit que você não tem do local
- aperte "ESC" e digite ":wq" e aperte "ENTER" //com isso vai puxar os arquivos do local pro remoto e ainda vai ter os commits que você realizou pronto para dar o push

**SOBREESCREVENDO O HISTORICO DO GITHUB PELO LOCAL**
- git push -f


