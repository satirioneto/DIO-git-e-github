# DIO | Resumos Git e GitHub

Repositório parae armazenar resumos sobre Git e GitHub do curso "Versionamento de Código com Git e GitHub" da [Digital Innovation One](https://www.dio.me)

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação Github](https://docs.hitgub.com/)

## 📒 Resumos das Aulas
| Aulas | Resumos |
|-------|---------|
|Tema   |Conteúdo |

## ⌨️ Comandos
#### Git e GitHub
```
git config
git init
git clone
git remote add < remoto(origin) > < URL do repositório remoto >
--- adiciona um novo repositório local a partir de um repositório remoto
git status
git push -u --set-upstream < remoto(origin) > < local(main) >
--- envia para o repositório remoto(origin) as atualizações feitas localmente(main).
git pull
--- trás para o repositório local(main) as atualizações feitas no remoto(origin).
git commit -m --message < "texto do commit" > | --amend --message <"renomear commit">
git log
git add
git reset --soft | --mixed | --hard
git reflog
git restore --staged < arquivo >
git branch -v --verbose | --list | --delete
--- manipulações referentes as branches
git merge < branch para mesclar >
--- mescla as a branch escolhida na atual
git remote show origin
```
#### Terminal
```
cat = "concatenate"
cd = "change directory"
pwd = "present working directory"
dir = "directory"
mkdir = "make directory"
touch = criar um arquivo vazio
rm -rf <file>
echo <cria mensagem>
```
## 📑 Referências 
[Edicição de arquivos markdown](https://readme.so)