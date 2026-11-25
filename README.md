# La 4L du Tandem de la Victoire en 3D

Configurateur 3D de la Renault 4 F4 de 1983 de l'équipage 435 du 4L Trophy 2027 (Paris → Marrakech, du 15 février au 3 mars 2027).

Il sert à montrer aux sponsors ce que donnerait leur logo sur la voiture :

- les emplacements sponsors du plan officiel 4L Trophy 2027, cliquables, avec leurs dimensions et leur tarif (toute la 4L : 7 900 €, le toit en option) ; les portières avant, la bande latérale, le bandeau de pare-brise et un carré de 15 × 15 cm sur le hayon sont réservés à l'organisation, et les emplacements déjà vendus affichent le logo du sponsor
- import d'un logo ou saisie d'un nom, total du pack, récapitulatif à copier et message « Je suis intéressé » prêt à envoyer
- 4 livrées, couleurs de carrosserie et d'accents
- équipements en option : galerie, roue de secours, jerricans, plaques, malle, pelle, phares longue portée, rampe LED, tandem sur le toit
- portières, capot et porte arrière ouvrants, avec le moteur et le chargement solidaire
- mode « En route » : roues qui tournent, décor qui défile, poussière
- 9 décors qui suivent le trajet : showroom, Paris, Biarritz, détroit de Gibraltar, dunes, bivouac de nuit, col du Tichka, Marrakech, autoroute du retour
- onglet Trajet : carte stylisée Paris → Marrakech (tracé indicatif)
- intro cinématique, phares, warnings, vues rapides et capture d'image
- page « L'équipage » : Milo, Dylan, la carte d'identité de La Chouette, pourquoi nous sponsoriser, comment ça marche et le budget
- page « Le volet solidaire » : notre coffre solidaire (paliers et liste officielle), l'offre partenaire solidaire, les associations partenaires, actions écocitoyennes et appel aux dons, avec lien vers la cagnotte HelloAsso (activé quand `HELLOASSO_READY` passe à `true` dans `index.html`)


## Technique

Une seule page `index.html`, sans étape de build. La 4L est modélisée en code avec [Three.js](https://threejs.org/) (chargé depuis jsDelivr), aux cotes du plan de la R4 F4 : 3,65 m de long, 1,50 m de large, 2,40 m d'empattement.

Pour l'ouvrir en local, il faut un petit serveur web (les modules JavaScript ne se chargent pas en `file://`) :

```bash
npx serve .
```

## Contact

Instagram : [@tdlv4ltrophy2k27](https://www.instagram.com/tdlv4ltrophy2k27/)
