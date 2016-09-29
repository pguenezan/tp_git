* Authors : BfoR, Flomonster

## Introduction à git

Bienvenue à ce TP GIT !

Nous allons commencer par vous rappeler quelques commandes de bases.

#### Configuration

Ces deux configurations sont nécessaires pour pouvoir réaliser un commit, 
il permet d'identifier la personne qui a produit le commit.

* ```git config --global user.name [pseudo]``` Permet de configurer votre pseudo.
* ```git config --global user.email [email]``` Permet de configurer votre email.

#### Création d'un commit

* ```git status``` Affiche l'état de l'arbre de travail.
* ```git add``` Permet d'ajouter des fichiers à l'index.
* ```git commit -m "Votre msg de commit"``` Sauvegarde le contenu de l'index dans un nouveau point de commit.

#### Opération sur les branches

Les branches vont vous permettre de développer sans affecter directement le projet. 
C'est très utile pour travailler à plusieurs sur un projet.

* ```git branch``` Affiches les branches, vous pouvez voir où vous êtes.
* ```git branch [branch_name]``` Créer une nouvelle branche.
* ```git checkout [branch_name]``` Vous déplace sur une autre branche. 
* ```git merge [branche_1] [branche_2]``` Fusionne la branche 2 sur la branche 1.

## Soumission d'exercice

Pour soumettre n'importe quel exercice utilisez la commande `git push --all`

Vous pouvez récupérer le flag est le rentrer ici : `http://ctf.bfor.ovh/`

Si la soumission est refusée, et que vous voulez recommencer, alors exécutez `git reset --hard origin/master`

## Premier pas !

```
git clone git@git.bfor.ovh:exercice1.git
cd exercice1
```

Vous devez pour ce premier exercice simuler plusieurs commit d'un projet.

1. Editez le fichier `main.py` et modifier le nom de la fonction `hello` par `bonjour`, sauvegardez.
2. Vous pouvez créer votre premier commit !
3. Ajouter la fonction suivante et commit à nouveau !

```
def magic(x):
	return x + 42
```

Vous pouvez maintenant soumettre votre code.

## Correction de bug

```
git clone git@git.bfor.ovh:exercice2.git 
cd exercice2
```

Dans cet exercice il va falloir corriger le bug dans un projet.
Cependant un membre de votre groupe de projet travaille déja sur la branche `master`.
Donc vous allez devoir effectuer la correction sur une autre branche !

1. Créez la branche `correction`.
2. Allez sur cette branche.
3. Editer le fichier `main.py` puis corrigé le bug.
4. Faite un commit.

Vous pouvez maintenant soumettre votre code.

## Fusionnnnnnnnnnn !!!!!!

```
git clone git@git.bfor.ovh:exercice3.git
cd exercice3
```

Le but de cet exercice est simple il faut fusionner la branche `fix` à la branche `master`.

## Rebase

```
git clone git@git.bfor.ovh:exercice4.git
cd exercice4
```

Pour cet exercice, vous devrais remettre les commits dans le bon ordre et
mettre tous les commits sur une `master`.

Pour cela la commande `git rebase` sera très utile !
