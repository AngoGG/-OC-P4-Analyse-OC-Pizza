# Cas  n°20

**Nom:** Payer une commande (package « Client »)<br>
**Acteurs(s):** Client<br>
**Description succincte:** Le paiement d'une commande doit être possible pour l'utilisateur<br>
**Auteur:** A Gomes<br>
**Date(s):** 26/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit se trouver sur l'onglet de passage de commande<br>
**Démarrage:** L’utilisateur a demandé le paiement d'une commande<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1. Le système demande à l'utilisateur quelle mode de paiement il veut
2. L'utilisateur choisit son mode de paiement
3. Le système créee la commande
4. Le système retourne à la page de consultation des commandes


**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur annule le paiement
2.  En (2): Si le client choisit paiement à la livraison, passage à l'étape 3
3.  En (2) Si le client choisit le paiement en ligne:
    - Le système lance une interface avec le système de paiement par carte bancaire
    - L'utilisateur valide son paiement en ligne
    - Fin du paiement et passage à l'étape (3) du scénario nominal

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 4 sur décision de l’utilisateur
- Scénario alternatif: à l'étape 2 sur décision de l'utilisateur

**Post-conditions:** L'utilisateur est mis au courant de la prise en compte du paiement, la commande est bien créee et accessible pour le client (Cas d'utilisation « Consulter les commandes en cours ») ainsi que pour la pizzéria (Cas d'utilisation « Consulter Commande »)
