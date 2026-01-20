---
title: Chiffrement RSA et attaque de Coppersmith
date: 2024-05-01
draft: false
summary: "Etude du chiffrement RSA et cryptanalyse à l’aide de l’algorithme LLL"
links:
  - name: PDF
    url: https://drive.google.com/file/d/1f9CyRPNxzd1_juD4jJ-KXPcKyzPo93VJ/view
tags:
  - Algorithme LLL
  - Coppersmith
  - Cryptanalyse
  - Cryptographie asymétrique
  - RSA

---

### Introduction

La cryptographie est l’étude des techniques utilisées pour sécuriser les communications et
protéger les informations en les rendant illisibles pour ceux qui ne sont pas autorisés à les voir.
Elle repose sur l’utilisation de multitudes d’algorithmes et de clés pour transformer des données
en un format indéchiffrable sans la clé de déchiffrement appropriée.

Il existe plusieurs types de cryptographie, notamment la cryptographie symétrique et la crypto-
graphie asymétrique. Dans la cryptographie symétrique, la même clé est utilisée pour chiffrer et

déchiffrer les données, tandis que dans la cryptographie asymétrique, deux clés distinctes (une
publique et une privée) sont utilisées pour le chiffrement et le déchiffrement. Il existe tout de même
une définition mathématique et très générale (système cryptographique) qui permet d’englober
toutes ces techniques de chiffrement.

### Présentation

Dans ce document nous décrivons le schéma de **chiffrement RSA** et nous présentons une méthode de cryptanalyse à l'aide de **l'algorithme LLL**
