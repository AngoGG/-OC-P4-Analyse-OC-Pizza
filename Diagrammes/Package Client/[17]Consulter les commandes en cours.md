# Cas  n°17

**Nom:** Consulter Commandes en cours (package « Client »)<br>
**Acteurs(s):** Client<br>
**Description succincte:** La consultation des commandes passées doit être possible pour l'utilisateur <br>
**Auteur:** A Gomes<br>
**Date(s):** 24/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être authentifié en tant que client( Cas d’utilisation « S’identifier »)<br>
**Démarrage:** L’utilisateur s'est connecté et a demandé la consultation des commandes passées<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système affiche une page contenant la liste des commandes passées.

**Les scénarios alternatifs**<br>
- Aucun

**Scénario d'exception**<br>
1. En (1): Aucune commande n'a jamais été passée par le client, le système affiche "Aucune commande"

**Fin:** Scenario nominal : à l'étape 1, après affichage des commandes par le système<br>
**Post-conditions:** Aucun
