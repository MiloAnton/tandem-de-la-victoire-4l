# La 4L du Tandem de la Victoire en 3D

Configurateur 3D de la Renault 4 F4 de 1983 de l'équipage 435 du 4L Trophy 2027 (Paris → Marrakech, du 15 février au 3 mars 2027).

Il sert à montrer aux sponsors ce que donnerait leur logo sur la voiture :

- 27 emplacements sponsors cliquables (avant, côtés, arrière, toit), avec leurs dimensions et un tarif indicatif
- import d'un logo ou saisie d'un nom, total du pack et récapitulatif à copier
- 4 livrées, couleurs de carrosserie et d'accents
- équipements en option : galerie, roue de secours, jerricans, plaques, malle, pelle, phares longue portée, rampe LED, tandem sur le toit
- 4 décors : studio, désert, bivouac de nuit, départ de Paris
- phares, warnings, vues rapides et capture d'image

## Technique

Une seule page `index.html`, sans étape de build. La 4L est modélisée en code avec [Three.js](https://threejs.org/) (chargé depuis jsDelivr), aux cotes du plan de la R4 F4 : 3,65 m de long, 1,50 m de large, 2,40 m d'empattement.

Pour l'ouvrir en local, il faut un petit serveur web (les modules JavaScript ne se chargent pas en `file://`) :

```bash
npx serve .
```

## Contact

Instagram : [@tdlv4ltrophy2k27](https://www.instagram.com/tdlv4ltrophy2k27/)
