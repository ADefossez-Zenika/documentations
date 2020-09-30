# Installation sur Freebox Delta

Il est possible d'installer Jeedom sur Freebox Delta via le système de VMs.

## Connexion à la Delta

Vous devez vous rendre sur l'interface de configuration de votre Freebox Delta. Cliquez ensuite sur *VMs*.

![delta1](images/delta1.png)

## Paramétrez les différentes options

Cliquez sur "Ajouter une VM"
![delta2](images/delta2.png)

Configurez les caractéristiques. Nous vous recommandons de mettre 2 CPUs et le maximum en RAM.

![delta3](images/delta3.png)

Configurez l'utilisateur et le mot de passe, **il faut bien les garder en mémoire ils vous seront demandés lors de la connexion SSH**:
![delta4](images/delta4.png)

## Installation en cours

Patientez pendant le téléchargement de l'image
![delta5](images/delta5.png)

## Connectez-vous à votre Jeedom

Vous pouvez vous connecter grâce à l'adresse indiquée sur la page:
![delta6](images/delta6.png)

Pensez à affecter le port USB de la Delta à la VM si vous souhaitez utiliser une antenne.

Ne **pas** cocher "Écran", ceci ne sert à rien sur l'image Jeedom (et engendre une surconsommation de ressources).

L'adresse ip de votre Jeedom sur la Freebox Delta est écrite en haut, sous son nom.

Les login et mot de passe par défaut sont admin/admin quand vous accédez a jeedom via votre navigateur.

Pour la suite, vous pouvez suivre la documentation [Premier pas avec Jeedom](https://doc.jeedom.com/fr_FR/premiers-pas/index.html)
