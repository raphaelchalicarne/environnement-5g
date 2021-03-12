---
layout: post
title: "La 5G, comment ça fonctionne?"
image: assets/images/cell-tower-5390644_1920.jpg
---

# Antennes et imbrication entre 4G et 5G
Une crainte concernant l'empreinte écologique de la 5G est que les antennes viennent s'ajouter massivement aux antennes 4G. Si cela est vrai dans la première phase du déploiement de la 5G, selon [la Fédération Française des Télécoms](https://www.fftelecoms.org/app/uploads/2020/10/CSF-5G-et-environnement-FINAL-22-septembre-2020.pdf#page=5), cette densification sera à priori ponctuelle et ciblée. De plus, la 5G s’inscrivant pleinement dans la continuité de la 4G, les équipements matériels et logiciels seront communs.

## 5G en zone dense
En zone dense, la 5G à 3,5GHz (bande "coeur 5G") vient rajouter une ressource supplémentaire, plus large et plus efficace que les bandes 4G. Le débit à partager dans la zone est donc plus important et répond à l’augmentation constante du trafic sur les réseaux mobiles (entre +30% et +50% par an).

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/5G_3-5GHz.png" alt="La 5G à 3,5GHz">
  <figcaption>Source : <a href="https://www.arcep.fr/fileadmin/cru-1614035751/user_upload/grands_dossiers/5G/aspects-techniques-5G-imbrication-entre-4G-et-5G.pdf#page=4">Arcep</a></figcaption>
</figure>

## La 5G sur des bandes de fréquences actuellement 4G
La 5G peut être déployée sur des fréquences actuellement utilisées en 4G (bande 700 MHz). Si la bande est déjà déployée en 4G dans la zone, on peut remplacer la ressource 4G par une ressource 5G plus optimisée en débit. Cela signifie que plus d'usagers pourront se connecter en 5G là où il y avait déjà la 4G. (Source : [Arcep](https://www.arcep.fr/fileadmin/cru-1614035751/user_upload/grands_dossiers/5G/aspects-techniques-5G-imbrication-entre-4G-et-5G.pdf#page=5))

Plus concrètement, la 5G utilise des antennes dites "massives" (*massive MIMO antennas*) qui ont pour but d’augmenter la directivité. Les antennes MIMO émettent le signal uniquement dans la direction du mobile en communication, plutôt que dans un large secteur comme le font les antennes à faisceau fixe communément utilisées en 4G. Cette caractéristique  augmente significativement le débit délivré par une antenne, chacun pouvant réutiliser les fréquences de la cellule. 

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/antenne_active.png" alt="Une exposition aux ondes optimisée grâce à l’orientation des signaux vers les appareils qui en ont besoin.">
  <figcaption>Source : <a href="https://www.economie.gouv.fr/files/files/PDF/2020/Brochure_5G_WEB.PDF#page=5">Arcep</a></figcaption>
</figure>


## 5G Non Stand Alone (NSA) et bande d’ancrage
Pour l'instant, la 5G fonctionne avec un cœur de réseau 4G : on parle de 5G "Non Stand Alone". Pour accéder à la 5G il faut donc être dans une zone couverte par la bande 5G, *mais aussi* couverte par la bande 4G portant la signalisation. Cette bande 4G "de pilotage" est appelée **bande d’ancrage**.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/5G_bande_dancrage.png" alt="5G Non Stand Alone et bande d’ancrage">
  <figcaption>Source : <a href="https://www.arcep.fr/fileadmin/cru-1614035751/user_upload/grands_dossiers/5G/aspects-techniques-5G-imbrication-entre-4G-et-5G.pdf#page=7">Arcep</a></figcaption>
</figure>

## 5G Stand Alone (SA)
La 5G "Stand Alone" contrôlée par un cœur de réseau 5G sera mise en place à partir de 2022 ou 2023. Cette architecture a été spécifiée en considérant les concepts de virtualisation des fonctions réseau  (NFV - *Network Function Virtualisation*). Il s'agit d'un concept d’architecture réseau qui utilise les technologies de virtualisation informatique pour virtualiser des classes entières de fonctions de nœuds réseau en blocs de construction qui peuvent se connecter, ou enchaîner, pour créer des services de communication.

# Sommaire
- [Article 1 : La 5G, c'est quoi?]({{ site.url }}{{ site.baseurl }}/2021/02/05/la-5g-cest-quoi.html). 
- [Article 3 : Quelle consommation est associée à la 5G?]({{ site.url }}{{ site.baseurl }}/2021/02/19/quelle-consommation-est-associee-a-la-5g.html).
- [Article 4 : La 5G peut elle provoquer une réduction des gaz à effet de serre?]({{ site.url }}{{ site.baseurl }}/2021/02/26/la-5G-peut-elle-provoquer-une-reduction-des-ges.html)