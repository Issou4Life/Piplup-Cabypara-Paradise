# Piplup & Cabypara PARADISE

**Piplup & Cabypara PARADISE** est un jeu mobile hybride alliant combats tactiques au tour par tour et gestion de village en idle. Le joueur explore des donjons, personnalise son personnage et ses compagnons, puis utilise ses ressources pour construire un village vivant, personnalisable et productif.

---

## 🎮 Caractéristiques principales

- **Combat stratégique au tour par tour** : affrontez des vagues d’ennemis sur une grille, enchaînez les vagues, choisissez vos récompenses et adaptez votre build en temps réel.
- **Récompenses aléatoires** : objets passifs, actifs ou compagnons rares influencent vos parties de manière unique à chaque session.
- **Gestion de village idle** : construisez des bâtiments, gérez des villageois aux effets variés et personnalisez votre île pour améliorer vos productions.
- **Personnalisation avancée** : modifiez votre personnage et vos compagnons entre chaque vague grâce à l’équipement, aux objets, et aux sorts trouvés.
- **Direction artistique mignonne en pixel art 256x256** : univers coloré peuplé de capybaras, canards, pingouins et autres créatures attachantes.

---

## ⚙️ Stack technique

- **Moteur** : Godot 4.x
- **Langage** : GDScript
- **Plateforme cible** : Android (plus tard iOS)
- **Orientation mobile** : Portrait
- **Graphismes** : Pixel art 256x256

---

## 📁 Arborescence du projet

Piplup-Cabypara-Paradise/
├── assets/ # Graphismes, sons, animations
├── src/ # Code source (combat, village, cœur du jeu)
│ ├── combat/ # Phase de combat tactique
│ ├── village/ # Phase de gestion idle
│ └── core/ # Systèmes globaux (UI, navigation, sauvegarde)
├── data/ # Données du jeu (objets, compagnons, bâtiments)
│ ├── objects.json
│ ├── companions.json
│ └── buildings.json
├── docs/ # Documents de design
│ └── GDD.md # Game Design Document complet
├── builds/ # Exports pour Android ou tests
├── README.md
├── LICENSE
└── .gitignore

---

## 📌 Avancement / TODO

- [x] Rédaction complète du Game Design Document
- [ ] Prototype du système de combat sur grille
- [ ] Génération dynamique d’objets et compagnons
- [ ] Développement du système de gestion idle
- [ ] Implémentation de la sauvegarde persistante
- [ ] Export mobile Android

---

## 📜 Licence

Projet sous licence **MIT**. Voir le fichier `LICENSE` pour plus d'informations.

---

## ✨ Inspirations

- *The Binding of Isaac* – gestion de builds aléatoires
- *Into the Breach* – combats tactiques lisibles sur grille
- *Animal Crossing / Stardew Valley* – ambiance cosy et gestion de village
- *Loop Hero* – boucle de progression avec choix stratégiques

---

## 💡 Auteur

Projet créé par **Issou4Life**, dans le cadre d’un projet personnel/bachelor en développement.
