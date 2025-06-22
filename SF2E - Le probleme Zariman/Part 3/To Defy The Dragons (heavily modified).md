# Session uno
```pf2e-stats
# Disrupteur Sonique
## 14
==Advanced== ==Sonic== ==Two-Handed== ==Boost 3d4== ==ranged Trip== ==Tech== ==Tracking +2==

---
**Range** 40 feet; **Damage** 3d8 Sonic

**Noqual** : si la cible de l'attaque est affectée par un effect magique, comparez le jet d'attaque au DC pour supprimer l'effet, s'il est supérieur, alors la cible perd l'effet.

**Fragment de pierre** : chaque cible touché par cette arme subit **Slow 1** (Slow 2 sur une réussite critique)

**Spécial** : cette arme utilise votre plus haute proficiency pour armes.
```
```pf2e-stats
# Armure en Noqual
## 14
==Light-armor== ==Noqual== ==Comfort== ==Flexible== ==Tech== ==Resilient +2==

---

**AC** +4 ; **Dex cap** +2, **Check penalty** -1, **Str** +1

**Armure assistée** Pour chaque action utilisé par son propriétaire, l'armure gagne 1 PP.

**Frappe anti-magique** (1+ PP) `[reaction]`: Lorsque l'utilisateur effectue une attaque contre une cible magique ou capable de lancer des sorts, il augmente les dégâts infligés de +2xPP dépensées

**Champs anti-magie** (2 PP) `[one-action]` : l'utilisateur crée un champs anti-magie autour de lui. Cette zone à une taille maximale de 80 feet. Tout les sorts dans la zone d'effet ont 25% d'échouer.

**Spécial** : cette armure utilise votre plus haute proficiency avec vos armures.
```
```pf2e-stats
# Armure en Inubrix
## 14
==Light-armor== ==Noqual== ==Comfort== ==Flexible== ==Tech== ==Resilient +2==

---

**AC** +4 ; **Dex cap** +2, **Check penalty** -1, **Str** +1

**Armure assistée** Pour chaque action utilisé par son propriétaire, l'armure gagne 1 PP.

**Corps éthérée** (2 PP) `[one-action]`: Vous devenez incorporel jusqu'à la fin de votre prochain tour.

**Passe-muraille** (3 PP) `[one-action]` : vous pouvez vous déplacer à travers les murs jusqu'à 3 cases.

**Spécial** : cette armure utilise votre plus haute proficiency avec vos armures.
```
```pf2e-stats
# Armure en Horacalcum
## 14
==Light-armor== ==Noqual== ==Comfort== ==Flexible== ==Tech== ==Resilient +2==

---

**AC** +8 ; **Dex cap** +0, **Check penalty** -3, **Str** +3

**Armure assistée** Pour chaque action utilisé par son propriétaire, l'armure gagne 1 PP.

**Bullet time** (2 PP) `[reaction]`: Lorsque vous subissez une attaque à distance, vous pouvez tenter d'esquiver en tentant un jet de save reflexe dont le DC est égal à l'attaque qui vous a touché.

**Pulsation temporelle** (4 PP) `[two-actions]` : Vous donnez une action supplémentaire à chacun de vos alliées jusqu'à la fin de leur prochain tour.

**Spécial** : cette armure utilise votre plus haute proficiency avec vos armures.
```
```pf2e-stats
# Armure en Siccatite
## 14
==Heavy-armor== ==Noqual== ==Comfort== ==Flexible== ==Tech== ==Resilient +2==

---

**AC** +8 ; **Dex cap** +0, **Check penalty** -3, **Str** +3

**Armure assistée** Pour chaque action utilisé par son propriétaire, l'armure gagne 1 PP.

**Bouclier radiant** (2 PP) `[reaction]`: Lorsque vous subissez une attaque de melée, vous ajoutez un +2 à votre AC et infligez 10 déĝats fire ou cold à l'attaquant.

**Explosion thermique** (2 PP) `[one-action]` : vous créez une explosion centré sur vous d'une taille maximum de 80 feet. Celle-ci inflige 6d8 dégâts fire ou cold (reflex save DC = class DC)

**Spécial** : cette armure utilise votre plus haute proficiency avec vos armures.
```
```pf2e-stats
# Sniperapide
## 14
==Advanced== ==Sniper== ==Two-Handed== ==Fatal d12== ==Tech== ==Tracking +2== ==Adamantine==

---
**Range** 100 feet; **Damage** 3d10 Piercing

**Horacalcum** : Vous pouvez effectuer une attaque à MAP 0 gratuitement une fois par tour.

**Spécial** : cette arme utilise votre plus haute proficiency pour armes.
```
```pf2e-stats
# Cristal de siccatite
## 14
==Tracking +2== ==Solarian== ==Fire== ==Cold==

---

**Siccatite** : Vous pouvez changer vos dégâts de feu en glace et vice-versa.

**Fragment de verre solaire** : une fois par tour, vous pouvez réutiliser un pouvoir de solarian ou un sort que vous avez utilisé durant ce même tour gratuitement.

**Spécial** : cette arme utilise votre plus haute proficiency pour armes.
```
# Session dos - Bataille contre Ayleth

