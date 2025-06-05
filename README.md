# Curso TMW Git & GitHub

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub

Além disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.

## Fluxo de trabalho Git local

01. git checkout -b <nova -branch>
02. cria ou atualiza arquivos
03. git status
04. git add *arquivos*
06. git status
07. git commit -m "minha mensagem"
08. git checkout main
09. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da empresa)
01. git clone <endereco do projeto>
02. git checkout -b <nova_branch>
03. alterações de arquivos
04. git status
05. git add *arquivos*
06. git status
07. git commit -m "nova mensagem"
08. git push origin <nova_branch>
09. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>