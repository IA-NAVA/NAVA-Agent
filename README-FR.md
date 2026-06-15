# NAVA — Neural Agentic Virtual Agent

[English version](README.md)

NAVA est un agent IA local et agentique développé par IA NAVA.

Il est conçu comme un **cerveau opérationnel** capable de comprendre une intention humaine, de choisir les bonnes capacités, d'utiliser les logiciels disponibles sur un PC réel, de produire des livrables, de vérifier les résultats, de générer des preuves, d'apprendre de ses expériences et de réutiliser automatiquement les compétences validées.

NAVA ne vise pas seulement à répondre à une question.

NAVA vise à transformer une intention utilisateur en **travail réellement exécuté et prouvé**.

---

# Vision

NAVA fonctionne selon une idée simple :

* **NAVA est le cerveau**
* **Le PC est le corps**
* **Les logiciels sont les mains**
* **Les fichiers, journaux et métriques sont la mémoire**
* **Les captures et validations sont les preuves**
* **La confiance guide les décisions**
* **L'apprentissage améliore les futures missions**

L'objectif est de permettre à un utilisateur non technique de déléguer des tâches informatiques complètes à partir d'une simple commande texte ou vocale.

Le cycle agentique recherché est :

```text
comprendre
↓
cadrer
↓
décider
↓
choisir les capacités
↓
sélectionner les outils
↓
agir
↓
vérifier
↓
prouver
↓
apprendre
↓
mémoriser
↓
réutiliser
↓
s'améliorer
```

---

# Objectif

Créer un agent IA capable d'assister réellement un utilisateur dans ses tâches :

* bureautiques ;
* commerciales ;
* documentaires ;
* organisationnelles ;
* décisionnelles ;
* administratives ;
* stratégiques.

Sans nécessiter :

* de code ;
* de copier-coller ;
* de manipulations techniques ;
* de workflows prédéfinis.

NAVA cherche à comprendre ce que l'utilisateur veut accomplir, puis construit une stratégie d'action adaptée.

---

# Principe de fonctionnement

Avant d'agir, NAVA cherche à comprendre :

* de quoi parle-t-on ?
* quel est l'objectif réel ?
* quels livrables sont nécessaires ?
* quelles capacités doivent être mobilisées ?
* quels outils sont disponibles ?
* quelles informations sont pertinentes ?
* quelles actions peuvent être exécutées immédiatement ?
* quelles actions doivent être reportées ?
* quelles actions nécessitent un apprentissage ?

Chaque mission produit un cadrage initial :

* sujet compris ;
* type de mission ;
* objectif ;
* stratégie ;
* contexte ;
* incertitudes ;
* capacités requises ;
* score de confiance ;
* preuves attendues.

---

# Architecture Agentique

Le moteur suit désormais une boucle complète :

```text
MISSION
↓
COMPRÉHENSION
↓
OBJECTIF
↓
CONTEXTE
↓
CAPACITÉS
↓
OUTILS DISPONIBLES
↓
CONFIANCE NAVA
↓
DÉCISION
↓
EXÉCUTION
↓
VÉRIFICATION
↓
APPRENTISSAGE
↓
MÉMOIRE
↓
RÉUTILISATION
```

---

# Algorithme de Confiance NAVA

Avant toute décision, NAVA calcule :

```text
Confiance = √(Fiabilité² + Adaptabilité²) / √2
```

La fiabilité prend en compte :

* les réussites passées ;
* les preuves disponibles ;
* les outils disponibles ;
* les validations précédentes.

L'adaptabilité prend en compte :

* les alternatives possibles ;
* les fallbacks ;
* les capacités d'apprentissage ;
* les stratégies de correction.

Le score influence :

* l'exécution ;
* le report ;
* la clarification ;
* l'entrée en mode apprentissage.

---

# Capacités démontrées

### Compréhension

* compréhension de commandes naturelles ;
* compréhension d'objectifs ouverts ;
* routage décisionnel ;
* arbitrage ;
* priorisation.

### Documents

* génération de rapports ;
* génération de synthèses ;
* génération de devis ;
* génération de dossiers complets ;
* génération de présentations.

### Tableurs

* création ;
* modification ;
* calculs ;
* graphiques ;
* tableaux structurés.

### Multi-logiciels

* coordination de plusieurs logiciels ;
* création de dossiers complets ;
* génération de preuves ;
* fermeture contrôlée.

### Messagerie

* lecture ;
* analyse ;
* brouillons ;
* pièces jointes ;
* réponses préparées.

### Agenda

* lecture ;
* création ;
* rappels ;
* planification.

### Décision Agentique

* arbitrage ;
* choix des actions ;
* choix des capacités ;
* calcul de confiance ;
* justification des décisions.

### Apprentissage

* détection d'une lacune ;
* création d'une fiche d'apprentissage ;
* test minimal ;
* promotion contrôlée ;
* mémorisation.

### Mémoire

* mémoire de compétences ;
* mémoire d'apprentissage ;
* mémoire d'exécution ;
* réutilisation des compétences validées.

---

