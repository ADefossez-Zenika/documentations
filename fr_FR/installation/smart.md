# Restauration en mode usine d'une Jeedom Smart

## Présentation

La Jeedom Smart est équipée d’un disque Emmc, garantissant une meilleur fiabilité qu'une carte SD, mais ce disque n’est pas directement accessible.

Le Recovery Mode USB englobe à la fois le système, l’OS, et aussi l’application Jeedom.

Il permet :

- La réinitialisation de la Jeedom Smart en configuration « usine » OS+Jeedom.
- La réinitialisation de la Jeedom Smart en configuration « usine », en appliquant ensuite sa sauvegarde Jeedom.

Pour rappel la gestion des sauvegardes/restauration est disponible dans Jeedom dans le menu « roues crantées » en haut à droite, puis « Sauvegardes ».

Jeedom propose un service avec abonnement de sauvegarde automatique sur cloud privé Jeedom, pour ne plus vous soucier de rien. (Sur le Market, dans votre compte, menu à gauche « Backup Cloud »).

## Fonctionnement du recovery mode

Matériel necessaire : une clé USB (minimum 8Go).

>**Note**
>
>Pensez à mettre de côté (en local) une sauvegarde de configuration Jeedom

- téléchargez l’archive que nous fournissons : [backupJeedom.tar.gz](https://images.jeedom.com/smart/backupJeedom.tar.gz). Attention de bien vérifier que le fichier à pour nom backupJeedom.tar.gz pour que la restauration marche.
- copiez cette archive sans la modifier ni la dézipper, sur une clé USB formatée en FAT32 et vierge
- arrêtez votre Smart proprement, par Jeedom
- débranchez là
- insérez votre clé USB
- redémarrez la Smart
- patientez environ 30min, box non accessible **NE PAS DEBRANCHER**
- cherchez votre Smart sur le réseau
- reconnectez vous avec le login : admin et le mot de passe : admin

> **Important**
>
> Attention ! Un Recovery Mode remet quoi qu’il arrive votre Smart en configuration « usine » neuve. Si vous avez une sauvegarde de votre configuration Jeedom il suffit après de la restaurer.

Ce Recovery Mode n’est compatible qu’avec la Jeedom Smart.
