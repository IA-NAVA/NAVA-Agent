# NAVA — Neural Agentic Virtual Agent

**De l'intention humaine à l'exécution réelle et vérifiable sur Windows.**

[Français](README-FR.md) · [English](README.md) · [État technique](docs/status-october-2026.md) · [Feuille de route](docs/roadmap.md) · [Partenariat](docs/partnership.md)

NAVA est un projet d'**agent IA local et hybride**, développé par **IA NAVA en Occitanie**. Il vise à comprendre une commande naturelle, piloter des logiciels Windows, produire des livrables natifs, vérifier les résultats et conserver des preuves d'exécution. Son objectif n'est pas simplement de répondre : **il doit agir, contrôler et démontrer le résultat**.

## Ce que NAVA cherche à accomplir

- **Comprendre la demande :** identifier tous les résultats réellement attendus.
- **Agir sur le PC :** exploiter les applications et fichiers Windows pris en charge.
- **Créer des livrables :** Word, Excel et PowerPoint dans les scénarios compatibles.
- **Exploiter l'agenda et la messagerie :** interpréter des rendez-vous, préparer des documents et des brouillons, avec confirmation pour les actions sensibles.
- **Coordonner plusieurs logiciels :** conserver l'objectif initial pendant la mission.
- **Vérifier :** distinguer l'exécution technique de la réussite métier.
- **Capitaliser sur l'expérience :** apprentissage contrôlé ; réparation autonome encore en validation.

## L'intention reste la référence

```text
Commande naturelle
       ↓
Effets demandés par l'utilisateur
       ↓
Plan d'exécution proposé (non souverain)
       ↓
Choix des capacités existantes
       ↓
Exécution réelle sur Windows
       ↓
Observation et vérification
       ↓
Effets obtenus et effets restants
       ↓
Preuves et validation humaine si nécessaire
```

Un plan généré par un modèle ne doit pas diminuer silencieusement la demande. Un clic, une réponse textuelle ou des tests unitaires réussis ne suffisent pas à déclarer une mission terminée.

## Exemple métier

> Analyse mes rendez-vous, prépare les documents nécessaires et crée les brouillons de mails correspondants.

Le fonctionnement recherché consiste à lire les événements concernés, comprendre leur contexte, retrouver les informations disponibles, préparer les livrables, les joindre aux brouillons lorsque c'est demandé et vérifier les résultats. L'envoi et les autres actions sensibles nécessitent l'autorisation appropriée.

## Priorité locale, cloud encadré

NAVA privilégie les logiciels et modèles disponibles sur le PC Windows. Un service cloud peut assister une mission lorsque son usage est activé et autorisé. Une réponse cloud ne constitue **pas** une preuve de livraison : l'existence, le contenu et la persistance du fichier natif final doivent être contrôlés.

## Niveau de preuve actuel

Plusieurs opérations Windows et bureautiques ont été démontrées. Des scénarios agenda ont réussi via l'interface. La minimisation et restauration réelles de la fenêtre NAVA ont aussi été vérifiées ; un devis Excel a fait l'objet de contrôles concrets. En revanche, **l'enchaînement métier multi-applications complet, la récupération du contexte Chrome, certains brouillons avec pièces jointes et l'auto-réparation autonome restent à certifier**.

Voir le [bilan technique d'octobre 2026](docs/status-october-2026.md), qui sépare les effets observés des simples succès de tests.

## NAVA Mail — assistant de traitement des e-mails professionnels

**Démonstrateur fonctionnel en cours de certification de bout en bout (29 octobre 2026).**

NAVA Mail vise à transformer un e-mail professionnel en plusieurs tâches coordonnées : comprendre le message et son contexte, identifier les demandes, préparer un plan multi-actions, générer les livrables pertinents puis préparer une réponse accompagnée des pièces jointes vérifiées.

- **Livrables métier :** synthèses, documents Word / Excel / PowerPoint / PDF selon les scénarios pris en charge, devis sans prix inventés, préparation de rendez-vous et correspondance.
- **Traçabilité :** chaque action est classée réalisée, en attente, bloquée ou à corriger selon ses effets réels.
- **Mode supervisé :** validation humaine appropriée avant les opérations externes sensibles.
- **Mode Auto :** le démonstrateur prévoit l'envoi sans validation individuelle **uniquement dans un périmètre expressément autorisé**, après contrôle complet. L'envoi automatique n'est **pas encore certifié de bout en bout** ; les opérations incertaines, bloquées ou non autorisées restent à valider.
- **Confidentialité :** respect du traitement local des données mail et agenda ; recours aux services externes sous autorisation.

**Dernier bilan de tests communiqué :** 4 533 PASS, 2 FAIL liés au format Agenda et 31 sous-tests PASS. Des corrections ultérieures ont été signalées, sans nouveau bilan complet vérifié ; ces chiffres ne démontrent pas une mise en production certifiée.

La validation restante concerne le parcours réel depuis l'interface en modes Auto et supervisé, les livrables et pièces jointes, les invités et liens Meet et la non-régression complète.

[Présentation publique détaillée de NAVA Mail](docs/nava-mail.md).

## Règles de développement

1. **Gel fonctionnel :** aucune nouvelle fonctionnalité avant stabilisation du noyau.
2. **Protocole d'acceptation de référence :** les commandes naturelles existantes.
3. **Interface réelle :** un runner direct ne prouve pas le fonctionnement depuis l'interface.
4. **Preuves répétées :** effet réel, vérification et preuve persistée sur plusieurs exécutions.
5. **Pas de tests rigidifiés :** corriger la cause générique et conserver les protections.
6. **Réutilisation du code existant :** pas d'architecture supplémentaire sans nécessité démontrée.

## Utilité pour les TPE et PME

NAVA vise la préparation des rendez-vous, dossiers clients, devis, rapports, tableaux de bord et brouillons de correspondance. L'ambition est de réduire les manipulations informatiques répétitives. Les gains de productivité restent à mesurer en conditions réelles, sans annoncer de pourcentage non démontré.

## Documentation publique et confidentialité

Ce dépôt constitue une **vitrine publique du projet**, pas son code source privé complet ni une certification indépendante. Le moteur interne, les méthodes propriétaires, les données clients, clés, journaux sensibles et éléments de sécurité ne sont pas publiés.

- [Bilan technique — octobre 2026](docs/status-october-2026.md)
- [Architecture publique](docs/architecture-public.md)
- [Feuille de route de stabilisation](docs/roadmap.md)
- [Partenariat, investissement et acquisition](docs/partnership.md)
- [English presentation](README.md)

**IA NAVA** · [ianava.fr](https://www.ianava.fr) · [contact@ianava.fr](mailto:contact@ianava.fr)

© 2026 IA NAVA — Tous droits réservés. Projet propriétaire.
