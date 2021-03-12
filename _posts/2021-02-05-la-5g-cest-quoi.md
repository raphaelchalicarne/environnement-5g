---
layout: post
title: "La 5G, c'est quoi?"
image: assets/images/cell-tower-5390644_1920.jpg
---

# Présentation
La 5G consiste en un standard de téléphonie mobile international élaboré par le 3rd Generation Partnership Project ([3GPP](https://www.3gpp.org/)). L'objectif [selon l'Arcep](https://www.arcep.fr/la-regulation/grands-dossiers-reseaux-mobiles/la-5g.html), n'est plus seulement de toucher les opérateurs mobiles grand public, mais de faciliter l'adoption de nouveaux usages au sein d'une même technologie.

# Performances

La 5G Infrastructure Public Private Partnership ([5G-PPP](https://5g-ppp.eu/)) a défini des indicateurs de performances clés correspondant aux objectifs qui doivent être atteints par la 5G par rapport à la 4G.
<figure class="align-center">
<table>
<thead>
  <tr>
    <th>Performances/Génération</th>
    <th>4G</th>
    <th>5G</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Débit maximal (Gbit/s)</td>
    <td>1</td>
    <td>20</td>
  </tr>
  <tr>
    <td>Débit aperçu par l’utilisateur (Mbit/s)</td>
    <td>10</td>
    <td>100</td>
  </tr>
  <tr>
    <td>Vitesse (km/h)</td>
    <td>350</td>
    <td>500</td>
  </tr>
  <tr>
    <td>Latence (ms)</td>
    <td>10</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Nombre d’objets connectés sur une zone (quantité d’objets/km²)</td>
    <td>10^5</td>
    <td>10^6</td>
  </tr>
  <tr>
    <td>Efficacité énergétique du réseau</td>
    <td>1x</td>
    <td>100x</td>
  </tr>
  <tr>
    <td>Débit sur une zone (Mbit/s/m²)</td>
    <td>0,1</td>
    <td>10</td>
  </tr>
</tbody>
</table>
<figcaption>Source : <a href="https://5g-ppp.eu/wp-content/uploads/2017/10/Euro-5G-D2.6_Final-report-on-programme-progress-and-KPIs.pdf#%5B%7B%22num%22%3A59%2C%22gen%22%3A0%7D%2C%7B%22name%22%3A%22XYZ%22%7D%2C82%2C781%2C0%5D">5G-PPP</a></figcaption>
</figure>

# Familles d'usage
La 5G se répartit en trois familles d'usage qui sont caractérisées par des usages et des performances appropriées. (Source : [Arcep](https://www.arcep.fr/fileadmin/cru-1614035751/reprise/dossiers/collectivites/ateliers-TC-2019/atelier-TC-5G-part01-260619.pdf#page=4))

* **eMBB : Enhanced Mobile Broadband** : Cette famille correspond au **très haut débit mobile** et représente l’évolution de la plupart des services proposés par les réseaux 4G. C'est d'abord cet usage qui sera activé.
* **mMTC : Massive Machine Type Communications (connexion d’un nombre massif d’objets connectés)** : Cette famille regroupe principalement les usages liés à l’Internet des objets. Ces services nécessitent une couverture étendue, une consommation énergétique contenue et des débits relativement restreints.
* **uRLLC : Ultra-reliable and Low Latency Communications (les communications critiques à très faible latence et très haute fiabilité)** : Cette famille regroupe toutes les applications nécessitant une réactivité extrêmement importante ainsi qu’une garantie très forte de transmission du message.

## Configuration en tranches ("network slicing")
Chaque famille d'usages correspond à un ensemble de performances adaptées. Les indicateurs de performance ne pourront être tous satisfaits simultanément sur un même réseau. Les réseaux 5G seront donc configurés en "tranches" qui s'adapteront dynamiquement à la demande, en fonction des usages. Cela est rendu possible par la "virtualisation" logicielle des fonctions, qui est la fonctionnalité la plus innovante de la 5G. Elle est attendue pour 2023.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/5G_usages_kpi.png" alt="Performances attendues selon les usages de chaque famille">
  <figcaption>Source : <a href="https://www.arcep.fr/fileadmin/cru-1614035751/reprise/dossiers/collectivites/ateliers-TC-2019/atelier-TC-5G-part01-260619.pdf#page=5">Arcep</a></figcaption>
</figure> 

# Bandes de fréquences
3 bandes ont été identifiées au niveau européen comme "pionnières" pour la 5G. Elles possèdent des propriétés différentes et complémentaires.
<figure class="align-center">
<table>
<thead>
  <tr>
    <th>Fréquences</th>
    <th>Date d'attribution</th>
    <th>Pénétration à l'intérieur</th>
    <th>Portée</th>
    <th>Débit</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><strong>700 Mhz</strong> : déjà attribuée aux opérateurs (depuis 2015) et utilisée pour la 4G, elle est pleinement disponible depuis mi-2019.</td>
    <td>2015</td>
    <td>★★★★</td>
    <td>★★★★</td>
    <td>★</td>
  </tr>
  <tr>
    <td><strong>3400 - 3800 MHz</strong> : elle est souvent identifiée comme la bande "coeur 5G"</td>
    <td>2020</td>
    <td>★★</td>
    <td>★★★</td>
    <td>★★★</td>
  </tr>
  <tr>
    <td><strong>26 GHz</strong> : Bande "millimétrique" avec des fréquences très élevées jusqu’à présent utilisées pour les liaisons satellitaires ou d’infrastructure, elle permettra des débits très importants dans des cellules de petites taille.</td>
    <td>Non attribuée</td>
    <td>★</td>
    <td>★</td>
    <td>★★★★</td>
  </tr>
</tbody>
</table>
<figcaption>Sources : <a href="https://www.arcep.fr/fileadmin/cru-1614035751/user_upload/grands_dossiers/5G/introduction-5G-usages-et-frequences.pdf#page=5">Arcep</a> et <a href="https://www.hautconseilclimat.fr/wp-content/uploads/2020/12/haut-conseil-pour-le-climat_rapport-5g.pdf#page=10">Haut Conseil pour le Climat</a></figcaption>
</figure>

Les principales performances attendues de la 5G - augmentations des débits, réduction de la latence, et augmentation de la densité possible de terminaux connectés reposent sur l’utilisation des andes de fréquences à 3,5 GHz et 26 GHz, souvent appellée "vraie 5G".

# Sommaire
- [Article 2 : La 5G, comment ça fonctionne?]({{ site.url }}{{ site.baseurl }}/2021/02/12/la-5G-comment-ca-fonctionne.html).
- [Article 3 : Quelle consommation est associée à la 5G?]({{ site.url }}{{ site.baseurl }}/2021/02/19/quelle-consommation-est-associee-a-la-5g.html).
- [Article 4 : La 5G peut elle provoquer une réduction des gaz à effet de serre?]({{ site.url }}{{ site.baseurl }}/2021/02/26/la-5G-peut-elle-provoquer-une-reduction-des-ges.html)