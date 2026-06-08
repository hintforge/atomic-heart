# Enchantment Under the Sea -- DLC Zone Gate List (DLC #3)

**status:** research-integrated
**last_reconciled:** 2026-06-05
**zone-id:** neptune_sechenov_complex, neptune_chelomey_ruins, neptune_lakeshore, neptune_babazina_hut, neptune_entry_hub, neptune_flooded, neptune_depot, neptune_railway, neptune_statue, neptune_cafeteria_whale, neptune_zoology, neptune_quarters, neptune_dolphin_rooms, neptune_sub_bay, neptune_open_water, neptune_block_b, neptune_city_of_dolphins, neptune_final_arena
**parent chapter:** Enchantment Under the Sea DLC -- full DLC scope
**zone type:** indoor-linear / indoor-branching / outdoor / open-world (underwater)

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:enchantment-under-sea_

> **Zone prefix correction:** P1 prefix `triton_complex_*` is partially correct. The facility is the **Neptune Complex (НИИ «Нептун»)**; "Triton" (Тритон) is a sub-complex name. Canonical prefix: `neptune_*`.
[Confirmed: VGTimes EN/RU, ShowGamer, Fandom, cyber.sports.ru -- 2 languages]

---

## Zone List

| zone-id | English in-game name | Russian in-game name | Aliases | Zone type |
|---|---|---|---|---|
| `neptune_sechenov_complex` | Sechenov Complex (interior) | комплекс Сеченова | "office start" | indoor-linear |
| `neptune_chelomey_ruins` | Destroyed Chelomey | Челомей (разрушенный) | "free flight area" | open-ish / outdoor |
| `neptune_lakeshore` | Lakeshore / lighthouse beach | берег озера Лазурь | "beach", "Baba Zina's hut area" | outdoor |
| `neptune_babazina_hut` | Baba Zina's hut / Kurortnaya stop | избушка бабы Зины | "resort station" | hub-ish |
| `neptune_entry_hub` | Neptune entry hall / dolphin aquarium hub | подводный комплекс «Нептун» | "Rapture", "dolphin hub" | indoor-branching |
| `neptune_flooded` | Flooded complex interior | затопленный комплекс | -- | indoor-linear |
| `neptune_depot` | Depot / cistern hall | депо | -- | indoor-linear |
| `neptune_railway` | Railway / metro tunnels | тоннели метро / перегон | "train section" | indoor-linear |
| `neptune_statue` | Neptune statue / admin offices | статуя Нептуна, офисы | "crab miniboss area" | indoor-branching |
| `neptune_cafeteria_whale` | Cafeteria + Whale hall | кафетерий, зал с китом | "whale disco" | indoor-linear |
| `neptune_zoology` | Zoology / reception / mannequin offices | отсек зоологии, регистратура | "graphic key door" | indoor-branching |
| `neptune_quarters` | Decontamination / Nastya & Hunter quarters | дезактивация, лаборатория | -- | indoor-linear |
| `neptune_dolphin_rooms` | Dolphin aquarium-tunnel rooms / show hall | блоки с дельфинами, Лукоморье | -- | indoor-branching |
| `neptune_sub_bay` | Submarine bay / engine room hatch | машинный зал | "airlock" | indoor-linear |
| `neptune_open_water` | Open underwater lake-bottom section | дно озера Лазурь | "stealth section", "Block B approach" | open-world (underwater) |
| `neptune_block_b` | Block "B" / assembly shop & repair cabinets | Блок «Б», сборочный цех | "Eleanor/Samodelkin labs" | indoor-branching |
| `neptune_city_of_dolphins` | City of Dolphins | город дельфинов | -- | indoor-linear |
| `neptune_final_arena` | Final boss arena (Thalassophobia) | арена у главных ворот | "Moray fight" | cutscene/arena |

[Confirmed: VGTimes EN/RU, ShowGamer, Fandom, cyber.sports.ru -- 2 languages]

---

## Chapter / quest mapping

EutS uses named in-game quests. [translated from: Russian where noted]

