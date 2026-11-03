# NAVA Agenda — Présentation publique / Public overview

**IA NAVA · 3 novembre / November 3, 2026**  
**Statut / Status :** démonstrateur en développement et validation / demonstrator in development and validation.

## Français — Ton agenda passe à l'action

NAVA Agenda est une application spécialisée, distincte de NAVA Mail, rattachée à l'écosystème **NAVA Core**. Son ambition : transformer la description d'un rendez-vous en tâches vérifiables, plutôt que se limiter à l'affichage d'un calendrier.

**Parcours visé :** connexion autorisée aux agendas → lecture des événements → sélection d'un rendez-vous → commande « Exécuter ce RDV » → interprétation des instructions → préparation ou exécution des tâches permises → contrôle des résultats et preuves.

**Fonctions ciblées :** consulter les rendez-vous, créer ou modifier des événements, préparer des brouillons d'e-mails et leurs pièces jointes, produire des documents Word, Excel, PowerPoint, PDF et des devis à partir de données disponibles et vérifiées.

**Principes :** interface de type agenda, configuration et connexions propres à l'application ; identification d'une mission, journal d'exécution et vérification des fichiers et actions ; approbation humaine avant toute action sensible non expressément autorisée. Aucun prix, destinataire, pièce jointe ou résultat ne doit être inventé.

**État des validations :** des lectures de semaine et scénarios agenda ont été rapportés et testés. L'exécution complète depuis le bouton de l'interface, les workflows multi-applications, les documents et pièces jointes, les modifications d'agenda et les éventuels envois nécessitent une campagne reproductible de validation de bout en bout. La présence d'un bouton ou un test unitaire réussi ne vaut pas certification.

## English — Your calendar becomes an execution workspace

NAVA Agenda is a calendar-oriented application within the original **NAVA Core** ecosystem, separate from NAVA Mail. Its intended workflow is: authorized calendar access → event reading → select a meeting → “Execute this meeting” → interpret instructions → prepare permitted outputs → verify real outcomes and retain evidence.

Target scenarios include creating or updating events, drafting related emails, and producing supported Word, Excel, PowerPoint, PDF and quotation outputs. The interface and integration configuration are application-specific. Sensitive actions require appropriate authorization; details and business data must never be fabricated.

**Validation boundary:** calendar-reading tests and selected interface scenarios have been reported, but complete cross-application execution, attachments, external changes and email actions are not yet comprehensively certified end to end.

## Confidentialité / Disclosure boundary

This public document does not disclose proprietary engine code, credentials, tokens, internal orchestration rules, customer information or private execution traces.

[Public README](../README.md) · [README français](../README-FR.md) · [NAVA Mail](nava-mail.md) · [Architecture](architecture-public.md)

© 2026 IA NAVA — Tous droits réservés / All rights reserved.

## Qualification complémentaire — 3 novembre 2026 / Additional qualification

L'audit du checkout `feature/nava-agenda` confirme des tests de lecture et de planification locale. Il indique que le raccordement effectif des boutons « Créer / modifier / Exécuter ce RDV » à une mission multi-application complète **n'est pas prouvé dans cette version**. La campagne ciblée a été interrompue par une exception Windows COM pendant un test de devis : statut **BLOCKED**, et non PASS global. Ces résultats ne permettent pas d'évaluer une autre version locale non auditée.

The audited checkout supports calendar reading and local planning tests, but GUI-triggered external effects were not established. A quotation test was blocked by a Windows COM exception. [November 2026 technical status](status-november-2026.md).

## Exécutions archivées — 3 novembre 2026

La revue de 11 missions Agenda archivées confirme des livrables Word, Excel et PowerPoint, des brouillons, deux reçus de changement de calendrier avec identifiants d'événements et cinq reçus SMTP. Le développeur confirme que la création des rendez-vous et les envois fonctionnent dans sa version utilisée. Cette revue étant hors ligne, chaque effet externe n'a pas été revérifié en direct et la campagne `BLOCKED` d'un checkout différent demeure documentée. [Revue des preuves](evidence-review-november-2026.md).
