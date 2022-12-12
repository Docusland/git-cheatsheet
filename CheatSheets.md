# Git Cheat Sheet
[Markdown](https://www.markdownguide.org/cheat-sheet/#basic-syntax)

# Commande de base
### **INIT**
Initialise un nouveau dépôt Git dans le répertoire courant.
```
 $ git init 
```
### **CLONE**
Clone un dépôt Git existant sur votre ordinateur
```
 $ git clone <url du projet>
```
### **ADD**
Ajout l'ensemble des fichiers du depot  
🚨 n'est pas conseillé !! 🚨
```
$ git add .
```
Ajoute un ou des fichiers dans la zone de transite avant le commit.
```
$ git add <fichier>
```
Permettre l’ajout de fichiers qui sont normalement ignorés.
```
$ git add --force <fichier>
```

### **COMMIT**
Enregistre les modifications actuelles dans l'historique du dépôt Git avant le push.
```
$ git commit -m "<message>"
```
### **PUSH**
Envoie les commits locaux vers un dépôt distant.
```
$ git push <remote> <branche>
```

### **PULL**
Récupère la dernière version d'un dépôt distant.

```
$ git pull <remote> <branche>
```

### **STATUS**
Affiche l'état des fichiers dans le dépôt Git, y compris les fichiers modifiés et non suivis.
```
$ git status
```
# commande secondaire

### **BRANCHE**
Affiche la liste des branches dans le dépôt Git.
```
$ git branch
```
voir +

### **LOG**
Affiche l'historique des commits du dépôt Git.
```
$ git log
```
```
$ git log --oneline
```
### **DIFF**
Affiche les différences entre les fichiers dans le dépôt Git.
```
$ git diff
```

### **RESET**
Annule les commits dans le dépôt Git.

```
$ git reset
```

### **REVERT**
Annule les commits dans le dépôt Git sans supprimer les commits 
```
$ git revert 
```




###


