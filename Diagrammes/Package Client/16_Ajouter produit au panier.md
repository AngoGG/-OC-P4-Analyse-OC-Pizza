# Cas  n°16

**Nom:** Ajouter un produit au panier (package « Client »)<br>
**Acteurs(s):** Client, Visiteur<br>
**Description succincte:** L'utilisateur doit pouvoir ajouter un produit au panier afin de pouvoir le commander<br>
**Auteur:** A Gomes<br>
**Date(s):** 18/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit avoir consulté la carte des produits<br>
**Démarrage:** L’utilisateur a demandé l'ajout d'un produit au panier<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1. Le système ouvre une fenêtre demandant le nombre de produits, et sa taille pour les pizzas, à ajouter au panier.
2. L'utilisateur choisit les options et valide la sélection
3. Le système met à jour le panier de l'utilisateur

**Les scénarios alternatifs**<br>
1. En (2): L'utilisateur annule la commande

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 3 sur décision de l’utilisateur<br>

**Post-conditions:** Les informations sur les produits ajoutés sont accessibles dans le panier