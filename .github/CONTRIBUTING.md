# Contributing to joomla france/joomla
(Fichiers de langue allemande pour Joomla! 5.1 et ultérieur)

:+1::tada: Tout d'abord, merci d'avoir pris le temps de contribuer! :tada::+1:

Consultez notre [Code de conduite](../CODE_OF_CONDUCT.md). Veuillez lire attentivement.

Commencez avec [git and github](https://guides.github.com/activities/hello-world/). Si vous n'avez pas git sur votre machine, [installez-le]( https://help.github.com/articles/set-up-git/).
#### *Si vous n'êtes pas à l'aise avec la ligne de commande, [voici des tutoriels utilisant des outils GUI.]( #tutorials-using-other-tools )*

## Travailler avec ce dépôt

### Forkez ce dépôt

Forkez ce dépôt en cliquant sur le bouton fork en haut de cette page.
Cela créera une copie de ce dépôt dans votre compte.

### Clonez le dépôt

Maintenant, clonez le dépôt forkez sur votre machine. Allez sur votre compte GitHub, ouvrez le dépôt forkez, cliquez sur le bouton clone puis cliquez sur l'icône *copier dans le presse-papiers*.

Ouvrez un terminal et exécutez la commande git suivante :

```
git clone "url que vous venez de copier"
```
où "url que vous venez de copier" (sans les guillemets) est l'URL de ce dépôt (votre fork de ce projet). Consultez les étapes précédentes pour obtenir l'URL.

Par exemple :
```
git clone https://github.com/this-is-you/joomla.git
```
où `this-is-you` est votre nom d'utilisateur GitHub. Ici, vous copiez le contenu du dépôt joomla sur GitHub sur votre ordinateur.

### Créez ou prenez un problème

Allez sur [Issues](https://github.com/AFUJ/langues-fr/issues) et créez un nouveau problème ou prenez un problème ouvert pour écrire une PR.
Normalement, pas de PR sans un problème préalable. Nous avons le *principe du problème d'abord*.

### Créez une branche

Allez dans le répertoire du dépôt sur votre ordinateur (si vous n'y êtes pas déjà) :

```
cd joomla
```
Maintenant, créez une branche en utilisant la commande `git checkout` :
```
git checkout -b <ajoutez-le-nom-de-votre-nouvelle-branche>
```

Par exemple :
```
git checkout -b <numéro-du-problème>
```
(Le nom de la branche n'a pas besoin d'avoir un numéro de problème comme nom de branche, mais c'est une chose facile à référencer ici.)

### Effectuez les modifications nécessaires et commitez ces changements

Maintenant, ouvrez tous les fichiers dans un éditeur de texte ou dans un IDE comme PhpStorm et modifiez-les. Enregistrez ensuite le fichier.

Si vous allez dans le répertoire du projet et exécutez la commande `git status`, vous verrez qu'il y a des modifications.


Ajoutez ces modifications à la branche que vous venez de créer en utilisant la commande `git add` :

```
git add .
```

Maintenant, commitez ces changements en utilisant la commande `git commit` :
```
git commit -m "e.g. fix #<numéro-du-problème>"
```
en remplaçant `<numéro-du-problème>` par le numéro du problème.

### Poussez (push) les changements vers GitHub

Poussez vos changements en utilisant la commande  `git push`:
```
git push origin <ajoutez-le-nom-de-votre-branche>
```
en remplaçant  `<ajoutez-le-nom-de-votre-branche>` par le nom de la branche que vous avez créée précédemment.

### Soumettez vos changements pour examen

Si vous allez dans votre dépôt sur GitHub, vous verrez un bouton  `Comparer et créer une pull request`. Cliquez sur ce bouton..

Soumettez maintenant la pull request.

Nous essaierons toujours d'éditer ou de fusionner les problèmes et les PR dès que possible. Vous recevrez un e-mail de notification une fois que les modifications auront été fusionnées.

### Où aller à partir de là ?

Félicitations ! Vous venez de terminer le flux de travail standard _fork -> clone -> edit -> PR_ workflow que vous rencontrerez souvent en tant que contributeur !
