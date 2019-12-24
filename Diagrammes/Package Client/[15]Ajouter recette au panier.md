# Cas  n°15

**Nom:** Ajouter recette au panier (package « Client »)<br>
**Acteurs(s):** Client, Visiteur<br>
**Description succincte:** Le client doit pouvoir ajouter une recette au panier afin de pouvoir la commander<br>
**Auteur:** A Gomes<br>
**Date(s):** 18/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit avoir consulté le catalogue de recette<br>
**Démarrage:** L’utilisateur a demandé l'ajout d'une recette au panier<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1. Le système ouvre une fenêtre demandant le nombre et la taille des pizzas à ajouter au panier.
2. L'utilisateur choisit les options et valide la sélection
3. Le système met à jour le panier de l'utilisateur

**Les scénarios alternatifs**<br>
1. En (2): L'utilisateur annule la commande
2. En (3): Chaque recette ajoutée au panier par l'utilisateur peut être modifiée ou supprimée 

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 3 sur décision de l’utilisateur<br>
- Scenario alternatif: à l'étape 2, sur décision de l'utilisateur<br>

**Post-conditions:** Les informations sur les recettes disponibles à la commande sont affichées