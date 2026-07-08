# Chambre « Havre de Paix » — Dossier de design d'intérieur

> Concept de redécoration pour une chambre de couple, pensée comme un refuge
> de calme et de détente. Le dressing étant dans une autre pièce, la chambre
> est libérée de toute fonction de rangement de vêtements.

## Lecture de l'existant (d'après les photos)

- **Atouts** : plafond avec retombée (soffite) et spots encastrés, murs clairs,
  tête de lit en bois massif, nouvelle TV TCL à installer, fenêtre avec
  ventilation, volumes sains.
- **Points à corriger** : linge et vêtements stockés dans la chambre (à
  déplacer vers le dressing), table à repasser + fer + ventilateur sur pied
  qui encombrent le mur principal, éclairage unique froid et brillant
  (spots blancs sur murs satinés), rideaux trop courts et dépareillés,
  table de chevet unique et encombrée, absence de tapis et de textiles.

## Concept : « Sérénité terracotta »

Une chambre d'hôtel-boutique chaleureuse et minimaliste. On garde
l'architecture (soffite, spots, fenêtre) et on transforme l'ambiance par la
lumière, les textiles et la symétrie.

### Palette

| Rôle | Couleur | Référence |
|------|---------|-----------|
| Murs | Blanc cassé chaud / greige, finition mate | `#EDE6DC` |
| Mur de tête de lit | Greige plus profond, effet chaux | `#C9BBA8` |
| Accent principal | Terracotta / rouille (rappel des coussins existants) | `#B65C3A` |
| Accent secondaire | Vert olive doux | `#7A7A52` |
| Bois | Noyer / teck moyen | `#8A5A3B` |
| Contrastes | Noir mat (tringle, luminaires, cadres) | `#1F1D1B` |

### Mur du lit (photo 2)

