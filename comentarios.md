
## MERGE e PULL REQUEST

fiz um novo repositorio para entender melhor o exercicio da merge e pull request.

criei um repositorio novo, e fiz 1 commit e fiz o push para atualizar la no github.

agora sei que meu local esta igual ao remoto do github.

crio branch de feature
git branch ft-login

passo para a branch ft-login
git checkout ft-login

vou atualizar a branch ft-login com o que tem no main, para eu não ficar desatualizado.
git merge main (ainda to na branch ft-login)
pronto agora o ft-login esta atualizado igual ao main do github.


salvo o que fiz no ft-login la para o repositorio remoto github
voiu salvar a branch de feature la para o github.
git push -u origin ft-login (ainda to na branch ft-login)

faça uma adição no código la no vscode mas que seja dentro da branch ft-login
e agora vamos fazer um git add . e depois o git commit, e por fim um git push -u origin ft-login
para enviarmos as alteracoes que fizemos no codigo dentro da branch ft-login la para o remoto github.

agora vamos no repositorio remoto, e abrimos um pull request da feature enviada
nesse exemplo foi a feature ft-login
vai abrir uma tela de pull request, e da pra escrever uma msg pra equipe ler.
obs outras pessoas que estao no projeto podem comentar esse pull request que fiz.

entao agora vai passar pelo processo de homologacao, e vai aprovar o pull request.
e alguem que tenha a permissao pra aprovar o pull request vai entrar e aprovar, clicando no botao 'merge pull request', entao aqui vai ser autorizado a fazer o merge para o main.

pronto, aqui o github ja fez a integracao e jogou o meu historico do branch ft-login para o branch main.
se eu for no main, vou ver que tem 3 commits agora, porque acrescentou o commit que veio do ft-login que fizemos o merge agora, fica escrito merge pull request.

obs opcionalmente posso deletar o branch feature ft-login no repositorio remoto.
posso ir no botao 'branches' e deletar a branch ft-login. justamente porque ja foi tudo passado da branch ft-login para a branch main.
obs mas é bom deixar a branch ft-login, para que possa ver o historico do que foi feito na branch ft-login.