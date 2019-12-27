# Cas  n°21

**Nom:** Payer en ligne (package « Client »)<br>
**Acteurs(s):** Client<br>
**Description succincte:** Le paiement d'une commande en ligne doit être possible pour l'utilisateur<br>
**Auteur:** A Gomes<br>
**Date(s):** 26/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit être sur la page de paiement de la commande<br>
**Démarrage:** L’utilisateur a sélectionné le paiement en ligne<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1. Le système lance une interface avec le système de paiement par carte bancaire
2. L'utilisateur valide son paiement en ligne
3. Le système valide le paiement et retourne sur la page de la commande ( Cas d'utilisateur « Passer une commande »)

**Les scénarios alternatifs**<br>
1.  En (2): L'utilisateur annule le paiement

**Scénario d'exception**<br>
1.  En (2): Erreur lors du Paiement, celui ci est refusé

**Fin:** 
- Scenario nominal : à l'étape 3 sur décision de l’utilisateur
- Scénario alternatif: à l'étape 2 sur décision de l'utilisateur
- Scénario d'exception: à l'étape 2, le paiement est refusé

**Post-conditions:** L'utilisateur est mis au courant de la prise en compte du paiement, un message de confirmation est visible sur la page de Paiement
