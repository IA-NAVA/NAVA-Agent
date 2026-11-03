# NAVA Mail — Public overview / Présentation publique

**IA NAVA · 29 October / octobre 2026**  
**Status / Statut:** functional demonstrator under validation / démonstrateur fonctionnel en validation.

## Français

**Un e-mail. Plusieurs tâches. Un seul circuit.**

NAVA Mail vise à comprendre les messages professionnels, leur contexte et leurs pièces jointes ; décomposer les demandes ; préparer les actions nécessaires ; produire les livrables ; vérifier les résultats ; composer une réponse avec les fichiers pertinents.

**Fonctions présentées :** synthèses, Word, Excel, PDF, PowerPoint, devis sans inventer de prix, préparation d'événements Google Agenda / Meet, réponses et pièces jointes. Les détails des correspondants proviennent du message original ; une invitation ou un lien Meet ne doit être annoncé qu'après vérification réelle.

**Modes :** en mode supervisé, les opérations sensibles sont soumises à validation. En mode Auto, le démonstrateur prévoit un envoi sans validation individuelle uniquement pour les opérations expressément préautorisées, complètes et vérifiées. Les cas incertains, bloqués ou hors autorisation restent en attente. Ce mode n'est pas encore certifié de bout en bout.

**Bilan communiqué :** 4 533 PASS, 2 FAIL concernant le format Agenda et 31 sous-tests PASS. Des correctifs sont mentionnés mais aucun nouveau bilan complet validé n'est disponible. Une campagne E2E depuis l'interface réelle et une non-régression complète restent nécessaires.

## English

**One email. Multiple tasks. One verified workflow.**

NAVA Mail aims to understand professional email and attachments, identify every requested action, coordinate execution, produce relevant business files, verify actual outcomes and prepare a complete response.

**Presented scope:** summaries, supported Word / Excel / PDF / PowerPoint outputs, quotations without invented prices, Calendar / Meet preparation and verified attachments. Contact identity and meeting details must be checked against the source message and actual event.

**Modes:** supervised actions require appropriate approval. Auto sending is designed for a specifically pre-authorized scope when completeness and verification checks pass. Uncertain, blocked or unauthorized cases remain pending. End-to-end Auto certification is outstanding.

**Reported results:** 4,533 PASS, 2 FAIL related to Calendar formatting, and 31 passing subtests. Later fixes were reported but a complete passing rerun has not been verified. Real-interface testing and full regression are pending.

## Public disclosure / Confidentialité

This repository is a project showcase, not the proprietary implementation. No source code, connector credentials, private business correspondence, internal rules or sensitive execution proofs are disclosed.

[English README](../README.md) · [README français](../README-FR.md) · [Technical status](status-october-2026.md)

IA NAVA · https://www.ianava.fr · contact@ianava.fr

© 2026 IA NAVA. All rights reserved.

## Audit complémentaire — 3 novembre 2026 / November 3 audit

Le rapport local du 28 octobre cité par l'audit du 3 novembre indique **4 597 tests réussis, 1 avertissement et 31 sous-tests réussis**. La campagne ciblée Core/Mail du 3 novembre compte **126 tests réussis**. Plusieurs missions réelles archivées restent cependant **INCOMPLETE** et l'envoi SMTP réel n'est pas prouvé dans ce périmètre. Les chiffres du 29 octobre ci-dessus sont conservés comme historique, pas comme dernier bilan.

The November 3 audit reports 126 passing targeted Core/Mail tests and newer archived October 28 figures (4,597 passed, one warning, 31 passing subtests). Full real GUI/SMTP completion remains unverified. [Current qualification](status-november-2026.md).

## Preuves complémentaires — 3 novembre 2026

Dans une archive de missions distincte, 8 dossiers Mail sur 9 comprennent des livrables et brouillons ; 9 pièces jointes MIME sont identiques aux fichiers Office produits. Le développeur confirme que les envois ont été effectués. L'audit hors ligne ne vérifie pas indépendamment la réception ; certains suivis `WAITING_APPROVAL` restent incohérents avec des mentions `SMTP_ACCEPTED`. Une mission est `INCOMPLETE`. [Revue des preuves](evidence-review-november-2026.md).
