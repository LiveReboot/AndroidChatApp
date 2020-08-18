# AndroidChatApp
Développement d'une application de communication sur android qui utilise les services de firebase.

## Présentation
Moi c'est Simon, je suis développeur depuis 10 ans maintenant. Vous retrouverez sur **LiveReboot**, les projets qu'il me semble intéressant de développer en public.

* Sur GitHub : https://github.com/LiveReboot/
Vous retrouverez les codes des projets que je vous propose.
* Sur Youtube : https://www.youtube.com/channel/UCJeBZH4HUF79p2oDImZHNgA
Je met en ligne les tutoriels vidéos correspondants aux projets. Vous me verrez coder en direct les projets. Dans ces vidéos j'essaye d'expliquer au mieux tout ce que je fais pour vous permettre de comprendre et de refaire ultérieurement dans vos projets.
* Sur le Site web : https://livereboot.fr
Vous retrouverez des articles en lien avec les projets, les liens vers la documentation, des explications supplémentaires, des exemples d'utilisations ...
* Sur Twitter : https://twitter.com/LiveRebootFr
Suivez moi sur twitter pour être informé des mises à jour, de l'ajout de nouveaux projets, communiquer avec moi ...

## Introduction

Dans ce projet, je vais développer de A à Z une application de t'chat sécurisé.
J'ai vu beaucoup de tutoriels déjà en ligne sur le même sujet, mais plusieurs choses me dérangent sur les tutos que j'ai suivi :

* La plus part était en anglais.
* Beaucoup étaient incomplets (oublis de certaines fonctionnalités critiques, non utilisable en production, gestion de la mémoire deffectueuse ...)
* Aucun ne proposait un système sécurisé avec chiffrage des messages

## Le projet

Le projet est donc de développer une application ANDROID (je ferai la même en IOS si je trouve le temps et que cela vous intéresse).
Cette application proposera un Chat sécurisé (du genre de Whatsapp). Pour cela, j'utiliserai **Android Studio** pour développer l'application. Nous nous reposerons sur les services de Firebase pour gagner du temps.

## Les fonctionnalités

Les fonctionnalités seront assez basiques :
- Authentification
  - Inscription
  - Mot de passe oublié
  - Connexion
  - Déconnexion
  - Supprimer mon compte
- Profil utilisateur  
  - Création d'un profil complet
  - Modification des informations
  - Sécurité des informations
- Gestion des contacts
  - Rechercher un utilisateur de l'application
  - Gestion des demandes en amis (demander, accepter, refuser, bloquer, supprimer)
  - Rechercher dans le répertoire de l'utilisateur
- Envoyer un message
  - Envoyer à un amis (personnel)
  - Créer un salon de discussion multi-utilisateur (public / privé)
  - Gestion des droits sur les salons de discussion (auteur, admin, rédacteur, lecteur)
  - Chiffrage RSA des messages
  - Création de salons à thème
- Réception de message
  - Notification à la réception
  - Gestion des messages non lus
  - Notifications de lectures
- Base de données SQLite
  - Alléger les accès aux serveurs
  - Enregistrement des clés RSA
  - Enregistrement des messages
  - Outils de recherche dans les messages
  - Envois de message 'Hors Ligne'
- Sécurisation de la base de données Firebase
- Publication sur le PlayStore


  

