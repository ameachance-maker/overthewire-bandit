# Bandit Niveau 6 → 7

## Objectif
Trouver le mot de passe du niveau 7 sur le serveur qui est :  
- Propriété de l’utilisateur bandit7  
- Propriété du groupe bandit6  
- Taille = 33 octets

## Commandes utilisées
cd ~
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password

## Résultat
Mot de passe trouvé → utilisé pour se connecter à bandit7.
