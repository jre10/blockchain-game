---
description: >-
  Rappels des points-clés à connaître pour bien apprécier l'application et le
  jeu. Ces points-clés ont été introduits dans la formation DeFi
  d'Acadee-Formation.
---

# Rappels sur la blockchain et les tokens non-fongibles

> Ce rappel des points constitue le minimum de connaissances à disposer pour bien appréhender l'application et le jeu proposé dans ce document.
>
> Pour plus d'information sur la formation DeFi : [cliquer ici](https://www.acadee-formation.com/nos-formations/formation-la-finance-decentralisee-defi-ethique/).

## Quatre points-clés à retenir pour bien pratiquer <a href="bkmrk-quatre-points-cl-c3-a9s-c3-a0" id="bkmrk-quatre-points-cl-c3-a9s-c3-a0"></a>

1. L'identification par `clés uniques versus` les `mots de passe`
2. Les quatre usages de la blockchain et les trois retenus par le framework de la société Spuro
3. L'`authentification` d'un document versus la `sauvegarde` d'un document
4. Le `stockage` des documents

Ces quatre points sont détaillés ci-après.

### 1. L'identification par `clés uniques` versus le `mot de passe` <a href="bkmrk-2.-les-cl-c3-a9s-uniques" id="bkmrk-2.-les-cl-c3-a9s-uniques"></a>

Comme toute application, il est nécessaire de s’identifier. Dans le cas de la blockchain, l’identification est particulière dans la mesure celle-ci sera intégrée à votre enregistrement dans le registre. Cette identification passe donc par un système d'une clé unique. Celle ne devra pas être ni perdue, ni connue.

Vous êtes certainement habituer à l'identification par nom d'utilisateur et un mot de passe. Pour mieux comprendre l'identification par clé, regardons la différence entre ces deux méthodes.

Un `mot de passe` est stocké sur le serveur qu'il permet de visiter. Le mot de passe peut être restitué par un mécanisme plus ou moins confidentiel que l'utilisateur peut facilement activer : en cliquant sur un bouton comme : `Mot de passe perdu ?` .

Ce n'est pas le cas dans la blockchain où il n'y a pas de serveur. La blockchain est basée sur le principe des `registres distribués`. C'est un "code" très complexe qui vous identifie et qui va circuler avec votre information. Pour retrouver cette information ou en afficher la paternité, vous devez entrer une `clé unique`.

Si la clé unique est perdue, il n'est plus possible de retrouver les enregistrements considérés. Pourtant, ces informations resteront à jamais dans la blockchain. À Noter que personne d'autre pourra accéder à vos enregistrement en essayant de deviner le code au regard de sa complexité.

Important : Si vous avez perdu votre clé unique sur la blockchain Acadee-Formation, contacter votre administrateur.

Note : Les plateformes Spuro, dont est issue la plateforme Acadee-Formation, ont retenu le principe des `clés uniques`. Les plateformes Spuro n'utilisent pas le système d'authentification avec des `clés publiques` et des `clés privées`.

Il est recommandé d'utiliser un `manager de mots de passe et/ou de clés numériques`. Le navigateur `Firefox` possède nativement cette fonction ou des applications open source comme `BitWarden` proposent des extensions pour les navigateurs.

Il est possible aussi d'utiliser des `wallets`, des porte-monnaies numériques généralement sous la forme d'une clé USB.

### 2. Usages de la blockchain et ceux proposés par la plateforme Spuro <a href="bkmrk-1.-usages-de-la-bloc" id="bkmrk-1.-usages-de-la-bloc"></a>

Dans la pratique, la blockchain propose 4 types d'usage.

* Ledger : Authentification de documents
* SmartContracts : Contrats intelligents
* Token : Titulaire d'un actif numérique représentant un partie d'un bien réel.
* Crypto :\_monnaie

Dessin Spuro

En dehors des applications pour la crypto-monnaie (Bitcoin, autres) qui nécessitent des ressources et une gouvernance particulière, les **trois autres usages sont accessibles par les plateformes Spuro** dont fait partie la blockchain Acadee-Formation.

Pour plus d'information, visiter le site : [http://spuro.eu/](http://spuro.eu)

### 3. L'authentification d'un document et la sauvegarde de ce document <a href="bkmrk-3.-l-27authentificatio" id="bkmrk-3.-l-27authentificatio"></a>

Il important de retenir que la blockchain n'a pas été conçue pour stocker les documents. La blockchain a été conçue pour identifier, et cela de manière infalsifiable, un document numérique, quel que soit sont format : texte, tableur, photo, dessin, code, sauvegarde d'application, autres).

Ceci est rendu possible grâce à un processus de `hachage` du document concerné. Le résultat de cette authentification est un hash, une longue suite aléatoire de caractères, incompréhensible, qu'il conviendra de conserver avec le document.

Pour démontrer l'authenticité du document, il sera nécessaire de rapprocher les deux éléments : le document lui-même, dans la même forme, et le hash obtenu lors de l'authentification.

Le hash du document est publique. Pour rapprocher ce document avec le propriétaire, il faut faire appel à une clé d'authentification, principe vu plus haut.

### 4. Le stockage des documents <a href="bkmrk-le-stockage-des-docu" id="bkmrk-le-stockage-des-docu"></a>

Comme évoqué plus haut, la blockchain ne sauvegarde pas les documents authentifiés.

Toutefois, les plateformes de la blockchain comme celle de Spuro propose aussi une fonction additionnelle de stockage des documents. Il est important de noter que cette fonction de stockage n'est pas inhérente à la blockchain et qu'il conviendra d'en vérifier le bon fonctionnement et/ou de conserver localement une copie ou l'originale de ce document.

* Cela n'existe plus avec la v19
* en `interne`, c'est à dire sur la plateforme elle-même,
* en `externe`, sur un serveur externe, généralement celui de l'utilisateur.
