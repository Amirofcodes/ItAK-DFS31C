# ItAK-DFS31C

Dépôt support aux rendus d'exercice pour la session DFS31C de l'IT-Akademy.

Dans ce dépôt, vous trouverez les ressources utiles évoquées en cours ainsi que les consignes des différents exercices, et éventuellement leur correction.

Chaque devoir à rendre devra se faire sur ce dépôt en utilisant une pull-request depuis un fork sur votre espace personnel.
La pull request devra suivre le format "Nom Prenom - Titre exercice".

## Sommaire des exercices

  - [D70 - Git / Github / Systèmes de versionning](D70_Git/README.md)
  - [D42 - Consolidation des connaissances en informatique](D42_Consolidation_info/README.md)
  - [D46 - Php / Design Patterns](D46_Php_Design_Patterns/README.md)
  - [D11 - Php / Symfony](D11_Php_Symfony/README.md)

## Commandes utiles

### Mettre à jour son fork à partir du dépôt principal

Publiez ou "stashez" votre projet; puis :
```sh
# seulement la première fois
git remote add upstream https://github.com/Nyxis/ItAK-DFS31C

git fetch -a -p
git checkout main
git pull --rebase upstream main
git push origin main --force
```
