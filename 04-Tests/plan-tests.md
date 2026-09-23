## Tests de la version 0.2

| ID      | Test                           | Méthode                         | Résultat attendu                                          |
|---------|--------------------------------|---------------------------------|-----------------------------------------------------------|
| V02-T01 | Vérifier le hostname de S1     | Observer l’invite CLI           | `S1#`                                                     |
| V02-T02 | Vérifier le hostname de S2     | Observer l’invite CLI           | `S2#`                                                     |
| V02-T03 | Vérifier le hostname de R1     | Observer l’invite CLI           | `R1#`                                                     |
| V02-T04 | Tester le mot de passe console | Fermer et rouvrir la session    | Le mot de passe `cisco` est demandé                       |
| V02-T05 | Tester le mode privilégié      | Exécuter `enable`               | Le mot de passe `class` est demandé                       |
| V02-T06 | Vérifier la bannière           | Ouvrir une nouvelle session     | La bannière de sécurité apparaît                          |
| V02-T07 | Vérifier le chiffrement        | Exécuter `show running-config`  | Les mots de passe simples ne sont plus affichés clairement|
| V02-T08 | Vérifier la sauvegarde         | Exécuter `show startup-config`  | La configuration sauvegardée apparaît                     |
| V02-T09 | Vérifier la persistance        | Fermer/rouvrir le fichier `.pkt`| Les configurations sont toujours présentes                |