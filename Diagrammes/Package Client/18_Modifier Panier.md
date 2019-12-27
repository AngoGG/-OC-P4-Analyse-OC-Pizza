# Cas  n°18

**Nom:** Modifier le panier (package « Client »)<br>
**Acteurs(s):** Client<br>
**Description succincte:** La modification du panier doit être possible pour l'utilisateur<br>
**Auteur:** A Gomes<br>
**Date(s):** 26/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être authentifié en tant que client ( Cas d’utilisation « S’identifier »)<br>
**Démarrage:** L’utilisateur a demandé la modification du panier<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le client choisit un produit du panier à modifier
2.  Le système demande à l'utilisateur quel type de modification il veut effectuer (Modifier quantité, modifier ingrédients)
3.  L'utilisateur effectue sa modification
4.  L'utilisateur valide sa modification
5.	Le système met à jour le panier.
6.	Le système redirige l'utilisateur vers le panier


**Les scénarios alternatifs**<br>
1.  En (3): L’utilisateur annule la modification
2.  En (4): L'utilisateur ne valide pas et annule la modification

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 6 sur décision de l’utilisateur
- Scénario alternatif: aux l'étape 3, 4 sur décision de l'utilisateur

**Post-conditions:** Le panier modifié est bien mise à jour et accessible pour le client (Cas d'utilisation « Consulter le panier »)
