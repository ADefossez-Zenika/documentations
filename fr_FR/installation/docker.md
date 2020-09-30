# Installation sur Docker

> **Important**
>
> Attention, nous partons ici du principe que vous maîtrisez déjà Docker, et que vous l'avez déja installé sur votre système.



## Installation d’une image Jeedom

Lancez la commande suivante

``sudo docker run --detach --name jeedom-server --privileged -v /opt/jeedom/www:/var/www/html -v /opt/jeedom/db:/var/lib/mysql -p 9080:80 jeedom/jeedom``

Avec :

- ``jeedom-server`` : nom du Docker jeedom voulu
- ``/opt/jeedom/www`` et ``/opt/jeedom/db`` : répertoire où les données de Jeedom sont mises sur l’hôte (attention a bien les créer avant)


Il vous faut ensuite installer Jeedom en allant sur : ``IP_DOCKER:9080``

Pour la suite, vous pouvez suivre la documentation [Premier pas avec Jeedom](https://doc.jeedom.com/fr_FR/premiers-pas/index)
