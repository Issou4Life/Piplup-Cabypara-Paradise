# Piplup & Cabypara PARADISE – Game Design Document

---

## 1. Concept global

**Genre** : Jeu mobile hybride sur Android (puis iOS)  
**Moteur** : Godot 4.x  
**Style graphique** : Pixel art 256x256

### Mécaniques principales :
- Combat tactique au tour par tour (rogue-lite stratégique)
- Gestion d’un village en idle
- Récompenses aléatoires après chaque vague (objets, compagnons, ressources)
- Personnalisation poussée du personnage et de son compagnon

### Détails supplémentaires :
- Le joueur peut personnaliser son personnage avec une arme, une armure, un objet, et plusieurs sorts.
- Ces éléments peuvent être choisis ou changés entre chaque vague, selon les récompenses proposées.
- Les compagnons sont très rares mais peuvent eux aussi être personnalisés (objets, stats, compétences).
- Les vagues d’ennemis sont aléatoires, mais équilibrées (ex : 5 ennemis faibles = 1 gros).
- Tous les X combats (5 ou 10), un mini-boss apparaît, seul ou en groupe, avec des builds variés.
- Le village repose sur des bâtiments orientés statistiquement (richesse, production, réputation, personnalisation de l’île).
- Les ressources peuvent provenir de bâtiments, donjons ou compagnons.
- L’île peut être terraformée, décorée, et les maisons des villageois peuvent être personnalisées.

---

## 2. Boucles de gameplay

### Phase 1 : Combat tactique (rogue-lite, tour par tour)

- Le joueur affronte des vagues successives d’ennemis dans des donjons thématiques (pas de déplacement sur carte).
- Chaque combat se joue sur une grille (ex : 5x5 ou 7x7).
- Une fois une vague terminée, le joueur peut :
  - Reconfigurer son build (équipement, sorts, compagnon)
  - Continuer ou retourner au village
- Les récompenses sont aléatoires : objets, compagnons, ressources.

### Phase 2 : Village / Idle

- Le joueur investit les ressources pour construire et améliorer son village.
- Les villageois (avec niveaux de rareté) peuvent être assignés à des bâtiments pour automatiser la production.
- Types de bâtiments :
  - Production (ressources, objets)
  - Commerce (échange pour la richesse)
  - Confort/réputation (influence l’efficacité des villageois)
- L’île peut être terraformée, décorée, et les bâtiments sont personnalisables intérieurement.

---

## 3. Contenu prévu

### Objets
- Objets passifs : bonus d’attaque, défense, régénération, critique, etc.
- Objets actifs : potions, téléportations, boosts temporaires.
- Objets épiques : modifient radicalement le style de jeu ou interagissent avec d'autres objets.

### Compagnons
- Rôles possibles : tank, soigneur, DPS, soutien, contrôle.
- Capacité à évoluer ou à être modifiés avec de l’équipement.
- Compatibles à la fois avec la phase de combat et la phase idle (travailleurs dans le village).
- Rareté variable, certains très rares sont uniquement disponibles en loot exceptionnel.

### Ennemis
- Archétypes : sprinteur, tireur, empoisonneur, bloqueur, etc.
- Difficulté adaptative : build des ennemis évolutifs, effets spéciaux, synergies.
- Mini-boss tous les 5 ou 10 rounds avec comportements uniques.

### Bâtiments
- Ferme : production de ressources de base.
- Forge : création ou amélioration d’objets.
- Académie : gain d’XP passif pour les compagnons.
- Spa : soin et amélioration temporaire.
- Maison : logement pour les compagnons/villageois, influence leur efficacité.
- Éléments décoratifs et terraformables (lacs, arbres, sentiers…).

---

## 4. Progression

- Alternance entre les phases de combat et les phases de gestion du village.
- Améliorations permanentes via les ressources collectées :
  - Niveau des compagnons
  - Capacité de stockage
  - Déblocage de nouveaux bâtiments ou mécaniques

### Système de prestige
- Le joueur peut réinitialiser une partie de sa progression pour obtenir une monnaie spéciale ("plumes dorées").
- Les plumes permettent de débloquer des compétences universelles, objets exclusifs, ou compagnons légendaires.

---

## 5. Interface et plateformes

- Cible : Android, puis iOS
- Orientation : portrait
- Menus prévus :
  - Sélection du donjon
  - Équipe / inventaire
  - Écran de gestion du village
  - Boutique / amélioration / prestige
- Interface pensée pour être minimaliste, accessible et tactile

---

## 6. Direction artistique

- Univers visuel mignon, cosy, inspiré de la nature
- Créatures stylisées (canards, capybaras, pingouins…)
- Environnement doux (lumières tamisées, animations lentes)
- Effets visuels simples mais expressifs (émotions des personnages, réactions au toucher)

---

## 7. Inspirations

- The Binding of Isaac : loot progressif, objets qui modifient le gameplay
- Into the Breach : combats stratégiques en grille, lisibilité
- Animal Crossing / Stardew Valley : gestion du village, ambiance relaxante
- Loop Hero / Archero : vague de combat, boucle de progression

---

## 8. TODO – Prochaines étapes

- [ ] Implémenter un prototype de grille pour le système de combat
- [ ] Générer des objets et compagnons aléatoires à la fin de chaque vague
- [ ] Implémenter la base du village et de sa production idle
- [ ] Créer un système d'amélioration de personnages et de bâtiments
- [ ] Ajouter la sauvegarde persistante des données (entre sessions)

