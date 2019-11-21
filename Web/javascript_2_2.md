# Hackerlab2019 – JavaScript 2/2 ?

* **Category:** Web
* **Points:** 150

## Challenge

> http://hackerlab.bj:8001/web05/web05_eterfrgtrhtrh.html (même challenge que le JavaScript 1/2)
## Solution
Le lien de cet épreuve nous a conduit vers une page vide. En faisant Ctrl+U pour afficher le code source de la page, on a remarqué qu’il y avait du code JavaScript qui était encoder (Javascript Obfuscator). On devait donc le désencoder  pour voir le contenu. Pour ce faire, on a utiliser l’outil eu ligne : [de4js](https://lelinhtinh.github.io/de4js/). En allant sur ce site, on a coller le code brouller copier dans le champ texte et on a cliquer sur Auto decode. On a donc eu le script décoder qui était : _//console.log("CTF_JavascriptEncodingIsNothingForYou");_
Le flag pour cet épreuve était donc : ```CTF_JavascriptEncodingIsNothingForYou```