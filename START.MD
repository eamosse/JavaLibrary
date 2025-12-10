# 🚀 Lier votre projet Java avec le repository Git

Ce guide explique comment **initialiser un dépôt Git dans un dossier contenant déjà du code** et comment le **lier à un dépôt GitHub**.

---

## ✅ 1. Accéder au dossier du projet

```bash
cd /path/to/your/project
```

---

## ✅ 2. Initialiser un dépôt Git local (si ce n'est pas déjà le cas)
>> Pour s'en assurer, faire 
```bash
git status
```

```bash
git init
```
Cela crée un dossier `.git` qui transforme votre dossier en dépôt Git.

---

## ✅ 3. Ajouter tous les fichiers existants 

```bash
git add .
```
---

## ✅ 4. Créer un premier commit

```bash
git commit -m "Initial commit"
```

---

## ✅ 5. Ajouter le dépôt distant

```bash
git remote add origin [VOTRE REPO]
```
---

## ✅ 6. Pousser le code vers la branche principale

### Si votre branche s’appelle **main** :
```bash
git push -u origin main
```

### Si votre branche s’appelle **master** :
```bash
git push -u origin master
```

---

## 🎉 Le projet est maintenant lié à votre dépôt Git distant !

Vous pouvez vérifier avec :

```bash
git remote -v
```
