---
title: Chant — politique de confidentialité
---

# Politique de confidentialité — Chant

Version 2 · application Android **Chant** (`com.methodart.chant`), éditée par **methodART**
(contact : contact@methodart.fr).

Dernière mise à jour : 27 octobre 2026.

## En bref

Chant ne collecte aucune donnée. Tout ce que vous faites reste sur votre téléphone.

## Votre voix

Le micro n'est utilisé que pendant les enregistrements que vous lancez (calibration, tessiture,
prises). L'analyse de la voix (hauteur, rythme, souffle) est calculée sur l'appareil. Les
enregistrements sont gardés dans le stockage privé de l'application, au plus pour le nombre de prises
choisi dans les réglages (20 par défaut), puis supprimés automatiquement. Ils ne sont pas inclus dans
la sauvegarde Android vers le cloud (`allowBackup` désactivé).

## Aucun envoi, aucun suivi

L'application ne fait aucune requête réseau : pas de compte, pas de serveur, pas de statistiques
d'usage, pas de publicité, pas d'identifiant publicitaire. La version publiée ne détient même pas la
permission `INTERNET`. Aucune donnée n'est partagée avec des tiers.

## Vos droits

Depuis Réglages → Mes données, vous pouvez exporter toutes vos données dans un fichier JSON, ou tout
effacer définitivement. Un export n'est copié hors de l'application que dans le dossier que vous
choisissez, ou vers l'application avec laquelle vous choisissez de le partager. Désinstaller
l'application supprime aussi toutes les données qu'elle conserve (pas les exports que vous avez
enregistrés ou partagés ailleurs).

Comme aucune donnée ne parvient à methodART, nous ne pouvons ni consulter ni effacer vos données à
distance : tout se fait depuis l'application. Il n'y a pas de compte, donc pas de suppression de
compte à demander.

## Permissions

Une seule permission demandée : le micro (`RECORD_AUDIO`), au premier enregistrement, après
explication. Les autres permissions techniques sont accordées à l'installation, sans écran, et ne
donnent accès à aucune donnée personnelle :

- `MODIFY_AUDIO_SETTINGS` : réglage du mode audio pour l'enregistrement ;
- `ACCESS_NETWORK_STATE` et `WAKE_LOCK` : déclarées par le lecteur audio (bibliothèque Media3 de
  Google) ; l'application ne s'en sert pas pour communiquer.

## Contact

methodART — contact@methodart.fr
