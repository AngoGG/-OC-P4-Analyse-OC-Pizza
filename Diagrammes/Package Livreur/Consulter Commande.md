# Cas  n°1

**Nom:** Consulter Commandes à livrer (package « Livreur »)<br>
**Acteurs(s):** Livreur<br>
**Description succincte:** La consultation des commandes en état « A livrer » doit être possible pour les livreurs de la pizzéria<br>
**Auteur:** A Gomes<br>
**Date(s):** 02/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être authentifié en tant Livreur ( Cas d’utilisation « S’identifier »)<br>
**Démarrage:** L’utilisateur a lancé l’interface et s’est connecté<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche une page contenant la liste des commandes prêtes à être livrées.
2.	L’utilisateur sélectionne une des commandes à livrer.
3.	Le système  recherche les informations sur la commande sélectionnée.
4.	Le système affiche les informations sur la commande sélectionnée
5.	L’utilisateur quitte la description détaillée de la commande.
6.	Le système retourne à l’affichage de l’écran d’accueil (Retour point 1.)

**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur quitte le logiciel

**Fin:** Scenario nominal : aux étapes 2 ou 5 sur décision de l’utilisateur<br>
**Post-conditions:** Aucun
