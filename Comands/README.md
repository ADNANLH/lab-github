# les commande utilisé pour la solution
1. Vérifier les branche et la branche actuel
```bash
    git branch
    git checkout master
```
2. Création des Branches pour le chef 1 et le chef 2:
```bash
git checkout -b chef-1 main #le chef 1 va travaille sur cette branche
git checkout main # pour retourner a le main branch
git checkout -b chef-2 main #le chef 2 va travaille sur cette branche
```

3. tansferer vers la branche master at merger des autre branches
```bash
git checkout main # pour la transfermation vers la branche main 
git merge chef-1 # merger les modification de chef-1
git merge chef-2 # merger les modification de chef -2
```

4. Ouvrir les conflit avec le button **Resolve the conflicts** sur l'éditeur de code
