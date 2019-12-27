# Cas  n°19

**Nom:** Passer une commande (package « Client »)<br>
**Acteurs(s):** Client<br>
**Description succincte:** L'utilisateur doit pouvoir passer une commande<br>
**Auteur:** A Gomes<br>
**Date(s):** 23/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être authentifié en tant que client ( Cas d’utilisation « S’identifier »)<br>
**Démarrage:** L’utilisateur a validé son panier et a demandé à passer sa commande<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1. Le système demande le type de commande (Sur place, Livraison)
2.1 Si la commande est à retirer sur place, passage à l'étape 3
2.2 Si la commande à est livrer, le système demande la confirmation de l'addresse du client pour livraison
    - 2.2.1 L'utilisateur confirme l'addresse
    - 2.2.2 Le système valide la disponibilité de l'addresse pour livraison
3. Le système lance le choix du mode de paiement (Cas d'utilisation « Effectuer le paiement d'une commande »)
4. Le système récupère la confirmation du paiement
5. Le système met à jour la base de donnée pour envoyer la commande à la pizzéria
6. Le système envoie une confirmation de commande au client


**Les scénarios alternatifs**<br>
1. En (2.2.1): L'utilisateur ne confirme pas son addresse et annule la commande
2. En (3): L'utilisateur annule la commande lors du paiement

**Scénario d'exception**<br>
1. En (2.2.1): L'addresse du client est non disponible pour livraison, le traitement reste bloqué jusqu'à la saisie d'une addresse valide, le changement de type de commande (sur place) ou l'annulation de la commande par l'utilisateur
2. En (3): Un problème survient lors du paiement, le traitement revient à l'étape 1.

**Fin:** 
- Scenario nominal : à l'étape 6 sur décision de l’utilisateur<br>
- Scenario alternatif: aux étape 2.2.1, 3 sur décision de l'utilisateur<br>
- Scenario d'exception: à l'étape 2.2.1 sur décision de l'utilisateur, 3 suite à problème lors du paiement<br>

**Post-conditions:** Les informations de commande sont accessibles via "Consulter une commande" pour le client, et dans "Consulter une commande" du package Pizzeria
