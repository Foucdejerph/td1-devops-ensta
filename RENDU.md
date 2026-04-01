# Rendu TD1 - [Votre Nom]

## Exercice 1
- Lien PR : [https://github.com/Foucdejerph/td1-devops-ensta]
- Pourquoi crée-t-on une branche plutôt que de committer directement sur main ?
On crée une branche pour isoler les modifications sans affecter la branche principale

## Exercice 2 - Capture The Bug

### Bug 1
- Déclencheur : Numéro de ligne supérieur à 12. Indexer out of bounds
- Commit fautif : [hash] 7abdaed
- Auteur : [nom] Serpico
- Ligne problématique : [code] 48
- Correction appliquée : [expliquez ce que vous avez changé et pourquoi]

### Bug 2
- Déclencheur : recherche avec aucun contenu 
- Commit fautif : [hash] e9b5614e 
- Auteur : [nom] Serpico
- Ligne problématique : [code] 25
- Correction appliquée : [expliquez ce que vous avez changé et pourquoi]

### Bug 3
- Déclencheur : Ne pas mettre de filtre
- Commit fautif : [hash] 002ad360 
- Auteur : [nom] Serpico
- Ligne problématique : [code] 14
- Correction appliquée : [expliquez ce que vous avez changé et pourquoi]

## Exercice 3
- Commit de résolution : [hash] 
- Qu'est-ce qu'un conflit Git et pourquoi survient-il ? Un conflit Git se produit lorsque deux branches modifient la même ligne ou le même fichier de manière différente.
- (Bonus) Différence entre merge et rebase : Non traité

## Exercice 4
- Commande utilisée pour squasher les 3 commits : [commande]
- Pourquoi squasher avant de merger ? [1 phrase]
- Différence entre `--soft`, `--mixed` et `--hard` : [1-2 phrases]
- Hash du commit hotfix sur main : [hash]
- Pourquoi cherry-picker vers dev plutôt que merger main dans dev ? [1 phrase]

## Exercices 5/6
- Lien vers le workflow GitHub Actions : [URL]
- Qu'apporte la CI par rapport à des tests lancés manuellement ? [1-2 phrases]
- Pourquoi filtrer les fichiers qui déclenchent la CI ? [1 phrase]