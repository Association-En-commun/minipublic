# Guide pratique — Tirage au sort stratifié

Ce guide accompagne l'[étape 3 — Tirage au sort](../03-tirage-au-sort.md) : il en reprend le déroulé opérationnel sous forme de checklist actionnable, pour l'équipe qui exécute le tirage.

## Avant de commencer

- [ ] Les critères de stratification et leurs quotas ont été validés avec la maîtrise d'ouvrage lors du [cadrage](../01-cadrage.md)
- [ ] La collecte des candidatures (mobilisation) est close
- [ ] Panelot est accessible et à jour

## Phase 1 — Extraction et préparation des données

- [ ] Exporter les réponses au formulaire en CSV (ClickUp : vue Tableur → Export, ou équivalent)
- [ ] Vérifier que toutes les candidatures attendues sont présentes
- [ ] Identifier et traiter les doublons ou inscriptions invalides
- [ ] Uniformiser les valeurs de chaque colonne de catégorie (ex. « F », « Femme », « femme » → une seule valeur)
- [ ] Vérifier la cohérence des tranches d'âge (calculer depuis la date de naissance si disponible)
- [ ] Documenter le nombre de candidatures valides retenues

## Phase 2 — Anonymisation

- [ ] Remplacer noms et prénoms par un identifiant numérique (`C001`, `C002`, …)
- [ ] Supprimer ou pseudonymiser emails et téléphones
- [ ] Conserver uniquement les variables de stratification
- [ ] Sauvegarder la table de correspondance `identifiant ↔ données personnelles` dans un fichier séparé, sécurisé, accessible uniquement à l'AMU

## Phase 3 — Configuration dans Panelot

- [ ] Créer un nouveau projet Panelot, importer le CSV anonymisé
- [ ] Définir les colonnes correspondant à chaque variable de stratification
- [ ] Configurer les quotas cibles par variable (validés au cadrage) — certains quotas peuvent être des minimums plutôt que des cibles exactes
- [ ] Générer **6 distributions** valides (pratique recommandée — permet un tirage au dé à 6 faces)
- [ ] Vérifier que chaque distribution respecte tous les quotas ; si aucune distribution valide n'est générée, revoir les quotas ou la taille du MiniPublic

## Phase 4 — Tirage public

- [ ] Choisir la modalité : tirage en public (recommandé) ou tirage filmé avec témoin indépendant
- [ ] Documenter date, lieu, témoins présents, résultat du dé, distribution retenue
- [ ] Si filmé : publier la vidéo sur la page web du processus ([étape 7 — Transmission](../07-transmission.md))

## Phase 5 — Identification et contact

- [ ] Utiliser la table de correspondance pour identifier les personnes sélectionnées
- [ ] Les contacter selon la procédure de l'[étape 2 — Mobilisation](../02-mobilisation.md)
- [ ] Constituer la liste de suppléant·es à partir des distributions non retenues (prioriser les profils les plus proches des quotas de la distribution retenue) — viser au moins 30 % de la taille du MiniPublic
- [ ] Documenter confirmations et refus

## Livrable jalon — Rapport de composition

- [ ] Rédiger le rapport de composition du MiniPublic (voir contenu détaillé à l'[étape 3](../03-tirage-au-sort.md))
- [ ] Le publier sur la page web du projet et le transmettre à la maîtrise d'ouvrage et à l'AMO

## Points de vigilance

- La table de correspondance est la seule pièce reliant identifiants et personnes réelles — sa perte rend le tirage inutilisable.
- Ne jamais modifier les quotas après génération des distributions ; tout ajustement se fait avant, et se documente.
- Les données personnelles des candidat·es non sélectionné·es doivent être supprimées à l'issue du processus (LPD, Suisse).
