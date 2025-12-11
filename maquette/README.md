# Maquette (faisabilité)

## Scénarisation de l'interactivité

### Scène 1

| Verbe action | Condition de déclenchement                                                                    | Effet visuel                                                                                                                 | Effet sonore                                                                                                                                                                            | Effet interactif                                                         |
| ------------ | --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Entrer       | Le visiteur suit le tapis vers l'exposition                                                   | Des empreintes d'animaux sur le tapis indiquent la direction                                                                 | Une musique de fond organique légère boucle                                                                                                                                             | NA                                                                       |
| Se déplacer  | S'approche du faisceau lumineux qui invitent le visiteur à se positioné devant les télévisons | Les vidéos des regards d'animaux se transforment en yeux d'humains avec un fondu du noir et les lumières changent de couleur | La même musique de fond joue après un son de carillon une fois la présence captée (synchronisé avec l'effet de transformation), en y incluant maintenant des textures sonores d'animaux | L'installation "reconnait" la présence du visiteur et passe à la scène 2 |

### Scène 2

| Verbe action                      | Condition de déclenchement                                                                   | Effet visuel                                                                                                                                                                                                       | Effet sonore                                                                                                                   | Effet interactif                                         |
| --------------------------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------- |
| Rester en place                   | Détection captée par le capteur (caméra)                                                     | Les yeux d'animaux de deux télévisions se transforment en l'oeil de l'interacteur et les lumières LED changent de couleur                                                                                          | La même musique de fond joue avec les textures sonores d'animaux                                                               | L'installation traduit les gestes en visuels et lumières |
| Tourne la tête                    | Capteur perd la présence de l'intéracteur après un certain temps                             | Les regards humains se transforment en animaux et les lumières redeviennent à leur état initial, c'est-à-dire des couleurs distinctes qui ont une légère animation s'apparentant à une respiration                 | La même musique de fond joue avec les textures sonores d'animaux et un son de carillon inversé lorsque la captation est perdue | Fin du cycle - passe à la scène 3                        |
| Caméra obstruée                   | Capteur perd la présence de l'intéracteur après un certain temps                             | Les regards humains se transforment en animaux et les lumières redeviennent à leur état initial, c'est-à-dire des couleurs distinctes qui ont une légère animation s'apparentant à une respiration                 | La même musique de fond joue avec les textures sonores d'animaux et un son de carillon inversé lorsque la captation est perdue | Fin du cycle - passe à la scène 3                        |
| Reste trop longtemps              | Une fois que l'interacteur reste plus de 2min                                                | Les regards humains se transforment en animaux et les lumières redeviennent à leur état initial, c'est-à-dire des couleurs distinctes qui ont une légère animation s'apparentant à une respiration                 | La même musique de fond joue avec les textures sonores d'animaux et un son de carillon inversé lorsque le temps s'est écoulé   | Fin du cycle - passe à la scène 3                        |
| Plusieurs personnes présentes     | Mouvements captés de la première personne captée                                             | Les yeux d'animaux de deux télévisions se transforment en l'oeil de la première personne captée et les lumières LED changent de couleur                                                                            | La même musique de fond joue avec les textures sonores d'animaux                                                               | L'installation traduit les gestes en visuels et lumières |
| Se déplace de gauche à droite     | Mouvements captés par le capteur (caméra)                                                    | Les yeux de deux télévisions, maintenant de l'interacteur, reflètent le mouvement de la personne, donc suit celle-ci                                                                                               | La même musique de fond joue avec les textures sonores d'animaux                                                               | L'installation traduit les gestes en visuels et lumières |
| Se déplace de l'arrière à l'avant | Mouvements captés par le capteur (caméra)                                                    | Les yeux de deux télévisions, maintenant de l'interacteur, reflètent le mouvement de la personne, donc suit celle-ci si elle se rapproche ou s'éloigne                                                             | La même musique de fond joue avec les textures sonores d'animaux                                                               | L'installation traduit les gestes en visuels et lumières |
| Sauter                            | Mouvements captés par le capteur (caméra) ou risque de perte de la présence de l'intéracteur | Les yeux de deux télévisions, maintenant de l'interacteur, reflètent le mouvement de la personne, mais peuvent se retransformer en animaux si le mouvemnent est trop rapide / le saut est trop haut pour le suivis | La même musique de fond joue avec les textures sonores d'animaux                                                               | L'installation traduit les gestes en visuels et lumières |

### Scène 3

| Verbe action | Condition de déclenchement | Effet visuel                                                                                                                                                                                                                                 | Effet sonore                                            | Effet interactif   |
| ------------ | -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ------------------ |
| Quitter      | Inactivité totale          | Les télévisons alternent entre des yeux d'animaux et les yeux d'humains déjà enregistrés et les lumières redeviennent à leur état initial, c'est-à-dire des couleurs distinctes qui ont une légère animation s'apparentant à une respiration | La même musique de fond joue avec un son de respiration | Passe à la scène 1 |

## Équipements

**Équipement audiovisuel**
| Nom | Disponibilité | Quantité |
|-------------------------|---------------|----------|
| Télévision cathodique | X | 4 |
| Caméra Sony A6500| ✔ | 1 |
| Ordinateur | ✔ | 1 |
| Haut-parleurs | ✔ | 2 |
| Carte de son | ✔ | 1 |

**Éclairage**
| Nom | Disponibilité | Quantité |
|--------------------|---------------|----------|
| Ampoule lumineuse | ✔ | 6 |
| Lumière LED | ✔ | 2 |
| Lumière DMX | ✔ | 2 |
| Spotlight | ✔ | 1 |

**Accessoires et décor**
| Nom | Disponibilité | Quantité |
|-----------------------------|---------------|----------|
| Bouquet de fleurs blanches | ✔ | 6 |
| Tapis noir et blanc | X | 4 |

**Câblage**
| Nom | Disponibilité | Quantité |
|-------------------------------|---------------|----------|
| Câble coaxial | ✔ | 4 |
| Adaptateur coaxial vers HDMI | X | 4 |
| Câble DMX | ✔ | 2 |
| Câble Ethernet | ✔ | 1 |
| Câble HDMI | ✔ | 7 |
| Multiprise | X | 4 |

## Logiciels

### - Midjourney

Générer les médias nécessaires au projet grâce à l'intelligence artificiel

### - Photoshop

Modifier les médias générés afin de les rendent interactifs

### - Touch Designer

Créer des expériences visuelles interactives avec Media Pipe  
Générer des animations en temps réel  
Connecter des capteurs ou données externes avec OSC

### - Pure Data

Concevoir des systèmes audio interactifs avec OSC

### - Reaper

Créer des expériences auditives interactives avec l'OSC

### - Hyper HDR

Connecter avec les lumières avec OBS

### - OBS

Relier les expériences visuelles interactive pour les lumières

![](logiciels.png)

## Synoptique

### Branchements

![](synoptique.png)

### Logiciels

![](synoptique.png)

## Plan d'implantation

![](plan_studio.png)

Plans d'implantation 2D

![](plan_plantation_01.png)
![](plan_plantation_02.png)

Plan d'implantation 3D

![](plan_plantation_3D.png)

## Budget estimé

| Nom                     | Prix | Quantité  |
| ----------------------- | ---- | --------- |
| Télévisions cathodiques | 75$  | 3         |
| Bouquet fleurs blanches | 25$  | environ 6 |
| Tapis noir et blanc     | 30$  | 4 mrcx    |
| Plywood 4' x 8'         | 25$  | 2         |
| Adaptateur              | 20$  | 4         |

Total: 625$ (sans taxes)
