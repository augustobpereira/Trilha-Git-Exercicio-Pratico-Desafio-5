## Comandos GIT Utilizados neste desafio prático:

```bash
git clone https://github.com/augustobpereira/Trilha-Git-Exercicio-Pratico-Desafio-5.git

cd "Trilha-Git-Exercicio-Pratico-Desafio-5"

git init

git fetch --all

git branch -a

git checkout main

git pull origin main

git checkout develop

git pull origin develop

git checkout -b fix/merge-conflito-develop-main

git merge main

git checkout main -- comandos-git.md

git checkout main -- assets/7c64059f71fc543737d315a88aa79963-102520219.jpg

git status

git add .

git commit -m "fix: Ajuste no conflito entre develop e main"

git push origin fix/merge-conflito-develop-main

git checkout -b docs/inclusao-readme

echo "# Desafio Prático

Este projeto é parte do desafio final da Trilha de Git Básico. Aqui foram aplicados conceitos como:
- Criação de branches
- Commits semânticos
- Resolução de conflitos
- Pull Requests
- Uso de terminal
" > README.md

git add README.md

git status

git commit -m "docs: adiciona documentação inicial no README"

git push origin docs/inclusao-readme

git checkout -b docs/renomea-arquivo-desafio-git-md

mv Desafio-GIT.md desafio_git.md

git add desafio_git.md

git commit -m "docs: renomeia arquivo de desafio para desafio_git.md"

git push origin docs/renomea-arquivo-desafio-git-md

git checkout -b docs/atualiza-arquivo-comandos-git-md

git add comandos-git.md

git commit -m "docs: Atualiza comandos-git.md com comandos git utilizados no desafio"
```