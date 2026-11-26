# Les Conditions

## Majorité

ALGORITHME majorité
VARIABLES
    age : ENTIER
DEBUT
    LIRE age

    SI age >= 18 ALORS
        ECRIRE "majeur"
    SINON
        ECRIRE "mineur"
    FIN SI
FIN

## Parité

ALGHORITHME parité
VARIABLES
 a_verifier : ENTIER

 DEBUT
    SI a_verifier MOD 2 = 0 ALORS
        ECRIRE "pair"
    SINON
        ECRIRE "impair"
    FIN SI
 FIN

 ## Le plus grand

 ALGORITHME Le plus grand

 VARIABLES
  nombre_1 : ENTIER
  nombre_2 : ENTIER

 DEBUT
    SI nombre_1 > nombre_2 ALORS
        ECRIRE nombre_1 
    SINON SI nombre_2 > nombre_1 ALORS
        ECRIRE nombre_2
    SINON 
        ECRIRE "Les deux nombres sont égaux"
 FIN
