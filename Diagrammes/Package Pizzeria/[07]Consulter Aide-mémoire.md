# Cas  n°7

**Nom:** Consulter Aide-Mémoire (package « Equipe Pizzeria »)<br>
**Acteurs(s):** Pizzaiolo<br>
**Description succincte:** Le Pizzaiolo doit pouvoir accéder à un aide-mémoire concernant les recettes de la Pizzeria<br>
**Auteur:** A Gomes<br>
**Date(s):** 04/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être authentifié en tant Pizzaiolo ou Responsable ( Cas d’utilisation « S’identifier »)<br>
**Démarrage:** L’utilisateur a demandé la consultation de l'aide-mémoire<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1. Le système affiche une page contenant la liste des recettes de la pizzéria
2. L’utilisateur sélectionne l'une des recettes.
3. Le système récupère les informations sur la recette sélectionnée.
4. Le système affiche la recette sélectionnée.


**Les scénarios alternatifs**<br>
1. En (2): L’utilisateur quitte la consultation
2. En (4): L’utilisateur quitte la consultation

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 4 sur décision de l’utilisateur
- Scenario alternatif: à l'étape 1 sur décision de l'utilisateur
**Post-conditions:** La recette sélectionnée est affichée

