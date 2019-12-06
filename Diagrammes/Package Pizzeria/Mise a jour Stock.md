# Cas  n°6

**Nom:** Modifier Etat du Stock (package « Equipe Pizzeria »)<br>
**Acteurs(s):** Pizzaiolo ou Responsable Pizzeria<br>
**Description succincte:** La modification manuelle de l'état du stock d'ingrédient doit être possible pour les Pizzaiolos et le Responsable de la Pizzéria<br>
**Auteur:** A Gomes<br>
**Date(s):** 06/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit se trouver sur la page de consultation des stock d'ingrédient (Cas d’utilisation "Consulter commandes à traiter")<br>
**Démarrage:** L’utilisateur a demandé la modification de la valeur du stock d'un ingrédient<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système demande une nouvelle valeur pour l'ingrédient sélectionné pour modification
2.	L’utilisateur entre la nouvelle valeur.
3.	L’utilisateur valide la nouvelle valeur.
4.	Le système met à jour la valeur du stock de l'ingrédient modifié.
5.	Le système rafraîchit l'affichage du stock d'ingrédients, avec la nouvelle valeur pour l'ingrédient modifié
6.	L'utilisateur quitte la consultation

**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur ne sélectionne aucune nouvelle valeur et quitte la modification

**Fin:** Scenario nominal : aux étapes 2 ou 6 sur décision de l’utilisateur<br>
**Post-conditions:** Le  stock de l'ingrédient modifié est bien visibile avec sa nouvelle valeur lors de la consultation du stock