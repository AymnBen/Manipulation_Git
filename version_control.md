# C02 — Comprendre le Version Control

## 1) C’est quoi le version control ?
Le version control (contrôle de version) est un système qui permet d’enregistrer l’historique des modifications d’un projet (souvent du code) dans le temps.  
Chaque modification importante peut être sauvegardée sous forme de “version” (commit), ce qui permet de suivre qui a changé quoi, quand, et pourquoi.

## 2) Pourquoi on en a besoin ?
- **Historique** : retrouver toutes les versions précédentes du projet.
- **Retour arrière** : annuler une erreur en revenant à une version stable.
- **Collaboration** : plusieurs personnes peuvent travailler sur le même projet sans se marcher dessus.
- **Traçabilité** : savoir exactement quels fichiers ont été modifiés et par qui.
- **Branches** : développer une nouvelle fonctionnalité sans casser la version principale.
- **Sauvegarde** : avec un dépôt distant (GitHub), ton projet est sauvegardé en ligne.

## 3) Exemple concret
Si je modifie un fichier et que je casse le projet, je peux revenir au dernier commit qui fonctionnait.  
Si je travaille avec une équipe, chacun travaille sur une branche, puis on fusionne (merge) quand c’est prêt.