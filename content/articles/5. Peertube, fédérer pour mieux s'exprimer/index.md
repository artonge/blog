---
title: "Peertube, fédérer pour mieux s'exprimer."
date: 2020-05-28
author: Louis Chemineau
tags:
  - Protocole
  - Peertube
  - Logiciels libres
  - Émancipation
  - Numérique
  - Alternatives
  - Souveraineté
  - Fédération
  - Créateurs
  - Youtube
---

[Framasoft](https://framasoft.org), l'une des associations référente dans l'univers des logiciels libres français, est depuis longtemps une porte d'entrée pour découvrir de nombreux services libres. Elle propose, gratuitement, plusieurs dizaines d'alternatives éthiques, permettant aux personnes à l'aise techniquement de profiter facilement de ces logiciels. Depuis quelques temps, Framasoft a décidé de changer son type de contribution au libre, passant d’hébergeur à développeur. Dans cet article, nous allons découvrir l'un de leur projet, [Peertube](https://joinpeertube.org), alternative à Youtube, dont la raison d’être a plus que jamais de sens, à l'aube de l'application de la loi Avia.

## Peertube

C'est au travers d'une campagne de financement participatif que Peertube a vu le jour en 2018. Portée par l'association Framasoft, cette campagne est rapidement un succès. Réitéré une seconde fois en 2019, avec le même succès, Framasoft espère actuellement réussir un troisième financement pour une troisième version de Peertube.

Peertube, est une alternative à Youtube, mais l'objectif n'est pas de copier les fonctionnalités de Youtube, ni de recréer une plateforme unique de diffusion de vidéos. Non, l'objectif est de permettre à chacun d'être maître de son propre service de diffusion de vidéos, à la fois en contrôlant les contenus qui y sont publiés, et en contrôlant les fonctionnalités qui y sont inclues.

[Nous avons vu]({{< ref "../3. Matrix, un protocole pour les gouverner tous/index.md" >}}) l’intérêt et le fonctionnement d'un système de fédération. Peertube utilise le protocole ActivityPub afin de communiquer entre utilisateurs de différentes instances. Par exemple, un utilisateur du serveur `tube-paris.beta.education.fr`, l'instance de l'académie de Paris, peut suivre et interagir avec les vidéos de `thinkerview.video`. Mais le protocole ActivityPub ne s’arrête pas à la publication de vidéos. Il est, de manière générale, un protocole permettant la diffusion de publications sociales de manière décentralisée. Plus concrètement, il est possible de suivre et d'interagir avec les vidéos d'une chaîne Peertube depuis un compte Mastodon, une alternative à Twitter.

Peertube facilite aussi l'administration d'une instance ayant une grande audience, sans que celle-ci croule sous les coûts de location des serveurs. En effet, avec Youtube, les internautes lisent la vidéo à partir des serveurs de Youtube. Pour Peertube, les spectateurs peuvent échanger entre eux les fichiers vidéos, réduisant la charge sur les serveurs. C'est la technologie paire à paire, ou peer to peer en anglais.

{{< figure src="peertube-federation-multiplicity.jpg" width="100%" caption="Modèle de fédération de Peertube - CC-By SA LILA">}}

## De la censure automatisée à la modération humaine.

La censure sur les réseaux sociaux est de plus en plus présente. Elle est principalement dûe à deux facteurs.

Premièrement, la morale du réseau social et de ses administrateurs. Ces derniers sont issus d'une certaine culture et ont donc une certaine morale. Cette morale, peut ne pas être celles des utilisateurs. Certains sujets, anodins pour quelques utilisateurs, peuvent être tabou pour les administrateurs, et donc se voir censurés. Une censure peut aussi se voir appliquer en fonction du type d'utilisateurs que les administrateurs souhaitent voir utiliser leur plateforme. Dans le cas des réseaux sociaux dominants, comme Facebook, la cible étant le plus grand nombre, les contenus doivent convenir au plus grand nombre. Aucune place n'est donc possible pour la différence, la dissidence et donc la pluralité et l'évolution d'idées.

Le second facteur est la pression législative. En France, celle ci se voit accrue à l'approche de la mise en application de la loi Avia. Cette loi demande aux administrateurs de grandes plateformes sociales de retirer, sous 24 heures, tous les contenus qualifiés de haineux, sous peine de se voir sanctionner d'une amende. Ceci rajoute une pression sur les administrateurs qui se voient obligés de retirer très rapidement certains contenus, préférant alors censurer hâtivement plutôt que de se voir sanctionnés.

La décentralisation de l'administration de plateformes sociales permet, en revanche, de réduire les censures abusives. Premièrement, en permettant aux créateurs de contenus de choisir leur hébergeur, réduisant alors la friction entre deux morales différentes. Ceci permet aussi de décentraliser la modération à un plus grand nombre d'administrateurs. La modération devient alors plus humaine et moins abusive.

Un exemple récent est celui du collectif QueerMotion, proposant d'héberger le contenu de créateurs non binaires sur leur instance Peertube, communauté particulièrement sujet à la censure.

Grâce au protocole ActivityPub et au travail des développeurs de logiciels comme Peertube, il est donc possible pour l'utilisateur de choisir le type de réseau social qu'il souhaite utiliser, micro-blogging, vidéo, image, etc, sans se couper du reste du contenu publié sur les autres réseaux. Il est aussi possible pour l'utilisateur de choisir le serveur et donc l'administrateur auquel il donne le pouvoir de modération sur le contenu qu'il peut voir et publier. L’administrateur pouvant ainsi être l'utilisateur lui-même, lui permettant de conserver ce pouvoir.

{{< about >}}
