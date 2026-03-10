# Template Node.js ETML

Template officiel ETML pour les projets Node.js utilises dans les cours et exercices. Ce depot sert de base aux depots crees automatiquement via **GitHub Classroom**.

L objectif est de fournir a tous les eleves :

* un environnement de developpement identique
* une structure de projet claire
* des outils professionnels de qualite de code

---

# Demarrage rapide

## 1. Ouvrir le projet dans VS Code

Ouvrez simplement le dossier dans **Visual Studio Code**.

VS Code detectera automatiquement le **Dev Container**.

Cliquez sur :

**Reopen in Container**

Cela va lancer un environnement de developpement complet configure pour le cours.

---

## 2. Installer les dependances

Dans le terminal :

```bash
npm install
```

---

## 3. Lancer le programme

```bash
npm start
```

Le point d entree du projet est :

```
src/index.js
```

---

# Qualite du code

## Verifier le code

```bash
npm run lint
```

## Corriger automatiquement certaines erreurs

```bash
npm run lint:fix
```

## Formatter tout le projet

```bash
npm run format
```

Ces outils sont standards dans l industrie logicielle.

---

# Structure du projet

```
src/    code source du projet
tests/  tests automatises
docs/   documentation
```

Regles importantes :

* le code doit rester dans **src**
* la documentation dans **docs**
* les tests dans **tests**

---

# Travail avec Git

Les commits doivent suivre les conventions **ETML Conventional Commits**.

Format :

```
type(scope): effet
```

Types principaux :

* feat  nouvelle fonctionnalite
* fix   correction de bug
* doc   documentation
* chore maintenance technique
* learn apprentissage
* meet  gestion de projet

Exemple :

```
feat(api): Ajoute endpoint de recuperation des utilisateurs
```

Chaque commit doit etre **atomique** :

> un commit = une tache complete

Voir le fichier :

```
CONTRIBUTING.md
```

---

# Technologies utilisees

Ce template inclut deja :

* Node.js
* Dev Containers
* ESLint
* Prettier

Ces outils permettent de travailler comme dans un projet logiciel professionnel.

---

# Contexte pedagogique

Ce template est utilise a l **ETML** afin de :

* standardiser les projets
* faciliter l evaluation
* introduire les bonnes pratiques de developpement logiciel