Le transpondeur dans le corps du golem d'Adamantine va attirer Ayleth et les PJ vont devoir se fight dans une forêt contre le dragon.

```encounter 
name: Bataille contre Ayleth
creatures :
- Ayleth, 280, 35, +29
```
```pf2e-stats
# Ayleth
## 16

---

==Huge== ==Occult== ==Dragon==

**Perception** +29; Darkvision
**Language** Common, Draconic, Jotun
**Skills** Acrobatics +28, Athletics +30, Diplomacy +29, Occultism +33, Computers +31, Society +31
**Str** +8, **Dex** +6, **Con** +7, **Int** +9, **Wis** +7, **Cha** +5

---

**AC** 35, **Fort** +22, **Ref** +23, **Will** +26
**HP** 280; **Immunities** doomed, paralyzed, sleep **Resistance** Physical 15 (except adamantine) **Vulnerabilities** cold 20
**Untethered to Fate** Ayleth can choose to negate any fortune or misfortune effects that would affect them. 
**Challenge Fate** `[reaction]` (misfortune, occult) **Trigger** Ayleth is targeted by an attack; **Effect** The fate is not set in stone. The attacker rolls the triggering attack twice and uses the worse results.
**Defy Fate** (misfortune, occult) **Trigger** Ayleth is hit by an attack after using Challenge Fate; **Effect** The triggering attack becomes a critical hit.
**Bound to earth** **Trigger** Ayleth is hit by an attack triggering a vulnerability (or adamantine);, or a critical hit **Effect** Ayleth can't fly for 1d4 rounds.

---

**Speed** 60 feet, fly 180 feet
**Melee** Jaws +30 [+25/+20] (magical, reach 15 feet), **Damage** 3d8+14 piercing + 1d8 mental
**Melee** Claw +30 [+26/+22] (agile, magical, reach 10 feet), **Damage** 3d6+14 slashing + 1d8 mental
**Melee** Tail +28 [+23/+18] (magical, reach 20 feet), **Damage** 3d8+14 bludgeoning + 1d8 mental
**Melee** Wing +28 [+24/+20] (agile, magical, reach 15 feet), **Damage** 2d8+14 slashing + 1d8 Mental

--- 

**Occult Innate Spells** DC 39 
- **7th** : Ill Omen (at will), mindlink (at will), true target (x2)
- **Cantrips** : Guidance (8th)

--- 

**Destiny Breath** `[two-actions]` Ayleth breathes a translucent mist of potentialities that overwhelm creatures with visions of possible features, dealing **15d6 mental** damage in **40-foot cone** (**DC 35 Will save**). A creature that fails its save is **slowed 1** for one round (two on critical failure) as it struggles with visions. Ayleth recharges her breath Destiny Breath in 1d4 rounds.
**Draconic Frenzy** `[two-actions]` Ayleth makes two claw Strikes and one wing Strike in any order.
**Draconic Momentum** The dragon recharges their Destiny Breath whenever they score a critical hit with a Strike.
**Walk the Timelines** `[two-actions]` (occult) **Frequency** once per hour; **Effect** Ayleth splits themself into two versions with different fates. Each copy Strides or Flies from the dragon's current space, then take a single action. If the actions are both attacks, they use the same multiple attack penalty and count as one attack toward the Ayleth's multiple attack penalty. After both actions, Ayleth chooses one of the two locations as their actual destination and the other version of themself disappears.
**Wellspring Plating** Magical plating integrated into Ayleth's admantine scale functions as a Haste spell. If the effect is deactivated (**DC 33**), Ayleth can reactivate it after 1d4 rounds.

```
A chaque fois qu'Ayleth subit des dégâts, les PJ auront des hallucinations de la simulation qui se brise de plus en plus. Lorsqu'elle meurt, ces derniers se retrouvent dans une immense pièce blanche (reconnaisse le [[Zariman]] mais en meilleur état) avec une gigantesque orbe d'énergie (comme un cephalon) qui les regarde.
Ayleth ne protégeant plus la simulation, il est l'heure pour la Volonté Suprême d'en finir avec celle-ci.

