# Delta.DomOS — logiciels libres et licences

Delta.DomOS assemble des logiciels libres et des composants propres à Delta.Dom. Ce dépôt réunit leurs licences :
la liste des paquets du système avec leur version et leur licence, les fichiers de licence de chacun, ceux des
composants de tiers de l'interface, et les textes officiels des licences citées.

Version décrite : **Delta.DomOS 17.3.dev111**.

## Remerciements

Delta.DomOS n'existerait pas sans les projets libres listés ici. Merci à leurs auteurs et à leurs contributeurs.

## Les grands composants

| Composant | Licence |
|---|---|
| Noyau Linux | GPL-2.0 |
| Outils et bibliothèques du système (BusyBox, systemd, bibliothèque C GNU, NetworkManager…) | GPL · LGPL · autres, selon le paquet : voir [la liste détaillée](systeme/manifest.csv) |
| Moteur de conteneurs Docker | Apache-2.0 |
| Système d'exploitation de base — projet amont, version modifiée par Delta.Dom | Apache-2.0 |
| Cœur domotique — projet amont, version modifiée par Delta.Dom | Apache-2.0 |
| Superviseur — projet amont, version modifiée par Delta.Dom | Apache-2.0 |
| Pont Zigbee (Zigbee2MQTT) | GPL-3.0 |
| Traitement vidéo (FFmpeg) | GPL-3.0 |
| Lecteur de projets ETS (Delta.Dom, code source livré avec le serveur) | GPL-2.0 |
| Courtier MQTT (Mosquitto) | EPL-2.0 |

Le résumé des modifications apportées par Delta.Dom aux projets amont figure dans le fichier `NOTICE-Delta.Dom.txt`,
livré avec chaque serveur.

## Paquets du système

- [`systeme/manifest.csv`](systeme/manifest.csv) : les 104 paquets du système, avec leur version, leur licence et
  l'adresse de leur source d'origine ;
- [`systeme/licences/`](systeme/licences) : les fichiers de licence de chaque paquet.

## Composants de tiers de l'interface

| Composant | Version | Licence | Modifié par Delta.Dom | Texte |
|---|---|---|---|---|
| [Alarmo](https://github.com/nielsfaber/alarmo) | 1.10.11 | Apache-2.0 | oui | [alarmo.LICENSE](interface/alarmo.LICENSE) |
| [Browser Mod](https://github.com/thomasloven/hass-browser_mod) | 2.7.0-beta.3 | MIT | non | [hass-browser_mod.LICENSE](interface/hass-browser_mod.LICENSE) |
| [Frigate (intégration)](https://github.com/blakeblackshear/frigate-hass-integration) | 5.15.4 | MIT | oui | [frigate-hass-integration.LICENSE](interface/frigate-hass-integration.LICENSE) |
| [Favicon](https://github.com/thomasloven/hass-favicon) | 10.4 | MIT | oui | [hass-favicon.LICENSE](interface/hass-favicon.LICENSE) |
| [Climate Group](https://github.com/daenny/climate_group) | 0.4.2 | MIT | non | [climate_group.LICENSE](interface/climate_group.LICENSE) |
| [auto-entities](https://github.com/thomasloven/lovelace-auto-entities) | 1.16.1 | MIT | non | [lovelace-auto-entities.LICENSE](interface/lovelace-auto-entities.LICENSE) |
| [button-card](https://github.com/custom-cards/button-card) | 7.0.1 | MIT | non | [button-card.LICENSE](interface/button-card.LICENSE) |
| [Mushroom](https://github.com/piitaya/lovelace-mushroom) | 4.5.0 | Apache-2.0 | non | [lovelace-mushroom.LICENSE](interface/lovelace-mushroom.LICENSE) |
| [go2rtc — lecteur VideoRTC](https://github.com/AlexxIT/go2rtc) | VideoRTC 1.6.0 (go2rtc v1.9.14) | MIT | oui | [go2rtc.LICENSE](interface/go2rtc.LICENSE) |
| [hass-web-proxy-lib](https://github.com/dermotduffy/hass-web-proxy-lib) | 0.0.8 | MIT | oui | [hass-web-proxy-lib.LICENSE](interface/hass-web-proxy-lib.LICENSE) |
| [titlecase](https://github.com/ppannuto/python-titlecase) | 2.4.1 | MIT | non | [python-titlecase.LICENSE](interface/python-titlecase.LICENSE) |
| Lecteur de projets ETS (Delta.Dom, code source livré avec le serveur) | 1.0 | GPL-2.0-only | non | [lecteur-ets.COPYING](interface/lecteur-ets.COPYING) |
| [Chart.js](https://github.com/chartjs/Chart.js) | 4.4.1 | MIT | non | [chartjs.LICENSE](interface/chartjs.LICENSE) |
| [Leaflet](https://github.com/Leaflet/Leaflet) | 1.9.4 | BSD-2-Clause | non | [leaflet.LICENSE](interface/leaflet.LICENSE) |

Les modifications des composants marqués « oui » sont décrites dans le fichier `MODIFICATIONS-Delta.Dom.txt` de
chacun, ou en tête du fichier modifié, sur le serveur.

## Textes des licences

[GPL-2.0](textes/GPL-2.0.txt) · [GPL-3.0](textes/GPL-3.0.txt) · [LGPL-2.1](textes/LGPL-2.1.txt) ·
[LGPL-3.0](textes/LGPL-3.0.txt) · [AGPL-3.0](textes/AGPL-3.0.txt) · [Apache-2.0](textes/Apache-2.0.txt) ·
[MPL-2.0](textes/MPL-2.0.txt) · [EPL-2.0](textes/EPL-2.0.txt) · [BSD-2-Clause](textes/BSD-2-Clause.txt) ·
[BSD-3-Clause](textes/BSD-3-Clause.txt) · [MIT](textes/MIT.txt) · [ISC](textes/ISC.txt)

## Code source

Pendant au moins trois ans après la dernière livraison de cette version, et tant que Delta.Dom en assure le support,
Delta.Dom fournit à toute personne qui le demande une copie complète, lisible par machine, du code source
correspondant des composants sous licence GPL, LGPL ou AGPL de Delta.DomOS, sans autre frais que le coût matériel de
la copie. Demande à contact@delta-dom.fr, en indiquant la version.

« Cette version » est la version de Delta.DomOS installée sur votre serveur, affichée dans les informations du système.

## Composants Delta.Dom

Les intégrations, les cartes de l'interface et les compilateurs propres à Delta.Dom sont la propriété de Delta.Dom
SASU, tous droits réservés. Ce ne sont pas des logiciels libres.

Contact : contact@delta-dom.fr