| # | English | Russian |
|---|---|---|
| 1 | Five Days Later... | Пять дней спустя… |
| 2 | Free Flight | Свободный полёт |
| 3 | Rings for Two | Кольца для двоих |
| 4 | Into the Depths | На глубину |
| 5 | Flooded Complex | Затопленный комплекс |
| 6 | Higher... / ...and Closer | Выше… / …и ближе |
| 7 | Shock and Awe | Шок и трепет |
| 8 | Train Ticket / Travel Pass | Проездной |
| 9 | The Cake is Worth the Candle | Игра стоит свеч |
| 10 | Whale of a Disco | Китовая дискотека |
| 11 | Out of the Frying Pan into the Fire | Из огня да в полымя |
| 12 | Where the Hell Are They?! | Да где они?! |
| 13 | Deactivation | Дезактивация |
| 14 | Major League | Высшая лига |
| 15 | Decorated Actress | Заслуженная артистка |
| 16 | Lukomorye | Лукоморье |
| 17 | A-Side Track Or... | Сказал «А»… |
| 18 | On the Bottom | На дне |
| 19 | It'll Only Take a Second! | Мне только спросить |
| 20 | Reboot | Перезапуск |
| 21 | Atlas Shrugged | Атлант расправил плечи |
| 22 | The Champion's Path | Путь чемпиона |
| 23 | Thalassophobia | Талассофобия |

Note: English translations are from VGTimes/ShowGamer RU walkthroughs. Quest 8 ("Проездной") is translated as either "Train Ticket" or "Travel Pass" across guides; in-game English string unconfirmed. [Single source for exact EN strings -- verify against in-game text]

---

## Entry point

Separate campaign from the main menu (own difficulty selection). Narratively picks up directly after Trapped in Limbo's ending -- P-3 wakes beside the damaged Twin hull; Katya pierces his glove and rides inside it (replacing CHAR-les). Story prerequisite is narrative continuity with DLC #2 and the base game "longer" ending; no save import required. Fully isolated save slot.

_[Narrative prerequisite carries spoiler: dlc:enchantment-under-sea -- deliver structural "main menu entry" info freely; gate narrative context]_
[Released: January 28, 2025. Gameplay trailer premiered December 9, 2024 -- Confirmed: multiple sources]

## Zone graph edges

| ID | From | To | Type | Direction | Condition | PoNR | Notes |
|---|---|---|---|---|---|---|---|
| EutS-E0 | Main Menu | `neptune_sechenov_complex` | **DLC ENTRY POINT** | one-way | Own DLC / Atomic Pass | No | Flagged: DLC entry edge |
| EutS-E1 | `neptune_sechenov_complex` | `neptune_chelomey_ruins` | story | one-way | Pick lock, descend | No | |
| EutS-E2 | `neptune_chelomey_ruins` | `neptune_lakeshore` | story (Bumblebee robot) | one-way | Robogirl boss | No | Robogirl fight (enemy-tier: 1) |
| EutS-E3 | `neptune_lakeshore` | `neptune_babazina_hut` | story | one-way | Get Kuzmich shotgun | No | Arena wave |
| EutS-E4 | `neptune_babazina_hut` | `neptune_entry_hub` | elevator | one-way | Baba Zina drop-off | Yes | Enter Neptune Complex |
| EutS-E5 | `neptune_entry_hub` --> ... | Sequential interior zones | story | mostly one-way | Quest progression | varies | Mostly linear through Neptune zones |
| EutS-E6 | `neptune_sub_bay` | `neptune_open_water` | airlock dive | one-way | Diving hatch | Yes | Stealth from MO-R4Y underwater |
| EutS-E7 | `neptune_city_of_dolphins` | `neptune_final_arena` | story | one-way | Reach gates | **Yes** | Final boss (enemy-tier: 1 -- MO-R4Y); sub escape follows |

Boss identities at EutS-E2 and EutS-E7: enemy-tier: 1 -- do not name preemptively at enemy-tier: 0.

## NORA stations

