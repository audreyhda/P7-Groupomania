# P7-Groupomania

Créez un réseau social d’entreprise

Mis à jour le mardi 7 septembre 2021

Ce projet a récemment été mis à jour. Si vous passez votre soutenance à partir du 1er Octobre 2021, vous devez absolument utiliser un framework front-end pour développer votre projet (voir détails plus bas). Pour toute soutenance avant cette date, une tolérance sera appliquée selon le temps qu'il vous reste pour terminer votre formation. Vous pouvez donc coder votre site sans framework. Cependant, l'utilisation d'un framework front-end est fortement recommandée puisque c'est une grande valeur ajoutée sur votre CV.

Scénario
Vous êtes développeur depuis plus d'un an chez CONNECT-E, une petite agence web regroupant une douzaine d'employés.

Votre directrice, Stéphanie, invite toute l'agence à prendre un verre pour célébrer une bonne nouvelle ! Elle vient de signer un contrat pour un nouveau projet ambitieux ! 🥂

Le client en question est Groupomania, un groupe spécialisé dans la grande distribution et l'un des plus fidèles clients de l'agence.


Le projet consiste à construire un réseau social interne pour les employés de Groupomania. Le but de cet outil est de faciliter les interactions entre collègues. Le département RH de Groupomania a laissé libre cours à son imagination pour les fonctionnalités du réseau et a imaginé plusieurs briques pour favoriser les échanges entre collègues.

Stéphanie vous envoie un message via l’outil de messagerie instantanée de l’entreprise.


> Stéphanie : Hello, comme tu le sais, nous démarrons un très beau projet avec Groupomania et j’aimerais que ce soit toi qui gères la partie développement.
> Stéphanie : Groupomania a déjà réfléchi aux fonctionnalités à intégrer dans le réseau social. Il s’agit en fait de produits déjà existants :
9GAG - ils veulent que les employés partagent et commentent les gifs avec d'autres collègues ;
Reddit - ils veulent que les employés écrivent et/ou partagent des articles avec leurs collègues sur des sujets qui les intéressent. 
> Vous : Super, je prends note. Est-ce qu’ils t’ont fourni les spécifications fonctionnelles ?
> Stéphanie : Oui, je te les envoie par mail tout de suite :)
La conversation entre Sophie et vous
Quelques minutes plus tard, vous recevez un mail de Stéphanie.

 

De : Stéphanie R

À : Moi

Lancement projet Groupomania

--------------------------------------------------------------------------------------------

Bonjour,

Comme convenu, voici les spécifications fonctionnelles. Tu trouveras également les logos de l’organisation pour l’habillage du site.

Par ailleurs, Groupomania et moi avons convenu que l’un des employés du groupe testera un MVP du produit, avec une seule des deux fonctionnalités proposées.

Cela nous permettra de nous assurer que nous répondons à leurs attentes.

Après plusieurs réunions avec Groupomania, il semble que les paramètres du projet changent régulièrement, je pense qu’une organisation “agile” serait plus adaptée pour s’adapter aux besoins du client au fur et à mesure des commentaires et affiner l’application au fil de l’eau.

Je suis à ta disposition pour toute question.

Stéphanie

De : Moi

À : Stéphanie R

Re : Lancement projet Groupomania

-----------------------------------------------------------------------------

Merci Stéphanie pour toutes ces informations !

Si je comprends bien, je dois fournir une première version d’une des fonctionnalités proposées par Groupomania et j’ai carte blanche concernant la forme que cela va prendre ?

Merci pour ces précisions.

De : Stéphanie R

À : Moi

Re : re : Lancement projet Groupomania

--------------------------------------------------------------------------

Oui, c’est ça !

La seule contrainte est que le client utilise une base de données relationnelles qui se manipule avec le langage SQL pour le stockage de données. Il faudra donc en tenir compte lorsque tu construiras ton application. Tu devras t’assurer que l’utilisateur puisse requêter les données requises depuis SQL et puisse soumettre ces changements à la base de données SQL. Les données de connexion doivent également être sécurisées. 

Merci.

Stéphanie

De : Moi

À : Stéphanie R


Re : re : re : Lancement projet Groupomania

----------------------------------------------------------------------------------

Ah oui, je vois ! Peux-tu me préciser quelles tâches entrent dans le périmètre de ma mission ?

Merci

De : Stéphanie R

À : Moi

Re : re : re : re : Lancement projet Groupomania

----------------------------------------------------------------------------------------

Bien sûr. Tu vas devoir :

choisir la fonctionnalité que tu vas développer,
estimer le temps que tu passeras sur le développement de chaque fonctionnalité,
développer la première version de l'application.
Deux dernières choses, tu devras faire en sorte que la web app puisse se connecter et se déconnecter à l’application et que la session de l’utilisateur persiste pendant qu’il est connecté.

Pour ce projet, il faut que tu utilises un framework Front-End. Tu peux utiliser celui que tu préfères (React, Vue, Angular, Ember, Meteor, Aurelia...). Par contre, le projet doit être codé en Javascript, donc n'utilise pas le framework Symfony par exemple. Enfin, tes pages devront respecter les standards WCAG.

Bon courage et à dispo si besoin :)
Stéphanie


Avec tous ces éléments en tête, vous vous attaquez à la réalisation de ce beau projet.


Compétences évaluées:

Personnaliser le contenu envoyé à un client web

Authentifier un utilisateur et maintenir sa session

Gérer un stockage de données à l'aide de SQL

Implémenter un stockage de données sécurisé en utilisant SQL
