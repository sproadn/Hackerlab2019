# Hackerlab2019 – Confiance zéro ?

* **Category:** Web
* **Points:** 150

## Challenge

> Les agents du HackerLab ont subit une attaque et font appel aux cyber-amazones. Mais dans le cyberespace béninois, 
>il faut faire attention à ne pas faire confiance à n'importe qui. Les agents du HackerLab ne font confiance qu'aux
>cyber-amazones venant de l'ANSSI-Benin ou du bjCSIRT. 
>http://hackerlab.bj:8001/web02/web02_ffzpiizef456_ori.php

## Solution
Le lien de l’épreuve nous conduisait sur une page qui affichait _"Prouvez votre origine ou retournez chez vous cyber-amazone!"_. Or on avait dans les consignes de pour l’épreuve que : _"Les agents du HackerLab ne font confiance qu'aux cyber-amazones venant de l'ANSSI-Benin ou du bjCSIRT."_. On a donc eu l’idée de modifier le Header de la requète HTTP en y ajoutant l’option Origin qui aurait pour valeur l’URL du site web du bjCSIRT qui est https://csirt.gouv.bj. Pour ce faire: on a utiliser la commande: `curl -X POST -H 'Origin: https://csirt.gouv.bj' http://hackerlab.bj:8001/web02/web02_ffzpiizef456_ori.php`  avec le -X pour spécifier la méthode avec laquelle on envoit la requete vers le serveur et -H pour spécifier qu’on modifiait le Header.
On a donc eu le flag qui était: ```CTF_GEG533HHGGSGG1CPJM```



