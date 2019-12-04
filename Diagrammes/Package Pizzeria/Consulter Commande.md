# Cas  n°1

**Nom:** Consulter Commandes à traiter (package « Pizzéria »)<br>
**Acteurs(s):** Pizzaiolo ou Responsable de la Pizzéria<br>
**Description succincte:** La consultation des commandes en doit être possible pour les livreurs de la pizzéria<br>
**Auteur:** A Gomes<br>
**Date(s):** 04/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être authentifié en tant Pizzaiolo ou Responsable ( Cas d’utilisation « S’identifier »)<br>
**Démarrage:** L’utilisateur a lancé l’interface et s’est connecté<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche une page contenant la liste des commandes.
2.	L’utilisateur sélectionne une des commandes.
3.	Le système  recherche les informations sur la commande sélectionnée.
4.	Le système affiche les informations sur la commande sélectionnée
5.	L’utilisateur quitte la description détaillée de la commande.
6.	Le système retourne à l’affichage de l’écran d’accueil (liste des commandes)

**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur quitte le logiciel

**Fin:** Scenario nominal : aux étapes 2 ou 5 sur décision de l’utilisateur<br>
**Post-conditions:** Aucun
