# Installation type "baremetal

## Installation sur une machine physique

Cette documentation a pour but de décrire l'installation de jeedom sur une machine physique x86-64 (type Intel NUC)

## Installation automatique

Téléchargez l'iso jeedom [ici](https://images.jeedom.com/x86-64/).

### Gravure sur clef USB

Vous pouvez utiliser l'outil UNetbootin (telechargeable [ici](https://unetbootin.github.io/) ).

#### Copie de l'image ISO sur la clé

- Selectionnez "Diskimage" (en bas)
- Cliquez sur les ... et selectionnez le fichier iso de Jeedom téléchargé à l'étape précédente
- Selectionnez votre clef USB dans "Lecteur"
- Cliquez sur OK

### Installation

Inserez la clef USB dans votre machine physique, configurez le boot sur le lecteur USB, puis

- Selectionnez "Avanced options"
- Et enfin "Install in text mode"

>**NOTE**
>
>Toutes les autres options génèreront des erreurs. Seule celle décrite dans cette documentation et valable

Patientez jusqu'à la fin de l'installation.

>**NOTE**
>
>Il faut absolument une connexion internet lors de l'installation

Ensuite, vous pouvez suivre la documentation [Premier pas avec Jeedom](https://doc.jeedom.com/fr_FR/premiers-pas/index)

## Installation manuelle

Une fois l'OS installé (Derniere version de Debian de préference) suivre cette [documentation](https://doc.jeedom.com/fr_FR/installation/cli)
