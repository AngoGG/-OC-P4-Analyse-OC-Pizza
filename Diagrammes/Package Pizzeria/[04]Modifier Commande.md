# Cas  n°4

**Nom:** Modifier Commandes à traiter (package « Equipe Pizzeria »)<br>
**Acteurs(s):** Pizzaiolo ou Responsable Pizzeria<br>
**Description succincte:** La modification des commandes en état « En cours de préparation » où « A livrer » doit être possible pour les Pizzaiolos et le Responsable de la Pizzéria<br>
**Auteur:** A Gomes<br>
**Date(s):** 04/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit se trouver sur la fiche d'une commande à traiter (Cas d’utilisation "Consulter commandes à traiter")<br>
**Démarrage:** L’utilisateur a demandé la modification de l'état de la commande<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche un choix de nouvel état pour la commande ('En cours de préparation', 'A livrer')
2.	L’utilisateur sélectionne l'une des options.
3.	L’utilisateur valide l'état sélectionné.
4.	Le système met à jour l'état de la commande.
5.	Le système redirige vers la liste des commandes

**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur ne sélectionne aucun état et annule la modification
2.  En (2): Si l'utilisateur est le responsable de pizzéria, il peut assigner une commande à livrer directement à un livreur
    1. Le système affiche la liste des livreurs
    2. L'utilisateur sélectionne le livreur à qui assigner la commande
2.  En (3): L'utilisateur ne valide pas la sélection et annule la modification

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 5 sur décision de l’utilisateur
- Scénario alternatif: aux étapes 2 et 3 sur décision de l'utilisateur
**Post-conditions:** Si la commande a été modifié en état "En cours de préparation, elle apparaît avec ce nouvel état dans la liste des commandes à traiter , si elle a été modifiée en "A livrer", elle n'est plus accessible dans la liste ( Cas d'utilisation "Consulter commandes à livrer")
