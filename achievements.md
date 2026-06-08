# Atomic Heart -- Achievements

**status:** research-integrated
**deferred-to:** n/a
**deferred-reason:** Doctor branch C (2026-05-22): 69 of ~82 retrieved; BoC gap noted. BoC gap filled 2026-05-22 via targeted deep-research (13 achievements confirmed). TiL and EutS remain partial scaffold (DLC not yet researched); deferred-to: DLC-research. Total: 82 confirmed. DLC counts corrected: TiL 10 (was 11/12), EutS 8 (was 6), BoC 13 (was 0).
**last_reconciled:** 2026-05-22
**stub_source:** Multiple mirrors -- Steam stats unavailable. Primary: vgtimes.com/games/atomic-heart/achievements-and-trophies/; secondary: daynglsgameguides.com, gamingbolt.com. BoC gap fill: Imagine Steam Community guide, Treyex Gaming, GAMES.GG (2026-04-27), iXBT.games (2026-04-16), TrueAchievements DLC pages, Steam Hunters AppID 668580.
**stub_fetched:** 2026-05-22

## Why this file exists

Single source of truth for "what achievements does this game have, and what do I need to do for each one." The reader routes all achievement-class queries here first (by name, category, or "what am I about to miss"), then follows `vector-binding` to the canonical claim home for full detail. Authoritative for trigger conditions, PoNR windows, and missability.

## Structure

One H2 per `trigger_type` (Progression / Branch / Mastery / Collection / Threshold / Discovery). H3 per achievement. DLC achievements carry `spoiler: dlc:<name>`. Entries for unresearched DLCs (Trapped in Limbo, Enchantment Under the Sea, Blood on Crystal) are partial scaffold with `deferred-to: DLC-research` and `vector-binding: _overflow/`.

---

## Progression

### Happy Polymerization Day!

- **id:** happy-polymerization-day
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Fly out of Chelomey City at the end of the Prologue
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `nav/architecture.md` edge E02
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** progression

### Pistils and Stamens

- **id:** pistils-and-stamens
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Exit Vavilov Complex via the elevator after delivering all 4 canisters
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `nav/architecture.md` edge E12
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** progression

### Tickets, Please!

- **id:** tickets-please
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Board the train at Lesnaya Maglev station
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** valid monthly pass (post-office rooftop; see `nav/architecture.md` Locks-and-Keys E15)
- **vector-binding:** `nav/architecture.md` edge E17
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** progression

### Quite an Achievement

- **id:** quite-an-achievement
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Complete the VDNH complex and escape via the Drill Mode sequence
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `nav/architecture.md` edge E28
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** progression

### Curtain

