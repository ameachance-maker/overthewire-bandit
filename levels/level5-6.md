# Bandit Niveau 5 → 6

## Objectif
Trouver le mot de passe du niveau 6 dans un fichier sous le répertoire `inhere` qui est :  
- Lisible par l’homme  
- Taille = 1033 octets  
- Non exécutable

## Commandes utilisées
cd inhere
find . -type f -size 1033c ! -executable -exec file {} \; | grep ASCII
cat ./maybehere07/.file2  # afficher le mot de passe

## Résultat
Mot de passe trouvé → utilisé pour se connecter à bandit6.
