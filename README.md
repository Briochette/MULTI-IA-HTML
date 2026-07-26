# MULTI-IA-HTML
HTML Unique permettant d'utiliser plusieurs modèles IA en local en passant par l'API.
Mon site IA est une application de chatbot entièrement réalisée en HTML/CSS/JavaScript, qui fonctionne directement dans le navigateur sans nécessiter de backend. Le code est contenu dans un seul fichier HTML, ce qui facilite son déploiement et son partage.

Fonctionnement et caractéristiques principales :

• Multiplateforme et multi-fournisseurs  
 – Intègre plusieurs API d’IA (OpenAI, Anthropic, Google et Mistral)  
 – Permet de choisir le fournisseur et le modèle via un sélecteur (avec regroupement par fournisseur)  
 – Supporte l’auto-routage pour envoyer automatiquement les messages au modèle le mieux adapté

• Interface et expérience utilisateur  
 – Interface au design sombre (« teal/anthracite ») avec une mise en page moderne et responsive  
 – Gestion des conversations avec historique, renommage, épinglage et recherche interne  
 – Possibilité de comparer les réponses de deux IA côte à côte

• Personnalisation et options  
 – Enregistrement des clés API et des configurations directement dans le localStorage (les données restent sur l’appareil)  
 – Options de personnalisation de l’avatar pour l’IA et l’utilisateur  
 – Réglages pour ajuster l’historique envoyé (nombre de messages et estimation des tokens de sortie)  
 – Option de prompt système personnalisé, avec mise en cache pour les appels Anthropic  
 – Possibilité d’activer/desactiver certains outils (réflexion approfondie, mode live de streaming, recherche web et génération d’image via DALL·E 3)

• Chargement de fichiers et glisser-déposer  
 – Supporte l’ajout de fichiers et de dossiers (images, textes, code…) en les glissant directement sur la page  
 – Les fichiers sont intégrés dans le prompt de l’IA ou affichés en tant que pièces jointes dans la conversation

• Streaming et live mode  
 – Possibilité d’afficher les réponses au fur et à mesure grâce au streaming (mode live)  
 – Affichage en direct des bulles de réponse et de la réflexion (si activé) pour une expérience interactive  

Fonctionnement technique :

• L’application est entièrement front-end – les conversations et les clés API sont stockées dans le localStorage du navigateur, garantissant ainsi que les données sensibles ne quittent jamais l’appareil.  
• Le code combine un style CSS importé (avec des polices Google) et du JavaScript modulaire (même dans un seul fichier) pour gérer l’interface, la logique métier (gestion de conversations, appels API, streaming…) et la personnalisation.  
• Des fonctions utilitaires (gestion des dates, escape HTML, rendu Markdown léger, etc.) permettent un affichage clair des messages et des détails d’utilisation (tokens, coût estimé, latence…).  
• Une gestion avancée du drag & drop permet d’ajouter des fichiers ou dossiers entiers à la conversation en toute simplicité.

En résumé, Mon IA est une solution complète, facilement configurable et personnalisable, pour tester et utiliser divers modèles d’IA directement depuis le navigateur, avec une interface moderne et des options avancées (streaming, fichiers, auto-routage) adaptées tant aux développeurs qu’aux utilisateurs finaux.
