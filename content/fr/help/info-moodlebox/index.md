---
title: Tableau de bord de la MoodleBox
authors:
  - Nicolas Martignoni
type: kb
date: 2017-11-12
lastmod: 2019-04-16
description: MoodleBox est fournie avec un tableau de bord permettant d'afficher différentes informations sur le matériel et le logiciel installé.
slug: tableau-de-bord
weight: 10
aliases:
  - quelle-est-la-version-de-ma-moodlebox
categories:
  - Premiers pas
  - Maintenance
---

Le tableau de bord de la MoodleBox se trouve dans l'interface d'administration, sous [Administration du site > Serveur > MoodleBox][1]. Il n'est accessible que pour les administrateurs de la plateforme.

{{< notice note >}}
Lorsque l'alimentation de la MoodleBox est insuffisante, __un avertissement est affiché en haut de chaque page__. Cette avertissement n'est visible que pour l'administrateur. Les autres utilisateurs de la MoodleBox ne le voient pas.
{{< /notice >}}

Le tableau de bord donne accès aux informations importantes sur le fonctionnement de la MoodleBox.
{{< figure src="info-moodlebox.png" width="750" caption="Informations MoodleBox" class="centered-image" >}}

Il permet également d'effectuer les opérations ci-dessous.

- Modifier la date et l'heure de la MoodleBox, lorsque celle-ci n'est pas connectée à Internet.
- [Changer le mot de passe principal][3] de la MoodleBox
- [Modifier la configuration du réseau Wi-Fi][4] fourni par la MoodleBox
- [Redémarrer ou éteindre][5] la MoodleBox

 [1]: http://moodlebox.home/admin/tool/moodlebox/index.php
 [3]: {{< relref "change-password" >}}
 [4]: {{< relref "wi-fi-configuration" >}}
 [5]: {{< relref "startup-shutdown-restart" >}}