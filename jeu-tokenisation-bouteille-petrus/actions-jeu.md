---
description: >-
  Version Communauté du jeu. Nous vous invitons à suivre méthodiquement les
  actions ci-dessous. Au regard de l'évolution permanente de la plateforme, des
  écrans peuvent être différents.
---

# Procédure de tokénisation d'une bouteille de Pétrus

## 1. Création du rôle de gestionnaire

> Dans la présente version 0.1, le joueur aura le profil de Gestionnaire. Dans la réalité, il a le rôle d'utilisateur. Le rôle de gestionnaire est normalement attribué uniquement aux animateurs de la blockchain : entreprises, communautés.

Pour que le joueur obtienne un profil de Gestionnaire, il existe de cas : 

1. **Acadee-Formation déclare votre profil Gestionnaire**. 
2. Vous **disposez déjà du profil d'administrateur, dans ce cas, il vous sera possible de créer un profil Gestionnaire**. 

Dans les deux cas, se renseigner auprès de Samuel d'Acadee-Formation.

{% tabs %}
{% tab title="Créé par Acadee-Formation" %}
Pour obtenir un profil de Gestionnaire, merci de contacter Samuel de Acadee-Formation en indiquant : **une adresse de courriel**.

1. Vous recevrez par courriel un lien de création de compte Gestionnaire. Cliquer sur le lien `lien vers l'inscription` puis documenter les différents champs proposés.

