# NAVA — État technique / Technical status — 3 novembre 2026

**Périmètre / Scope :** audit Codex transmis par le porteur du projet, effectué sur un checkout local de la branche `feature/nava-agenda`. L'audit comprend lecture de code, rapports archivés et tests ciblés. Il **ne certifie pas** le comportement de toutes les versions ni une exécution réelle complète depuis les interfaces.

## Résultats / Findings

| Produit / Product | Résultats vérifiés / Verified results | Limites / Boundaries |
| --- | --- | --- |
| **NAVA Core** | Contrats d'intention, routage et vérification testés localement ; quelques observations Windows en lecture seule documentées antérieurement. | Autonomie complète, récupération et mission multi-application réelle non démontrées. |
| **NAVA Mail** | Lecture/triage, préparation de brouillons, protections d'envoi et génération contrôlée de livrables couvertes par des tests et des rapports historiques. | Plusieurs missions archivées `INCOMPLETE` ; envoi SMTP réel et chaîne GUI complète non certifiés. |
| **NAVA Agenda** | Synchronisation/lecture, analyse de descriptions et planification locale validées au niveau indiqué par le rapport. | Exécution des boutons et chaîne complète de production d'actions externes non confirmées ; campagne de tests bloquée par une exception Windows COM. |
| **Community Manager** | Aucun élément applicatif suivi trouvé dans le checkout audité. | État d'autres branches ou environnements non évalué. |

**Tests du 3 novembre :** 126 tests ciblés Core/Mail réussis en 9,02 s. La campagne incluant l'orchestrateur Agenda a été interrompue par une exception Windows COM et est classée **BLOCKED**, sans résultat complet. Ces tests n'impliquent pas d'envoi réel de mails ni de modification de rendez-vous.

**Résultats archivés Mail du 28 octobre :** 4 597 tests réussis, 1 avertissement et 31 sous-tests réussis d'après le rapport local. Ce bilan historique ne constitue pas une certification E2E du checkout courant.

**Déclarations de démonstration :** NAVA Core (observation et contrats agentiques), NAVA Mail (préparation de mails/documents sous supervision), NAVA Agenda (lecture et plans locaux) sont les scénarios étayés par cet audit. Les envois automatiques, mutations de calendrier, exécutions multi-applications complètes et publications sociales restent à démontrer sur des scénarios autorisés et rejouables.

## English summary

The November 3 audit reports **126 passing targeted Core/Mail tests**, a **blocked Agenda test campaign** (Windows COM exception), and historical Mail results of **4,597 passed, one warning and 31 passing subtests**. It distinguishes local/contractual evidence from fully verified end-to-end external application effects. The audit applies to a particular local checkout and does not certify all versions or configurations.

## Références et confidentialité / References and disclosure

Résumé public expurgé d'un audit interne remis le 3 novembre 2026. Aucun chemin local, jeton, adresse personnelle, correspondance privée, trace nominative ou moteur propriétaire n'est publié ici.

[README français](../README-FR.md) · [English README](../README.md) · [NAVA Mail](nava-mail.md) · [NAVA Agenda](nava-agenda.md) · [Historique octobre 2026](status-october-2026.md)

© 2026 IA NAVA — Tous droits réservés.
