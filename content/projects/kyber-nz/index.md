---
title: kyber-nz
date: 2025-11-20
draft: false
summary: "Implémentation FIPS 203 : Développement en Rust pur du standard
  ML-KEM (Kyber), validé par les vecteurs de tests officiels du NIST (KATs) pour
  les niveaux 512, 768 et 1024."
links:
  - type: site
    url: https://github.com/nougzarm/kyber-nz
tags:
  - Open Source
  - Kyber
  - PQC
  - Cryptography

---

<!-- Describe the problem, your approach, key results, and links to code/data. -->

### Présentation du projet

Ce projet est une librairie de **Cryptographie Post-Quantique (PQC)** développée en Rust pur.

#### Points clés :
* **Standard FIPS 203** : Implémentation complète de ML-KEM (Kyber), validée par les vecteurs de tests officiels du NIST (niveaux 512, 768 et 1024).
* **Sécurité Offensive** : Conception résistante aux attaques par canaux auxiliaires (opérations en temps constant et nettoyage de la mémoire avec `zeroize`).
* **Performance** : Optimisation système sans allocations dynamiques pour une utilisation en informatique embarquée.