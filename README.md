# TP-17 : Comparaison JSON, XML et Protobuf avec Node.js

**Réalisé par : Abdelwahid Amdjar**

## Description du Projet

Ce projet a pour objectif de comparer les performances (temps d'encodage/décodage) et la taille des fichiers générés par trois formats de sérialisation de données :

1. **JSON**
2. **XML**
3. **Protocol Buffers (Protobuf)**

## Structure du Projet

- `index.js` : Script principal effectuant la sérialisation et la comparaison.
- `employee.proto` : Définition du schéma pour Protobuf.
- `data.json`, `data.xml`, `data.proto` : Fichiers de sortie générés.

## Installation et Exécution

1. **Installer les dépendances** :

   ```bash
   npm install
   ```

2. **Lancer le script** :
   ```bash
   node index.js
   ```
