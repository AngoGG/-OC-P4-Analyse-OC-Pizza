# Cas  n°26

**Nom:** S'identifier<br>
**Acteurs(s):** N'importe quel utilisateur disposant d'un compte<br>
**Description succincte:** L'identification doit être possible pour l'utilisateur<br>
**Auteur:** A Gomes<br>
**Date(s):** 01/01/2020 (première rédaction)<br>
**Pré-conditions:** L'utilisateur s'est connecté au site<br>
**Démarrage:** L’utilisateur a demandé l'identification à son compte du site<br>

### **DESCRIPTION**

**Le scénario nominal**<br>
1. Le système demande le nom et le mot de passe de l'utilisateur
2. L'utilisateur remplis les informations de connexion
3. L'utilisateur valide les information
4. Le système vérifie les informations
5. Le système connecte l'utilisateur et affiche la page d'accueil de son interface

**Les scénarios alternatifs**<br>
1.  En (2): L'utilisateur annule la connexion et quitte l'écran

**Scénario d'exception**<br>
En (4): Lors de la validation, si les informations entrées par l'utilisateur sont erronées (compte inexistant ou mot de passe incorrect), le système redirige vers l'étape (1)

**Fin:** 
- Scénario nominal: à l'étape 5, sur décision de l'utilisateur
- Scénario alternatif: à l'étape 2 sur décision de l'utilisateur

**Post-conditions:** L'utilisateur est connecté et a accès à son compte