# La 4L du Tandem de la Victoire en 3D

Configurateur 3D de la Renault 4 F4 de 1983 de l'équipage 435 du 4L Trophy 2027 (Paris → Marrakech, du 15 février au 3 mars 2027).

Il sert à montrer aux sponsors ce que donnerait leur logo sur la voiture :

- 32 emplacements sponsors cliquables (capot, pare-chocs, côtés, arrière, toit), avec leurs dimensions et un tarif indicatif ; la plaque équipage sur les portières, le bandeau de pare-brise et le bas de porte arrière gauche sont réservés à l'organisation du 4L Trophy
- import d'un logo ou saisie d'un nom, total du pack, récapitulatif à copier et message « Je suis intéressé » prêt à envoyer
- 4 livrées, couleurs de carrosserie et d'accents
- équipements en option : galerie, roue de secours, jerricans, plaques, malle, pelle, phares longue portée, rampe LED, tandem sur le toit
- portières, capot et porte arrière ouvrants, avec le moteur et le chargement solidaire
- mode « En route » : roues qui tournent, décor qui défile, poussière
- 8 décors qui suivent le trajet : showroom, Paris, Biarritz, détroit de Gibraltar, dunes, bivouac de nuit, col du Tichka, Marrakech
- onglet Trajet : carte stylisée Paris → Marrakech (tracé indicatif)
- intro cinématique, phares, warnings, vues rapides et capture d'image


## Technique

Une seule page `index.html`, sans étape de build. La 4L est modélisée en code avec [Three.js](https://threejs.org/) (chargé depuis jsDelivr), aux cotes du plan de la R4 F4 : 3,65 m de long, 1,50 m de large, 2,40 m d'empattement.

Pour l'ouvrir en local, il faut un petit serveur web (les modules JavaScript ne se chargent pas en `file://`) :

```bash
npx serve .
```

## Contact

Instagram : [@tdlv4ltrophy2k27](https://www.instagram.com/tdlv4ltrophy2k27/)
