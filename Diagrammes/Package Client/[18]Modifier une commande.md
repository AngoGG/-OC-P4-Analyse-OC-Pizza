# Cas  n°18

**Nom:** Modifier Commandes (package « Client »)<br>
**Acteurs(s):** Livreur<br>
**Description succincte:** La modification d'une commande qui n'est pas encore en cours de préparation doit être possible pour l'utilisateur<br>
**Auteur:** A Gomes<br>
**Date(s):** 24/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit se trouver sur la fiche d'une commande qui n'est pas en cours de préparation<br>
**Démarrage:** L’utilisateur a demandé la mofication de la commande<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche la liste des recettes en cours de la commande avec possibilité de supprimer une recette, ainsi qu'une liste des recettes disponibles pour ajout à la commande
2.	L’utilisateur sélectionne l'une des options disponible et modifie sa commande.
3.	L’utilisateur valide la modification de sa commande.
4.	Le système met à jour la commande.
5.	Le système redirige vers la liste des commandes


**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur annule la modification
2.  En (3): L'utilisateur ne valide pas et annule la modification

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 5 sur décision de l’utilisateur
- Scénario alternatif: aux étapes 2 et 3 sur décision de l'utilisateur

**Post-conditions:** La commande modifiée est bien mise à jour et accessible pour le client (Cas d'utilisation « Consulter les commandes en cours ») ainsi que pour la pizzéria (Cas d'utilisation « Consulter Commande »)
