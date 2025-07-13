
# 🤝 Guide de contribution à Morph0

Merci de votre intérêt pour **Morph0** !  
Nous accueillons volontiers toute aide : idées, corrections de docs, schémas
KiCad, fichiers 3D, prototypage, applications mobiles, etc.

---

## 1. Avant de commencer

1. **Lisez le README** pour comprendre le concept et la roadmap.  
2. **Vérifiez les issues existantes** : prenez-en une ou ouvrez‑en une
   nouvelle s’il n’y a pas déjà un sujet similaire.  
3. **Discutez** : un commentaire rapide ou un message dans
   [GitHub Discussions](../../discussions) permet de valider la direction avant
   de coder ou modéliser longtemps.

---

## 2. Licence des contributions

En soumettant un _pull request_ :

* vous acceptez que votre contribution soit distribuée   
  • sous **MIT** (code)  
  • sous **CC BY‑NC‑SA 4.0** (documents, médias)  
* vous autorisez Fabien Buisson à intégrer votre travail dans la  
  **Licence Commerciale** vendue à des tiers (4 000 €/an).  
  Vous restez crédité : votre nom/pseudo sera ajouté à `AUTHORS.md`.

_Si cela ne vous convient pas, merci **de ne pas soumettre** de PR._

---

## 3. Types de contributions bienvenues

| Catégorie | Exemples |
|-----------|----------|
| **Docs** | Traductions 🇬🇧/🇪🇸, schémas Draw.io, orthographe |
| **KiCad** | Net‑tie, footprints, iBOM, routage v0 |
| **3D (FreeCAD / Blender)** | Maillage coussin, support tige, rendu Eevee |
| **Firmware** | Code ESP32‑C3, gestion pompe/valves, profil BLE GATT |
| **App mobile** | Maquette Figma, prototype Flutter, icônes |
| **Tests & normes** | Tableur EN 71‑1 traction, script endurance pompe |

_Toute idée créative hors liste est aussi bienvenue._

---

## 4. Workflow Git

1. **Fork** le dépôt puis clonez votre fork :  
   ```bash
   git clone https://github.com/votre‑pseudo/Morph0.git
   ```
2. Créez une branche dédiée :  
   ```bash
   git checkout -b feat/ma-feature
   ```
3. Faites vos modifs (tests ou captures si visuel).  
4. Commitez clairement :  
   ```bash
   git commit -m "feat: ajout support FSR"
   ```
5. Poussez puis ouvrez une **Pull Request** sur GitHub.

### Bonnes pratiques

| Astuce | Pourquoi |
|--------|----------|
| Un sujet = une PR | Relecture simple, historique propre |
| Préfixes `feat:`, `fix:`, `docs:`… | Changelog lisible |
| Captures PNG/MP4 pour visuel | Compréhension instantanée |
| Doc à jour | Pas de divergence code / docs |

---

## 5. Style & outillage

| Domaine | Règles / Outils |
|---------|-----------------|
| **Markdown** | Titres `#`, tables alignées, pas d’espaces fin ligne |
| **C / C++ / Arduino** | `clang-format` LLVM, pas de macros obscures |
| **Python** | `black`, `flake8` |
| **KiCad** | Noms nets 🇬🇧, lib KiCad 7, export iBOM |
| **STL / 3D** | mm, origine (0,0,0), pas de faces dégénérées |

---

## 6. Code de conduite

Nous suivons le [Contributor Covenant 2.1](governance/CODE_OF_CONDUCT.md).  
Soyez respectueux, bienveillants et inclusifs.

---

## 7. Merci !

Chaque contribution, même minime, fait avancer Morph0.  
Votre nom figurera dans `AUTHORS.md` et dans le changelog des releases.

**Contact** : scgfamp@hotmail.com  
— L’équipe Morph0

---

# 🤝 Contribution Guide for Morph0

Thank you for your interest in **Morph0**!  
We gladly welcome any help: ideas, doc fixes, KiCad schematics, 3‑D models,
prototyping, mobile apps, and more.

---

## 1. Before you start

1. **Read the README** to understand the concept and the roadmap.  
2. **Check existing issues**: claim one or open a new one if no similar topic
   exists.  
3. **Discuss first**: a quick comment or a post in
   [GitHub Discussions](../../discussions) helps confirm the direction before
   you spend time coding or modelling.

---

## 2. Contribution licence

By submitting a _pull request_ you agree that your contribution will be
distributed:  
* under **MIT** (code)  
* under **CC BY‑NC‑SA 4.0** (documents, media)

You also grant Fabien Buisson the right to include your work in the  
**Commercial Licence** sold to third parties (€ 4 000 / year).  
You will still be credited: your name/handle will be added to `AUTHORS.md`.

_If you are not comfortable with this, **please do not submit** a PR._

---

## 3. Contribution areas welcome

| Category | Examples |
|----------|----------|
| **Docs** | English / Spanish translations, Draw.io diagrams, typo fixes |
| **KiCad** | Net‑ties, footprints, iBOM, first PCB routing |
| **3‑D (FreeCAD / Blender)** | Cushion mesh, rod holder, Eevee render |
| **Firmware** | ESP32‑C3 code, pump/valve control, BLE GATT profile |
| **Mobile app** | Figma mock‑ups, Flutter prototype, icons |
| **Tests & standards** | EN 71‑1 tensile spreadsheet, pump endurance script |

_Creative ideas beyond this list are also welcome._

---

## 4. Git workflow

1. **Fork** the repository and clone your fork:  
   ```bash
   git clone https://github.com/your‑handle/Morph0.git
   ```
2. Create a dedicated branch:  
   ```bash
   git checkout -b feat/my-feature
   ```
3. Make your changes (tests or screenshots if visual).  
4. Commit clearly:  
   ```bash
   git commit -m "feat: add FSR support"
   ```
5. Push and open a **Pull Request** on GitHub.

### Good practices

| Tip | Why |
|-----|-----|
| One topic = one PR | Easier review and clean history |
| Prefixes `feat:`, `fix:`, `docs:`… | Readable changelog |
| PNG/MP4 screenshots for visuals | Instant understanding |
| Up‑to‑date docs | No divergence code / docs |

---

## 5. Style & tooling

| Area | Rules / Tools |
|------|---------------|
| **Markdown** | `#` headings, aligned tables, no trailing spaces |
| **C / C++ / Arduino** | `clang-format` LLVM, no undocumented macros |
| **Python** | `black`, `flake8` |
| **KiCad** | English net names, KiCad 7 libs, iBOM export |
| **STL / 3‑D** | mm units, origin (0,0,0), no degenerate faces |

---

## 6. Code of conduct

We follow the [Contributor Covenant 2.1](governance/CODE_OF_CONDUCT.md).  
Be respectful, welcoming and inclusive.

---

## 7. Thank you!

Every contribution—even small—pushes Morph0 forward.  
Your name will appear in `AUTHORS.md` and in the release changelog.

**Contact**: scgfamp@hotmail.com  
— The Morph0 team
