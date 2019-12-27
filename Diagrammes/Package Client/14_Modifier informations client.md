# Cas  n°14

**Nom:** Modifier les informations client (package « Client »)<br>
**Acteurs(s):** Client<br>
**Description succincte:** La modification des informations personnelles doit être possible pour l'utilisateur<br>
**Auteur:** A Gomes<br>
**Date(s):** 18/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être authentifié en tant que client (Cas d’utilisation « S’identifier »)<br>
**Démarrage:** L’utilisateur a demandé la mofication des informations personnelles<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche un écran contenant les informations personnelles
2.	L’utilisateur modifie une ou plusieurs informations.
3.  L'utilisateur valide les modifications
4.  Le système met à jour les informations et rafraîchit l'affichage

**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur ne modifie aucune information et quitte l'écran
2.  En (3): L'utilisateur ne valide pas les modifications et quitte l'écran

**Scénario d'exception**<br>
1. En (3): Lors de la validation, si l'utilisateur n'a pas rempli certaines informations obligatoire, la validation ne se fait pas et un message s'affiche pour lui demander de le faire 

**Fin:** 
- Scenario nominal : à l'étape 4 sur décision de l’utilisateur
- Scénario alternatif: aux étapes 2 et 3 sur décision de l'utilisateur

**Post-conditions:** Les informations personnelles sont bien mises à jour