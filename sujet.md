* Authors : BfoR, Flomonster

## Introduction à git

Bienvenue à ce TP GIT !

### Partie 1..

## Soumission d'exercice

Pour soumettre n'importe quelle exercice utilisez la commande `git push --all`.

Vous pouvez récupérer le flag est le rentrer ici : `http://ctf.bfor.ovh/`

Si la soumission est refusée alors executez `git reset --hard origin/master` pour chaqu'une des branches.

## Premier pas !

```
git clone git@git.bfor.ovh:exercice1.git
cd exercice1
```

Vous devez pour ce premier exercice simuler plusieur commit d'un projet.

1. Editez le fichier `main.py` et modifier le nom de la fonction `hello` par `bonjour`, sauvegardez.
2. Vous pouvez creer votre premier commit !
3. Ajouter la fonction suivante et commit à nouveau !

```
def magic(x):
	return x + 42
```

Vous pouvez maintenant soumettre votre code.

## Correction de bug

```
git clone git clone git@git.bfor.ovh:exercice2.git 
cd exercice2
```

Dans cet exercice il va falloir corriger le bug dans un projet.
Cependant un membre de votre groupe de projet travail déja sur la branche `master`.
Donc vous allez devoir effectuer la correction sur une autre branche !

1. Créez la branche `correction`.
2. Allez sur cette branche.
3. Editer le fichier `main.py` puis corriger le bug.
4. Faite un commit.

Vous pouvez maintenant soumettre votre code.

