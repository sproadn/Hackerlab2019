# Hackerlab2019 – Que faire ?

* **Category:** Web
* **Points:** 100

## Challenge

> Pour défendre notre cyber-contrée, les cyber-amazones devaient choisir la bonne méthode. 
>http://hackerlab.bj:8001/web01/web01_sqfrs35_quefaire.php

## Solution
Le lien de l’épreuve conduisait sur une page vide. Même en inspectant la page il n’y avait rien. On a donc eu l’idée de changer le Header la page qui était envoyer avec la méthode _GET_ par _POST_ et en ensuit par _OPTIONS_ en utilisant `CURL`.
En tapant la commande `curl -X OPTIONS http://hackerlab.bj:8001/web01/web01_sqfrs35_quefaire
.php` nous sommes tombés sur le flag qui était : ```CTF_34GFGLFRFE343432323R2```.

