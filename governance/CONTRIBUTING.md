# 🤝 Guide de contribution à Morph0

Merci de votre intérêt pour **Morph0** !  
Nous accueillons volontiers toute aide : idées, corrections de docs, schémas
KiCad, fichiers 3D, prototypage, applications mobiles, etc.

---

## 1. Avant de commencer

1. **Lisez le README** pour comprendre le concept et la roadmap.  
2. **Vérifiez les issues existantes** : prenez-en une ou ouvrez-en une
   nouvelle s’il n’y a pas déjà un sujet similaire.  
3. **Discutez** : un commentaire rapide ou un message dans
   [GitHub Discussions](../../discussions) permet de valider la direction avant
   de coder/modéliser longtemps.

---

## 2. Licence des contributions

En soumettant un _pull request_ :

* vous acceptez que votre contribution soit distribuée
  - sous **MIT** (code)  
  - sous **CC BY-NC-SA 4.0** (documents, médias)
* vous autorisez Fabien Buisson à intégrer votre travail dans la
  **Licence Commerciale** vendue à des tiers (4 000 €/an).  
  Vous restez crédité : votre nom/pseudo sera ajouté au fichier `AUTHORS.md`.

Si cela ne vous convient pas, merci **de ne pas soumettre** de PR.

---

## 3. Types de contributions bienvenues

| Catégorie | Exemples |
|-----------|----------|
| **Docs** | Traductions 🇬🇧/🇪🇸, schémas Draw.io, orthographe |
| **KiCad** | Net-tie, footprints, iBOM, routage v0 |
| **3D (FreeCAD / Blender)** | Maillage de coussin, support de tige, rendu Eevee |
| **Firmware** | Code ESP32-C3, gestion pompe/valves, BLE GATT |
| **App mobile** | Mock-up Figma, prototype Flutter, icônes |
| **Tests & normes** | Tableurs EN 71-1 traction, script d’autotest pompe |

_Bien sûr, toute idée créative est la bienvenue._

---

## 4. Workflow Git

1. **Fork** le repo et clonez votre fork.  
2. Créez une branche :  
   ```bash
   git checkout -b feat/ma-feature

