---
title: "Matrix un protocole pour les gouverner tous ?"
date: 2020-05-14
author: Louis Chemineau
aliases:
  - /blog/matrix-un-protocole-pour-les-gouverner-tous
---

> ...et dans la lumière les lier.

Non, il ne s'agit pas d'un crossover entre "Matrix" et "Le Seigneur des anneaux", mais de la mission dont se sont emparés les développeurs de Matrix, un protocole très séduisant pour construire de nouveaux services de communication, car il dispose de deux fonctionnalités clés, le chiffrement de bout en bout et la fédération.

Commençons avant tout par discuter de l'intérêt de construire un énième service de communication. Il y en a au moins deux.

Premièrement, cela permet d'inclure un chat dans un service dont ce n'est pas la priorité. Par exemple, Leboncoin permet à des utilisateurs de communiquer, mais la communication n'est pas leur spécialité, leur chat est donc rudimentaire. On pourrait imaginer qu'ils utilisent de projets développés autour de Matrix pour créer un service de communication plus poussé.

Deuxièmement, la nécessité d'indépendance. Certaines organisations ne peuvent pas, pour plusieurs raisons, dépendre de grands fournisseurs de service de communication. C'est le cas de l'armée allemande ou du gouvernement français. Ce dernier a, par exemple, déployé le projet Tchap qui permet aux agents de l'État de communiquer en toute sécurité sur une plateforme administrée par le gouvernement français.

## Le chiffrement de bout en bout

Le chiffrement de bout en bout est une méthode de protection qui permet le chiffrement et déchiffrement des messages uniquement sur les appareils des utilisateurs. Ceci signifie que les fournisseurs de services ne peuvent avoir accès au contenu des messages, et ce, que leurs motivations soient d'ordre financier ou bien légal. Ce mécanisme est inclus dans le protocole Matrix. Ceci vous permet de communiquer en toute intimité, même si vous ne faite pas confiance à votre hébergeur ou à celui de votre correspondant.

Néanmoins, le chiffrement de bout en bout ne résout pas tout. Prenons l'exemple de WhatsApp, qui inclut cette méthode. Non seulement la validité de leur mise en place fait débat, mais en plus, leurs motivations financières passant avant tout, ils ont astucieusement contourné les limitations, en intégrant à leur application, et donc sur les appareils des utilisateurs, les logiques nécessaires à la récolte de données. Dans ce cas, si WhatsApp était sous licence libre, on imagine facilement qu'une version alternative aurait rapidement été publiée, et ce, sans les mécanismes de récolte de données. Matrix, en revanche, de part son ouverture, permet à chacun, particulier ou organisation, de proposer des applications sous la licence qu'il souhaite.

## La fédération

Pour expliquer le concept de fédération, il suffit d'étudier le fonctionnement des mails. Si vous avez un compte Gmail, rien ne vous empêche de communiquer avec une personne ayant un compte Outlook. Ces deux services sont dits "fédérés", car ils utilisent le même protocole pour communiquer, bien qu'ils soient proposés par deux organismes différents. Le protocole Matrix, de la même manière, permet à plusieurs organisations de créer des services de communication pouvant communiquer entre eux. Pour revenir à l'exemple de la France et du service Tchap, si les administrateurs de Tchap l'autorisaient, il serait possible de créer une communication direct entre des comptes Tchap et des comptes Riot, et cela, aussi facilement qu'avec les mails. Riot est actuellement la principale application compatible avec le protocole Matrix.

Mais ce n'est pas tout, Matrix souhaite aussi fédérer les différents services existants comme Slack, Telegram et Discord. Ceci permet, par exemple, à un utilisateur de Slack et à un utilisateur de Discord d'être réunis au sein d'une même conversation, tout en restant sur leurs applications respectives.

{{< figure src="bridges_lotsofmatrix.svg" width="100%" caption="Matrix crée des ponts vers les autres services">}}

En pratique, l’interconnexion avec les fournisseurs de grands services de communication n'est pas simple. Ces derniers ne font pas d'efforts pour aider le projet, il faut donc constamment adapter les ponts entre services pour qu'ils continuent de fonctionner. De plus le chiffrement de bout en bout est presque impossible à mettre en place. Mais fort d'une communauté très productive, l'expérience se fait de plus en plus stable pour les utilisateurs.

[Nous avons vu]({{< ref "../2. Logiciels libres, cancer du numérique ou solution d'émancipation/index.md" >}}) comment les logiciels libres permettaient une émancipations des utilisateurs par rapport aux services qu'ils utilisent. C'est ici un cas concret. Le protocole Matrix, grâce à sont ouverture et sa volonté d'unir plutôt que de fragmenter, permet à chacun de choisir la plateforme de communication qu'il préfère. Bien entendu, les messages que vous échangez avec vos contacts présents sur les autres plateformes seront visibles par ces dernières. Mais vous n'êtes plus retenu par le fameux effet réseau, qui vous pousse à utiliser les services que vos contacts utilisent.

{{< about >}}
