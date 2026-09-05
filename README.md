# SAS JavaScript Console — Dépôt candidat

Ce dépôt accompagnera toute ta progression pendant les sept journées du SAS. Les exercices seront ajoutés progressivement : tu ne recevras que la journée en cours.

## Mon identité

- Nom et prénom :
- Classe :
- Nom d'utilisateur GitHub :

## Première installation

Après avoir créé ton dépôt avec **Use this template** :

```bash
git clone URL_DE_TON_DEPOT
cd NOM_DE_TON_DEPOT
git status
```

## Ajouter le paquet du jour

1. Télécharge le ZIP publié dans Google Classroom.
2. Extrais le dossier `dayXX` à la racine de ce dépôt.
3. Vérifie les nouveaux fichiers avec `git status`.
4. Crée un commit avant de commencer les solutions.

```bash
git add dayXX
git commit -m "jour XX : ajouter les fichiers de départ"
git push
```

## Routine quotidienne

```text
Lire → Coder → Exécuter → Vérifier → git add → git commit → git push
```

Commandes détaillées : [docs/commandes-git.md](./docs/commandes-git.md)

Progression : [PROGRESSION.md](./PROGRESSION.md)

## Vérification automatique

`npm test` vérifie que les fichiers déjà publiés ne sont plus vides et qu'ils ne contiennent pas d'erreur de syntaxe. Cette vérification ne remplace pas l'explication orale ni l'évaluation du formateur.
