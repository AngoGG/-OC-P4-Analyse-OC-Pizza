# Cas  n°13

**Nom:** S'inscrire (package « Client »)<br>
**Acteurs(s):** Visiteur<br>
**Description succincte:** La création d'un compte doit être possible pour l'utilisateur<br>
**Auteur:** A Gomes<br>
**Date(s):** 26/12/2019 (première rédaction)<br>
**Pré-conditions:** L'utilisateur s'est connecté au site<br>
**Démarrage:** L’utilisateur a demandé l'inscription en tant que client du site<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1. Le système affiche un formulaire contenant les informations nécessaires à l'inscription
2. L'utilisateur remplis les informations
3. L'utilisateur valide le formulaire
4. Le système crée le compte
5. Le système rafraîchit l'affichage et propose la connection

**Les scénarios alternatifs**<br>
1.  En (2): L'utilisateur annule la création du compte et quitte l'écran
2.  En (3): L'utilisateur ne valide pas les modifications et quitte l'écran

**Scénario d'exception**<br>
En (3): Lors de la validation, si l'utilisateur n'a pas rempli certaines informations obligatoire, la validation ne se fait pas et un message s'affiche pour lui demander de le faire

**Fin:** 
- Scénario nominal: à l'étape 5, sur décision de l'utilisateur
- Scénario alternatif: à l'étape 2, 3 sur décision de l'utilisateur

**Post-conditions:** Le compte est bien crée, l'utilisateur peut se connecter sur son compte