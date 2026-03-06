# C07 — Undo sans paniquer (restore vs reset)

## git restore
- Sert à annuler des changements locaux.
- Peut annuler les modifications d’un fichier dans le working directory :
  - `git restore fichier.txt`
- Peut aussi retirer un fichier du staging (index) :
  - `git restore --staged fichier.txt`
- Objectif : revenir à l’état du dernier commit (ou de l’index) sans toucher à l’historique.

## git reset
- Sert à déplacer le pointeur HEAD (et parfois l’index + working directory).
- Types principaux :
  - `git reset --soft <commit>` : garde les changements en staging.
  - `git reset --mixed <commit>` (par défaut) : garde les changements mais enlève du staging.
  - `git reset --hard <commit>` : supprime les changements (attention, destructif).
- Objectif : réécrire l’état du projet et parfois l’historique local.

## Différence simple
- **restore** : annule des changements sur des fichiers (safe, ne modifie pas l’historique).
- **reset** : revient à un commit (peut modifier l’historique local et être plus risqué).