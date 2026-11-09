# Politique de confidentialité — Mater-réussites

*Version du 2026-11-02. Ce texte fait foi ; la copie publiée en ligne lui est identique (empreinte SHA-256 consignée
dans la procédure de publication).*

## Qui édite l'application

Mater-réussites est éditée par **Matteo Musseo**, développeur indépendant. Pour toute question sur cette politique ou
sur l'application : **contact.mater-reussites@trlt.fr**.

## Ce que fait l'application

Mater-réussites est une application pour les classes de maternelle. Sur une tablette ou un téléphone de la classe, les
élèves photographient eux-mêmes leurs productions réussies ; chaque photo est rangée dans le dossier de l'enfant, sur
l'appareil. L'enseignant gère la liste de la classe dans un espace protégé par un code à quatre chiffres.

## L'application n'envoie rien

- L'application **n'a aucun accès au réseau** : elle ne demande pas la permission d'accéder à Internet et ne peut donc
  rien envoyer ni recevoir.
- Elle **ne crée aucun compte** et ne demande aucune identification.
- Elle **ne collecte, ne transmet et ne partage aucune donnée**, ni avec l'éditeur, ni avec un tiers : aucune
  statistique d'usage, aucune mesure d'audience, aucune publicité, aucun service d'analyse ou de rapport d'erreur.
- Mater-réussites ne fait sortir elle-même aucune donnée de l'appareil. Les données en sortent quand l'enseignant
  récupère les photos, enregistre une sauvegarde de la classe, ou active sur l'appareil un service qui copie les photos
  (ci-dessous).

## Ce qui est enregistré, et où

- **Les photos** prises par les élèves sont enregistrées dans le stockage partagé de l'appareil, dans un dossier par
  enfant (`Pictures/MaterReussites/`), nommé d'après son prénom et l'initiale de son nom. L'enseignant les récupère par
  câble USB ou par le gestionnaire de fichiers. Comme tout le stockage partagé, ces dossiers sont lisibles par les autres
  applications auxquelles l'enseignant a accordé la lecture des images, et une application de synchronisation (par
  exemple une sauvegarde de photos en ligne) peut les copier hors de l'appareil si elle est activée : c'est un réglage
  de l'appareil, qui ne dépend pas de Mater-réussites.
- **La liste de la classe** (prénom, initiale du nom, niveau, groupe, pictogramme ou portrait de chaque enfant) et le
  **code de l'enseignant** sont enregistrés dans un fichier privé de l'application, que les autres applications ne
  peuvent pas lire. Le portrait n'apparaît jamais dans les dossiers de photos. La sauvegarde automatique d'Android est
  désactivée pour ce fichier : il n'est pas copié vers un compte Google.
- **Une sauvegarde de la classe**, si l'enseignant en enregistre une : un fichier qui contient la liste de la classe et
  les portraits (jamais le code de l'enseignant, jamais les photos), **chiffré par un mot de passe** que l'enseignant
  choisit, et écrit à l'emplacement qu'il choisit dans le sélecteur de documents d'Android — sur l'appareil, sur une
  carte ou une clé, ou dans un service de stockage en ligne installé sur l'appareil. L'application avertit, avant
  d'enregistrer, que ce fichier contient des données d'enfants. Ce fichier n'est pas effacé par la purge ni par la
  désinstallation.

## Permissions demandées, et pourquoi

| Permission | Pourquoi |
|---|---|
| Caméra | prendre les photos des productions des élèves, et, si l'enseignant le choisit, le portrait de chaque enfant qui l'aide à reconnaître sa carte |
| Lecture des images | afficher la galerie et le nombre de photos de chaque enfant, reconnaître le dossier d'un enfant déjà existant, et supprimer les photos lors de la purge de fin d'année |

L'application ne demande aucune autre permission : ni Internet, ni localisation, ni contacts, ni micro.

## Responsabilité de l'enseignant

Les photos et la liste de la classe concernent des **enfants mineurs**. L'enseignant qui utilise l'application est
responsable des données de ses élèves enregistrées sur l'appareil de la classe : de l'accès à cet appareil, de la
récupération des photos, des sauvegardes qu'il enregistre et de leur conservation hors de l'appareil, dans le respect des règles de son établissement
et du règlement général sur la protection des données (RGPD). L'éditeur n'a accès à aucune de ces données.

## Supprimer les données

- **Purge de fin d'année** : dans l'espace enseignant, la purge efface la liste de la classe et les photos des élèves.
- **Désinstallation** : désinstaller l'application efface la liste de la classe et le code de l'enseignant. Les photos,
  enregistrées dans le stockage partagé, **restent sur l'appareil** : l'enseignant les supprime depuis le gestionnaire
  de fichiers (dossier `Pictures/MaterReussites/`) ou par câble USB.
- **Sauvegardes de la classe** : l'enseignant supprime lui-même les fichiers de sauvegarde qu'il a enregistrés, à
  l'emplacement où il les a mis.

## Modifications

Toute modification de cette politique est publiée à la même adresse, avec sa nouvelle date de version.
