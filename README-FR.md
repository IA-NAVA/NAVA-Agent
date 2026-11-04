# NAVA — L'intelligence artificielle qui passe de la conversation à l'exécution

**Une technologie agentique Windows conçue pour transformer les demandes professionnelles en actions, documents et résultats vérifiables.**

[English](README.md) · [Preuves techniques](docs/update-2026-11-04.md) · [Architecture](docs/architecture-public.md) · [Partenariats](docs/partnership.md)

NAVA est un projet d'**intelligence artificielle agentique propriétaire, développé en Python**, par **IA NAVA en Occitanie**. Son objectif : permettre aux professionnels de déléguer des tâches dans leurs logiciels habituels, au-delà d'une simple réponse conversationnelle. NAVA associe compréhension par modèle de langage, orchestration des missions, exécution Windows, observation et contrôle des résultats.

**Maturité au 4 novembre 2026 :** prototype avancé fonctionnel, avec plusieurs capacités démontrées en conditions réelles. La fiabilité de l'exécution complète et la récupération autonome après incident sont en cours de stabilisation.

## L'opportunité

Dans une TPE ou une PME, une simple demande mobilise souvent boîte mail, agenda, documents, devis et plusieurs applications. NAVA vise à exécuter cette chaîne de travail : comprendre la demande, coordonner les actions, produire les livrables et vérifier le résultat.

### Trois applications au cœur du projet

| Application | Usage métier visé | Résultats déjà documentés |
| --- | --- | --- |
| **NAVA Mail** | Transformer les e-mails en documents, devis, brouillons et réponses avec pièces jointes | Livrables Office, brouillons et pièces jointes MIME correspondantes présents dans les archives auditées |
| **NAVA Agenda** | Transformer les descriptions des rendez-vous en tâches : documents, communications et opérations d'agenda | Dossiers d'exécution, fichiers Office, reçus SMTP et opérations d'agenda consignées |
| **NAVA Core + Computer Agent** | Coordonner et exécuter des actions dans des logiciels Windows | Opérations Windows réelles et brouillon Thunderbird rapportés dans les campagnes ciblées |

**Exemple :** une demande liée à un rendez-vous peut déclencher l'analyse de son contexte, la création d'un document, la préparation d'un e-mail et la vérification des livrables. Les envois et modifications externes restent soumis aux autorisations appropriées.

## Une technologie Python, pas un simple assemblage no-code

NAVA repose sur un **développement logiciel Python** : il ne se limite pas à l'assemblage de scénarios no-code ou n8n. Son architecture vise à conserver l'intention métier, coordonner plusieurs outils et vérifier les effets réels des commandes exécutées.

```text
Demande professionnelle
          ↓
Modèles de langage locaux ou cloud autorisés
          ↓
NAVA Core — orchestration et suivi de mission
          ↓
NAVA Bridge — liaison avec l'exécution
          ↓
Computer Agent / Mail / Agenda / Office — actions réelles
          ↓
Observer + Supervisor — surveillance et preuves
          ↓
Self-Healer — recherche de reprise contrôlée
          ↓
Résultat vérifié / validation humaine si nécessaire
```

Mail et Agenda sont des applications spécialisées complémentaires de NAVA Core. L'écosystème comporte aussi Bridge, Supervisor, Observer/Watcher, Self-Healer et un module Community Manager en développement. [État des neuf modules](docs/module-status-2026-11-04.md).

## Des preuves concrètes

La revue d'archives de novembre 2026 a identifié :

- **18 fichiers Office structurellement vérifiés :** 9 Excel, 6 Word et 3 PowerPoint.
- **9 pièces jointes MIME** identiques octet pour octet aux livrables archivés.
- **9 dossiers de missions Mail**, dont 8 avec livrables et brouillons, et **11 dossiers d'exécution Agenda**, avec des reçus d'opérations d'agenda et de transport SMTP.
- Des tests réels ciblés sur Windows et des applications ; un scénario isolé de Self-Healer a fait l'objet d'un correctif réel suivi d'un test réussi, selon le rapport.

Le développeur confirme avoir exécuté des envois et créations de rendez-vous dans son environnement. **La réception distante indépendante, la répétabilité complète depuis les interfaces et la reprise autonome d'une mission réelle interrompue ne sont pas encore globalement certifiées.** Les chiffres des campagnes de tests ne doivent pas être additionnés.

[Consulter les preuves Mail/Agenda](docs/evidence-review-november-2026.md) · [Bilan technique du 4 novembre](docs/update-2026-11-04.md).

## Le potentiel technologique

L'approche de NAVA repose sur une chaîne **intention → actions coordonnées sur le poste → livrables natifs → observation → preuves**. Elle vise à automatiser les processus administratifs multi-applications des TPE/PME dans leurs outils existants. Les gains économiques, la capacité de déploiement et le modèle commercial devront être démontrés par des pilotes mesurés ; aucun avantage concurrentiel exclusif n'est revendiqué sans comparaison probante.

## Prochaines étapes

1. Stabiliser les missions multi-applications lancées depuis les interfaces réelles.
2. Collecter et vérifier automatiquement les preuves de résultat.
3. Valider la correction d'un incident suivie de la reprise de la mission initiale.
4. Répéter les scénarios critiques Mail, Agenda et Office, avec contrôle des autorisations et des effets réels.

**NAVA est un prototype avancé, pas encore un produit certifié pour une autonomie complète sans surveillance.** Les résultats détaillés et les anomalies restent consultables dans la documentation technique.

## Partenariats et investissement

IA NAVA recherche des **partenaires techniques, entreprises pilotes et échanges avec des investisseurs** pour accélérer la stabilisation, la transformation en produit et la validation commerciale. Des démonstrations et rapports techniques peuvent étayer ces échanges.

[Partenariats et investissement](docs/partnership.md) · [Feuille de route](docs/roadmap.md) · [Audit technique complet](docs/status-november-2026.md)

**IA NAVA — France** · [ianava.fr](https://www.ianava.fr) · [contact@ianava.fr](mailto:contact@ianava.fr)

© 2026 IA NAVA. Projet propriétaire. Tous droits réservés. Ce dépôt est une vitrine publique et ne contient pas le moteur source privé.
