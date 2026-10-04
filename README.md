# Mon Projet
## Partie 1: Initialisation et premier commit 
1. git init
2. git status
4. git add ./README.md
5. je remarque que j ai un fichier tracker par git et son etat est "modified"
6. git commit -m "added README.md file"
7. git log --oneline
8. deja fait
## Partie 2: Branches, historique & conflits
9. git checkout -b feature-login
10. git diff
11. git commit -m "modifier le ficher README.md"
12. git checkout master, j ai trouver le contenu initiale qui etait avant le changement au branche feature-login
13. git merge feature-login
15. lorsque deux branche modifient la meme ligne d'un meme fichier , apres cette modification on peut pas merger ces deux branch , on a appel cela " un conflit de merge " ou git ne sait pas quel changement a garder pour cette ligne modifie par les deux branch , et par la suite pour resoudre cela , on doit faire une reuinion ou juste une discussiona avec le propriétaire du branch pour decider quel modification on doit garder la mienne ou la tienne  
## Partie 3 : Dépôt distant : push & pull
17. git remote add origin https://github.com/0UDINE/mon-projet-git.git
18. git push -u origin main
20. modification local
## Partie 4 : Collaboration : Pull Request