# Cas  n°10

**Nom:** Gestion des droits utilisateurs (package « Equipe Nationale »)<br>
**Acteurs(s):** Equipe Nationale<br>
**Description succincte:** La modification des droits ou l'assignation à un groupe d'un compte utilisateur doit être possible pour les membres de l'Equipe Nationale<br>
**Auteur:** A Gomes<br>
**Date(s):** 18/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être authentifié en tant que membre de l'Equipe Nationale (Cas d’utilisation « S’identifier »)<br>
**Démarrage:** L'utilisateur a demandé le lancement de la gestion des droits utilisateurs<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche la liste des utilisateurs
2.	L'utilisateur peut modifier les droits d'un compte existant
3.	Le système met à jour la base de donnée et revient au point (1)

**Les scénarios alternatifs**<br>
1.  En (1): 
    1. Si la gestion des droits a été ouverte depuis la consultation du bilan d'activité globale, la liste affichée est celle de tous les membres du groupe
    2. Si la gestion des droits a été ouverte depuis la consultation individuelle d'un restaurant, la liste affichée est celle de tous les membres de ce restaurant
1.  En (1): L’utilisateur quitte sans avoir fait de modification
2.  En (2): L'utilisateur veut créer un nouveau compte utilisateur, il sélectionne "Créer compte utilisateur" et valide le nouveau compte avec les informations

**Scénario d'exception**<br>
- 1. En (2): Lors de la création d'un nouveau compte, si ce dernier existe déjà, message d'avertissement et impossibilité de créer le compte sans modifier le nom de ce dernier.

**Fin:** 
- Scenario nominal : à l'étape 3 sur décision de l’utilisateur
- Scenariot alternatif: aux étapes 1 et 2 sur décision de l'utilisateur

**Post-conditions:** Les modifications sont mises à jour et accessible sur l'écran de gestion des droits utilisateurs
