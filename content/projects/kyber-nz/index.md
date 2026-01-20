---
title: kyber-nz
date: 2025-11-20
draft: false
summary: "Implémentation FIPS 203 : Développement en Rust pur du standard
  ML-KEM (Kyber), validé par les vecteurs de tests officiels du NIST (KATs) pour
  les niveaux 512, 768 et 1024."
links:
  - type: Depôt GitHub
    url: https://github.com/nougzarm/kyber-nz
tags:
  - Cryptography
  - Kyber
  - ML-KEM
  - Open Source
  - PQC
  - Rust

---

### Présentation du projet

kyber-nz est une librairie de **Cryptographie Post-Quantique (PQC)** haute performance développée en Rust pur.

#### Points clés :
* **Standard FIPS 203** : Implémentation complète de ML-KEM (Kyber), validée par les vecteurs de tests officiels du NIST (niveaux 512, 768 et 1024).
* **Sécurité Offensive** : Conception résistante aux attaques par canaux auxiliaires (opérations en temps constant et nettoyage de la mémoire avec `zeroize`).
* **Qualité & CI/CD** : Mise en place d’une chaîne d’intégration continue complète (Tests, Audit de
sécurité), benchmarking statistique (criterion) et fuzzing pour la robustesse.
* **Performance** : Optimisation système avec un mimimum d'allocations dynamiques pour une utilisation en informatique embarquée.

#### Implémentation en Python

Une autre librairie développé en Python également disponible : [draft-post-quantum-crypto](https://github.com/nougzarm/draft-post-quantum-crypto).