- Lit king avec **grande tête de lit tapissée** en tissu bouclé écru
  (ou l'actuelle tête en bois poncée et huilée si budget serré).
- Literie en **percale blanche** + plaid lin terracotta + 2 coussins olive.
- **Deux chevets assortis en noyer**, dégagés, avec chacun une petite lampe
  céramique à lumière chaude (2700 K) — symétrie = repos visuel.
- Panneau de **tasseaux de bois verticaux** ou peinture effet chaux derrière
  le lit pour ancrer la zone nuit.
- **Grand tapis** jute + laine débordant de 60 cm de chaque côté du lit.

### Mur TV (photo 1 — actuel mur table à repasser)

- Table à repasser, fer et ventilateur sur pied **sortent de la chambre**
  (vers le dressing / buanderie).
- **TV TCL fixée au mur**, câbles encastrés dans une goulotte peinte.
- **Console basse flottante en noyer** sous la TV.
- Paire de **cadres d'art abstrait** aux tons terracotta/olive + un grand
  **palmier d'intérieur (areca)** en pot pour adoucir l'angle.
- Le ventilateur sur pied est remplacé par un **ventilateur de plafond
  silencieux** ou un modèle mural discret.

### Mur fenêtre (photo 3)

- **Rideaux sur toute la largeur du mur**, du plafond au sol : voilage ivoire
  + rideau occultant lin écru, sur tringle noire existante rallongée —
  la fenêtre paraîtra 3× plus grande.
- **Coin lecture** : fauteuil rotin + coussin bouclé, liseuse arquée noire,
  petite table d'appoint, plante verte.
- Plus aucun vêtement suspendu ni posé au sol (tout part au dressing).

### Lumière (la clé de la détente)

- Spots existants sur **variateur**, ampoules remplacées en **2700 K**.
- **Ruban LED chaud dissimulé dans le soffite** (éclairage indirect du soir).
- 2 lampes de chevet + 1 liseuse : trois niveaux de lumière, zéro plafonnier
  le soir.

---

## Prompts Gemini prêts à l'emploi

Modèle : `gemini-3.1-flash-image-preview` · ratio `4:3` · `imageSize 2K`.

### Option A — Édition des photos réelles (recommandé)

À utiliser avec `gemini_edit_image` ou
`python3 .claude/skills/banana/scripts/edit.py --image PHOTO --prompt "..."`
en fournissant chaque photo d'origine.

**A1 · Mur du lit :**

```
Redesign this bedroom photo into a serene boutique-hotel couple's retreat while
PRESERVING the exact room architecture: same walls, ceiling soffit with recessed
spotlights, window and light-switch positions. Repaint walls in warm matte
off-white, the bed wall in a soft limewash greige. Replace the bed with a
king-size bed with a tall oatmeal boucle upholstered headboard, crisp white
percale bedding neatly made, a rust-terracotta linen throw folded at the foot
and two olive-green cushions. Matching walnut nightstands on BOTH sides, each
holding a small ceramic lamp glowing warm 2700K light. A jute and wool area rug
under the bed, a discreet warm LED strip washing light from the ceiling soffit.
The room is perfectly tidy, no clothes or boxes anywhere. Captured on a Sony
A7R IV, 24mm lens at f/8, calm warm evening ambiance, Architectural Digest
interior feature.
```

**A2 · Mur TV (ex-table à repasser) :**

```
Redesign this bedroom wall photo while PRESERVING the room architecture: same
wall, ceiling recessed spotlights and tiled floor. REMOVE the ironing board,
iron, standing fan, laundry piles and hanging clothes entirely. In their place:
a wall-mounted flat-screen TV centered on the wall above a low floating walnut
media console with two closed drawers, a pair of framed abstract artworks in
terracotta and olive tones to one side, and a tall potted areca palm softening
the corner. Walls repainted warm matte off-white. A jute rug edge visible on
the floor. Warm 2700K lighting from the spotlights, cozy and immaculate.
Captured on a Sony A7R IV, 24mm lens at f/8, Architectural Digest interior
feature.
```

**A3 · Mur fenêtre :**

```
Redesign this bedroom window wall while PRESERVING the architecture: same
window with its metal grille, wall vent and ceiling. REMOVE all hanging
clothes, garment bags, floor clutter and bags entirely. Dress the window with
floor-to-ceiling double curtains spanning the whole wall on a slim matte-black
rod: an ivory sheer layer and oatmeal linen blackout panels, elegantly draped.
Add a cozy reading corner beside the window: a rattan armchair with an oatmeal
boucle cushion, a slim black arc floor lamp glowing warm light, a small round
side table with a book and a ceramic cup, and a leafy potted plant. Walls in
warm matte off-white, tidy tiled floor with a soft rug. Calm dusk ambiance.
Captured on a Sony A7R IV, 24mm lens at f/8, Architectural Digest interior
feature.
```

### Option B — Génération libre (sans photo source)

`python3 .claude/skills/banana/scripts/generate.py --prompt "..." --aspect-ratio "4:3"`

```
A serene boutique-hotel style couple's bedroom in a modern West African
apartment, evening ambiance. King bed with a tall oatmeal boucle upholstered
headboard against a soft limewash greige wall, crisp white percale bedding
with a rust-terracotta linen throw and two olive cushions. Matching walnut
nightstands with small ceramic lamps glowing warm 2700K light. A ceiling
soffit with dimmed recessed spotlights and a hidden warm LED cove light.
Floor-to-ceiling ivory sheer and oatmeal linen curtains on a matte black rod,
a rattan reading chair with a black arc floor lamp in the corner, a jute and
wool rug over tiled floor, a tall areca palm, a wall-mounted TV over a
floating walnut console. Perfectly tidy, no clutter. Captured on a Sony A7R
IV, 24mm lens at f/8, Architectural Digest interior feature.
```

---

## Pour lancer la génération

1. Créer une clé gratuite : https://aistudio.google.com/apikey
2. `export GOOGLE_AI_API_KEY="..."` (ou configurer le MCP via `/banana setup`)
3. Renvoyer les 3 photos dans la conversation, puis demander la génération —
   les prompts ci-dessus seront appliqués tels quels.
