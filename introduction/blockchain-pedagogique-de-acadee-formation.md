---
description: >-
  Présentation générale de la plateforme blockchain de Acadee-Formation ainsi
  que des recommandation pour le nom des comptes. Les écrans présenté dans cette
  version 0.1 sont ceux de version de la platef
---

# Connexion à la plateforme Acadee-Formation

L'accès à une blockchain se fait uniquement par un navigateur, sur ordinateur, tablette ou smartphone.

L’accès à la blockchain pédagogique Acadee-Formation se fait par une URL qui est remise aux auditeurs de la formation DeFi par Acadee-Formation.

À venir, un lien direct à la blockchain pédagogique Acadee-Formation à partir de votre espace de formation.

Un accès par `nom d'utilisateur` et `clé unique` vous sera remis

A noter que vous n'aurez pas un mot de passe (récupérable) à entrer mais votre `clé unique`.

## Les nodes <a href="bkmrk-les-nodes" id="bkmrk-les-nodes"></a>

{% hint style="info" %}
Ce qui suit peut apparaître trop technique et relever de l'administration du système. Nous pensons que cela fait parti de la "culture blockchain" à connaître pour une bonne compréhension des processus. Nous avons tenté d'être le plus pratique possible et orienté utilisateur.
{% endhint %}

Une blockchain peut être décrite comme un ensemble de serveurs, appelés `nodes` (des nœuds), qui "fédèrent" des groupes d'utilisateurs d'une blockchain dédiée.

Par exemple, des groupes de spéculateurs sur des bouteilles de vin Pétrus à Troyes, Brest, Nancy, voire même à Saint-André-les-vergers qui se sont inscrits sur une même blockchain. Chacun s'inscrivant sur son "node". À noter qu'une personne de Brest peut s'inscrire sur le node de Troyes.

Ces nodes sont des serveurs où l'on installe rigoureusement le même programme. Dans le cas de la blockchain Acadee-Formation, ce code est créé à travers un framework développé par la société Spuro.

Il est important de savoir qu'il existe des mécanismes de sécurité qui vont :

* isoler des nodes "suspects", comme un node attaqués par des hackers malveillants,
* isoler des nodes où le code ne serait par identique à la dernière version, problème de mise à jour, maintenance,
* vérifier que les informations dans les `registres` sont bien identiques sur tous les nodes d'une même blockchain.

A tout instant, l'administrateur de la blockchain peut faire ces vérifications.

À noter que l'installation d'un node requiert un serveur avec beaucoup de ressources et une expertise pour son installation et sa gestion. Juste pour préciser qu'un node ne s'installe pas comme une application mobile sur un smartphone.

Comme cela est suffisant pour ce jeu pédagogique, la blockchain pédagogique Acadee-Formation dispose que d'un seul node.

## Navigation dans la plateforme <a href="bkmrk-cete-blockchain-comp" id="bkmrk-cete-blockchain-comp"></a>

Les chapitres suivants détaillent les navigations sur la plateforme. Le présent chapitre a pour but de vous familiariser avec cette plateforme afin de mieux intégrer "mentalement" son interface.

### Page d'accueil <a href="bkmrk-page-d-27accueil" id="bkmrk-page-d-27accueil"></a>

Remarque : la version au 12/10/2021. 

![Noter le menu de gauche. Dans l'en-tête, les nom du connecté et du nom du node. En bas à droite, la version et Déconnexion](<../.gitbook/assets/image (3) (1).png>)



### L'organisation de la plateforme <a href="bkmrk-l-27organisation-de-la" id="bkmrk-l-27organisation-de-la"></a>

La plateforme Acadee-Formation dispose de plusieurs sections identifiable par les accès dans le menu de gauche :

1. **La partie `Administration`**. Partie technique gérée par l'administrateur. Note : Pour les autres rôles, le sous-menu est visible mais les commandes ne sont pas utilisable. Si vous cliquez dessus, un message vous avertit que vous n'avez pas l'accès.
2. **La partie `Sécurité`**. Accessible au gestionnaire, permet de vérifier l'intégrité des registres et codes sources.
3. **La partie `SmartContracts`**. Partie qui permet de réaliser des smarts contracts, des règles de gestions entre tous les membres, quelque soit le nodes.
4. **La partie `Fonctionnalités`**, pour des fonctions transversales à plusieurs utilisations comme
   1. Tracer mon document
   2. Invalider mon compte
   3. **Gestion de la preuve** (authenticité de document et du propriétaire, un Ledgerofproof)
5. **La partie `Tokens`**, pour la tokénisation d'un bien et les échanges de ces tokens
6. Et enfin la **partie `Applications`**. Présentes ou pas selon la configuration. Exemples :thumbsup:
   1.  L'application **Suffrage**. Pour des votes.
   2. **Ekoco**, une application qui "protège la planète" et qui "récompensera de vos efforts en tokens ". [http://www.ekoco.fr](http://www.ekoco.fr)

Ces applications sont créées et développées par la société Spuro ou des éditeurs indépendants.

_Rappel : dans la version 0.1, c'est en tant que gestionnaire que vous effectuerez le parcours._



Pour plus d'information sur le fonctionnement de la plateforme, se référer à la documentation de l'éditeur Spuro. 



## Recommandation pour le nommage des différents comptes <a href="nommage_compte" id="nommage_compte"></a>

Nous vous invitons à respecter ces règles de nommages des utilisateurs : **votre trigramme précédé du type de compte séparé pas un tiret**.

🏴 Le nom d'utilisateur, et bien sûr aussi le mot de passe, sont sensibles aux majuscules/minuscules.

* Pour utilisateur : **u-xxx**, exemple pour le trigramme jre (**J**osé **Re**lland) : u-jre
* Pour gestionnaire : **g-xxx**, exemple pour le trigramme jre : g-jre
* Pour le validateur : **v-xxx**, exemple pour le trigramme jre : v-jre
* Pour l'administrateur : **a-xxx**, exemple pour le trigramme jre : a-jre

Dans la version 0.1, un même courriel pourra être utilisé. 

Une nouvelle fois, nous vous recommandons de bien conserver votre **clé unique** et la** clé de sauvegarde**. Vous recevez cette dernière par courriel.
