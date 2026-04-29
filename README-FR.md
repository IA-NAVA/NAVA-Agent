[English version](README.md)

# NAVA — Neural Autonomous Virtual Agent

NAVA est un agent IA local développé par IA NAVA.

Il est conçu pour comprendre des instructions naturelles, identifier le logiciel adapté, exécuter des actions sur un environnement Windows réel, vérifier ses résultats et améliorer progressivement ses comportements.

## Objectif

Créer un agent IA capable d’assister un utilisateur dans ses tâches informatiques quotidiennes sans nécessiter de code, de copier-coller ou de manipulation technique.

NAVA vise à rendre l’automatisation bureautique accessible à un utilisateur non technique, en permettant de piloter des logiciels réels à partir d’instructions naturelles.

## Capacités démontrées

- Compréhension de commandes naturelles
- Routage automatique vers les bons logiciels
- Exécution de workflows Word, Excel, Thunderbird, Google Chrome et PowerPoint
- Gestion de commandes multi-applications
- Création de documents Word
- Création et modification de fichiers Excel
- Préparation de mails Thunderbird avec pièces jointes
- Navigation et recherche web avec Google Chrome
- Génération de fichiers bureautiques
- Vérification des actions exécutées
- Détection multi-écrans
- Perception de l’environnement Windows
- Mode vocal local
- Architecture modulaire avec adapters logiciels
- ProcessRegistry avec actions logicielles
- Mémoire comportementale
- Auto-correction et amélioration progressive

## Résultats de validation

NAVA a été testé avec deux batteries de validation internes exécutées en environnement Windows local.

### Test système complet v3

- Score final : 98,2 %
- Niveau : Excellent
- Résultat : 221 validations OK, 4 échecs, 5 avertissements
- Validation de l’environnement Windows
- Validation de la structure du projet
- Validation des imports critiques
- Validation de la perception écran
- Validation de la détection multi-écrans
- Validation de la pile voix locale
- Validation du routeur vocal
- Validation du replay engine
- Validation de l’intent executor
- Validation des adapters logiciels
- Validation du ProcessRegistry
- Validation des actions Word, Excel, PowerPoint, PDF, Thunderbird et Google Chrome
- Validation du routage voix → intention → exécution

### Test runtime v6

- Score final : 93,0 %
- Niveau : Production Ready
- Résultat : 160 validations OK sur 172
- Validation du pipeline complet
- Validation des commandes complexes multi-étapes
- Validation du routage générique
- Validation des workflows multi-applications
- Validation des workflows Google Chrome → Word
- Validation des workflows Excel → Thunderbird
- Validation des workflows Chrome → Excel → Thunderbird
- Validation de la robustesse sur commandes longues, ambiguës et multi-applications
- Validation de l’auto-détection de pièces jointes Thunderbird
- Validation des scénarios Word, Excel, Thunderbird et Google Chrome

## Démonstrations validées

NAVA a démontré sa capacité à exécuter des scénarios concrets tels que :

- Ouvrir Google Chrome, effectuer une recherche web, puis créer un rapport Word
- Créer un tableau Excel avec colonnes et lignes dynamiques
- Modifier un fichier Excel existant
- Préparer un mail Thunderbird avec une pièce jointe
- Lire des mails non lus dans Thunderbird
- Générer un document Word structuré avec sections
- Exécuter un workflow Chrome → Word
- Exécuter un workflow Excel → Thunderbird
- Exécuter un workflow multi-étapes avec plusieurs logiciels

  ## Sorties publiques de démonstration

Des exemples anonymisés générés pendant les tests de validation NAVA sont disponibles ici :

[Voir les sorties de démonstration NAVA](assets/demo-outputs/)

## Points encore en amélioration

NAVA reste en phase de développement privé.

Les derniers tests ont identifié quelques axes de correction :

- Export PDF Word isolé dans certains cas
- Gestion de certaines commandes Excel sans virgules entre les colonnes
- Transmission Excel → Thunderbird dans certains scénarios complexes
- Stabilisation de certains workflows très longs

Ces points sont identifiés, suivis et intégrés à la feuille de route technique.

## Statut

Le cœur du moteur NAVA reste propriétaire et privé.

Ce dépôt public présente uniquement :

- La vision du projet
- L’architecture générale
- Les capacités démontrées
- Les résultats de validation
- Les démonstrations publiques
- La feuille de route

Le code source complet, les modules internes, les adapters avancés, la mémoire, les fichiers de routage, les journaux détaillés et les mécanismes d’auto-correction ne sont pas publiés.

## Propriété intellectuelle

NAVA est un projet propriétaire développé par IA NAVA.

Copyright © 2026 IA NAVA — Tous droits réservés.

Aucune reproduction, modification, redistribution ou exploitation commerciale du code source, de l’architecture, des mécanismes internes ou du concept technique n’est autorisée sans accord écrit préalable.

## Contact

IA NAVA  
https://www.ianava.fr  
contact@ianava.fr
