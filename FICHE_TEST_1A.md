# FICHE DE TEST — R3 / ÉPROUVETTE 1a
Version : 1a-v1. Objet : persistance locale seulement. Ne valide PAS synchronisation, conflits, droits serveur ou réponse perdue après commit.

## Preuve appareil
Pour chaque appareil : date/heure, modèle exact, OS/version, navigateur/version, URL, version 1a-v1.

## Données fictives
Créer au moins : plein + odomètre, entretien + photo, dépense, mesure, document, transition de déplacement. Aucune donnée personnelle réelle.

## Séquence
1. Ouvrir en HTTPS et capturer Diagnostic.
2. Demander le stockage persistant; noter accord/refus.
3. Créer les données fictives; exporter la preuve JSON.
4. Mode avion/hors connexion; fermer complètement puis rouvrir hors ligne; vérifier page, données et pièces jointes.
5. Redémarrer l’appareil hors ligne; rouvrir et vérifier.
6. Revenir en ligne; vérifier qu’aucune donnée n’a expiré/changé sans action.
7. À l’échéance prévue par le protocole, revérifier l’absence d’expiration.
8. Test destructif séparé : preuves sauvegardées, effacer volontairement les données du site/navigateur; consigner exactement ce qui disparaît. Ne pas confondre avec un redémarrage normal.

## Verdict
RÉUSSI / ÉCHEC / INDÉTERMINÉ — TEST INSUFFISANT. Un refus de navigator.storage.persist() est à consigner et doit être confronté à la survie réellement observée. Tous les critères 1b restent INDÉTERMINÉ — TEST INSUFFISANT jusqu’au vrai backend.

## Preuves
Captures avant/après, JSON avant/après, modèle/OS/navigateur, IDs, fichiers fictifs, anomalies/reproductibilité, interventions manuelles.
