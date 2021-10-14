---
description: Essai d'analyse du registre et d'un bloc du registre
---

# Décoder un bloc du registre

### Le registre

Le registre du réseau des nodes de cette blockchain est lisible, uniquement avec le profil d'administrateur, par Sécurité > Registre.

![Registre d'une blockchain Spuro. Possibilité de sauvegarder ce registre et de faire des recherches dans les chaînes de caractères.](<../.gitbook/assets/image (5).png>)

Bien noter la longueur de la chaîne de caractères en regardant la largeur de l'ascenseur horizontal en bas de l'écran blanc. Dans l'exemple ci-dessus, la première ligne comprend 751 caractères.

Il est possible de copier-coller tout un bloc ou seulement une portion.

### Analyser une ligne, ou bloc, du registre

Dans cet exemple ci-dessous, nous avons reproduit et découpé le bloc (une ligne du registre) d'un prêt réalisé à travers un Smart Contract du compte g-jre vers a2-jre.

> 1. 1634228165087;
> 2. sc_loan;8e44d394f35b8d192eded7ab14a7dbd3cba6ca5d0b2bcb441a31f684fbf47b2f
> 3. ;IggEE1Z0EA==##6p3Akl7A477GTBmL/Z6qLw==##JBYIGiCp9EavicN4AhSyHAIroW5fyjtWgYhMJYkbMox8Vg5CrXUcjXf5wAgCiv+8ujXX0uFXFP+1u7ZufuTXeQ==;
> 4. {"empreinteInitiateur":"150561131fb4c93572595160191e6a46fcb499b5db2dc0d6fa9fac91946473ee", 
> 5. "valueLoaned":"3100", 
> 6. "valuePayBack":"3100.000",
> 7. "timeToPayBack":575636367599000,
> 8. "failurePayBack":"3100.000",
> 9. "idLoan":"1634228165087080046",
> 10. "status":"waiting"};
> 11. true;cf3adda47cdde44b2b1ec7070d1389f15b17c38ceb60a1d9b09a07edac920077;IoFlCHhwNw==##HWxLGE6L2YzYavhc0wFL6w==##mb6MKhiFeUC6fCjynnmJgjQzTzG5ptit0sOfnEjVQju2+b9TQetyrpPo9R9rDPDy7YkyDSKKx/DtxS/E0kXrgw==

Certains éléments sont assez "lisible" d'autres sont, à ce stade non-déchiffrés.

1. Semble être un chrono
2. L'empreinte du destinataire du prêt
3. Non-déchifré
4. L'empreinte de l'initiateur du prêt
5. Le montant du prêt : 3 100 STC
6. La valeur à l'issue du prêt. Les intérêts étaient à 0 %
7. La date de fin du prêt, le 11 mars 2022
8. Le montant dû en cas de non-remboursement
9. L'identification du prêt. Commence par le numéro de chrono, le point 1.
10. Statut : À découvrir. hypothèse, prêt pas encore remboursé
11. Non-déchifré

### Vérification du registre et du code source

À noter qu'il est possible, dans ce même menu Sécurité, de : 

* Vérifier l'Intégrité des registres
* Vérifier l'Intégrité du code source

sur l'ensemble des nodes de cette blockchain.



Noter que la blockchain Acadee-Formation ne possède qu'un seul node, ces vérifications n'ont pas d'intérêt.









###







