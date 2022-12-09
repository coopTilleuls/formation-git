# Formation Git

## Exercice 1
- Clonez le projet https://github.com/coopTilleuls/formation-git
- Créez un fichier en y mettant le contenu de votre choix
- Commitez ce fichier

## Exercice 2 : 
- Créez une branche dédiée à votre fonctionnalité "feat/homepage-content"
- Dans le fichier `index.html`: 
  - ajoutez une class `dark-mode` à la balise `body`
  - ajoutez une class `full` à la balise `header`
  - ajoutez une balise `aside` avec du contenu sous la balise `header`
  - ajoutez une balise `section` avec du contenu
- Créez un commit qui contiendra toutes les modifications du fichier **sauf la balise section**
- Faîtes une faute de frappe dans le message de votre commit
- Enregistrez ce commit

## Exercice 3 : 
- Editez le message du dernier commit pour corriger les fautes d'orthographe de votre message

## Exercice 4 : 

- Dans la balise "header", remplacez la class "full" par une class "medium".
- Commitez ce changement sans la balise "section".
- Ce changement ne devrait pas apparaître dans cette branche. Supprimez-le commit.
- Créer une branche dédiée au fix "fix/header-size" (c'est une correction de main, donc attention à la source de la branche utilisée) et appliquez-lui le commit que vous venez de supprimer.
- Allez sur main et mergez la branche "fix/header-size".

## Exercice 5 : 
- Retournez sur la branche "feat/homepage-content"
- Créez un commit qui contiendra l'ajout de `section` dans `index.html`
- Dans le fichier `index.html` , ajoutez une class `right` à la balise aside
- Commitez ce changement. Attention ce changement concerne une partie déjà traitée dans cette branche, les changements concernant cette partie devrait donc être dans un seul commit.

## Exercice 6 :
Finalement, la demande concernant le header a changé : 
- Ajoutez une class `contained` à la balise `header`
- Commitez ce changement dans votre branche de fonctionnalité

## Exercice 7 : 
Il est maintenant temps de préparer votre pull request pour la merger sur main
- Vérifiez l'état de votre branche par rapport à main
- Mettez-là à jour si vous pensez que c'est nécessaire
- Faites une dernière relecture
- Mergez votre branche dans main

## Exercice 8 : 
Passez le body en "dark-mode" était une erreur
- Retrouver le commit qui a causé ça et avisez sur la meilleure façon de régler ce problème
