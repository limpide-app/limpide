# Limpide

Des tableaux de bord limpides, qui se mettent à jour tout seuls.

Limpide transforme des exports Excel, des fichiers CSV, des listes SharePoint, des tables Dataverse et des API web en tableaux de bord qui se mettent à jour tout seuls. L'agent IA installé sur votre poste les construit avec vous ; ensuite, tout tourne sans lui, sur votre poste, et vos données y restent.

Ce dépôt contient les installeurs de Limpide et les notes de chaque version. Limpide est développé par Cybermatik.

## Télécharger

La dernière version est sur la [page des versions](https://github.com/limpide-app/limpide/releases/latest), dans « Assets ».

| Système | Fichier |
| --- | --- |
| Windows 10 et 11, processeur Intel ou AMD | `Limpide_<version>_x64-setup.exe` |
| Windows 11 sur processeur ARM | `Limpide_<version>_arm64-setup.exe` |
| macOS 12 ou plus récent, puce Apple | `Limpide_<version>_aarch64.dmg` |

Les fichiers `latest.json` et `Limpide.app.tar.gz` servent aux mises à jour automatiques : inutile de les télécharger.

## Installer

Les installeurs ne sont pas encore signés pour Windows et macOS : le système avertit à la première ouverture.

- **Windows** : l'installeur s'installe pour l'utilisateur, sans droits d'administrateur. Si Windows affiche « Windows a protégé votre ordinateur », cliquez sur « Informations complémentaires », puis « Exécuter quand même ».
- **macOS** : ouvrez le `.dmg` et glissez Limpide dans Applications. À la première ouverture, macOS refuse une application non notarisée : ouvrez Réglages Système, Confidentialité et sécurité, puis « Ouvrir quand même » en face de Limpide.

## Mises à jour

Limpide cherche ses nouvelles versions ici même, au démarrage puis deux fois par jour. Il montre leurs nouveautés et demande avant d'installer. Une version n'est installée que si elle porte la signature de Limpide : une version modifiée, ou venue d'ailleurs, est refusée. Sur un poste géré par un service informatique, la variable d'environnement `LIMPIDE_UPDATES=off` coupe la recherche.

## Licence

Limpide s'essaie gratuitement sur un projet d'un seul thème. Une licence nominative, émise par Cybermatik, débloque tous les projets et tous les thèmes ; elle s'installe dans Limpide, Paramètres généraux, carte Licence. Le logiciel est distribué sous [Elastic License 2.0](https://www.elastic.co/licensing/elastic-license).

## Contact

Une démonstration, un devis, une question : [dimitri.goimbault@cybermatik.fr](mailto:dimitri.goimbault@cybermatik.fr?subject=Limpide).
