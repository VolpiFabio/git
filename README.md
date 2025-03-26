# Curso TMW Git & Github 2025

Curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com Github.

Alem disso, vamos trabalhar com GitFlow ao final do curso e VS Code.

Confira tudo o que temos no nosso YouTube. É gratis! Segue o link:

[Curso Git 2025](https://youtube.com/teomewhy)

Alem do nosso yt, se ligue no nosso site e agenda para ficar por dentro de tudo que vai rolar em 2025


## Fluxo de trabalho Git local

1. git checkout -b <nova-branch>
2. cria ou atualiza arquivos
3. git status
4. git add 'arquivos'
5. git status
6. git commit -m 'minha mensagem'
7. git checkout main
8. git merge nova-branch

## Fluxo de trabalho Github <> local (projeto proprio ou da sua empresa)

1. git clone <endereço projeto>
2. git checkout -b  <nova-branch>
3. alterações de arquivos
4. git status
5. git add 'arquivos'
6. git status
7. git commit -m 'nova mensagem'
8. git push origin <nova-branch>
9. abrir pull request no Github para main
10. excluir <nova-branch> origin
11. git checkout main
12. git branch -D <nova-branch>

## Fluxo de trabalho Github <> local (projetos open-source)

1. fork do projeto para seu proprio Github
2. gitclone <endereço do projeto fork>
3. git checkout -b <nova-branch>
4. alterações
5. git status
6. git add 'arquivos'
7. gis status
8. git commit -m 'nova mensagem'
9. git push origin <nova-branch>
10. abrir pull request no github da branch fork para a main do projeto original
11. excluir <nova-branch> origin
12. git checkout main
13. git branch -D <nova-branch>