The DLC's repair/upgrade vendors are **repair cabinets** named **Eleanor (Элеанора)** and **Samodelkin (Самоделкин)** -- powered on by the player, climbed inside to upgrade. NORA appears narratively (comedic interactions with Blesna). Save points are rest/safe rooms (комната отдыха). Isolated from base-game NORA network.

| zone-id | Location | Function |
|---|---|---|
| `neptune_block_b` | Repair cabinets Eleanor & Samodelkin | Weapon / glove upgrades |
| (various) | Rest / safe rooms throughout Neptune | Save + supply |

[Confirmed: subagent + ClutchPoints]

## DLC weapons and abilities introduced

**Weapons:**
- **Thunderclap / Громовержец** -- electric hammer/flail hybrid; extracted from a NORA robot. Core melee/ranged hybrid weapon. Tied to DLC progression.
- **KM-4 / KZMI-4 "Kuzmich" / «Кузьмич»** -- customizable double-barrel shotgun with grenade alt-fire. Obtained early (Baba Zina area).

**Glove abilities:**
- **Whip** -- grapple hook; 3D mobility, pull to enemies/ledges, dodge. Core traversal and combat tool. Community rates it highly.
- **Blaze / Загар** -- burning polymer fireballs; AoE; burns polymer growths blocking paths.

All tied to DLC progression.
[Confirmed: Steam/PSN store + reviews]

> **Reconciliation note (Reddit sweep vs deep research):** The pre-ingestion reddit sweep (F20) mentioned a "Spear weapon" for EutS. Deep research confirms two weapons only (Thunderclap and Kuzmich); no separate Spear documented. "Spear" may be a community nickname for Thunderclap (the flail/hammer can be thrown as a projectile). The deep research is authoritative; treat "Spear = Thunderclap" as working hypothesis until in-game verification. [Single source for Spear identity -- verify]

> **Reconciliation note (Polymorphs):** The pre-ingestion reddit sweep (F16) attributed Polymorphs to EutS. Deep research confirms Polymorphs (fire/ice-switching crystal humans) are introduced in **DLC #4 Blood on Crystal**, not EutS. Corrected per deep research.

## Traversal

Return to base-game-style FPS combat after the platformer DLC #2. Key new element: **Whip grapple-hook** for 3D mobility. Notable set-piece: **open underwater section** (`neptune_open_water`) where the player must avoid the giant final boss creature -- you cannot fight it underwater; getting spotted means death. The BioShock/Rapture atmosphere is a deliberate homage (Mundfish plays BioShock-like music on Neptune Complex entry).
[Confirmed: 2 languages]

## Optional content registry

| Content name | Type | Parent zone | Unlock condition | Access window | Recommended point | Failure mode |
|---|---|---|---|---|---|---|
| Chirpers (Щебетари) | Collectible audio | Multiple zones | Exploration | During pass | As encountered | **Missable** -- backtracking limited |
| Hunter's stashes | Collectible | Multiple zones | Exploration ("Master of Survival" achievement) | During pass | -- | **Missable** |
| Dolphin Footballer toy | Collectible toy | Early Neptune | Found in restroom | Once | Early | Appears on safe-room TVs after pickup |
| Yellow chests (weapon upgrades) | Upgrade | All zones | Exploration | During pass | -- | Recoverable if backtrack available |
| Moby Dick window song | Achievement event | Specific window in Neptune | Listen to chirper at view | Specific moment | -- | **Missable** -- see achievements.md |

See `../sections/missables.md` for the full DLC missable list.

## Locks-and-keys

| Lock location | Key required | Key source zone | Visible before key? | Notes |
|---|---|---|---|---|
| Dolphin cage / gate ("Candle" socket) | "Candle" (Свеча) power source | Neptune interior rooms | Yes | Must answer the dolphin's continent riddle |
| Graphic-key door ("Where Are They?!") | Graphic key code | Found near destroyed bridge / lake bottom | Yes | Only one graphic-key lock in DLC |
| Submarine bay doors | Override / valve sequence | Depot/cistern puzzle | Yes | Cistern puzzle: Down -> Rotate -> Up |

## Soft-locks

