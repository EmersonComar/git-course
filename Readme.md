# GitHub

Esse é um curso introdutório de Git/GitHub.
Estou fazendo modificações apenas para testar o
funcionamendo do Git.

Modificando novamente


Estou gostado do curso, acho que consigo aprender !!

Comandos importantes:

confgurando o git
git config --global user.name "" : nome do autor dos commits
git config --global user.email "" : email do autor dos commits
git config --list : lista de todas as modiicações

trabalhando com o git
git show <hash_commit> : verificar mudanças feitas neste commit
git diff : verificar mudanças antes de commitar
git log : todos os commits
git log --author="" : buscar commits somente deste autor
git shortlog : log menos detalhados mostrando o autor e a sua quantidade de commits
git log --graph : mostrar as branches de forma gráfica
git checkout <nome_arquivo> : não aplicar uma modificação em estado Modified
git reset HEAD <arquivo> : retornar arquivo que estão em staged para Modified

git reset --soft : irá matar o atual commit e retornar o arquivo em stage, pronto
		   para ser novamente commitado
	  --mixed : Matar o commit atual, porém irá voltar o arquivo para modified, pronto para
	  	    add
	  --hard : Irá ignorar completamente o commit atual

comando: git reset --soft <hash na qual eu quero retornar>

git push -u origin main : git push serve para enviarmos o estado do repositório para o servidor
                          remoto; origin significa para onde vai e o main significa para de onde 
                          vem; o -u serve para 'traquear', ou seja, não ficar mais digitando
                          o restante do código toda vez