# Apprentissage Agentique

Lorsque NAVA rencontre un élément inconnu :

* logiciel ;
* capacité ;
* métier ;
* document ;
* workflow ;
* environnement ;

il applique :

```text
IDENTIFICATION
↓
ANALYSE
↓
APPRENTISSAGE
↓
TEST MINIMAL
↓
MESURE
↓
VALIDATION
↓
MÉMOIRE
```

Une compétence n'est ajoutée à la mémoire que si :

* le test est réussi ;
* la preuve est générée ;
* la confiance dépasse le seuil ;
* la compétence est réutilisable.

---

# Mémoire et Expérience

NAVA possède désormais :

### Mémoire de compétences

Compétences validées :

```text
memory/nava_skills.json
```

### Mémoire d'apprentissage

Compétences en cours d'acquisition :

```text
memory/nava_learning_events.json
```

### Mémoire d'exécution

Historique réel :

```text
memory/nava_execution_metrics.json
```

Chaque mission enregistre :

* succès ;
* échec ;
* durée ;
* qualité ;
* preuve ;
* confiance avant ;
* confiance après ;
* outil utilisé ;
* capacité utilisée.

Cette mémoire influence directement les futures décisions.

---

# Sécurité

NAVA applique plusieurs garde-fous :

### Mail Gate

* aucun envoi automatique ;
* brouillons uniquement ;
* destinataire requis ;
* justification obligatoire.

### Calendar Gate

* aucun rendez-vous automatique sans besoin réel ;
* date exploitable obligatoire ;
* justification obligatoire.

### Learning Gate

* aucune compétence promue sans preuve ;
* aucun apprentissage validé sans test.

### Verification Gate

* vérification du fichier ;
* vérification du contenu ;
* vérification des fenêtres ;
* preuve obligatoire.

---

# Résultat Actuel

Dernier protocole de validation :

```text
Maturité technologique validée : 96,4 %
```

Axes validés :

| Axe                      | Résultat |
| ------------------------ | -------- |
| Autonomie locale         | 100 %    |
| Capacité agentique       | 100 %    |
| Exécution réelle PC      | 100 %    |
| Apprentissage autonome   | 100 %    |
| Mémoire et réutilisation | 100 %    |
| Preuve produit interface | 100 %    |
| Robustesse               | 88 %     |
| Preuve visuelle          | 80 %     |
| Sans cloud obligatoire   | 100 %    |

---

# Les 6 Niveaux de Preuve

### Niveau 1 — Exécution locale réelle

* création ;
* ouverture ;
* vérification ;
* capture ;
* preuve.

### Niveau 2 — Multi-logiciels

* Excel ;
* Word ;
* PowerPoint ;
* orchestration locale.

### Niveau 3 — Décision agentique

* mission ouverte ;
* arbitrage ;
* confiance ;
* décisions.

### Niveau 4 — Apprentissage autonome

* capacité inconnue ;
* test minimal ;
* promotion contrôlée.

### Niveau 5 — Mémoire et amélioration

* réutilisation ;
* métriques ;
* amélioration mesurable.

### Niveau 6 — Preuve produit via interface

Validation :

```text
Interface NAVA
↓
_execute_command()
↓
Routeur principal
↓
Workflow
↓
Exécution locale
↓
Vérification
↓
Preuve
```

avec :

```text
source_commande = interface
routeur_utilise = routeur principal NAVA
script_direct = false
```

---

# Différence avec un Chatbot

```text
Chatbot
↓
Question
↓
Réponse
```

```text
NAVA
↓
Objectif
↓
Compréhension
↓
Décision
↓
Capacités
↓
Actions PC
↓
Livrables
↓
Preuves
↓
Mémoire
↓
Amélioration
```

NAVA est conçu comme un agent opérateur local.

---

# Limites Actuelles

Axes encore en amélioration :

* robustesse sur très longues durées ;
* endurance 24h / 7 jours / 30 jours ;
* amélioration de la preuve visuelle ;
* meilleure analyse sémantique des livrables ;
* calibration statistique de la confiance ;
* enrichissement automatique des capacités ;
* exploitation avancée des logiciels peu utilisés ;
* amélioration continue du moteur vocal.

---

# Statut

NAVA est un projet propriétaire développé par IA NAVA.

Le dépôt public présente :

* la vision ;
* les capacités ;
* les validations ;
* les résultats ;
* les scénarios démontrés ;
* la feuille de route.

Le cœur du moteur, les mécanismes internes, la mémoire complète, les adapters avancés, les journaux détaillés et les stratégies d'auto-correction restent privés.

---

# Propriété intellectuelle

NAVA est un projet propriétaire développé par IA NAVA.

Copyright © 2026 IA NAVA — Tous droits réservés.

Aucune reproduction, modification, redistribution ou exploitation commerciale du code source, de l'architecture, des mécanismes internes ou du concept technique n'est autorisée sans autorisation écrite préalable.

---

# Contact

IA NAVA

https://www.ianava.fr

[contact@ianava.fr](mailto:contact@ianava.fr)