- **id:** curtain
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Complete the theater sequence (Ch.4 -- defeat Natasha + collect Petrov's head)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `nav/architecture.md` edge E39; `npcs/bosses.md` Natasha entry
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression
- **notes:** Entry names Natasha boss encounter in vector-binding; gate at enemy-tier: 1.

### Medical Checkup

- **id:** medical-checkup
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Reach the hospital ward in Pavlov Complex (Ch.5)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `nav/architecture.md` edge E44
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** progression

### Freedom Reflex

- **id:** freedom-reflex
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Reach Pavlov Complex (Sanatorium / Hospital area, Ch.5)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `nav/architecture.md` edges E43-E44
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** progression

### Kommunism 2.0

- **id:** kommunism-2-0
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Discover the Academy of Consequences secret in the underwater segment (Ch.6)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `nav/architecture.md` edge E50
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** progression

### Make It Go Round

- **id:** make-it-go-round
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Defeat the Hedgie boss at Arena Park (Ch.3)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `npcs/bosses.md` Hedgie entry; `nav/architecture.md` edge E21
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression

### Medium Rare

- **id:** medium-rare
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Defeat the Belyash boss at Lastochkin Theater Grounds (Ch.4)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `npcs/bosses.md` Belyash entry; `nav/architecture.md` edge E36
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression

### Plyusch Rush

- **id:** plyusch-rush
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Defeat the Plyusch boss inside VDNH (Ch.3)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `npcs/bosses.md` Plyusch entry
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression

### Show's Over

- **id:** shows-over
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Defeat the Natasha boss at Theater Stage (Ch.4)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `npcs/bosses.md` Natasha entry; `nav/architecture.md` edge E39
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression

### Dew Point

- **id:** dew-point
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Defeat the Dewdrop boss at Lighthouse Beach (Ch.6)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `npcs/bosses.md` Dewdrop entry; `nav/architecture.md` edge E49
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression

### Artisan

- **id:** artisan
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Craft any weapon at a NORA station for the first time
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** any weapon blueprint + materials
- **vector-binding:** `mechanics.md` NORA section; `items/weapons.md`
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** Classified progression over discovery: the game directs the player to NORA in the Ch.1 tutorial. Every player who follows the tutorial arc will trigger this naturally.

---

_DLC -- Annihilation Instinct_

### Weird Science

- **id:** weird-science
- **hidden:** yes
- **trigger_type:** progression
- **trigger:** Gain access to the ORB laboratory (Lebedev's Lab) in the Annihilation Instinct DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** DLC started; Greenhouse Sector cleared
- **vector-binding:** `nav/mendeleev_complex.md` Lebedev's Lab entry; `nav/architecture.md` DLC edge DLC-E05
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct

### Lord of the Flies

- **id:** lord-of-the-flies
- **hidden:** yes
- **trigger_type:** progression
- **trigger:** Use the Strekoza (flying platform) for the first time in the Annihilation Instinct DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Lebedev's Lab Strekoza unlock (DLC-E06)
- **vector-binding:** `nav/mendeleev_complex.md`; `nav/architecture.md` DLC edge DLC-E06
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct

### A Girl's Best Friend

- **id:** a-girls-best-friend
- **hidden:** yes
- **trigger_type:** progression
- **trigger:** Feed all BEA-D units (8 total) to NORA's Brain/Cradle
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** All 8 BEA-Ds collected across DLC missions
- **vector-binding:** `nav/mendeleev_complex.md` BEA-D sequence; `nav/architecture.md` DLC edge DLC-E12
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct

### Return to Utopia

- **id:** return-to-utopia
- **hidden:** yes
- **trigger_type:** progression
- **trigger:** Complete the Annihilation Instinct DLC (reach ending cinematic)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** All main DLC missions; all BEA-Ds delivered (DLC-E12)
- **vector-binding:** `nav/mendeleev_complex.md`; `nav/architecture.md` DLC edge DLC-E12
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct

---

_DLC -- Enchantment Under the Sea (doctor ingested 2026-06-05)_

### And now--CHAR-les

- **id:** and-now-char-les
- **hidden:** yes
- **trigger_type:** progression
- **trigger:** Complete the Enchantment Under the Sea story DLC (reach the submarine escape ending -- quest "Thalassophobia" final)
- **missable:** no
- **ponr-window:** n/a (story completion)
- **prereqs:** EutS DLC started and all quests completed
- **vector-binding:** `nav/enchantment_under_sea.md` EutS-E7 (final boss arc); `nav/architecture.md` §DLC -- Enchantment Under the Sea
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:enchantment-under-sea
- **notes:** DLC attribution CONFIRMED by primary sources (TrueAchievements DLC page, VGTimes EutS trophy list, GameFAQs). "And now--CHAR-les" is the EutS story-completion gold trophy; CHAR-les is the main antagonist named at DLC completion but not fought until BoC ("Farewell, Old Friend" is the distinct BoC final boss achievement).
_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:enchantment-under-sea_

---

_DLC -- Blood on Crystal_

### This Is the End

- **id:** this-is-the-end
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Complete the Blood on Crystal story DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Blood on Crystal DLC started and all story missions completed
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

### Let's Shake on It!

- **id:** lets-shake-on-it
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Exterminate the RACCOON boss in the Blood on Crystal DLC (story-required encounter)
- **missable:** no
- **ponr-window:** n/a (story-required)
- **prereqs:** Blood on Crystal DLC; reach RACCOON boss encounter
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

### Clean in Two

- **id:** clean-in-two
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Defeat the Second Twin boss in the Blood on Crystal DLC (story-required encounter)
- **missable:** no
- **ponr-window:** n/a (story-required)
- **prereqs:** Blood on Crystal DLC; reach Second Twin encounter
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

### For Chief's a Jolly Good Fellow

- **id:** for-chiefs-a-jolly-good-fellow
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Save Sechenov -- reach the story beat requiring Sechenov's rescue in the Blood on Crystal DLC
- **missable:** no
- **ponr-window:** n/a (story beat on main path)
- **prereqs:** Blood on Crystal DLC; reach the Sechenov story event
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

### Farewell, Old Friend

- **id:** farewell-old-friend
- **hidden:** no
- **trigger_type:** progression
- **trigger:** Beat CHAR-les in the Blood on Crystal DLC final confrontation
- **missable:** no
- **ponr-window:** n/a (final boss; story-required)
- **prereqs:** Blood on Crystal DLC; reach the CHAR-les final fight
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
- **notes:** CHAR-les also appears in Enchantment Under the Sea ("And now--CHAR-les"). This achievement is the Blood on Crystal final boss fight specifically.
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

---

## Branch

### Murderous Beauty

- **id:** murderous-beauty
- **hidden:** no
- **trigger_type:** branch
- **trigger:** Defeat the Twins by choosing the E52b path at the Chelomey revisit dialogue -- choose Granny Zina option 2 (the fight/main ending) rather than option 1 (walk-away ending)
- **missable:** yes
- **ponr-window:** chelomey_revisit (E51/E52) -- must choose E52b; E52a (walk-away) permanently skips the Twins fight and locks this achievement
- **prereqs:** Reach chelomey_revisit (Ch.6); choose E52b
- **vector-binding:** `nav/architecture.md` edges E52a/E52b/E53; `npcs/bosses.md` Twins entry; `sections/ch10_endgame.md`
- **enemy-tier:** 2
- **puzzle-tier:** 0
- **spoiler:** story
- **notes:** E52a (walk-away / "good" ending) has no corresponding achievement. E52b is described in architecture.md as the "canonical bad/main ending." Branch call: every player reaches the E52a/E52b dialogue (not progression), but only E52b triggers the achievement. Also note: Scanner achievement requires scanning both Twins during the E53 fight -- both Scanner and Murderous Beauty require E52b.

---

_DLC -- Blood on Crystal_

### Validol's Our Bro

- **id:** validols-our-bro
- **hidden:** no
- **trigger_type:** branch
- **trigger:** Complete Validol's mission peacefully -- do not kill the three depressed crystal humans; let Nastya/NORA speak in dialogue
- **missable:** yes
- **ponr-window:** Before Validol's mission conclusion in Blood on Crystal DLC -- killing any crystal human permanently forfeits the achievement
- **prereqs:** Blood on Crystal DLC; Validol's mission active; choose non-lethal path throughout
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

---

## Mastery

### Strike

- **id:** strike
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Defeat Hedgie at Arena Park (Ch.3) without firing any weapon -- Hedgie must destroy all five arena statues; any weapon shot permanently forfeits the achievement
- **missable:** yes
- **ponr-window:** arena_park boss fight at E21 -- one-shot window; no retry
- **prereqs:** none (enter arena with no weapon shots fired)
- **vector-binding:** `npcs/bosses.md` Hedgie entry; `dependencies.md` DEP-013; `nav/architecture.md` edge E21
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression
- **notes:** Restriction: zero weapon use. Statues + Shok must deal all damage. DEP-013 confirms the one-shot constraint. Whether Polymer abilities (Telekinesis, Frostbite, Shok) count as "weapons" is unconfirmed [C:2] -- sources say "without firing any shots," implying projectile weapons only.

### Chop Chop Chop

- **id:** chop-chop-chop
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Defeat Belyash at Lastochkin Theater Grounds (Ch.4) using only melee weapons -- any ranged weapon use permanently forfeits the achievement
- **missable:** yes
- **ponr-window:** lastochkin_theater_grounds boss fight (first Belyash encounter, E35/E36) -- one-shot window
- **prereqs:** Zvezdochka or other melee weapon equipped
- **vector-binding:** `npcs/bosses.md` Belyash entry; `dependencies.md` DEP-014; `nav/architecture.md` edge E36
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression
- **notes:** Restriction: melee only. DEP-014 says "ranged weapon use forfeits." Whether Polymer abilities count as "ranged" is unconfirmed [C:2].

### Atomic Heart

- **id:** atomic-heart-achievement
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Complete the full game on Armageddon (Hardcore) difficulty
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Must select hardest difficulty at game start (or NG+ equivalent)
- **vector-binding:** `mechanics.md` difficulty section
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** "Armageddon" per daynglsgameguides.com; "Hardcore mode" per gamingbolt/vgtimes -- same difficulty, different localization label. Confirm in-game difficulty name [C:3].

### Hothead

- **id:** hothead
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Land 25 aimed headshots using the PM (Makarov) pistol specifically, via the aim-down-sights mechanic
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** PM pistol (available from Ch.1 start)
- **vector-binding:** `items/weapons.md` PM pistol section
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Triple Penetration

- **id:** triple-penetration
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Kill 3 or more enemies with a single Railgun shot, using the Railgun's penetrating-shot mechanic to line up multiple targets
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Railgun weapon
- **vector-binding:** `items/weapons.md` Railgun section
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** Mastery over discovery: the Railgun's penetrating shot is documented in the weapon description. See DEP-017 -- do NOT use Railgun on Lab Techs (destroys loot). Aim for grouped non-farming targets.

### Alcoholics Anonymous

- **id:** alcoholics-anonymous
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Drink enough vodka consumables to enter drunk status, then kill 5 enemies while drunk
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Vodka consumables (lootable throughout game)
- **vector-binding:** `mechanics.md` consumables/status section; `items/crafting_materials.md`
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** Mastery/discovery borderline. Drunk-status is flagged on the vodka item (not hidden), so Q3 (restriction: must be drunk) wins over Q6. The required drunk state during kills is the deliberate constraint.

### Time in a Bottle

- **id:** time-in-a-bottle
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Kill 3 enemies within a single technostasis activation in the Annihilation Instinct DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Technostasis ability (granted by Lebedev in DLC-E05)
- **vector-binding:** `nav/mendeleev_complex.md`; `items/abilities.md` technostasis entry
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct

### Maximum Strength

- **id:** maximum-strength
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Fully upgrade both the Klusha and Secateur to maximum level (all upgrade slots on each weapon filled)
- **missable:** yes
- **ponr-window:** Before DLC-E12 (Eleanor's Heart final PoNR) -- requires all Klusha and Secateur blueprints plus sufficient Energy Modules
- **prereqs:** Klusha blueprints: Handle (Flooded Village), Blade (Mendeleev Complex), Cartridge (Mendeleev Hangar); Secateur blueprints: Energy Supercharger, Wide-Spread, Extended Magazine (all Mendeleev Complex); Energy Modules from BEA-D ostrich farming (DEP-021)
- **vector-binding:** `items/weapons.md` Klusha + Secateur entries; `dependencies.md` DEP-021; `nav/architecture.md` DLC Optional Content Registry
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct
- **notes:** Klusha Handle location confirmed in Flooded Village (before Lebedev); many EN video guides incorrectly place it in Freedom Park. Energy Module bottleneck: farm BEA-D ostrich variants before DLC endgame per DEP-021.

---

_DLC -- Trapped in Limbo mastery (partial scaffold)_

### Slashing Through the Limbo Waves

- **id:** slashing-through-the-limbo-waves
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Complete the Plateau of Responsibility area in Trapped in Limbo without dying
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Trapped in Limbo DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo

### Conqueror of Annapurna

- **id:** conqueror-of-annapurna
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Complete the Tower of Memory area in Trapped in Limbo without dying
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Trapped in Limbo DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo

### Conqueror of Chomolungma

- **id:** conqueror-of-chomolungma
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Complete the Cliff of Perseverance area in Trapped in Limbo without dying
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Trapped in Limbo DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo

### Daring as a Bullet is Sharp

- **id:** daring-as-a-bullet-is-sharp
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Complete the Avenue of Speed area in Trapped in Limbo without dying
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Trapped in Limbo DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo

### Don't Mess With the Major

- **id:** dont-mess-with-the-major
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Complete the entire Trapped in Limbo DLC without dying
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo

### Conservationist

- **id:** conservationist
- **hidden:** yes
- **trigger_type:** mastery
- **trigger:** Collect a gold coin in Trapped in Limbo without shooting the Pchela repair robot
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** gold-coin-adjacent Pchela encounter; Trapped in Limbo DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo
- **notes:** Restriction: no Pchela shots at the relevant coin pickup. Pchela mechanics in base game documented in DEP-005; Trapped in Limbo Pchela behavior unresearched.

---

_DLC -- Blood on Crystal_

### Terminator's Death

- **id:** terminators-death
- **hidden:** no
- **trigger_type:** mastery
- **trigger:** Use an industrial press to destroy robots -- freeze a robot under the press in the Engineered Future section near Garage Door 19
- **missable:** yes
- **ponr-window:** Before Engineered Future section closes in Blood on Crystal DLC
- **prereqs:** Blood on Crystal DLC; reach Engineered Future section (Garage Door 19 area); freeze method (Frostbite or equivalent)
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
- **notes:** Restriction: must use the industrial press specifically (not standard weapons). Freeze a robot to position it under the press before activating.
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

---

## Collection

### The Motherland Does Not Forget its Heroes

- **id:** the-motherland-does-not-forget-its-heroes
- **hidden:** no
- **trigger_type:** collection
- **genre:** meta
- **trigger:** Unlock every other achievement in the game (base game + all DLC)
- **missable:** yes (depends on all other missable achievements)
- **ponr-window:** n/a (depends on individual achievement windows)
- **prereqs:** All other achievements
- **vector-binding:** `achievements.md` (this file)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** PS4 Platinum equivalent. On Steam this is a standard achievement. Finite set: all 82 achievements (per search-result count). Practical prerequisite order: missable achievements first (Strike, Chop Chop Chop, How Can I Help You?, Scanner/Murderous Beauty, all TG8/TG12-locked collectibles).

### Lord of War

- **id:** lord-of-war
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Craft all 12 base game weapon types at NORA at least once
- **missable:** no
- **ponr-window:** n/a (NORA crafting available in post-game free-roam; weapon blueprints are not locked by PoNR)
- **prereqs:** All weapon blueprints + sufficient crafting materials
- **vector-binding:** `items/weapons.md` full weapon list
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Weapon Master

- **id:** weapon-master
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Craft any 5 distinct weapon types at NORA (subset of Lord of War)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** 5 weapon blueprints + materials
- **vector-binding:** `items/weapons.md`
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Chemist

- **id:** chemist
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Craft at least one of each consumable type at NORA
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** All consumable recipes + materials
- **vector-binding:** `items/crafting_materials.md` consumables section
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### The Great Inventor

- **id:** the-great-inventor
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Fully upgrade a single weapon to its maximum level (all upgrade slots filled on one weapon)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Sufficient upgrade materials for one weapon; see `items/upgrades.md` for material costs
- **vector-binding:** `items/weapons.md`; `items/upgrades.md`
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Lefthand Mastery

- **id:** lefthand-mastery
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Fully unlock all nodes in one Polymer ability skill tree branch (Frostbite, Telekinesis, Shok, or Mass TK)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Sufficient neuropolymer; NORA respec available if branch was wrong choice
- **vector-binding:** `items/abilities.md` skill tree section
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Scanner

- **id:** scanner
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Scan every enemy mob type in the game (35-38 types per sources [C:2]). Bosses must be scanned before kill; each is a one-time encounter. Twins (Left + Right) must be scanned individually during the Ch.10 final fight only -- Prologue appearance does not count per DEP-012.
- **missable:** yes
- **ponr-window:** Multiple windows. Critical: (1) must take E52b ending path to access Twins scan (E52a skips Twins fight permanently); (2) each boss is a one-time scan window. Scan all bosses on first encounter or the window is gone.
- **prereqs:** Scanner ability (Polymer glove); E52b at chelomey_revisit to access Twins
- **vector-binding:** `npcs/bosses.md` (all boss entries); `npcs/robots.md`; `npcs/mutants.md`; `dependencies.md` DEP-012
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** progression
- **notes:** Source discrepancy: architecture.md Optional Content Registry says "38 enemy scans" vs daynglsgameguides "35 mob types." May reflect individual-encounter vs distinct-type counting. Confirm total in-game [C:2]. Practical note: Scanner and Murderous Beauty both require E52b -- do both in the same playthrough.

### Burning Ears

- **id:** burning-ears
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Find all 72 Chirpers (audio collectibles found throughout all chapters)
- **missable:** yes
- **ponr-window:** Multiple PoNRs each lock the preceding zone: E12 (Vavilov), E17 (Forester), E28 (VDNH building interior), E39 (Theater/Sechenov area), E42 (Pavlov bridge). Open-world Chirpers are always-available including post-game free-roam.
- **prereqs:** Scanner ability to locate
- **vector-binding:** `nav/architecture.md` Optional Content Registry (Chirpers row); per-chapter `sections/` files
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** Community recommends using multiple guides in tandem -- no single guide has documented all 72 locations; combination of DaynglsGuides + Divinsion's Steam guide is the most-cited pairing. Community reports a known 71-documented/one-glitched discrepancy where one Chirper is widely noted as not registering or being absent from all guide lists; corpus count of 72 is from official trophy text and should be treated as the target total, but if 71 are confirmed and the achievement does not trigger, investigate the glitch report.
_source: r/atomicheart/comments/11tazdc (community chirper discussion) · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

### The Necromancer

- **id:** the-necromancer
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Interact with every Talking Dead body in the game (53 total -- scan + interact)
- **missable:** yes
- **ponr-window:** Same PoNR structure as Burning Ears: E12, E17, E28, E39, E42, E48 each permanently lock bodies in their preceding zones
- **prereqs:** Scanner ability
- **vector-binding:** per-chapter `sections/` files; `nav/architecture.md` Optional Content Registry (Talking Deads row)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Beast Friend

- **id:** beast-friend
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Find all 3 talking dead animals: hen, cow, and a third animal near the solar arrays in the Solnechnaya open world
- **missable:** no
- **ponr-window:** n/a (open-world locations; always-available per architecture.md)
- **prereqs:** none
- **vector-binding:** `nav/architecture.md` Optional Content Registry (Beast Friend row)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### More Than Profit

- **id:** more-than-profit
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Find all 24 Lootyagin chests (3 bronze/silver/gold per Testing Ground x 8 TGs)
- **missable:** yes
- **ponr-window:** TG8 missable before E36/E39 (DEP-002); TG12 missable before E48 (DEP-003). All other TGs are always-available including post-game free-roam.
- **prereqs:** Complete each Testing Ground to unlock its chest progression
- **vector-binding:** `optional_zones/polygons.md`; `dependencies.md` DEP-002, DEP-003
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Clean-up

- **id:** clean-up
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Complete all 8 accessible Testing Grounds (TG1, TG2, TG6, TG8, TG9, TG10, TG11, TG12)
- **missable:** yes
- **ponr-window:** TG8: before E36/E39 (Ch.4); TG12: before E48 (Ch.5). All others are always-available.
- **prereqs:** TG8 and TG12 entered in their respective missable windows (see DEP-002, DEP-003)
- **vector-binding:** `optional_zones/polygons.md`; `nav/architecture.md` Optional Content Registry; `dependencies.md` DEP-002, DEP-003
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Apple Pie

- **id:** apple-pie
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Pick up all apples in the Limbo dream sequences (Chs 3-5)
- **missable:** yes
- **ponr-window:** Each Limbo sequence closes when its dream ends. Specific PoNR timing per dream sequence unknown [C:1] -- verify in-game.
- **prereqs:** none
- **vector-binding:** `sections/` (per-chapter walkthrough files for Limbo sequences)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** progression
- **notes:** Limbo apple locations are not documented in current corpus (not covered in P1-P4 research). Needs targeted fetch. [C:1]
  **Platform note (PS5 only):** Community reports a PS5-specific bug where the apple counter resets to 0 after re-entering Limbo, requiring all apples to be collected in a single session per Limbo visit. Not applicable to PC.
  _source: r/atomicheart/comments/11tazdc (PS5 counter bug report) · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: progression_

---

_DLC -- Trapped in Limbo collection (partial scaffold)_

### Gold Rush

- **id:** gold-rush
- **hidden:** yes
- **trigger_type:** collection
- **trigger:** Collect 76 gold coins across the Trapped in Limbo DLC (collection: if the DLC contains exactly 76 coins)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Trapped in Limbo DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo
- **notes:** Classified collection on the assumption that the DLC has exactly 76 coins (finite named set). If any coin counts toward the 76 (no named set), reclassify as threshold.

### Master of Survival

- **id:** master-of-survival
- **hidden:** yes
- **trigger_type:** collection
- **trigger:** Find all of the Hunter's stashes in the Enchantment Under the Sea DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Enchantment Under the Sea DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Enchantment Under the Sea
- **notes:** Re-attributed from Trapped in Limbo to Enchantment Under the Sea per TrueAchievements DLC page cross-check (2026-05-22). Visible on VGTimes PS5 trophy page for EutS DLC.
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Enchantment Under the Sea_

### The Casino Isn't Always in the Black

- **id:** the-casino-isnt-always-in-the-black
- **hidden:** yes
- **trigger_type:** collection
- **trigger:** Obtain every item from the slot machine in the Trapped in Limbo DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Sufficient coins to operate the slot machine; Trapped in Limbo DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo

---

_DLC -- Blood on Crystal_

### Crystal Platinum

- **id:** crystal-platinum
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Collect all 11 crystal figurines hidden in the Blood on Crystal complex in a single playthrough -- no chapter select available
- **missable:** yes
- **ponr-window:** Before DLC endgame PoNR; all 11 figurines must be found in one run (no chapter select in Blood on Crystal DLC)
- **prereqs:** Blood on Crystal DLC; locate all 11 figurine hiding spots
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
- **notes:** Hardest BoC achievement: ~19% completion rate (108 of 6,763 Xbox trackers per GAMES.GG/TrueAchievements as of 2026-04-27). Steam description: "Collect all of the figurines hidden in the complex." The "11 figurines" count is from Imagine's Steam Community 100% guide; treat as working target until in-game verification.
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_
> **Cross-system dependency** -- see `dependencies.md` DEP-025: All 11 crystal figurines must be collected in one run (no chapter select); missing any one permanently voids this achievement. Confirmed independently in `nav/blood_on_crystal.md`, `sections/missables.md`, and `nav/architecture.md`.

### Final Burn-down

- **id:** final-burn-down
- **hidden:** no
- **trigger_type:** collection
- **trigger:** Destroy all infected Mother plants on the submarine section of Blood on Crystal DLC -- backtrack to kill any missed plants
- **missable:** yes
- **ponr-window:** Before the submarine section closes in Blood on Crystal DLC; backtracking within the section may be possible but zone may lock later
- **prereqs:** Blood on Crystal DLC; reach the submarine section
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

---

## Threshold

### Polymerization

- **id:** polymerization
- **hidden:** no
- **trigger_type:** threshold
- **trigger:** Collect a cumulative total of 100 units of Polymer Jelly (any source; counter is persistent)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none
- **vector-binding:** `items/crafting_materials.md` Polymer Jelly entry
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Avatar

- **id:** avatar
- **hidden:** no
- **trigger_type:** threshold
- **trigger:** Kill 10 enemies while on fire + 10 while electrified + 10 while frozen (three independent 10-kill counters using elemental status effects)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Frostbite (freeze), Shok/electro cartridge (electrify), fire cartridge (fire)
- **vector-binding:** `mechanics.md` elemental status section; `items/abilities.md`
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Hands on the Hood

- **id:** hands-on-the-hood
- **hidden:** no
- **trigger_type:** threshold
- **trigger:** Hit 20 enemies total using a Moskvich car (drive into or over them in the open world)
- **missable:** no
- **ponr-window:** n/a (Moskvich cars available in Forester + Solnechnaya open world; post-game free-roam works)
- **prereqs:** Moskvich car; open-world zone with enemy clusters
- **vector-binding:** `mechanics.md` vehicle section
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Ultimate Storm

- **id:** ultimate-storm
- **hidden:** yes
- **trigger_type:** threshold
- **trigger:** Destroy 15 enemies total using the Neuropolymeric Launch Module ability in Annihilation Instinct DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Neuropolymeric Launch Module (granted in DLC)
- **vector-binding:** `items/abilities.md` neuropolymeric launch module; `nav/mendeleev_complex.md`
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct

---

_DLC -- Trapped in Limbo threshold (partial scaffold)_

### Apple Pie 3826

- **id:** apple-pie-3826
- **hidden:** yes
- **trigger_type:** threshold
- **trigger:** Collect 3,826 apples total across the Trapped in Limbo DLC (cumulative; large count)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Trapped in Limbo DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo
- **notes:** Threshold over collection: 3,826 is a count of any apple in the DLC, not a finite named set. The number 3826 is likely a facility reference (Facility 3826).

---

## Discovery

### How Can I Help You?

- **id:** how-can-i-help-you
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Interact with a specific phone booth on the embankment near the fountain in Chelomey City Prologue -- "fountain on embankment, turn from boat toward fountain"
- **missable:** yes
- **ponr-window:** Before E02 (helicopter flight from Chelomey) -- Prologue-only; permanently locked after E02
- **prereqs:** Must be in chelomey_city_prologue before story advances
- **vector-binding:** `sections/ch0_chelomey.md`; `nav/architecture.md` Optional Content Registry (phone-booth row)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** Location description quoted verbatim from architecture.md Optional Content Registry. Hidden flag confirms non-obvious trigger. High-priority early-game flag: any player who cares about completeness should interact with this during Prologue before advancing.

### Explorer

- **id:** explorer
- **hidden:** no
- **trigger_type:** discovery
- **trigger:** Find and enter any Testing Ground for the first time
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** none (TG1 is the most accessible first TG)
- **vector-binding:** `optional_zones/polygons.md`; `nav/architecture.md` edge E16 (TG1 -- earliest accessible)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Below Zero

- **id:** below-zero
- **hidden:** no
- **trigger_type:** discovery
- **trigger:** Apply Frostbite to a Vova robot while the Vova is airborne (during its jump/lunge arc)
- **missable:** no
- **ponr-window:** n/a (Vova robots are common throughout the game)
- **prereqs:** Frostbite ability; Vova encounter
- **vector-binding:** `npcs/robots.md` Vova entry; `items/abilities.md` Frostbite section
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** Discovery: the airborne-freeze interaction is not signposted. Vova has a predictable jump pattern -- apply Frostbite during the jump arc. Non-obvious mechanic combination.

### Assimilation Procedure Interrupted

- **id:** assimilation-procedure-interrupted
- **hidden:** no
- **trigger_type:** discovery
- **trigger:** Kill a Sprout while it is actively reanimating a Mutant corpse (kill the Sprout before the transformation completes)
- **missable:** no
- **ponr-window:** n/a (Sprout + Mutant encounters in Algae Workshop, Pesticide Workshop, VDNH, Pavlov onward)
- **prereqs:** Sprout + Mutant corpse encounter; understanding that Sprouts reanimate corpses
- **vector-binding:** `npcs/mutants.md`; `npcs/robots.md` Mother/Sprout section; `dependencies.md` DEP-019
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none
- **notes:** Discovery: the Sprout-reanimation mechanic (DEP-019) is non-obvious on first encounter. Kill order rule: destroy Mothers first, then Sprouts -- but for this achievement, interrupt a Sprout mid-reanimate.

### Bull's Eye!

- **id:** bulls-eye
- **hidden:** no
- **trigger_type:** discovery
- **trigger:** Use Telekinesis to throw any object at a LUC-1 Owl drone and knock it down
- **missable:** no
- **ponr-window:** n/a (LUC-1 Owls appear throughout the game)
- **prereqs:** Telekinesis ability; throwable object + LUC-1 Owl in proximity
- **vector-binding:** `npcs/robots.md` LUC-1 Owl section; `items/abilities.md` Telekinesis
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** none

### Divide et Impera

- **id:** divide-et-impera
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Use a single Secateur shot to split apart a group of combined BEA-D units in the Annihilation Instinct DLC
- **missable:** no
- **ponr-window:** n/a (multiple combined-BEA-D encounters in Mendeleev Complex / Radiochemical Lab)
- **prereqs:** Secateur weapon; combined BEA-D encounter
- **vector-binding:** `nav/mendeleev_complex.md`; `items/weapons.md` Secateur entry
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct
- **notes:** Discovery: the fact that the Secateur can split combined BEA-Ds is not telegraphed in-game.

### John Silver's Crew

- **id:** john-silvers-crew
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Kill 3 M4D-5 mannequin robots consecutively while each is performing its hopping-on-one-foot idle animation
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** M4D-5 encounter group (Annihilation Instinct DLC); patience for idle animation timing
- **vector-binding:** `nav/mendeleev_complex.md`; `npcs/robots.md` M4D-5 section (if present)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Annihilation Instinct
- **notes:** Discovery: requires observing the M4D-5 idle animation state and timing kills during it.

### Overkill

- **id:** overkill
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Collect the secret 77th gold coin in the Trapped in Limbo DLC (one coin beyond the 76 required for Gold Rush, hidden in the DLC world)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Gold Rush completed (or in progress); knowledge of 77th coin location
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Trapped in Limbo

### Moby Dick

- **id:** moby-dick
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Hear the beautiful song while taking in the fantastic view -- find a specific Chirper at a scenic window location in the Enchantment Under the Sea DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Enchantment Under the Sea DLC; reach the Chirper's location
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Enchantment Under the Sea
- **notes:** Re-attributed from Trapped in Limbo to Enchantment Under the Sea per TrueAchievements DLC page cross-check (2026-05-22). Steam description: "Hear the beautiful song while taking in the fantastic view." Visible on VGTimes PS5 trophy page for EutS DLC.
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Enchantment Under the Sea_

### Water Sports

- **id:** water-sports
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Toss a ball back and forth with a dolphin NPC three times in the Enchantment Under the Sea DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Enchantment Under the Sea DLC; reach the dolphin's location
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Enchantment Under the Sea

### You've Read the Manual!

- **id:** youve-read-the-manual
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Use the Whip weapon to pull yourself close to an enemy (grapple-pull mechanic in Enchantment Under the Sea DLC)
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Whip weapon (Enchantment Under the Sea DLC)
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Enchantment Under the Sea

### I'm here if you need to talk

- **id:** im-here-if-you-need-to-talk
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Speak to the NPC named Terentiy in the Enchantment Under the Sea DLC
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Enchantment Under the Sea DLC; reach Terentiy
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Enchantment Under the Sea

### Hic Sunt Dracones

- **id:** hic-sunt-dracones
- **hidden:** yes
- **trigger_type:** discovery
- **trigger:** Swim past the warning boundary of the underwater world in Enchantment Under the Sea DLC, deliberately ignoring the game's warning prompts
- **missable:** no
- **ponr-window:** n/a
- **prereqs:** Enchantment Under the Sea DLC
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Enchantment Under the Sea

### Demonstration of Violence

- **id:** demonstration-of-violence
- **hidden:** yes
- **trigger_type:** progression
- **trigger:** Destroy the Robogirl at the Destroyed Chelomey zone (EutS-E2 encounter -- story-required fight early in Enchantment Under the Sea)
- **missable:** no
- **ponr-window:** n/a (story-required fight on main path)
- **prereqs:** Enchantment Under the Sea DLC; reach `neptune_chelomey_ruins` (EutS-E2)
- **vector-binding:** `nav/enchantment_under_sea.md` EutS-E2; `nav/architecture.md` §DLC -- Enchantment Under the Sea
- **enemy-tier:** 1
- **puzzle-tier:** 0
- **spoiler:** dlc:enchantment-under-sea
- **notes:** DLC attribution CONFIRMED by deep research (doctor 2026-05-27). The Robogirl is the first boss encountered in EutS, fought at `neptune_chelomey_ruins`. Story-required; cannot be missed.
_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:enchantment-under-sea_

---

_DLC -- Blood on Crystal_

### Secret Meeting

- **id:** secret-meeting
- **hidden:** no
- **trigger_type:** discovery
- **trigger:** Open the secret room with observers during the Making Contact objective -- interact with the terminal then use the key from Door 3
- **missable:** yes
- **ponr-window:** Before Making Contact objective window closes in Blood on Crystal DLC
- **prereqs:** Blood on Crystal DLC; Making Contact objective active; terminal interaction then Door 3 key sequence
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

### Better Late Than Never

- **id:** better-late-than-never
- **hidden:** no
- **trigger_type:** discovery
- **trigger:** Find the dolphin figurine in the secret room behind a locked door after the art-gallery combat arena -- door code is hinted on PEAR terminals
- **missable:** yes
- **ponr-window:** Before the art-gallery area closes in Blood on Crystal DLC
- **prereqs:** Blood on Crystal DLC; reach art-gallery area; find PEAR terminal code hint; unlock the door
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

### Fluffy Easter Egg

- **id:** fluffy-easter-egg
- **hidden:** no
- **trigger_type:** discovery
- **trigger:** Find the secret room with the fluffball during the Life After Life mission -- follow the cookie/nut trail near Nastya's clone to an outhouse with an "X" pattern lock
- **missable:** yes
- **ponr-window:** Before Life After Life mission window closes in Blood on Crystal DLC
- **prereqs:** Blood on Crystal DLC; Life After Life mission active; follow the cookie/nut trail; solve "X" pattern lock on outhouse
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

### Marco... Polo!

- **id:** marco-polo
- **hidden:** no
- **trigger_type:** discovery
- **trigger:** Fall into the water at the Wave complex and get killed by Morays -- do this right after the Wave complex opening cutscene
- **missable:** yes
- **ponr-window:** Before Wave complex section closes in Blood on Crystal DLC; best done immediately after the opening cutscene of the Wave area
- **prereqs:** Blood on Crystal DLC; reach Wave complex
- **vector-binding:** `_overflow/` (deferred-to: DLC-research)
- **enemy-tier:** 0
- **puzzle-tier:** 0
- **spoiler:** dlc:Blood on Crystal
- **notes:** Death achievement. The Moray kill method and specific Wave complex location are the non-obvious components. Do it on first arrival at the Wave complex to avoid missing the window.
_source: deep-research 2026-05-22 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Blood on Crystal_

---

## Genre vocabulary

No corpus-specific genre values declared. `meta` used for "The Motherland Does Not Forget its Heroes" (all-achievements unlock).

## Sources

- https://steamcommunity.com/stats/1227700/achievements -- canonical Steam list; returned "No stats available" at time of fetch 2026-05-22
- https://vgtimes.com/games/atomic-heart/achievements-and-trophies/ -- primary mirror; pages 1-2 retrieved (69 achievements total; PS5 EutS trophy page used for Moby Dick + Master of Survival DLC attribution cross-check)
- https://daynglsgameguides.com/2023/02/23/atomic-heart-trophy-achievement-guide/ -- secondary; 42 base game confirmed
- https://gamingbolt.com/atomic-heart-guide-how-to-unlock-all-trophies-and-achievements -- tertiary; 42 base game confirmed
- Steam Community 100% guide by "Imagine" -- Blood on Crystal: all 13 achievement names, descriptions, missability (canonical English names from Steam stats page)
- Treyex Gaming launch guide -- Blood on Crystal cross-check on all 13
- GAMES.GG (2026-04-27) -- Blood on Crystal cross-check; Crystal Platinum completion rate (Xbox: ~19%, 108 of 6,763 trackers)
- iXBT.games (2026-04-16 launch day) -- Blood on Crystal Russian/English name mapping; DLC count and Gamerscore
- TrueAchievements DLC pages -- canonical pack counts (AI: 9, TiL: 10, EutS: 8, BoC: 13); total 82 / 2,480 GS
- Steam Hunters AppID 668580 -- total 82 achievements confirmed ("82 Achievements 12,245 Points")

## Coverage check (updated 2026-05-22 -- BoC gap fill + DLC cross-check corrections)

**Total Steam achievements: 82 confirmed** (Steam Hunters AppID 668580; TrueAchievements: "Full list of all 82 Atomic Heart achievements worth 2,480 gamerscore"; XboxAchievements.com independent confirmation).

**Canonical DLC breakdown:** Base 42 / Annihilation Instinct 9 / Trapped in Limbo 10 / Enchantment Under the Sea 8 / Blood on Crystal 13 = 82

| DLC scope | Canonical count | Corpus entries | Status |
|---|---|---|---|
| Base game | 42 | 42 | Resolved -- trigger, PoNR, vector-binding populated |
| Annihilation Instinct | 9 | 9 | Resolved -- corpus has AoI coverage from P3 (2026-05-09) |
| Trapped in Limbo | 10 | 10 | **Resolved** -- doctor 2026-06-05: all triggers confirmed by primary sources (TrueAchievements, GameFAQs, VGTimes). Count corrected from 11/12 to 10 (Moby Dick + Master of Survival re-attributed to EutS 2026-05-22). |
| Enchantment Under the Sea | 8 | 8 | **Resolved** -- doctor 2026-06-05: And now--CHAR-les attribution confirmed; Demonstration of Violence confirmed EutS-E2; all 8 triggers populated from primary sources. Count corrected from 6 to 8 (Moby Dick + Master of Survival re-attributed from TiL 2026-05-22). |
| Blood on Crystal | 13 | 13 | Resolved -- all 13 achievements populated from gap-fill research (2026-05-22). |

**Base game completeness:** All 42 base game achievements resolved. Four stitch-edge pre-classifications confirmed: DEP-012 (Scanner/Twins), DEP-013 (Strike/Hedgie), DEP-014 (Chop Chop Chop/Belyash), DEP-021 (Maximum Strength/Klusha-Secateur).

**DLC corrections (2026-05-22):** Moby Dick and Master of Survival re-attributed from Trapped in Limbo to Enchantment Under the Sea per TrueAchievements DLC page cross-check. TiL canonical count is 10 (was over-counted at 11/12); EutS canonical count is 8 (was under-counted at 6).

**Silent scaffolds:** 0. All DLC partial scaffolds are explicitly marked deferred-to: DLC-research.

---

## Known Bugs -- Platform-Specific Issues

### Steam Achievement Reset Bug (PC)

Community-confirmed bug: Steam achievements can silently reset to 0% progress when starting a new game. This does NOT affect save files -- only the Steam achievement tracking layer resets. Reported in r/atomicheart and confirmed by multiple players.

**Workaround:** SAM (Steam Achievement Manager) tool. Community consensus: using SAM to restore lost achievements is in a grey zone (not a cheat, no in-game advantage, just restoring lost progress that was already earned). The tool is widely cited as the recommended fix for this specific case. Player discretion applies.

**Note:** Does not affect game completion -- only affects Steam trophy/achievement display layer. If achievements reset after starting NG+, this bug is likely the cause.

_source: r/atomicheart (multiple threads, Steam discussion) · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

### BoC Windows Launch Bug (PC -- RESOLVED)

Blood on Crystal DLC had a Windows-specific launch bug at release that prevented startup. **Patched and resolved.** If guides or community posts reference this, the fix is already live -- update the game and launch normally.

_source: r/atomicheart/comments/1suhzwz and related threads · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood_on_crystal_
