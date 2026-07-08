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

### Mur commode + TV discrète (photo 1 — actuel mur table à repasser)

> Révision v2 : la TV ne doit pas être mise en avant — c'est une chambre
> pour se reposer. Pas de meuble TV imposant.

- Table à repasser, fer et ventilateur sur pied **sortent de la chambre**
  (vers le dressing / buanderie).
- **Commode en noyer à 4 tiroirs** (rangement du couple), plateau dégagé :
  un vase, une bougie, c'est tout.
- **TV TCL fixée au mur au-dessus de la commode**, cadre fin noir, câbles
  encastrés — elle se fond dans le mur comme un tableau, sans meuble dédié.
- Un grand **palmier d'intérieur (areca)** en pot pour adoucir l'angle.
- Le ventilateur sur pied est remplacé par un **ventilateur de plafond
  silencieux** ou un modèle mural discret.

### Mur fenêtre (photo 3)

- **Rideaux sur toute la largeur du mur**, du plafond au sol : voilage ivoire
  + rideau occultant lin écru, sur tringle noire existante rallongée —
  la fenêtre paraîtra 3× plus grande.
- **Coin gauche de la fenêtre : petite coiffeuse en noyer avec miroir rond**
  et tabouret bouclé — le coin beauté de madame, éclairé par la lumière
  naturelle de la fenêtre.
- **Petit meuble fermé pour les sacs à main** (colonne étroite à portes ou
  cabinet en rotin tressé) côté droit — tout rangé derrière des portes pour
  garder le calme visuel.
- **Coin lecture** : fauteuil rotin + coussin bouclé, liseuse arquée noire,
  plante verte (si la largeur du mur le permet, sinon le fauteuil migre près
  de la commode).
- Plus aucun vêtement suspendu ni posé au sol (tout part au dressing).

### Variante hypoallergénique (rhinite allergique — retenue)

> Madame souffre de rhinite allergique : on supprime les surfaces textiles
> non lavables qui piègent poussière et acariens, sans perdre le style.

- **Tête de lit bois massif à lattes verticales**, finition huilée mate,
  à la place du bouclé tapissé (l'actuelle tête en bois peut être poncée
  et huilée). Surface lisse, un coup de chiffon humide suffit.
- **Tapis coton tissé plat lavable en machine**, ton sable, à la place
  du jute + laine.
- **Housses anti-acariens** sur matelas et oreillers + percale lavable 60 °C.
- **Tabouret de coiffeuse bois + cannage** à la place du bouclé.
- Terreau du palmier couvert de **galets** (anti-moisissures), ou
  remplacement par un vase de branchages secs.

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

### Vue d'ensemble — fusion des trois murs (Gemini, avec les 3 photos jointes)

```
Using these three photos of the SAME bedroom (bed wall, opposite wall, window
wall), create ONE single wide-angle photo showing the ENTIRE redesigned room,
keeping the real architecture: ceiling soffit with recessed spotlights, window
with its metal grille, tiled floor. Serene boutique-hotel style for a couple.
Bed wall in soft limewash greige: king bed with tall oatmeal boucle headboard,
white percale bedding, rust-terracotta throw, olive cushions, matching walnut
nightstands with warm ceramic lamps. On the wall DIRECTLY FACING the bed: a
walnut chest of drawers with a slim flat TV mounted on the wall above it — the
TV MUST stay discreet and blend into the wall like a dark frame, NO bulky TV
unit. The wall to the LEFT of the bed leads to the dressing room: keep it
clear, no furniture against it, just a framed artwork. Window wall:
floor-to-ceiling ivory sheer and oatmeal linen curtains on a black rod; in the
LEFT corner of the window a small walnut vanity with a round mirror and a
boucle stool; on the right a slim closed rattan cabinet for handbags. Jute and
wool rug, tall areca palm, warm 2700K evening light. Perfectly tidy.
Architectural Digest interior.
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
