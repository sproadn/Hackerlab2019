# Hackerlab2019 – Choosy Web Server ?

* **Category:** Web
* **Points:** 150

## Challenge

> C'est l'histoire d'un serveur web qui choisit ses agents minutieusement. 
>http://hackerlab.bj:8001/web07/

## Solution
Le challenge pour cette épreuve était de trouver le User-agent nécessaire pour afficher le contenu de la page. Étant donné qu’il existe plusieurs User-agent, on ne pouvait pas les tester chacun.
Avec la commande `ua-tester` Kali Linux, on pouvait avoir le User-agent spécifique à ce serveur.
Pour faire, on a utilisé la commande:
`ua-tester -u http://hackerlab.bj:8001/web07/`. 
A la fin de l’exécution de la commande, on vu que le User-agent était **Lynx**.Pour pouvoir changer le User-agent et afficher le contenue de la page web, nous avons utiliser la commande CURL de la manière suivante:
`curl -A 'Lynx' http://hackerlab.bj:8001/web07/`, le -A pour spécifier le User-agent qu’on voulait utiliser.
A la fin de cette commande, on donc eu le flag qui était: ```CTF_LynxIsLightAsHell```
