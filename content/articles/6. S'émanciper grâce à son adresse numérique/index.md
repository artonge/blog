---
title: "S'émanciper grâce à son adresse numérique"
date: 2020-06-04
author: Louis Chemineau
aliases:
  - /blog/emancipate-with-digital-address
---

Proche d'une sorte de "darwinisme numérique", les logiciels décentralisés tel que Nextcloud, Mastodon, ou Peertube, ont tous évolué jusqu'à être capables de se connecter à une fédération de services similaires. Derrière cette fonctionnalité, se cache un socle essentiel d'Internet, les noms de domaine.

## Les noms de domaine

Les noms de domaine sont apparus dès 1985, afin de palier à la difficulté de se souvenir des adresses IP, longue série de chiffres identifiant un ordinateur. Il est possible pour n'importe qui, organisation ou particulier, de louer des noms de domaine auprès d'organismes accrédités.

Par exemple, l'adresse IP du nom de domaine `gouvernement.fr` est `185.11.125.117`, et l'ordinateur associé à cette adresse IP, héberge le site du gouvernement. Les noms de domaine sont donc très pratiques pour accéder facilement, et de manière sécurisée, aux sites internet en général. Mais ils apparaissent aussi dans certaines adresses, elles aussi fortement utiles, que sont les adresses e-mails.

Par exemple, on pourrait imaginer que l'adresse e-mail du président ressemble à l'adresse suivante: `president@gouvernement.fr`.

Cette adresse mail, qui permettrait, théoriquement, de contacter le président, pourrait-elle aussi servir à identifier le président au travers d'autres protocoles, tel que [Matrix]({{< ref "../3. Matrix, un protocole pour les gouverner tous/index.md" >}}) ou [Activity Pub]({{< ref "../5. Peertube, fédérer pour mieux s'exprimer/index.md" >}}) ?

## L'adresse numérique

Vous l'aurez compris, c'est une question rhétorique. Grâce à cette adresse numérique, il serait possible de contacter le président au travers de différents protocoles, sous condition qu'il les utilise effectivement.

Ci-dessous, un tableau listant plusieurs protocoles, les fonctionnalités qu'ils dispensent et les applications qui nous permettent de les utiliser. On peut observer, en particulier, que le protocole Activity Pub, permettant de publier de nombreux types de média, est utilisable via plusieurs applications, chacune optimisée pour le contenu qu'elle traite.

| Protocole       | Fonctionnalité               | Application            |
| --------------- | ---------------------------- | ---------------------- |
| Email           | Envoie de messages           | Client mail quelconque |
| Matrix          | Communication instantanée    | Riot                   |
| Open Cloud Mesh | Partage de fichiers          | Nextcloud              |
| ActivityPub     | Blogging                     | Write.as               |
| ActivityPub     | Microblogging                | Mastodon               |
| ActivityPub     | Publication de vidéo         | Peertube               |
| ActivityPub     | Publication musicale         | Funkwhale              |
| ActivityPub     | Publication de photographies | Pixelfed               |
| ActivityPub     | Organisation d'évenements    | Mobilizon              |

Derrière une simple adresse numérique, peut donc se cacher une myriade de services permettant d'interagir avec un individu.

Le fait d’être identifié par un nom de domaine que l'on détient, permet, à l'utilisateur ou à l'organisation, de changer d'hébergeur sans avoir à informer ses contacts d'un changement d'adresse numérique, car celle-ci reste la même. L'utilisateur peut alors s'émanciper lorsqu'il le souhaite de son hébergeur et n'est donc plus dépendant d'une plateforme qu'il ne peut quitter, sous peine de se couper du réseau. Il peut même décider d'héberger, lui-même et chez lui, tous ces services. Une réelle indépendance numérique peut alors se mettre en place, dans laquelle l'utilisateur est maître des logiciels et du matériel qu'il utilise. Cette liberté de mouvement octroie alors à l'utilisateur un certain pouvoir, celui d'être en mesure d'exiger certaines choses de la part des développeurs et des hébergeurs.

{{< about >}}
