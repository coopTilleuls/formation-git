# Formation Git

## Exercice 1
- Clonez le projet https://github.com/coopTilleuls/formation-git ou créez un dépôt local.
- Créez un fichier en y mettant le contenu de votre choix.
- Commitez ce fichier.

## Exercice 2 : 
- Créez une branche dédiée à votre fonctionnalité `feat/something-new`
- Réaliser l'une des modifications suivantes :
  - Dans le fichier `index.html`:
    - ajoutez une class `dark-mode` à la balise `body`.
    - ajoutez une class `full` à la balise `header`.
    - ajoutez une balise `aside` avec du contenu sous la balise `header`.
    - ajoutez une balise `section` avec du contenu.
    - Créez un commit qui contiendra toutes les modifications du fichier **sauf la balise section**.
  - Dans un nouveau fichier :
    - inscrivez ces animaux de compagnie `lapin, ours, chat, chien`, un par ligne.
    - Créez un commit qui contiendra toutes les modifications du fichier **sauf le poney**.
- Faîtes une faute de frappe dans le message de votre commit.
- Enregistrez ce commit.

## Exercice 3 : 
- Éditez le message du dernier commit pour corriger les fautes d'orthographe de votre message.

## Exercice 4 :
- Ajoutez de nouvelle modification au sein des premières lignes du fichier.
- Commitez ce changement toujours **sans la balise `section`** ou **sans le chien**.
- Mince ! Vous vous rendez-compte que ce changement n'aurait pas dû apparaître dans cette branche. Supprimez le commit.
- Créez une branche dédiée au fix `fix/my-correction` (c'est une correction de main, donc attention à la source de la branche utilisée) et appliquez-lui le commit que vous venez de supprimer.
- Allez sur main et mergez la branche `fix/my-correction`.

## Exercice 5 : 
- Retournez sur la branche `feat/something-new`.
- Créez un commit qui contiendra enfin l'ajout de la section ou du chien.
- Dans le fichier effectuez un changement sur une ligne que vous avez déjà modifiée.
- Commitez ce changement. Attention, comme ce changement concerne une partie déjà traitée dans cette branche, les changements concernant cette partie devrait donc être dans un seul commit.

## Exercice 6 :
Finalement, après avoir vu vos modifications, la demande du client a changé : 
- Ajoutez une class `contained` à la balise `header`, ou précisez `lapin nain`.
- Commitez ce changement dans votre branche de fonctionnalité.

## Exercice 7 : 
Il est maintenant temps d'intégrer votre fonctionnalité sur main :
- Vérifiez l'état de votre branche par rapport à main.
- Mettez-là à jour si vous pensez que c'est nécessaire.
- Faites une dernière relecture.
- Mergez votre branche dans main.

## Exercice 8 : 
Passer le body en `dark-mode` / ajouter l'`ours` était une erreur, il faut l'enlever.
- Retrouvez le commit qui a causé ça et avisez sur la meilleure façon de régler ce problème.
