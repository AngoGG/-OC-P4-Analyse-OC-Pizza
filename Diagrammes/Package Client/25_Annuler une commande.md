# Cas  n°25

**Nom:** Annuler une commande (package « Client »)<br>
**Acteurs(s):** Client<br>
**Description succincte:** L'annulation d'une commande qui n'est pas encore en cours de préparation doit être possible pour l'utilisateur<br>
**Auteur:** A Gomes<br>
**Date(s):** 26/12/2019 (première rédaction)<br>
**Pré-conditions:** L’utilisateur doit se trouver sur la fiche d'une commande qui n'est pas en cours de préparation<br>
**Démarrage:** L’utilisateur a demandé l'annulation de la commande<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1.	Le système demande la confirmation de l'annulation de la commande
2.	L’utilisateur valide l'annulation
4.	Le système supprime la commande (ou la commande passe en état "Annulée").
5.	Le système redirige vers la liste des commandes

**Les scénarios alternatifs**<br>
1.  En (2): L’utilisateur annule la suppression

**Scénario d'exception**<br>
- Aucun

**Fin:** 
- Scenario nominal : à l'étape 5 sur décision de l’utilisateur
- Scénario alternatif: à étape 2  sur décision de l'utilisateur

**Post-conditions:** La commande annulée est bien mise à jour et visible pour le client avec un état « Annulée » (Cas d'utilisation « Consulter les commandes en cours ») ainsi que pour la pizzéria (Cas d'utilisation « Consulter Commande »)
