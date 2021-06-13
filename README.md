# Atividade
![a](https://github.com/ecdc44/atividade/blob/main/Screenshot_1.png)
##
### Passo-a-passo

1. Abrir o visual studio code e o github.
2. Criei um novo projeto no github.
3. Fiz um ``git clone`` + a URL do saite.
4. Criei dois arquivos no vsc (visual studio code) o numero 1 e o numero 2.
5. Usei um ``ls`` para ver onde estava a minha pasta, depois usei o ``cd`` + o local do arquivo na bash e coloquei onde se encontrava eles.
6. Utilizei o ``git add .`` para adicionar todos os arquivos.
7. coloquei um commit nos arquivos 1 e 2 ``git commit -m`` a qual chamei de **"um"**.
8. Depos de todo coloquei ``git status`` para verificar se estava tudo certo.
9. Vendo que não tem erro usei ``git push`` para adicionar no site github.
10. Usei o ``git log --oneline`` para ver a estrutura do projeto.
11. Adicionei mais um arquivo a qual coloquei como 3.
12. A qual fiz o mesmo processo só que commit **dois**.
13. Criei uma tag a qual coloqui (1.0 "verão de início") ``git tag -a 1.0 -m``.
14. Depois coloqui a tag associada na branch **main** ``git push origin main --tags``.
15. Criei uma nova ramificação a qual coloquei o nome de **dvp** usando ``git checkout -b dvp``.
16. Depois de ver que tudo tava certo usei o ``git rm arquivo2.js`` para tira o arquivo 2.
17. Criei um arquivo 4 a qual fiz o mesmo processo de cima e commitei como **três**.
18. Coloqeui uma linha a mais no meu arquivo1.js e commitei como **quatro**.
19. Criei uma novo ramificação a qual nomeei como **temp** utilizando os mesmo comando de outro.
20. Criei uma novo arquivo 5 e coloquei uma linha nos arquivos 3 e 4 as quais commitei como **cinco**.
21. Dei puch no branch temp.
22. Depois de tudo, voltei para a ramificação "dev" ``git checkout dev``.
23. Mesclei as ramificação temp com as da dev ``git merge temp``.
24. Depois de aplicar tudo eu tirei o arquivo 4 e adicionei mais uma linha no arquivo um a qual commitei como **seis**.
25. Mesclei as ramificação temp com as da main ``git merge dev``.
26. Depois de aplicar tudo criei mais uma tag a qual foi nomeada como 1.1 "versão de entrega".
27. Adicionei a tag na branch main.

## Branch utilizado
+ main <br> 
+ dev <br>
+ temp <br>

Coloquei nas três branch o passo-a-passo.