# Session tres - La Volonté Suprême

Ayleth n'empêchant plus la simulation de s'arrêter, les PJ vont avoir de plus en plus de vision d'une immense salle blanche. 
Pour déterminer si elle la simulation est une réussite ou un échec, la Volonté Suprême va soumettre le groupe à une série de test basé sur leurs expériences passées.
En cas d'échec, ils risquent l'anéantissement.

https://monster.pf2.tools/

La Volonté Suprême est accompagné de 5 Volonté Fragmentée qui se régénère à chaque nouvelle phase.

## Phase 1
La Volonté Suprême projette l'image du [[Zariman]], un labyrinthe et un guide vers un monde meilleur. 
Chaque Volonté Fragmentée prend l'apparence d'un cristal dans lequel est incrusté un terminal. Il est possible d'intéragir avec ces terminaux afin de résoudre le **Labyrinthe du [[Zariman]]**.

A1 | B3

Combinaison erronée : B1 | C1
A2 | B2
C1 | B3
B3 | B3
	C2 m
```encounter 
name: Phase 1
creatures :
- 2: Volonté Suprême, 0, 33, 26
- 5: Volonté Fragmentée, 0, 0, 21
```
```pf2e-stats
# Volonté Suprême - Phase 1
## 13

---

==gargantuan== ==monitor== ==drift== ==construct==  
**Perception** +26; Truesight   
**Str** -4, **Dex** -4, **Con** +4, **Int** +9, **Wis** +9, **Cha** +5

---
**Boss final** : La Volonté Suprême lance deux fois l'initiative et joue donc deux fois.
**Labyrinthe du [[Zariman]]** (Drift)  
When this layer appears, draw a 3x3 grid – the labyrinth – on a piece of paper and sequentially mark the rows A/B/C and the columns 1/2/3. Secretly note down the coordinates of two of the nine spaces (i.e., A1, B3, etc.). As a quick action, characters adjacent to the layer or one of its shards can make two guesses about which spaces in the labyrinth contain a mark. Tell them if they are correct or not. When a character guesses both marks correctly in the same attempt, the layer is destroyed. For each incorrect guess, the Eidolon uses INCORRECT against them as a reaction, ignoring the 1/turn limit. Each target (i.e., the Eidolon or one of its shards) can only be used to guess once per round.  
  
AC 33; Fort +23, Ref +18, Will +29  
HP 0; Immunities All  
Speed 0  
Ranged [[A]] réalité corrompu +27, Damage 3d8+14 mental  
Arcane Spells DC 33, attack +25; 7th World Warp (at will);  
INCORRECT [[R]]  
La Volonté Suprême inflige 30 points de dégâst mentaux à la cible.
```
```pf2e-stats
# Volonté Fragmentée - Phase 1
## 11
---

==Medium== ==Construct== ==Mindless== ==Drift==
**Perception** +21
```
## Phase 2
La Volonté Suprême projette une roue de différentes couleurs : rouge (feu), bleu clair (cold), vert (acide), bleu foncé (électrique), gris (physical), rose (sonic). 
La Volonté Suprême est vulnérable à l’élément associé à la couleur et immunisé aux restes. A chaque fois qu'une vulnérabilité est frappée, la roue avance d'un cran.
Les Volonté Fragmentée sont immunisé au type de dégât affiché sur la roue, mais vulnérable au reste. Lorsqu'elles sont touchés, elles avancent la roue jusqu'au type de dégâts correspondant.
```encounter 
name: Phase 2
creatures :
- 2: Volonté Suprême, 0, 35, 28
- 5: Volonté Fragmentée, 0, 0, 22
```
```pf2e-stats
# Volonté Suprême - Phase 2
## 14

---

==gargantuan== ==monitor== ==drift== ==construct==  
**Perception** +28; Truesight  
**Str** -4, **Dex** -4, **Con** +4, **Int** +9, **Wis** +9, **Cha** +5  

---

**AC** 35; **Fort** +25, **Ref** +19, **Will** +30  
**HP** 195; **Immunities** Variable 
**Speed** 0  
**Ranged** [[A]] Fragment d'une réalité corrompue +27, **Damage** 3d8+14 mental  

---

**Arcane Spells** DC 34, attack +26; 7th World Warp (at will);

---

**Rayon destructeur** La Volonté Suprême choisie 3 rangées de cases, et tire un rayon destructeur sur chacune d'entre elle. Celui-ci est suffisament puissant pour détruire n'importe quelle couverture mais aussi suffisament pour ne pas anéantir le paysage. **4d12+10** dégâts du type affichée sur la roue (Basic ref save DC 34).

```
```pf2e-stats
# Volonté Fragmentée - Phase 2
## 12
---

==Medium== ==Construct== ==Mindless== ==Drift==
**Perception** +22
```
## Phase 3
La Volonté Suprême se lie aux PJ, tout les dégâts qui lui sont infligé sont répartis entre les PJ. Tout les dégâts infligés aux PJ sont envoyé à la Volonté Suprême.
Les Volonté Fragmentée se concentre sur le fait d'attaquer la Volonté Suprême.
```encounter 
name: Phase 3
creatures :
- 2: Volonté Suprême, 0, 36, 29
- 5: Volonté Fragmentée, 0, 0, 23
```
```pf2e-stats
# Volonté Suprême - Phase 3
## 15

---

==gargantuan== ==monitor== ==drift== ==construct==  
**Perception** +29; Truesight  
Str -4, Dex -4, Con +4, Int +9, Wis +9, Cha +6  

---

**AC** 36; **Fort** +26, **Ref** +20, **Will** +32  
**HP** 210
**Speed** 0  

**Arcane Spells** DC 36, attack +28; 7th World Warp (at will);

```
```pf2e-stats
# Volonté Fragmentée - Phase 3
## 13
---

==Medium== ==Construct== ==Mindless== ==Drift==
**Perception** +23
```
## Phase 4
La réalité simulé par la Volonté Suprême est maintenant en pleine effondrement, une porte s'ouvre du côté le plus éloignée des PJ. Traverser cette porte est leur seule issue.
L'incarnation de la Volonté Suprême, devenue instable avec l'effondrement de la simulation, attaque en projetant des vagues d'énergies frappant tout le monde et attirant les PJ vers elle (4 cases à chaque fois).
```encounter 
name: Phase 4
creatures :
- 2: Volonté Suprême, 0, 38, 30
```
```pf2e-stats
# Volonté Suprême - Phase 4
## 16

---
 
==gargantuan== ==monitor== ==drift== ==construct==  
**Perception** +30; Truesight  
**Str** -4, Dex -4, Con +5, Int +10, Wis +10, Cha +6  

---

AC 38; Fort +28, Ref +22, Will +33  
HP 221; Immunities All  
Speed 0  
Ranged [[A]] réalité corrompu +27, Damage 3d8+14 mental  
Ranged [[A]] réalité brulante +25, Damage 3d10+16 fire  
Arcane Spells DC 37, attack +29; 7th World Warp (at will);
```

# Fin et épilogue

Après avoir quitté leur simulation maudite, les PJ se retrouve dans un bar, "Le Mixeur" étant écris sur un néon accroché au mur. Des écrans sur les murs semblent montrer une centaine de réalité différente. Les murs et couloir ressemble trait pour trait à ceux du [[Zariman]] qu'ils ont visité il y a quelques années.

Un humain, ressemblant à Jean-Marie Bigard habillé en barman vintage leur fait signe, et leur propose un verre.
[FIN]

