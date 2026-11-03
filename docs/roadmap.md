# NAVA — Stabilisation / Stabilization roadmap

**11 octobre / October 11, 2026 — Functional freeze / Gel fonctionnel**

Le projet est en **stabilisation des commandes existantes** : aucune nouvelle fonctionnalité, nouvelle branche ou nouvelle architecture sans nécessité démontrée.

The project focuses on **stabilizing existing commands**: no new features, branches or architecture without proven necessity.

1. Préserver l'intention et tous les effets demandés avant le plan LLM / Preserve requested user outcomes before LLM planning.
2. Vérifier la conservation réelle du contexte Chrome et de l'onglet actif / Prove browser tab context retention in the real UI.
3. Achever le chemin Agenda → devis Excel déjà vérifié → pièce jointe → brouillon Thunderbird sans doublon / Complete the existing business workflow without duplicating events or files.
4. Reprendre les commandes Office, Cloud et Social non certifiées / Revalidate unproven existing command families.
5. Valider les mécanismes de reprise et d'auto-réparation avec preuves réelles / Prove runtime recovery and self-repair in real executions.
6. Déclarer une version terminée quand le noyau critique passe plusieurs fois selon le protocole / Declare a scoped completed release after repeated acceptance passes.

**Règle :** ne jamais assouplir un garde-fou pour satisfaire un ancien test incohérent ; diagnostiquer et documenter la divergence.

**Rule:** never weaken a security guard to force an outdated test to pass; investigate and document the contract mismatch.

[Detailed evidence status](status-october-2026.md)

## Mise à jour du périmètre — 3 novembre 2026 / Scope update

Le gel fonctionnel du noyau initial reste un objectif de stabilisation ; les développements NAVA Mail et NAVA Agenda sont suivis comme applications spécialisées, sans déclarer le NAVA Core terminé ou remplacé.

Priorités de validation : (1) conserver la suite de tests de l'agent Windows généraliste ; (2) certifier les scénarios Mail depuis l'interface réelle, y compris les pièces jointes et autorisations ; (3) certifier les scénarios Agenda depuis « Exécuter ce RDV » jusqu'aux documents, brouillons et modifications d'événements, avec preuves et sans doublons ; (4) contrôler les régressions entre branches avant toute fusion.

Core stabilization remains an active track. Mail and Agenda are separate application tracks; their UI-to-output workflows require reproducible evidence and approval gates.

[Agenda](nava-agenda.md) · [Mail](nava-mail.md)

