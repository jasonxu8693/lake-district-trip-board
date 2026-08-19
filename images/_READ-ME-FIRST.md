# READ ME FIRST — Lake District board images

**Write the 12 new .jpg files into this folder, next to this file.**
The 30 images already here are DONE — do not regenerate them.

---

# Round 2: the 12 images the board is still faking

Round 1 delivered all 30 named-landmark scenes. They're live. ✅

**This round is different.** It isn't "nice extras" — an audit of every image slot on the board found that
**one photo is doing the job of seven**, and several cards are showing the wrong thing entirely (three train
legs currently show a lake; the Saturday work block shows a town street). These 12 images retire the fakes.

---

## Workflow

Save each as the **exact filename**, **into this very folder** — the one this file is sitting in.

```
C:\Users\jason\Documents\Claude\Projects\Travel Planner\Trips\Lake District\lakes-board-github\images\
```

**Filenames must match exactly** (lowercase, `scene-` prefix, `.jpg`). Nothing else needed — the board binds by filename.

**Specs:** 1024 × 1024 square, JPG, ~200–300 KB. Single subject, **centred**, key content in the middle ~80%
(these get cropped to a circle on the day beads). **No text, no borders, no watermarks, no large foreground faces.**

**Cohesion is the whole point** — these sit beside 30 that already exist. Generate them in **one session**, and if
one drifts, regenerate it "in the same style as the previous images."

---

## Master style prompt (paste in front of every scene)

> Flat-but-rich **vector travel illustration** in a warm, premium *illustrated-poster / travel-infographic* style —
> think a high-end "The Lake District in 4 days" illustrated map. Soft cel-shading and gentle gradients, clean refined
> shapes, a subtle paper-grain texture; modern and elegant, **not** heavy-outline cartoon. Single subject,
> **centred composition** filling the middle, simple uncluttered background with soft depth. Cohesive **English
> Lakeland palette**: tarn blue `#2f7fae`, pale lake silver-blue `#8fc2dd`, fell green `#3d8f5f`, deep bracken bronze
> `#a4652a`, mossy dark green `#20503c`, Lakeland slate grey-purple `#5a5f70`, drystone wall grey `#9a9a90`,
> heather purple `#7d5fae`, buttermilk cream `#f2ede2`. Soft northern-English light with big scudding clouds, hazy
> layered fells receding into the distance, and drystone walls threading the valleys (or warm lamplit evening where
> noted). **No text, no words, no borders, no frames.** Square 1:1, high detail.

**Assembled example (what you actually paste):**
> [master style prompt above] — Subject: *A sleek modern intercity train pulling out of a grand Victorian London
> terminus at dusk under an arched iron-and-glass roof, warm lit carriage windows, heading north.*

---

## Priority 1 — these cards are currently showing the WRONG thing (9)

| Filename | Board slot | Currently faking it with | Subject line |
|---|---|---|---|
| `scene-train.jpg` | Wed: "Leave home → Euston, board the 18:30" | a lake 😬 | A sleek modern intercity train pulling out of a grand Victorian London terminus at dusk beneath an arched iron-and-glass roof, warm lit carriage windows, platform clock, heading north |
| `scene-arrival.jpg` | Wed: "Oxenholme change → Windermere, walk to the guest house" | a lake 😬 | A small country railway station platform at night in the rain, a single lamp glowing, two travellers with bags walking toward warm village lights and slate cottages, dark fells behind |
| `scene-train-night.jpg` | Mon: "Avanti → London Euston, arrives 22:27" | a lake 😬 | A lit intercity train speeding south through dark countryside at night, glowing carriage windows streaking past, a low moon and the silhouette of distant fells receding behind |
| `scene-drive.jpg` | Thu: car pickup · Mon: drive to Kendal | Kirkstone Pass (×3) | A small hire car on a narrow Lakeland road between high drystone walls, winding up a green fellside past sheep and a cattle grid, big cloudy sky |
| `scene-stay.jpg` | Thu: "Check in — 3 Cambridge Villas" | a town street | A cosy Lakeland slate-and-whitewash guest house at dusk with warm-lit windows, a lamp over the door, drystone wall and a garden gate, dark fells rising behind |
| `scene-work.jpg` | Fri + Mon work blocks | a town street (×2) | A laptop open on a wooden desk beside a cottage window, a mug of tea and a notebook, green Lakeland fells and a lake visible through the glass, soft morning light, no people |
| `scene-fairfield.jpg` | Sat: **FAIRFIELD HORSESHOE — the trip's biggest day** | Langdale (a stand-in) | A high grassy horseshoe ridge walk curving around a deep green valley head, a thin path along the broad spine with cairns, Ambleside and Windermere far below, layered blue fells to the horizon |
| `scene-dinner.jpg` | Sat: "Eat EARLY" after the big walk | Hawkshead village | A Lakeland pub dinner on a rustic wooden table — a coiled Cumberland sausage with mash, a sticky toffee pudding and a pint of cask ale, warm low-beamed pub light, no people |
| `scene-blackwell.jpg` | Mon: "Kat — Blackwell, the Arts & Crafts house" | a lake | An Arts and Crafts manor house interior — a white panelled room with an inglenook fireplace, stained-glass window details and a window seat looking out over a lake and low fells |

## Priority 2 — real places currently sharing a generic town photo (3)

| Filename | Board slot | Subject line |
|---|---|---|
| `scene-wansfell.jpg` | Thu: "Wansfell Pike — evening fell" | Wansfell Pike — a steep stepped path climbing a grassy fellside to a rocky cairned summit, the full length of Windermere shining directly below in low golden evening light |
| `scene-stockghyll.jpg` | Idea card: Stock Ghyll Force | Stock Ghyll Force — a tall narrow waterfall dropping through a mossy wooded ravine on several tiers, ferns and dripping rock, a small railed viewing platform among the trees |
| `scene-herdwick.jpg` | "Lakes in five frames" gallery | A Herdwick sheep — the iconic Lake District breed with a thick grey fleece and a bright white face and ears, standing on a rocky fellside among bracken, layered blue fells behind |

---

## Optional, if you're on a roll (2)

| Filename | Subject line |
|---|---|
| `scene-pub.jpg` | A cosy fell-side inn after a walk — muddy boots by a stone porch, a crackling fire glowing through the window, a hanging sign, low golden evening light on the fells behind |
| `scene-cruise.jpg` | A classic white Windermere pleasure steamer crossing a wide calm lake, wooded shoreline and a small wooden jetty, gentle summer light |

---

## When they land

Tell me and I'll push them and re-point every mapping. After this round, **no image is used more than twice**,
and the only remaining repeats are intentional — an itinerary card and its matching idea card for the same place
(Hill Top, Grasmere, Castlerigg), which is correct.
