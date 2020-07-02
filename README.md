primeiros passos no Git, primeira alteração do commit
brench, README.md - aula com informações sobre como modificar e atualizar informações 
comandos:
git add -A adiciona ao git os arquivo 
git status: mostra o status dos arquivos
git log: usado logo apos o commit para ver o log de quem modificou cada
git commit -m - faz o commit
git branch - mostra todos os projetos master abertos
git commit am: modifica e adicona o commit " mensaggem"
usar o git reset --soft - volta para um estado anterior ao commit, 
usar o git reset --mixed - precisa commitar novamente dar o add
usar o git reset --hard - remove tudo e volta ao estado anterior sem necessidade de modificar arquivos
usar o git reset -hard nimero do log do commt enterior

TRABALHANDO COM DIFERENTES BRANCH
git branch - mostrao todos os gits em que eu estou
git branch novo branch - este é o comando para criar novo branch
git checkout " nome do branch". ex git checkout teste - vai para o branch teste
COMO SABER AS DIFERENÇAS DOS ARQUIVOS AINDA NÃO ADD AO COMMIT NO COMPUTADOR
POIS O STATUS INDICA APENAS OS ARQUIVOS MODIFICADOS, SEM RELATAR QUAIS AS ALTERAÇÕES FEITAS NOS MESMOS
USA-SE O GIT DIFF - lista as modificaçoe nos arquivos a serem comitados
git diff --name-only - mostra qual o arquivo modificado
git dif"nome do arquivo que foi alterado, mostra as alterações naquele arquivo especifico
por exemplo git diff README.md - mostra as alterações no README
git chackout HEAD --README.md - retorna ao estado anterior das alterações neste arquivo e depois pode se fazer add e commit paar os outros arquivos

 teste esta mensaggem devera 
 
