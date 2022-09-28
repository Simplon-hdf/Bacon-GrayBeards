# Bacon Graybeards
Brief CDA "Pire2Pire"

## Table des matières
1. [Intro](#Intro)
2. [Authentification et Mots de passe](#authentification-et-mots-de-passe)  
   2.1. [Définition](#définition)  
   2.2. [Authentification simple & multifacteurs](#authentification-simple-et-multifacteurs)  
   2.3. [Différents facteurs d'authentification](#différents-facteurs-dauthentification)  
   2.4. [Quelques recommandations d'authentification](#quelques-recommandations-concernant-lauthentification)

##	**Intro**
------------------------------------
##	**Authentification et Mots de passe**

###	**Définition**
Il s'agit d'un processus de vérification de l'identité. Ce processus peut-être "simple" ou "multifacteurs".
L’authentification est un mécanisme faisant intervenir deux entités distinctes : un prouveur et un vérifieur :

 - Le prouveur cherche à prouver son identité au vérifieur.

 - Le vérifieur doit être capable de s’assurer de la validité de l’identité du prouveur. 

###	**Authentification simple & multifacteurs**
- **Authentification simple**
    - Il s'agit d'une authentification basique avec le couple utilisateur/mot de passe.
    Le mot de passe peut-être chiffré de manière cryptographique, donnant lieu à une authentification dite "robuste".
- **Authentification multifacteurs**
    - Authentification mettant en œuvre plusieurs facteurs d’authentification appartenant à des types différents.

###	**Différents facteurs d'authentification**
- **Facteur de connaissance**
    - Il s’agit d’une connaissance devant être mémorisée telle qu’une phrase de passe, un mot de passe, un code pin etc...
- **Facteur de possession**
    - Il s’agit d’un élément secret non mémorisable contenu dans un objet physique qui idéalement protège cet élément de toute extraction, tel qu’une carte à puce, un token, un téléphone etc...
- **Facteur inhérent**
    - Il s’agit d’une caractéristique physique intrinsèquement liée à une personne et indissociable de la personne elle-même, telle qu’une caractéristique biologique (ADN), morphologique (empreinte digitale, empreinte rétinienne) etc...


###	**Quelques recommandations concernant l'authentification**
- Mener une analyse de risques lors de la mise en place de moyens d'authentification.
- Privilégier une authentification multifacteurs.
- Privilégier une authentification sur des facteurs de possession.
- Adapter la robustesse des mots de passe à son contexte d'utilisation.
- Utiliser un coffre-fort de mots de passe.

---------------------
