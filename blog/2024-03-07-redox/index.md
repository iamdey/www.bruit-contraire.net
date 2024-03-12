---
slug: redox-keyboard
title: Redox - Un clavier ergonomique
authors:
  name: David Epely
  image_url: https://github.com/iamdey.png
tags: [électronique, DIY, lowtech]
---

Je vous présente aujourd'hui
[Redox keyboard](https://hackaday.io/project/160610-redox-keyboard) le clavier
que j'utilise tous les jours depuis 2020.

![Photo du clavier redox, celui-ci est scindé en deux et relié par un cordon. Les touches n'ont pas de marquage.](./Redox.jpg)

Il s'agit d'un clavier mécanique très inspiré par
[ergodox](https://www.ergodox.io/).

<!-- truncate -->

C'est de mes premiers projets d'électronique d'envergure, (le coût et l'objectif
en font plus qu'un jouet que l'on abandonne au bout de 2 heures). La plupart des
pièces viennent de [falbatech](https://falbatech.click/). J'ai pu ainsi
sélectionner les switchs, des cherry MX silent et les caps.

![Photo de composants électronique (PCB, switchs et arduinos) prêt à être montés](./20200707_122948.jpg)

Ma compagne ayant accès à ce moment à un fablab, elle a pu grâce à une
découpeuse laser produire le boitier à partir de contre plaqué de 3mm.

![Photo de 3 plaques de contre-plaqué ayant le même galbe que la PCB. Le premier (socle) a un dessin de personnage fait au pyrograveur, les 2 autres sont troués pour laisser passer les switchs. On voit une des deux PCB sur laquelle sont montés l'arduino et les diodes.](./20200821_164709.jpg)

Il ne me restait plus qu'à souder les différents éléments, les diodes, les
switches et les 2 arduinos à la PCB.

![Photo des switchs sur le contre-plaqué avant soudure](./20200821_203939.jpg)
![Photo des 2 parties du clavier en cours de soudures, tous les éléments sont installés, on voit nottament de bande de led RGB pouvant être monté de ](./20200822_182409.jpg)

Pour finir, il est nécessaire d'installer le firmware sur les 2 arduinos. Redox
utilise le framework [QMK Firmware](https://qmk.fm/). Il propose une
configuration par défaut en
[qwerty](https://github.com/qmk/qmk_firmware/tree/master/keyboards/redox) mais
avec quelques bidouillages, il devient une bonne base pour configuration en
[Bépo](https://bepo.fr/wiki/Accueil). Il fonctionne très bien autant sur
GNU/Linux que sur Windows (une fois
[le pilote installé](https://bepo.fr/wiki/Windows)).

J'ai tout de même fait une erreur pendant l'assemblage, la fiche USB sur les
arduinos est très fragile. N'ayant pas utilisé le boitier imprimé en 3D, ni le
boitier en bambou usiné par falbatech, il n'y avait pas de garde fou. À force de
bouger le clavier pour le nettoyer (c'est à dire tapoter dessus pour faire
tomber la poussière), j'ai arraché la prise. J'ai donc dû dessouder et remplacer
un des deux arduinos (le principal), c'était un peu moche comme opération mais
ça m'a montré à quel point j'en suis accroc.

![Photo de la PCB et de l'arduino une fois déssoudé. On voit une pompe à déssouder en arrièer plan](./20201207_093308.jpg)

À ce jour cela fait 3 ans que je l'utilise autant pour travailler que pour pour
jouer. Les switchs MX silent sont comme prévu très agréables et silencieux.
Certes le temps d'apprentissage peu rebuter mais la disposition bépo est juste
génial, je ne regarde plus mon clavier. Au début j'utilisais des stickers sur
les touches mais très vite je m'en suis passé. C'est comme une manette de jeu
vidéo, une fois apprise, on ne la regarde plus quand on joue. Seul «défaut», ce
n'est pas fait pour tapper à une main. Pour ce qui est de l'ergonomie, c'est
difficile à dire, est-ce que j'aurai plus ou moins de tendinite que mes paires à
moyen et long terme ? Il faudrait, pour le vérifier faire de vraies
statistiques.

![Photo du redox avant d'enlever les stickers, les keycaps utilisés étaient ceux d'un vieux clavier utilisé dans mon autre projet, le LMN-3](./20200824_003200.jpg)

En tout cas à l'heure actuelle je ne peux honnêtement plus m'en passer.
