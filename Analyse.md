# Analyse Besoin et identification acteurs et tâches

## Acteurs

- Responsable
- Pizzaiolos
- Livreurs
- Client
- Système bancaire
- Equipe Nationale

**Questions**<br>
- Aucune


<img src = "Diagrammes/Diagramme_contexte.jpg" title = "Diagramme de contexte">

## Packages et Tâches

### Package Interface Equipe Nationale

<img src = "Diagrammes/Diagramme_packages.jpg" title = "Diagramme de contexte">

### Package Equipe Nationale

- **Equipe Nationale doit pouvoir**
  - Se connecter
    - Consulter les commandes en cours peut importe leur état, y compris les commandes livrées
    - Consulter l'état du stock d'ingrédients
    - Gérer les droits utilisateurs (administration)

<img src = "Diagrammes/Package Equipe Nationale/Cas d'utilisation Equipe Nationale.jpg" title = "Cas d'utilisation Equipe Nationale">

### Package Interface Equipe Pizzéria

- **Responsable doit pouvoir**
  - Se connecter
    - Consulter les commandes en cours peut importe leur état
    - Modifier l'état d'une commande ('en cours de préparation, 'à traiter')
    - Consulter l'Aide-mémoire de recettes de pizza
    - Consulter l'état du stock d'ingrédients
    - Gérer les droits utilisateurs (administration)
- **Pizzaiolo doit pouvoir**
  - Se connecter
  - Consulter les commandes à traiter
  - Modifier l'état d'une commande ('en cours de préparation, 'à traiter')
  - Consulter l'Aide-mémoire de recettes de pizza
  - Consulter l'état du stock d'ingrédient?

<img src = "Diagrammes/Package Pizzeria/Cas d'utilisation Pizzeria.jpg" title = "Cas d'utilisation Equipe Pizzéria">

### Package Interface Livreur

- **Livreur doit pouvoir**
  - Se connecter
  - Consulter commandes à livrer
  - Changer état commander en "Livrée"
  - Récupérer Paiement Commande

<img src = "Diagrammes/Package Livreur/Cas d'utilisation Livreur.jpg" title = "Cas d'utilisation Livreur">

<img src = "Diagrammes/Package Livreur/Cycle ommande Livreur.jpg" title = "Cycle Commande Livreur">

### Package Interface Client

- **Visiteur doit pouvoir**
  - Consulter catalogue recettes
  - S'incrire
  - S'identifier

- **Client doit pouvoir**
  - Sélectionner produits
    - Valider commande
    - Choisir mode  paiement
      - Payer en ligne
      - Payer à la livraison
    - Vérifier état commande
      - Modifier commande tant que pas "en préparation"
      - Annuler commande tant que pas "en préparation"

<img src = "Diagrammes/Package Client/Cas d'utilisation Client.jpg" title = "Cas d'utilisation Client">
<img src = "Diagrammes/Package Client/Cycle commande Client.jpg" title = "Cycle Commande Client">
