# Politique de confidentialité

_Dernière mise à jour : 13 octobre 2026._

Interior Mood est une application Android d'aménagement intérieur en 3D, éditée par un
particulier. Elle fonctionne **sur votre appareil** : sans compte, rien n'est envoyé. Un
**compte Google facultatif** permet de sauvegarder vos données dans votre propre Google Drive et
de **partager un dossier chantier** avec les personnes que vous invitez (sections 6 bis et 6 ter).
Si vous connectez votre **Home Assistant**, l'application échange directement avec lui
(section 6 quater). L'application n'affiche pas de publicité et n'intègre aucun outil de mesure
d'audience.

## 1. Responsable

L'éditeur de l'application est responsable des traitements décrits ici.

Contact : **serge.simono27@gmail.com**

## 2. Ce qui est enregistré sur l'appareil

| Donnée | Finalité | Durée |
| --- | --- | --- |
| Projets : pièces, dimensions, meubles, matériaux, éclairage, variantes | Retrouver vos aménagements | Jusqu'à ce que vous les supprimiez ou désinstalliez l'application |
| Géométrie et mesures issues d'un scan | Reconstituer la pièce à sa taille réelle | Comme les projets |
| Suivi des travaux : lots, artisans (nom, entreprise, téléphone, e-mail, adresse, notes que vous saisissez), devis, factures, paiements, avenants, budget | Piloter votre chantier | Comme les projets |
| Planning, journal de chantier et problèmes notés (dont les réserves de fin de travaux) | Suivre le chantier | Comme les projets |
| Décisions prises, garanties (artisan, durée, dates) et date de réception des travaux | Garder la trace du chantier et des garanties | Comme les projets |
| Photos de chantier | Garder l'état avant, l'avancement et le résultat des travaux | Jusqu'à ce que vous les supprimiez ou désinstalliez l'application |
| Documents copiés dans l'application (devis, factures, photos) | Les retrouver même si l'original est déplacé | Jusqu'à ce que vous les supprimiez ou désinstalliez l'application |
| Fichiers exportés (rapport, tableurs, données, sauvegarde) avant leur partage | Vous les remettre pour que vous les partagiez ou les enregistriez | Dossier temporaire : effacés lors d'un export suivant s'ils ont plus de 24 heures, ou par Android quand il libère de la place |
| Maison connectée : sources reliées (adresse de votre Home Assistant), appareils, pièces que vous leur donnez, dernières valeurs mesurées | Afficher votre logement en direct, même sans connexion | Jusqu'à ce que vous retiriez la source ou désinstalliez l'application |
| Historique de la maison connectée : relevés, résumés, événements (la présence seulement si vous l'activez) | Afficher l'évolution de chaque pièce | 7 jours, 90 jours et sans limite par défaut, réglables ; effaçable à tout moment |
| Jeton d'accès à Home Assistant | Vous connecter à votre Home Assistant | Chiffré sur l'appareil ; effacé quand vous retirez la connexion |
| Miniatures des projets | Afficher la liste des projets | Recréées au besoin, jamais sauvegardées |
| Réglages de l'application | Conserver vos préférences | Jusqu'à la désinstallation |

Ces données restent dans l'espace privé de l'application. Elles ne sont envoyées ni à
l'éditeur ni à un tiers, sauf ce que vous choisissez de sauvegarder en ligne ou de partager
(sections 6 bis et 6 ter).

## 3. Caméra, scan de la pièce et photos de chantier

La caméra n'est utilisée que si vous lancez un scan ou prenez une photo, et seulement après votre
autorisation.

Une **photo de chantier** est prise par l'application appareil photo de votre téléphone, puis
gardée dans l'espace privé d'Interior Mood ; une photo choisie dans votre galerie y est copiée.
Elle conserve les métadonnées que votre appareil photo y a écrites — dont la **position**, si vous
avez activé cette option dans votre appareil photo. Interior Mood ne lit pas cette position.
Seules les photos des tâches et des réserves d'un dossier que vous partagez sont envoyées
(section 6 ter) : **réduites et sans ces métadonnées**, sauf si vous choisissez d'envoyer l'original.

Pour le scan :
les images de la caméra sont analysées **sur l'appareil**, en temps réel, et **ne sont jamais
enregistrées** : seules la géométrie de la pièce (murs, portes, fenêtres) et ses mesures sont
conservées dans le projet.

Le scan en réalité augmentée repose sur les **Services Google Play pour la RA (ARCore)**,
fournis par Google et régis par les
[règles de confidentialité de Google](https://policies.google.com/privacy). L'application
reste entièrement utilisable sans ARCore, en traçant ou en saisissant la pièce.

## 4. Documents et lecture des devis

Un document (PDF ou photo) n'est ouvert que si vous le choisissez vous-même dans le sélecteur
d'Android. Vous décidez s'il est **lié** (l'application garde seulement l'autorisation de
relire le fichier à son emplacement) ou **copié** dans l'espace privé de l'application.

Lorsque vous importez un devis, son texte est lu par reconnaissance de caractères
(**ML Kit**, de Google) **entièrement sur l'appareil** : le modèle est intégré à
l'application et la lecture se fait sans connexion. Ni le document ni son texte ne sont
envoyés à l'éditeur, à Google ou à un tiers. Les montants et
informations repérés vous sont proposés, et ne sont enregistrés qu'après votre validation.

Les coordonnées des artisans que vous saisissez concernent d'autres personnes : elles restent
sur votre appareil et ne servent qu'à votre suivi de chantier.

## 4 bis. Assistant du chantier

Le résumé du jour, la revue de la semaine et les réponses aux questions (devis le plus complet,
dépassement du budget, tâches bloquées, factures à payer) sont **calculés sur l'appareil**, à
partir des seules données de votre dossier. Aucun service d'intelligence artificielle en ligne
n'est utilisé, et rien n'est envoyé. L'assistant ne prend aucune décision : il n'accepte pas de
devis et n'enregistre aucun paiement.

## 5. Ce qui ne quitte l'appareil qu'à votre demande

- **Rendus et plans** : une image n'est enregistrée dans votre galerie ou partagée que
  lorsque vous le demandez. Le partage passe par le menu de partage d'Android, vers
  l'application que vous choisissez.
- **Exports du chantier** : le rapport de fin de chantier (PDF), les tableurs (CSV), le
  dossier complet (JSON) et la sauvegarde complète ne sont créés que lorsque vous le demandez.
  Vous choisissez ensuite de les partager, par le menu de partage d'Android, ou de les
  enregistrer à l'emplacement de votre choix. Le dossier complet et la sauvegarde contiennent
  les coordonnées de vos artisans et vos montants, et la sauvegarde contient aussi vos photos et
  documents de chantier : ne les confiez qu'à des personnes de confiance.
- **Import** : un fichier n'est lu que si vous le sélectionnez vous-même.

## 6. Sauvegarde Android

Si la sauvegarde est activée dans les réglages de votre téléphone, Android peut copier les
projets et réglages de l'application dans **votre** compte Google, pour les restaurer sur un
nouvel appareil. Cette sauvegarde est gérée par Android et Google, chiffrée, et l'éditeur n'y
a pas accès. Les documents copiés et les photos de chantier en sont exclus en raison de leur taille ; ils sont en
revanche transférés lors d'un transfert direct vers un nouvel appareil. Le jeton d'accès à Home Assistant
n'est jamais sauvegardé ni transféré : sur un nouvel appareil, il faut le saisir à nouveau. Vous pouvez la désactiver dans les réglages de votre téléphone.

## 6 bis. Compte Google et sauvegarde en ligne (facultatifs)

La connexion avec Google n'est jamais nécessaire pour utiliser l'application. Si vous vous
connectez :

- votre **identifiant de compte**, votre **nom** et votre **adresse e-mail** sont transmis par
  Google au service d'authentification **Firebase** ;
- un **profil** (nom affiché, quelques réglages, date et taille de la dernière sauvegarde) est
  enregistré dans **Cloud Firestore** (Firebase, serveurs en Europe), lisible par vous seul ;
- la **sauvegarde en ligne**, lorsque vous la lancez, est une archive de vos projets, photos et
  documents déposée dans un **dossier caché de votre propre Google Drive**, que seule
  l'application peut lire. L'éditeur n'y a pas accès.

Firebase et Google Drive sont fournis par Google et régis par les
[règles de confidentialité de Google](https://policies.google.com/privacy). Vous pouvez
supprimer votre profil et votre sauvegarde depuis votre profil dans l'application ; la
déconnexion retire l'accès de l'application à votre compte.

## 6 ter. Dossiers chantier partagés

Partager un dossier chantier n'arrive que si vous invitez quelqu'un. Le dossier partagé est alors
enregistré dans **Cloud Firestore** (Firebase, serveurs en Europe) :

- l'**équipe** : nom affiché, rôle et droits de chaque membre (pas leur adresse e-mail) ;
- les **invitations** : nom de la personne qui invite, nom du dossier, rôle proposé et, si vous la
  saisissez, l'adresse e-mail de la personne invitée ;
- les **discussions**, épingles dans la 3D, fil d'activité, propositions et versions du design
  des pièces partagées, et la **présence** (l'écran ou la pièce où chacun se trouve) ;
- la **vue du chantier** : les lots, les tâches (dates, état, avancement), les réserves et
  problèmes (avec les noms des pièces et des entreprises), les demandes de photos et les
  **photos** de ces tâches et réserves ;
- les **documents partagés** (ceux que vous choisissez de partager, et ceux que l'équipe envoie,
  comme un devis), avec leurs versions et qui les a relus ;
- les **demandes de modification** de l'équipe, avec leur **coût** et leur délai, et votre décision.

Ne sont **jamais** partagés : les autres montants de votre dossier (devis saisis, factures,
paiements, budget), vos notes privées, les coordonnées des artisans, ni vos autres projets.
Les données d'un dossier partagé sont transmises aux téléphones de **tous ses membres**. Le
serveur vérifie ce que chacun a le droit de **modifier** ; ce que chacun **voit** est filtré
par l'application selon ses droits : par exemple, les documents financiers (devis, factures,
contrats) et les coûts ne s'affichent qu'aux membres qui voient le budget, et à leur auteur.
N'invitez donc que des personnes à qui vous confiez le contenu du dossier. Les données d'un dossier
partagé restent en ligne tant que le dossier est partagé ; pour les faire supprimer, écrivez
à l'adresse de contact.

## 6 quater. Maison connectée (facultative)

L'onglet « En direct » montre, pièce par pièce, ce que mesurent vos capteurs et l'état de vos
appareils. Il ne fonctionne que si vous reliez une source :

- la **maison de démonstration** simule des valeurs sur l'appareil ; rien n'est échangé ;
- **Home Assistant** : l'application se connecte **directement** à votre Home Assistant, à
  l'adresse que vous indiquez (sur votre réseau domestique, ou l'adresse d'accès à distance que
  vous avez choisie), avec un **jeton d'accès** que vous créez dans Home Assistant. Elle y lit la
  liste de vos zones, appareils et entités et leur état (températures, humidité, CO₂, éclairage,
  consommation, ouvertures, présence…). Rien ne passe par l'éditeur ni par un tiers, en dehors
  du service d'accès à distance que vous utilisez peut-être déjà pour Home Assistant.

Le jeton est **chiffré** avec une clé qui ne quitte pas l'appareil (Android Keystore) ; il n'est
jamais affiché, journalisé, sauvegardé ni partagé. Les dernières valeurs sont gardées sur
l'appareil pour afficher le logement hors connexion ; la **présence** (une pièce occupée ou non)
n'est jamais enregistrée. Ces données ne sont **jamais** envoyées aux membres d'un dossier
chantier partagé.

**Historique.** L'application garde sur l'appareil l'historique des mesures et des événements
(fenêtre ouverte, chauffage en marche, lumière allumée) pour afficher des courbes ; elle le
complète avec l'historique que votre Home Assistant conserve déjà. Par défaut, chaque relevé est
gardé 7 jours, des résumés par quart d'heure 90 jours et des résumés par jour sans limite ; vous
réglez ces durées et pouvez tout effacer dans « Historique et données ». L'historique de
**présence** n'est pas gardé, sauf si vous l'activez. L'export en CSV n'a lieu qu'à votre
demande : le fichier est remis à l'application que vous choisissez.

Sur Android 17 et suivants, joindre un Home Assistant sur votre réseau domestique demande
l'autorisation « appareils à proximité / réseau local », que l'application ne demande qu'au
moment où vous le connectez. Retirer la connexion efface ses appareils, leurs valeurs et le
jeton de l'appareil ; le jeton reste valable dans Home Assistant tant que vous ne l'y supprimez
pas.

## 7. Ce qui n'est jamais fait

- aucune utilisation de vos données par l'éditeur au-delà des fonctions décrites ici ;
- aucune publicité, aucun suivi, aucune mesure d'audience ;
- aucune vente, location ou cession de données ;
- aucune localisation.

## 8. Enfants

L'application ne s'adresse pas spécifiquement aux enfants.

## 9. Vos droits

Vos données sont sur votre appareil et vous en gardez la maîtrise : supprimez un projet dans
l'application, ou effacez toutes ses données en la désinstallant ou depuis les réglages
Android. Le profil et la sauvegarde en ligne se suppriment depuis votre profil (section 6 bis).
Pour accéder aux données d'un dossier partagé, les rectifier ou les faire supprimer, et pour
toute question : **serge.simono27@gmail.com**.

## 10. Modifications

Toute évolution de cette politique sera publiée sur cette page, avec sa date de mise à jour.
Toute nouvelle fonction en ligne sera facultative et décrite ici avant sa mise à disposition.
