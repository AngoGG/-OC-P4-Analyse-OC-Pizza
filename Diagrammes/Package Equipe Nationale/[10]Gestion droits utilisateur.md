# Cas  n°8

**Nom:** Gestion des droits utilisateurs (package « Equipe Pizzeria »)<br>
**Acteurs(s):** Responsable Pizzeria<br>
**Description succincte:** La modification des droits ou l'assignation à un groupe d'un compte utilisateur doit être possible Responsable de la Pizzéria<br>
**Auteur:** A Gomes<br>
**Date(s):** 10/12/2019 (première rédaction)<br>
**Pré-conditions:** L'utilisateur est identifié en tant que responsable de pizzéria<br>
**Démarrage:** L'utilisateur a demandé le lancement de la gestion des droits utilisateurs<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche la liste des utilisateurs de la pizzéria
2.	L'utilisateur peut modifier les droits d'un compte existant
3.	Le système met à jour la base de donnée et revient au point (1)

**Les scénarios alternatifs**<br>
1.  En (1): L’utilisateur quitte sans avoir fait de modification
2.  En (2): L'utilisateur veut créer un nouveau compte utilisateur, il sélectionne "Créer compte utilisateur" et valide le nouveau compte avec les informations

**Scénario d'exception**<br>
- 1. En (2): Lors de la création d'un nouveau compte, si ce dernier existe déjà, message d'avertissement et impossibilité de créer le compte sans modifier le nom de ce dernier.

**Fin:** 
- Scenario nominal : à l'étape 3 sur décision de l’utilisateur
- Scenariot alternatif: aux étapes 1 et 2 sur décision de l'utilisateur

**Post-conditions:** Les modifications sont mises à jour et accessible sur l'écran de gestion des droits utilisateurs
