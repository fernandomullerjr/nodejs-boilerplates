
git status
eval $(ssh-agent -s)
ssh-add /home/fernando/.ssh/chave-debian10-github
git add .
git commit -m "NodeJS Boilerplates. Projeto em NodeJS simples via docker-compose."
git push
git status
