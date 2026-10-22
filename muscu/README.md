# Muscu – carnet de musculation

Petite application pour noter tes séries (poids + répétitions) depuis ton téléphone.
Elle s'installe sur l'écran d'accueil comme une vraie app, marche **hors connexion**
et garde tes données **sur ton téléphone** (rien n'est envoyé sur internet).

## Fonctionnalités

- **Séance** : choisis un exercice (ou tape son nom pour en créer un), règle le poids et les
  répétitions avec les boutons − / +, puis « Ajouter la série ». Les valeurs de ta dernière
  séance sont pré-remplies et rappelées en haut de l'écran.
- **Programmes** : tes séances toutes prêtes (A, B, C — avec des dips buste penché pour le bas des pecs —, et D1 footing / D2 fractionné en option). « Lancer la séance » te guide exercice par
  exercice avec l'objectif (séries × répétitions, repos) : tu n'as qu'à valider le poids et les
  répétitions de chaque série, puis « Exercice suivant ». Les programmes se modifient
  (exercices, séries, objectif, repos, conseil) et tu peux en créer d'autres.
- **Écran toujours allumé** pendant une séance de programme et pendant le chrono, pour que le
  compte à rebours et le bip fonctionnent même téléphone posé ou en poche (Réglages pour le couper).
- **Chrono de repos** : pendant un programme, compte à rebours selon le repos prévu (le téléphone
  vibre à la fin) ; sinon, temps écoulé depuis ta dernière série.
- **EMOM** (« every minute on the minute ») : un exercice de programme peut être en mode EMOM
  (ex. tractions 8 min × 3 en séance C). Bip au début de chaque minute, une série notée
  automatiquement par minute, et progression proposée : +1 min jusqu'à 12, puis 8 min avec
  +1 rep. Se règle dans Programmes → Modifier.
- **Test de max** (lien « 🎯 Faire un test de max » sur un exercice) : enregistre ton maximum,
  suivi dans Progrès, sans compter dans la séance ni les suggestions. Un test au poids du corps
  règle automatiquement les EMOM de l'exercice sur environ un tiers du max.
- **EMOM** : 5 s pour se mettre en place, puis 3 petits bips avant chaque minute et un bip de départ.
- **Exercices en durée** : gainage, killy, course… se notent en secondes ou en minutes
  (Réglages → Exercices → type). Bouton **▶ Lancer le chrono** : compte à rebours, écran
  maintenu allumé, bip + vibration à la fin et série notée automatiquement.
- **Suggestion de charge** : si toutes tes séries ont atteint le haut de l'objectif
  (ex. 3 × 12 sur « 8–12 »), l'app propose la charge suivante (+ le pas choisi dans Réglages)
  et la pré-remplit.
- **Résumé de séance** : à la fin d'un programme (ou depuis l'Historique) : durée, séries,
  volume, records battus, comparaison avec la fois précédente et charges conseillées pour la
  prochaine fois.
- **Records** : 🏆 quand tu dépasses ta charge max sur un exercice.
- **Badges** (onglet Progrès) : 23 défis à débloquer (séances, records, tonnes soulevées,
  semaines d'affilée…), avec leur progression, et une célébration quand tu en gagnes un.
- **Récompenses** (Progrès → carte niveau) : des XP à chaque série, record, séance, badge et
  défi ; des niveaux qui débloquent des thèmes de couleur, des avatars, des titres et des
  célébrations (confettis, feu d'artifice, pluie d'or) ; 3 défis de la semaine ; un bonus de
  régularité (×1,5 dès 4 semaines d'affilée, ×2 dès 8) et des jokers qui sauvent ta série.
- **Historique** : toutes tes séances, jour par jour, avec le tonnage soulevé.
- **Progrès** : courbe de la charge max par séance, record, 1RM estimé.
- **Réglages** : pas des boutons (0,5 / 1 / 1,25 / 2,5 / 5 kg), renommer / supprimer des
  exercices, **exporter / importer** une sauvegarde.

Astuce : mets **0 kg** pour un exercice au poids du corps (affiché « PDC »).

## Mettre l'app en ligne (une seule fois)

1. Sur GitHub, ouvre le dépôt → **Settings** → **Pages**.
2. *Source* : **Deploy from a branch**, choisis la branche (par ex. `main` après fusion) et le
   dossier **/ (root)**, puis **Save**.
3. Après 1 à 2 minutes, l'app est disponible sur
   `https://<ton-pseudo>.github.io/whip-assets/muscu/`.

## L'installer sur le téléphone

- **iPhone (Safari)** : ouvre le lien → bouton Partager → **Sur l'écran d'accueil**.
- **Android (Chrome)** : ouvre le lien → menu ⋮ → **Installer l'application** /
  **Ajouter à l'écran d'accueil**.

## Sauvegarde

Les données sont stockées dans le navigateur du téléphone. Pense à faire
**Réglages → Exporter mes données** de temps en temps (et avant de changer de téléphone) ;
tu pourras les remettre avec **Importer une sauvegarde**.
