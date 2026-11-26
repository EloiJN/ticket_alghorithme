# Série 1 - Variables, saisie, affichage

## 1.1 - Bonjour

ALGORITHME Bonjour

VARIABLES
    prenom : TEXTE

DEBUT
    LIRE prenom
    ECRIRE "Bonjour", prenom
FIN

## 1.2 - Surface

ALGORITHME Surface

VARIABLES
    longueur : ENTIER
    largeur : ENTIER
    surface : ENTIER

DEBUT
    LIRE longueur
    LIRE largeur
    SURFACE = longeur * largeur
    ECRIRE "La surface est de ", SURFACE, "m2" 
FIN

## Echange

ALGORITHME Echange

VARIABLES
    a : ENTIER
    b : ENTIER
    C : ENTIER

DEBUT

    c <- b
    b <- a
    a <- c

    ECRIRE a
    ECRIRE b

FIN

## Durée de randonnée

ALGORITHME duree_randonnee

VARIABLE
    temps_rando : ENTIER
    heures : ENTIER
    minutes : ENTIER
    time : TEXTE
DEBUT

    LIRE temps_rando
    heures <- temps_rando DIV 60
    minutes <- temps_rando MOD 60

    time <- heure, "h", minute, "min"


    ECRIRE temps_rando, time
FIN

## Rendu de monnaie

ALGORITHME rendu_monaie

VARIABLE
    montant : ENTIER
    montant_restant : ENTIER
    nbr_billet_10 : ENTIER
    nbr_billet_5 : ENTIER
    nbr_piece_2 : ENTIER
    nbr_piece_1 : ENTIER

DEBUT
    LIRE montant

    montant_restant <- montant

    //calcul du nombre de billet de 10
    nbr_billet_10 <- montant_restant / 10
    montant_restant <- montant_restant -  nbr_billet_10 * 10

    //calcul du nombre de billet de 
    nbr_billet_5 <- montant_restant / 5
    montant_restant <- montant_restant -  nbr_billet_10 * 5

    //calcul du nombre de pièces de 2
    nbr_piece_2 <- montant / 2
    montant_restant <- montatnt_restant - nbr_piece_2 * 2

    //calcul du nombre de pieces de 1
    nbr_piece_1 <- montant / 1
    montant_restant <- montant_restant - nbr_piece_1 * 1

    ECRIRE montant, "donne ", nbr_billet_10, " billets de 10€ ", nbr_billet_5, " billets de 5€ "
FIN
