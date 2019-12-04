# Fiche descriptive du cas d’utilisation « Consulter catalogue produits »

## Identification
|         |            |
| ------------- |-------------|
| **Numéro**    | 1 |
| **Nom**     | Consulter Commandes à livrer (package « Livreur »)      |
| **Description succincte** | La consultation des commandes en état « A livrer » doit être possible pour les livreurs de la pizzéria    |
| **Auteur** | A Gomes    |
| **Date(s)** | 02/12/2019 (première rédaction)   |
| **Pré-conditions** | L’utilisateur doit être authentifié en tant Livreur    |
| **Démarrage** | L’utilisateur a demandé la page ‘Consultation Commandes à livrer    |
	
## Le dialogue : le scénario nominal
| Étape du scénario        | Utilisateur | Système  |
| :-------------: |:-------------:| -----|
| 1.    |  | Il affiche une page contenant la liste les catégories de produits. |
| 2.      | Il sélectionne une des commandes à livrer.	      |    |
| 3. |       |    Il recherche les informations sur la commande sélectionnée. |
| 4. |       |    Il affiche les informations sur la commande sélectionnée |
| 5. | Il quitte la description détaillée de la commande.      |     |
| 6. |      |    Il retourne à l’affichage de l’écran d’accueil |
 

## Le dialogue : les scénarios alternatifs
| Étape du scénario | Utilisateur | Système  |
| :-------------: |:-------------:| -----|
| 1.     | Il affiche une page contenant la liste les catégories de produits. |  |
| 2.a    | Il peut décider de quitter la consultation de la catégorie choisie | 	  |
| 2.b    | Il peut décider de quitter la consultation du catalogue | 	  |
| 5.a    | Il peut décider de quitter la consultation des produits de la catégorie | 	  |
| 5.b    | Il peut décider de quitter la consultation des produits de la catégorie | 	  |
| 5.b    | Il peut décider de quitter la consultation du catalogue | 	  |
| 7.a    | Il peut décider de quitter la consultation des produits de la catégorie | 	  |
| 7.b    | Il peut décider de quitter la consultation du catalogue  |  |
| Fin    | Scénario nominal	Système : aux points 2, 5 ou 7, sur décision de l’utilisateur | |
**Post-conditions**	Aucun

## Compléments
|         |            |
| ------------- |-------------|
| Ergonomie    | L’affichage des produits d’une catégorie devra se faire par groupe de 15 produits. Toutefois, afin d’éviter à l’utilisateur d’avoir à demander trop de pages, il devra être possible de choisir des pages avec 30, 45 ou 60 produits. |
| Performance attendue     | La recherche des produits, après sélection de la catégorie, doit se faire de façon à afficher la page des produits en moins de 10 secondes.      |
| Problèmes non résolus	 | Nous avons fait la description basée sur l’information que les produits appartiennent à une catégorie. Est-ce qu’il existe des sous-catégories ?<br> Si tel est le cas, la description devra être revue. <br> Est-ce que la consultation du catalogue doit être possible uniquement par catégorie ou est-ce qu’on doit prévoir d’autres critères de recherche de produits ? <br> Doit-on prévoir un affichage trié sur des critères choisis par l’utilisateur (par exemple : par tranche de prix, par disponibilité, etc) ?  |