![Documenter les différents champs puis créer votre compte Gestionnaire (Voir les règles de nommage de l'identifiant)](<../.gitbook/assets/image (4) (1) (1) (1).png>)

Confirmer le ou les écrans de sécurité.

2\. Vous recevez un second courriel de confirmation de la création de votre compte Gestionnaire. 

Ce courriel est très important car il contient le `code de récupération` et doit être conservé précieusement et secrètement. Ce code vous permet de récupérer votre clé unique.  

3\. À ce stade, retourner sur la page de connexion de la plateforme Blockchain Acadee-Formation et entrer vos nouveaux identifiant et clé unique.

L'écran apparaît de la manière suivante. À noter que sur la gauche, le sous-menu Tokens apparaît complètement. C'est dans cet menu que nous 'allons jouer'.

![](<../.gitbook/assets/image (5) (1) (1) (1).png>)


{% endtab %}

{% tab title="À partir du rôle d'administrateur" %}
Vous devez disposer des droits d'administrateur. Se renseigner auprès de Samuel.

Dans le menu Administration, cliquer sur \`Créer un gestionnaire\`.

L'écran vous propose d'indiquer votre courriel puis de lancer le processus.

À ce stade, le processus doit être poursuivi comme au cas \`Créé par Acadee-Formation\` du premier onglet.
{% endtab %}
{% endtabs %}

### 2. Connaître mon empreinte

Pour réaliser des transactions en STCs, en fait en tokens, il est nécessaire de connaître son empreinte de compte et l'empreinte du destinataire. 

{% hint style="danger" %}
Cette empreinte n'est pas confidentielle, sans pour autant être publique, et elle ne doit pas être confondu avec sa clé unique.
{% endhint %}

Aller dans le menu Tokens > Connaître mon empreinte. Entrer vos identifiants puis cliquer sur \`Générer mon empreinte\`.

Celle-ci va apparaître en bas de cette même fenêtre.

Vous pouvez sauvegarder cette empreinte, cette suite de chiffres et lettres, par un copier-coller. 

### 3. Mon solde de STCs avec Mes tokens

Préalablement à toutes transactions de tokens, il est nécessaire de connaître votre solde de tokens. Au début du jeu, ce solde est à 0.

Pour vérifier le solde des tokens de son profil : menu Tokens > Mes Tokens.

Entrer à nouveau vos identifiants. Le solde à 0 apparaît dans l'écran. Si vous avez déjà chargé votre compte, un solde différent apparaîtra. 

![Écran indiquant le solde des tokens de votre profil. Les colonnes Types et Statut seront vues plus loin.](<../.gitbook/assets/image (6) (1) (1) (1) (1).png>)

{% hint style="warning" %}
Ce solde est toujours positif ou nul, il ne peut pas être négatif. Une opération de retrait de STCs supérieure au nombre des STCs possédés n'est pas possible.
{% endhint %}

#### Mes tokens fongibles et mes tokens non-fongibles.

Ce point est important. Comme vu dans la formation DéFi de Benjamin Faraggi sur la plateforme Acadee-Formation, nous avons : 

1. Les tokens fongibles, 
2. et les tokens non-fongibles, les NFTs. 

Exemple d'un solde d'un compte avec tokens fongibles et tokens non-fongibles.

![Solde des tokens d'un compte avec des tokens fongibles et des tokens non-fongibles (NFT)](<../.gitbook/assets/image (8) (1).png>)

**Les tokens fongibles** n'ont pas de "sous-jacents" uniques. Leur valeur est celle du marché. C'est donc une crypto-monnaie. Note : dans notre jeu, cela servira uniquement aux transactions, 1 token (ou STC) vaudra toujours 1 euro. Cette comparaison est fictive dans notre jeu.

**Les tokens non-fongibles (NFT) **ont un sous-jacent. ces tokens s'appuient sur la valeur d'un objet réel, unique et identifié. Ceci est important à comprendre car c'est la base de la "tokénisation" du monde réel. Nous espérons que si vous n'avez pas encore acquis ce concept exposé par Benjamin Faraggi, cela sera le cas à la fin de la pratique de ce jeu. Dans notre jeu, c'est une bouteille de Pétrus 1945 qui a été tokénisé. Détails ci-dessous.

{% hint style="info" %}
Dans notre jeu, la valeur sous-jacente de nos tokens est une des rares bouteilles de Pétrus 1945. Cette bouteille est bien été identifiée et est précieusement conservée dans un coffre. D'où des frais annuels de ce gardiennage. 

Comme la bouteille n'a pas été découpée physiquement en différents morceaux pour chaque 'propriétaire', elle a été **tokénisée**. C'est à dire que sa valeur a été partagée entre des bons de valeur, les tokens non-fongible, représentant une fraction de la valeur totale de la bouteille. Dans notre exemple, nous avons choisie 10 fractions soit un total de 10 tokens. La valeur "initiale" étant de 25 000 €, chaque bon, en fait un token, vaudra 2 500 €.

Autre point important à acquérir. Ces 10 tokens ont été identifiés individuellement dans la blockchain par un hash. Lors des transactions, il vous sera possible de vérifier, et nous vous conseillons de le faire, que vous **achetez bien un ou plusieurs des vrais tokens**. 

Si vous ne faisiez pas cette vérification et que les tokens proposés sont faux, vous auriez perdu vos tokens fongibles (en fait votre argent dans la réalité).

Autre point. Si vous perdez vos tokens non-fongibles de cette bouteille de Pétrus1945, ils seront perdus à jamais et pour tout le monde.
{% endhint %}

Ces rappels effectués, passons à la pratique. 

### 4. Disposer de STCs en début de jeu

Il est proposé de donner **à chaque participant 5 000 STCs comme "tokens fongibles"**. Ici, nous n’achetons pas des NFTs, nous distribuons "l'argent" pour le jeu. Ce montant peut varier en fonction du nombre de joueurs ou du prix de l'élément qui est tokenisé. Comme au Monopoly quand la banque distribue de l'argent au début du jeu.

Nous avons retenu 10 NFT à 2 500 € STCs l'unité pour la tokénisation de la bouteille de Pétrus 1945. Les 5 000 STCs proposés serviront aussi à l'achat d'un NFT mais aussi à payer différents frais.

{% hint style="info" %}
Note sur le jeu lui-même. Il pourrait être imaginé un développement du jeu sous la forme d'un Monopoly avec le tirage de cartes comme : 

* « Vous avez fait un héritage de 3 000 STCs »
* ou, moins chanceux « La justice vous impose de payer vos dettes, vous devez vendre votre NTF Bouteille de Pétrus 1945 au plus offrant ! »
{% endhint %}

> Rappel. Il est **nécessaire de disposer préalablement des tokens pour toutes transactions**. La blockchain Acadee-Formation ne fait pas crédit.

Sur la plateforme Acadee-Formation, le STC vaut un euro. Il est rappelé ici que l'achat est fictif est que la carte bancaire ne sera pas demandé.

Pour obtenir des STCs, avec le compte Gestionnaire ou le compte Administrateur, aller dans le menu Tokens > Acheter des STCs. Remplir les différents champs.

![](<../.gitbook/assets/image (3).png>)

Retourner dans Mes Tokens pour vérifier votre nouveau solde. Il s'agit bien de tokens fongibles.

![Mon solde de STCs fongibles soit 5 000 STCs. ](<../.gitbook/assets/image (7) (1) (1) (1).png>)



### 5. Création des tokens non-fongibles

Il s'agit ici d'une opération importante, la tokénisation de la bouteille de Pétrus 1945. 

Dix documents ont été créés et sont à identifier dans la blockchain.

Ci-dessous le processus pour un de ces documents avec GDP, Gestion De Preuve. Dans le menu : Fonctionnalités > Gestion de preuve > Démonstration GDP. 

![Écran principal de Gestion de preuve](<../.gitbook/assets/image (4) (1).png>)

Pour enregistrer numériquement notre NFT Bouteille de Pétrus 1945, nous utiliserons, pour des raisons de simplifications, la procédure "Sans Validation". La procédure "Avec Validation" peut être utilisée mais nécessite une tierce personne, un validateur.

{% hint style="success" %}
Nous avons réalisé pour vous ces 10 documents. Téléchargeables ci-dessous. Il est tout à fait possible de rédiger vos propres documents et de les enregistrer dans la blockchain Acadee-Formation. Et ceci afin de réaliser votre propre tokénisation de votre propre "sous-jacent" réel : un appartement, un terrain, une œuvre d'art.

Dans ce jeu, cela restera fictif. Pour une blockchain réel, contacter la société Spuro.
{% endhint %}

#### Création dans la blockchain Acadee-Formation de 10 tokens NFT de la bouteille de Pétrus 1945

{% file src="../.gitbook/assets/Tokens NFT Pétrus 1945.zip" %}
Les 10 tokens NFT pour la bouteille de Pétrus 1945. À vérifier si ceux-ci ont déjà été chargés dans Gestion De Preuve.
{% endfile %}

### 6. Transférer des STCs

Ce chapitre est très important. Il permet de transférer des tokens d'un joueur à l'autre.

Il existe deux moyens de transférer de STCs. Cela correspond au deux types de Tokens vus plus haut : 

* **Les tokens fongibles**, il s'agit juste d'un "transfert" d'argent, avec en entrée des (faux) euros,
* **Les tokens non-fongibles**, basés sur un sous-jacent qui sera ici les tokens NFT de la bouteille de Pétrus 1945.   

Dans l'écran ci-dessous, ce comte possède des tokens fongibles et des non-fongibles. Cela paraît évident mais cela va mieux en le disant, il n'est pas possible de transférer des NFTs que l'on ne possèdent pas !

![Les tokens de ce compte sont : des tokens fongibles d'une valeur de 500 STC et onze tokens non-fongibles. La valeur de ces tokens NFT est le hash du document qui identifie le produit du monde réel. Sa valeur est celle du marché.](<../.gitbook/assets/image (10) (1) (1).png>)

Dans notre jeu, le transfert de STCs fongibles a comme principal objectif l'achat d'un de STCs non-fongibles, une fraction de la bouteille de Pétrus 1945. Un peu comme au Monopoly lorsque la banque distribue de l'argent au début du jeu. 

Le transfert de STCs non-fongibles a pour but : 

* soit d'acquérir entièrement la bouteille de Pétrus, 
* soit d'en acquérir des fractions pour les revendre plus cher et ainsi réaliser des plus values. 

Le transfert de STCs est présenté dans les deux onglets ci-dessous. 

Note : Un courriel de confirmation est adressé dans les deux cas.

{% tabs %}
{% tab title="Transférer des STCs fongibles " %}


Ici, il s'agit de créditer le compte des joueurs pour négocier des NFTs de la bouteille de Pétrus 1945. Un peu au Monopoly lorsque la banque distribue des billets en début de jeu.

Un STC égale un euro (fictif)

Pour faire un transfert, il est nécessaire de connaître l'empreinte du destinataire. Ce point a été vu plus haut. Pour mémoire, le destinataire doit vous la faire parvenir (elle n'est pas secrète mais il n'est pas utile de la rendre publique) en copiant-collant son empreinte dans : Tokens > Mon empreinte.

 

Pour réaliser ce transfert, aller dans Tokens > Transférer des tokens. Remplir l'écran d’authentification.

Le solde de vos tokens apparaît. Comme déjà indiqué, vous ne pouvez pas transférer des tokens que vous n'avez pas.

Selon le cas, dans la liste, il apparaît : 

* Au minimum des tokens fongibles
* Si c'est le cas, des tokens non-fongibles. Une référence apparaît en début de ligne.

Ici, pour le transfert de STCs fongibles, nous allons nous intéresser uniquement au STC fongibles. **Cliquer sur le montant de vos STCs fongibles**, un nouvel écran apparaît.  

Ce nouvel écran, Transférer des tokens , vous demande : 

* L'empreinte du récepteur de votre transfert (en fait le destinataire !)
* Et le nombre de STC à transférer. 

Si vous êtes au début du jeu, le transfert sera de 5 000 STCs. Exemple d'écran.



![L'empreinte du destinataire et le montant de STCs à transférer. Il reste à Valider le transfert.](<../.gitbook/assets/image (6) (1) (1) (1).png>)



L'expéditeur et le destinataire peuvent vérifier les mouvements de STCs fongibles de leur compte respectif en allant sur : Tokens > Mes tokens.
{% endtab %}

{% tab title="Transférer des NFTs avec document" %}


Ici, nous sommes dans le coeur de la tokénisation d'un objet réel. Ceux qui peuvent prouver, et c'est la mission de la blockchain, qu'ils détiennent ces tokens non-fongibles est donc le propriétaire, au moins du point de vue de la blockchain, de l'objet réel. 

Si votre compte et piraté et vos NFT détournés vers d'autres comptes ou si vous perdez l'accès à votre compte, vous ne pourrez plus prétendre à la propriété virtuelle de l'objet réel et donc à des droits réels dessus.



Pour transférer un NFT, aller dans Tokens > Transférer des tokens. Entrer les identifiants de votre compte. 

Dans le nouvel écran, il apparaît : 

* Le solde de vos tokens fongibles,
* Éventuellement la liste de vos tokens non-fongibles qui commencent pas une référence,
* Et, ce qui est important pour notre procédure, la fonction "Vérifier le hash de votre document". Voir le chevron à droite pour éventuellement faire apparaître la zone "Déposer votre fichier ici.").



Glisser-déposer votre token NFT qui est sous la forme d'un fichier. Voir plus haut la proposition de tokens pour la bouteille de Pétrus 1945 ou glisser votre propre token NFT.

La zone devient verte, les informations du fichier apparaissent.



Exemple d'écran. 

![Les informations liées au fichier pour initier le transfert des STCs. Conserver ces informations.](<../.gitbook/assets/image (9) (1) (1).png>)



Nous allons voir que dans la suite de la procédure, le destinataire du transfert aura le choix d'accepter ou de refuser ce transfert. Si il accepte, les échanges se font. Si il refuse, tout revient à l'état initial. Pour connaître le statut de ces échanges, allez dans Tokens > Transfert en attente. C'est l'objet du chapitre suivant.



Pour mémoire, le transfert des tokens fongibles décrit dans l'autre onglet ne dispose pas de cette fonction (dans la version actuelle).
{% endtab %}
{% endtabs %}



### Rappels et précisions dans le contexte du jeu

Les manipulations proposées ci-dessous sont applicables quelque soit le contexte. Il est possible à chacun de créer son propre contexte.

{% hint style="info" %}
Si vous êtes le seul joueur de la partie, il est nécessaire de créer le compte d'un joueur supplémentaire pour faire les transactions. Ce compte pourrait avoir pour identifiant : \`Gérant\`. Le mot de passe et le courriel pourrait être le même que le profil en cours.

Il est recommandé d'ouvrir deux navigateurs différents pour bien isoler les deux comptes qui vont pointer sur la même url. Avec Firefox, l'extension 'Firefox Multi-Account Containers' permet d'isoler les comptes des différents onglets dans un même navigateur.. 
{% endhint %}

Avec un autre joueur, ou avec un second compte 'Gérant', transférer 

{% hint style="success" %}
Détails du transfert

* 25 000 €/STCs d'achat de la bouteille de Pétrus 1945 divisé entre 10 personnes : 2 500 €/STCs chacun
* 500 €/STCs de frais de transaction par personne
* 100 €/STCs de frais de gardiennage de la bouteille

Soit un versement initial de 3 100 €/STCs.
{% endhint %}

Nous vous rappelons qu'il s'agit ici d'une version communauté. Il vous est possible de contribuer à l'élaboration de la règle du jeu, voire d'en créer une nouvelle.

### Accepter ou refuser un transfert de NFTs

Pour Accepter ou refuser un transfert de NFTs dont vous êtes l'unique destinataire : 

Aller dans Tokens > Transfert en attente. Dans la "Liste des transferts reçus en attente d'acceptation", cliquer sur l'icône du marteau du NFT considérés. Un nouvel écran s'ouvre qui permet d'Accepter ou de Refuser le transfert.

![Votre réponse à donner suite à une transfert en votre faveur d'un NFT en échange de STCs.](<../.gitbook/assets/image (7) (1).png>)

Pourquoi refuser le transfert, la question pourrait se poser : 

* Il y a eu une erreur d'empreinte, vous n'êtes pas le destinataire attendu
* Vous avez changé d'avis sur le montant en échange ou sur le projet
* Vous n'avez plus, ou pas encore, les STCs dans votre compte.

### Annuler un transfert de NFTs

Le principe d'annulation d'un transfert par l'initiateur de ce transfert est assez similaire à la procédure d'acceptation ou de refus d'un NFT.

Envoyer d'abord un NFT, s'assurer que le destinataire ne va pas l'accepter. 

Aller dans Tokens > Transferts en attente. Entrer les données pour l'authentification.

Dans l'écran suivant, dans la "Liste des transferts envoyés en attente d'acceptation", repérer votre NFT. Dans la colonne Action, repérer l'icône avec la croix. Cliquer sur cette icône la proposition de transfert disparaît.  

![](<../.gitbook/assets/image (5).png>)

### Acheter des NFTs sans disposer suffisamment de STCs

Lors d'un transfert d'un NFT en échange de tokens fongibles, après acceptation par le  destinataire, si celui-ci n'a pas suffisamment de STCs, le transfert est refusé.

![C'est après acceptation du transfert par le destinataire que l'on vérifie si celui-ci possède suffisamment de STCs.](<../.gitbook/assets/image (5) (1).png>)



À noter qu'il est possible de transférer "gracieusement" un NFT en cochant la case "Donation" lors du transfert.

![Ici, le NFT sera transféré gratuitement, sans échange de STCs.](<../.gitbook/assets/image (4).png>)

Dans le cas d'un transfert par donation, il n'y a pas de Transfert en attente, le NFT est immédiatement crédité au destinataire.

Note : Un courriel de confirmation est adressé à l'auteur.

### Fin de la procédure, début du jeu

Toutes les procédures du jeu sont désormais connues et pratiquées (selon le profil du joueur).

En premier lieu, il vous est possible de proposer les corrections des fautes d'orthographe et fautes de style du présent document :tada: .

Ensuite, comme évoqué, 

* soit vous trouver un partenaire pour faire les échanges
* soit vous jouer seul et il vous sera nécessaire de créer plusieurs comptes.



Dans tous les cas, nous vous encourageons à enrichir ce jeu.



Nous vous souhaitons une bonne pratique.

Rédacteur initial : José Relland, JRE Services.

Contact : Samuel Dumas, platefrome Acadee-Formation.
