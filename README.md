# git-clone-https-github.com-Prof-Icaro-uscs-open.git-cd-uscs-open
git checkout -b feature/me_indica develop
# Edite o arquivo README.md para adicionar as informações
# Após as edições, adicione e faça commits
git add README.md
git commit -m "Adicionado nome do projeto 'Me Indica' e nome do colaborador 'Guilherme Vilas Boas Sales'"
# Faça outros commits conforme necessário
git checkout develop
git merge --no-ff feature/me_indica
git tag -a v1.0 -m "Versão 1.0"
git push origin develop
git push --tags