No notable soft-locks reported. PSNProfiles rates it 2/10 difficulty, 0 glitched trophies. The underwater stealth section can kill repeatedly but reloads at checkpoint.
[Confirmed]

## Carry-over

Standalone campaign with its own save and arsenal. No documented weapon carry-over to the base game. [Single source / structural inference -- verify on first run]

## Story connection

[spoiler: dlc:enchantment-under-sea]

Direct sequel to Trapped in Limbo. P-3 + Katya escape Limbo, traverse destroyed Chelomey, reunite with Granny Zina (Katya's mother) and Terentiy (from DLC #1), then dive to Neptune to recover the **Beta Connector rings** P-3 discarded in the base game. New allies: **Nikolai/Kolya** (modeled on and voiced by science-communicator Kyle Hill -- confirmed by game director Robert Bagratuni: "decided to involve the famous sci-pop influencer Kyle Hill, who gave his appearance and voice to one of the new characters of the DLC"), **the Hunter**, and **Nastya** (ichthyologist), plus repair-bot Samodelkin. Final boss: **MO-R4Y / Мурена** (designation МУР-8Н4). They escape by submarine; Katya is now in a Twin's body, setting up Blood on Crystal.

Note: designation "MOR-4Y/МУР-4Й" used in some community posts is wrong. Russian sources and Fandom wiki give **МУР-8Н4 / MO-R4Y "Мурена" (Moray)**.

**The Twins:** Ekaterina/Katya's consciousness was split by Sechenov into the Left and Right robotic ballerina Twins. By EutS, Katya has reassembled into P-3's glove (the "Blesna"/Teardrop) and later takes control of one surviving Twin body to gain firepower. [Deliver post-encounter on player request; enemy-tier: 1]
[Confirmed: Fandom wiki, 2 languages]

## What makes EutS stand out

Return to spectacular base-game FPS combat after the divisive platformer DLC #2. Community and critics credit: the **Whip grapple** for 3D mobility, two strong new weapons (Thunderclap, Kuzmich), the **Rapture-like Neptune atmosphere**, and a stronger character-driven story (Nastya, Kolya, Hunter). Metacritic user reviews repeatedly call it the best DLC.
[Confirmed: Focus Entertainment, Metacritic, Niche Gamer, ClutchPoints]

## Common confusions

- The final boss designation "MOR-4Y/МУР-4Й" used in some guides is wrong -- correct is МУР-8Н4 / MO-R4Y "Мурена" (Moray).
- Polymorphs appear in DLC #4 Blood on Crystal, NOT in EutS.
- Zone prefix is `neptune_*`, not `triton_complex_*` (Triton is a sub-complex name).
- Quest 8 English name uncertain: "Train Ticket" or "Travel Pass" -- verify in-game.

## Length

~5-6 hours (game director Robert Bagratuni, Game Rant interview).
[Confirmed: 2 languages]

---

## Reddit sweep additions (2026-05-28)

**Moray boss (F18):** Final boss of EutS. Community consensus: hardest boss in the entire game including all DLCs. Primary threat: shockwave orb projectile bursts. Recommended loadout: Whip (fully upgraded) + horizontal shotgun mod. Sustained high mobility; dodge shockwave orbs as top priority. See `../npcs/bosses.md` Moray entry for full tactics (enemy-tier: 1 -- post-encounter only).

**Thunderclap / "Spear" weapon (F20):** Deep research confirms Thunderclap/Громовержец as the EutS electric hammer. Community "Spear" nickname likely refers to Thunderclap's projectile throw. Extremely effective when fully upgraded -- near-one-shots enemies outside boss encounters. [identity reconciliation above; verify in-game]

_source: r/atomicheart/comments/1tkw1i0 (score 122, 0.94 ratio) · capture: manual_paste · confidence: medium · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:enchantment-under-sea_

---

## Sources

Primary: VGTimes.ru (EN/RU), ShowGamer.ru, Fandom wiki, cyber.sports.ru, ClutchPoints, Focus Entertainment press release (Jan 28, 2025), Game Rant director interview, Metacritic, PSNProfiles
_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:enchantment-under-sea_
