[English version](README.md)

# NAVA — Neural Agentic Virtual Agent

NAVA est un agent IA local et agentique développé par IA NAVA.

Il est conçu pour comprendre des instructions naturelles, identifier les logiciels adaptés, planifier des actions, exécuter des workflows sur un environnement Windows réel, vérifier les résultats obtenus, corriger certaines erreurs et améliorer progressivement ses comportements.

## Objectif

Créer un agent IA capable d’assister un utilisateur dans ses tâches informatiques quotidiennes sans nécessiter de code, de copier-coller ou de manipulation technique.

NAVA vise à rendre l’automatisation bureautique accessible à un utilisateur non technique, en permettant de piloter des logiciels réels à partir d’une simple demande écrite ou vocale.

L’objectif n’est pas seulement d’ouvrir un logiciel ou de répondre à une commande isolée, mais de transformer une intention humaine en action numérique complète :

comprendre → planifier → exécuter → vérifier → corriger → rendre compte.

## Capacités démontrées

- Compréhension de commandes naturelles
- Routage automatique vers les bons logiciels
- Exécution de workflows multi-applications
- Planification séquentielle de tâches complexes
- Création de documents Word
- Création et modification de fichiers Excel
- Création de présentations PowerPoint
- Préparation de mails Thunderbird sans envoi automatique
- Lecture de mails Thunderbird dans les dossiers Courrier entrant des comptes configurés
- Réponses Thunderbird avec signature du compte utilisé
- Gestion de pièces jointes Thunderbird
- Création de relances dans Google Calendar
- Navigation et recherche web avec Google Chrome
- Génération de fichiers bureautiques
- Vérification des actions exécutées
- Validation des fichiers créés
- Validation des fenêtres Thunderbird ouvertes
- Validation des pièces jointes demandées
- Détection multi-écrans
- Perception de l’environnement Windows
- Mode vocal local
- Fonctionnement LLM cloud ou local via Ollama selon les tâches
- Architecture modulaire avec adapters logiciels
- ProcessRegistry avec actions logicielles
- Orchestrateur agentique multi-étapes
- Mémoire comportementale
- Auto-correction et amélioration progressive

## Résultats de validation

NAVA a été testé avec plusieurs batteries de validation internes exécutées en environnement Windows local.

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

### Validations agentiques récentes

Les derniers tests internes ont validé des workflows plus avancés :

- Création locale de tableaux Excel avec colonnes, lignes et formules
- Création locale de documents Word courts et export PDF
- Création locale de présentations PowerPoint de 3 slides
- Workflow PowerPoint → Word
- Workflow Excel → Word → Thunderbird
- Workflow Thunderbird → Excel → Word → Thunderbird → Google Calendar
- Préparation de mails avec les bons fichiers joints
- Création de relances Google Calendar avec dates relatives corrigées
- Fonctionnement en mode LLM cloud
- Fonctionnement en mode local uniquement via Ollama
- Vérification renforcée des fichiers créés et des pièces jointes

## Démonstrations validées

NAVA a démontré sa capacité à exécuter des scénarios concrets tels que :

- Ouvrir Google Chrome, effectuer une recherche web, puis créer un rapport Word
- Créer un tableau Excel avec colonnes, lignes dynamiques et formules
- Modifier un fichier Excel existant
- Créer une présentation PowerPoint de 3 slides
- Créer un document Word puis l’exporter en PDF
- Préparer un mail Thunderbird avec une ou plusieurs pièces jointes
- Lire le dernier mail reçu d’un compte Thunderbird spécifique
- Répondre à un mail Thunderbird sans envoyer
- Utiliser la signature du compte Thunderbird utilisé
- Générer une réponse professionnelle à partir d’un mail reçu
- Créer une fiche Excel à partir d’un mail client
- Joindre automatiquement le bon fichier à un brouillon Thunderbird
- Programmer une relance dans Google Calendar
- Exécuter un workflow Chrome → Word
- Exécuter un workflow Excel → Thunderbird
- Exécuter un workflow Excel → Word → Thunderbird
- Exécuter un workflow Thunderbird → Excel → Word → Thunderbird → Calendar

## Sorties publiques de démonstration

Des exemples anonymisés générés pendant les tests de validation NAVA sont disponibles ici :

[Voir les sorties de démonstration NAVA](assets/demo-outputs/)

## Points encore en amélioration

NAVA reste en phase de développement privé.

Les derniers tests ont identifié quelques axes de stabilisation :

- Stabilisation fine du mode vocal et du comportement micro
- Renforcement du journal de preuve après chaque workflow
- Validation encore plus stricte des workflows très longs
- Amélioration de la mémoire métier par utilisateur
- Sécurisation renforcée des actions sensibles : envoi, suppression, archivage, déplacement
- Meilleure distinction entre commande vocale ponctuelle et écoute continue
- Amélioration de certains scénarios multi-applications très complexes

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
