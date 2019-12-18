# Cas  n°2

**Nom:** Modifier Commandes (package « Livreur »)<br>
**Acteurs(s):** Livreur<br>
**Description succincte:** La modification des commandes en état « Livraison terminée » doit être possible pour les livreurs de la pizzéria<br>
**Auteur:** A Gomes<br>
**Date(s):** 04/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit se trouver sur la fiche d'une commande à livrer (Cas d’utilisation « Consulter commandes à livrer)<br>
**Démarrage:** L’utilisateur a demandé la mofication de l'état de la commande<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche un choix de nouvel état pour la commande ('En cours de livraison', 'Livraison terminée')
2.	L’utilisateur sélectionne l'une des options.
3.	L’utilisateur valide l'état sélectionné.
4.	Le système met à jour l'état de la commande.
5.	Le système redirige vers la liste des commandes


**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur ne sélectionne aucun état et annule la modification
2.  En (3): L'utilisateur ne valide pas la sélection et annule la modification

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 5 sur décision de l’utilisateur
- Scénario alternatif: aux étapes 2 et 3 sur décision de l'utilisateur

**Post-conditions:** Si la commande a été modifié en état "En cours de livraison, elle apparaît avec ce nouvel état dans la liste des commandes à traiter , si elle a été modifiée en "Livraison terminée", elle n'est plus accessible dans la liste ( Cas d'utilisation "Consulter commandes à livrer")
