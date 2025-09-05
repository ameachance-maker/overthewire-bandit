# Bandit Niveau 0 → 1

## Objectif
Se connecter au serveur en SSH et trouver le mot de passe du niveau suivant dans un fichier `readme`.

## Commandes utilisées
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
# mot de passe : bandit0

ls
cat readme
