---
description: >-
  Commandes et écrans de la partie sécurité de la blockchain pédagogique
  Acadee-Formation.
---

# Sécurité de la plateforme

## Le sous-menu Sécurité

Les commandes de sécurité de la la plateforme de la blockchain Acadee-Formation sont regroupées dans le sous-menu Sécurité.

Ce sous-menu Sécurité est accessible aux administrateurs et aux gestionnaires. Le gestionnaire peut donc détecter des failles des sécurités mais n'a pas accès aux commandes de l'administration. Il devra dont en référer à l'administrateur pour toute intervention.

Le sous-menu Sécurité contient les items suivants :

* Registre
* Intégrité des registres
* Intégrité du code source.

### Registre

L'écran Registre affiche les hashs de la blockchain. Ces registres sont difficilement interprétables par un être humain. Pour mémoire, les blockchain ne sont pas interopérables en elles. Ces blocks ne serviraient à rien dans une autre blockchain comme par exemple Ethereum.  

![Dans S&#xE9;curit&#xE9; &amp;gt; Registre, la liste des registres partag&#xE9;s sur cette blockchain.](https://jreservices.fr/bookstack/uploads/images/gallery/2021-07/scaled-1680-/image-1626278511326.png)



Les `registres` sont partagés entre tous les nodes de la blockchain. Il est capital que tous ces registres soient copiés à l'identiques. Cette vérification est proposée dans la commande suivante.

### Intégrité des registres

L'écran Intégrité des registres permet de lister l'ensemble des registres. Le bouton VERIFICATION MANUELLE DE L'INTÉGRITÉ DES REGISTRES permet de vérifier en temps réel cette intégrité.

Note : La blockchain Acadee-Formation disposant que d'un seul node, le registre donc bien intègre avec lui-même . 😇 

![image-1626278435991.png](https://jreservices.fr/bookstack/uploads/images/gallery/2021-07/scaled-1680-/image-1626278435991.png)

Si un ou plusieurs des nodes n'étaient pas synchronisés, cela pourrait signifier une attaque sur ce ou ces nodes. Le ou les nodes seraient immédiatement supprimés de la blockchain par l'administrateur.

Cette action serait sans risque pour la blochain. Les registres étant recopiés sur les autres nodes, la blockchain continurait de fonctionner sur d'autres nodes.

L'intégrité des registres sur chaque node repose sur le fait que le code de chaque node est bien identique. C'est ce que permet de vérifier la commande suivante.

### Intégrité du code source

Le `code source` \(backend, le coeur de la blockchain\) est recopié à l'identique sur tous les nodes de la blockchain. Il est capital que tous ces codes sources soient toujours conformes sur chacun des nodes.

L'écran Intégrité du code source permet de lister l'ensemble des registres. Le bouton `VERIFIER MANUELLEMENT L'INTÉGRITÉ DU CODE SOURCE` permet de vérifier en temps réel que le code source de chaque node est bien conforme.

Note : Ici, il n'existe qu'un seul node, les codes sources sont donc "bien" synchronisés.

![image-1626278074521.png](https://jreservices.fr/bookstack/uploads/images/gallery/2021-07/scaled-1680-/image-1626278074521.png)

Si un ou plusieurs des nodes ne contenait pas le même code source, cela pourrait signifier une attaque sur ce ou ces nodes. Le ou les nodes seraient immédiatement supprimer de la blockchain.

Cette action serait sans risque pour la blochain. Les autres nodes continuerait à fonctionner. 

