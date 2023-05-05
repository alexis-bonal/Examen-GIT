# VERSIONNING GIT

## 1) A quoi sert un gestionnaire de versions ?

- [x] Conserver un historique
- [x] Revenir en arrière en cas de problème
- [x] Travailler à plusieurs
- [x] Suivre les modifications de chaque fichier
- [ ] Mettre en ligne un site web

## 2) Git est un gestionnaire de version décentralisé

- [ ] Faux
- [x] Vrai

## 3) Quelle commande permet d'initialiser son projet dans Git Bash ?

- [x] git init
- [ ] git start
- [ ] git in
- [ ] git initial

## 4) Quelles sont les trois zones locales majeures dans Git ?

- [x] Working directory
- [ ] Cloud
- [x] Repository
- [x] Index

## 5) Vous avez créé votre dépôt distant sur GitHub, que l'on appellera monDepotDistant, et vous souhaitez le lier avec votre dépôt local sur Git. DEP représente le nom court qui sera utilisé pour appeler le dépôt.

Quelle ligne de commande devez-vous taper ?

- [ ] git remote DEP https://github.com/xxxxxx/monDepotDistant
- [ ] git remote DEP add https://github.com/xxxxxx/monDepotDistant
- [x] git remote add DEP https://github.com/xxxxxx/monDepotDistant
- [ ] git add DEP https://github.com/xxxxxx/monDepotDistant

## 6) Maintenant que votre dépôt distant est lié à votre dépôt local, vous allez devoir dupliquer son contenu en local. Pour ce faire, nous devons utiliser

- [ ] git clone DEP https://github.com/xxxxxx/monDepotDistant
- [ ] git duplicate https://github.com/xxxxxx/monDepotDistant
- [x] git clone https://github.com/xxxxxx/monDepotDistant
- [ ] git duplicate DEP

## 7) Je suis sur ma Branch1 et je viens d’ajouter un fichier "File2.txt". Je change d’avis : je veux finalement ajouter mon fichier à une nouvelle branche, "BranchFile". Que dois-je faire ?

- [ ] réponse 1 :

```bash
git status
git branch BranchFile
git checkout BranchFile
git status apply
```

___

- [ ] réponse 2 :

```bash
git status
git stash
git branch BranchFile
git checkout BranchFile
git status apply
```

___

- [x] réponse 3 :

```bash
git status
git stash
git branch BranchFile
git checkout BranchFile
git stash apply
```

## 8) ```git commit --amend -m "Test"``` Cette commande permet de

- [ ] revenir au commit précédent
- [x] modifier le message du commit précédent
- [ ] créer un nouveau commit avec le message "Test"

## 9) Quelle est la différence entre git revert et git reset?

- [ ] git revert ne réinitialise qu’un commit alors que git reset réinitialise tout
- [x] git revert crée un nouveau commit alors que git reset, non
- [ ] git reset crée un nouveau commit alors que git revert, non

## 10) Je souhaite savoir qui a touché à une ligne en particulier dans le fichier `test.html`. Quelle commande vais-je devoir exécuter ?

- [ ] git log
- [ ] git reflog
- [x] git blame
- [ ] git cherry pick
