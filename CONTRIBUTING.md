# Contribuer à un projet ETML

Ce projet utilise certaines conventions afin de garantir un travail clair,
reproductible et professionnel.

## Structure du projet

src/ → code source de l'application
tests/ → tests automatisés
docs/ → documentation du projet

Les étudiants doivent respecter cette organisation.

## Installation

```bash
npm install
```

## Lancer le projet

```bash
npm start
```

## Vérifier le code

```bash
npm run lint
```

Les erreurs ESLint doivent être corrigées avant de livrer le projet.

## Style du code

Le formatage est géré automatiquement par **Prettier**.

Les règles de qualité sont gérées par **ESLint**.

## Commits

Les commits doivent suivre la convention **Conventional Commits ETML** :

```
type(scope): effet
```

Types autorisés :

* feat → nouvelle fonctionnalité
* fix → correction de bug
* doc → documentation
* meet → gestion de projet
* learn → apprentissage
* chore → maintenance technique

Exemple :

```
feat(auth): Ajoute la connexion utilisateur
```

Chaque commit doit être **atomique** :
un commit = une tâche complète.
