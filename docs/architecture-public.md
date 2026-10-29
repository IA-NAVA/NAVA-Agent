# NAVA — Architecture publique / Public architecture

```text
Intention utilisateur / User intent
             ↓
Effets attendus / Requested outcomes
             ↓
Plan LLM indicatif / Advisory AI plan
             ↓
Capacités existantes / Existing capabilities
             ↓
Exécution Windows / Windows execution
             ↓
Observation / Observation
             ↓
Résultats réels et effets restants / Actual and remaining effects
             ↓
Vérification et preuve / Verification and evidence
```

L'architecture conceptuelle prévoit une IA locale prioritaire, une assistance cloud contrôlée lorsque permise, une exécution sur les logiciels réels et une validation humaine pour les opérations sensibles.

The conceptual design is local-first, with optional controlled cloud assistance, real software execution and human approval for sensitive operations.

## NAVA Mail — conceptual workflow / Flux public

```text
Incoming professional email / E-mail reçu
                   ↓
Understand requests and attachments / Comprendre les demandes
                   ↓
Plan multiple actions / Planifier plusieurs actions
                   ↓
Produce business outputs / Produire les livrables
                   ↓
Verify outcomes / Vérifier les résultats
                   ↓
Draft or authorized Auto reply / Brouillon ou réponse Auto autorisée
```

Two modes are described: **supervised** (approval for sensitive external operations) and **Auto** (only specifically pre-authorized, verified sending; unresolved cases remain pending). The architecture also involves authorized mail/calendar integrations and business-file production, without disclosing proprietary internals.

Ce schéma décrit le fonctionnement présenté du démonstrateur NAVA Mail, pas une certification de bout en bout. Les frontières de confidentialité restent applicables.

## Functional contract

NAVA is designed around a closed mission loop:

`understand intent → plan → execute → observe → verify → continue until the requested outcome is complete`

The loop is deliberately outcome-oriented. It should preserve unfinished outcomes, surface uncertainty, request approval for sensitive actions, and provide evidence of what actually happened. This is the intended public contract; support and certification remain scoped to documented scenarios.

**Important :** ce schéma décrit le fonctionnement recherché et ne prouve pas que toutes les missions sont certifiées. Aucune information détaillée sur le moteur propriétaire, ses adaptateurs, sa mémoire ou ses algorithmes de réparation n'est publiée.

**Important:** This is an intended operating contract, not evidence that every possible mission is certified. No proprietary internal implementation is disclosed.
