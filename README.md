# ROSE Online — Cosmetic Mods

Client-side cosmetic mods for ROSE Online. Interface recolours, combat text, loot beams, and
an expanded Friends window. **Nothing here touches the server, your account, or any game
logic.**

---

## UI Themes

Four complete interface recolours — window frames, buttons, tabs, chat box, minimap ring,
cursors, gauges, and combat text.

| Theme | Look |
|---|---|
| **Void** | purple and violet chrome, magenta clan accent — the original |
| **Crimson** | near-black glass, deep blood-red glow, bone-white rim, amber alerts |
| **Moldie** | royal blue chrome, hat-gold highlights |
| **Ancient** | slate verdigris chrome, copper highlights, clay and steel gauges |

![UI themes in game](images/ui_themes_window.png)

<details><summary>Component breakdown, and all four in game</summary>

![UI components](images/ui_themes_all.png)

![All four in game](images/ui_themes_ingame.png)

</details>

**Download:**
[Void](../../releases/latest/download/ROSE_UI_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_UI_Crimson.zip) ·
[Moldie](../../releases/latest/download/ROSE_UI_Moldie.zip) ·
[Ancient](../../releases/latest/download/ROSE_UI_Ancient.zip)

Potion colours are **not** included in the theme packs — they're separate below, so you can
mix and match rather than having a colour forced on you.

---

## Combat Text (standalone)

Just the floating combat numbers, for anyone who wants a clearer damage readout without
changing their whole interface. 13 files.

![Combat text in a real fight](images/combat_text_ingame.png)

![Combat text, every damage type](images/combat_text_all_themes.png)

**Download:**
[Void](../../releases/latest/download/ROSE_CombatText_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_CombatText_Crimson.zip) ·
[Moldie](../../releases/latest/download/ROSE_CombatText_Moldie.zip) ·
[Ancient](../../releases/latest/download/ROSE_CombatText_Ancient.zip)

Damage types are told apart by colour, so each one is assigned rather than everything being
tinted the same way:

- **damage you deal** — the theme's colour
- **damage you take** — red
- **healing** — green
- **critical hits** — matches the theme's glow
- **blocked / absorbed** — muted variants
- **miss** — neutral grey

In **Crimson, Moldie and Ancient**, damage taken and healing are **identical** — they never
change between themes, so you don't have to relearn your own combat log when you switch.

**Void is the exception.** It was made before I settled on that rule, so its whole set sits in
the violet/magenta family — healing reads blue, received damage reads magenta. It suits the
Void interface, but if you want the clearest readout, one of the other three is the better
pick.

*Already running a full UI theme? You don't need this — the combat text is included in it.*

---

## Potion Beams

Recolours of the potion flask and the light beam it casts. Two files each — the recoloured
texture, and the beam mesh, which is my own work built from scratch. Works with any UI theme,
or with none.

This was the first one. The other drop groups are under [Loot Beams](#loot-beams) below, and
they all share the same beam.

![Potion beams in game](images/potion_beams_ingame.png)

<details><summary>The flask and beam artwork on its own</summary>

![Potion sprites](images/potion_beams_all.png)

</details>

**Download:**
[Void](../../releases/latest/download/ROSE_Potion_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_Potion_Crimson.zip) ·
[Moldie](../../releases/latest/download/ROSE_Potion_Moldie.zip) ·
[Verdigris](../../releases/latest/download/ROSE_Potion_Verdigris.zip) ·
[Lime](../../releases/latest/download/ROSE_Potion_Lime.zip) ·
[Chem](../../releases/latest/download/ROSE_Potion_Chem.zip)

---

## Loot Beams

A tall beam of light over the drops worth stopping for, plus a new model for the drop
itself so you can tell at a glance *what* you're looking at, not just that something's there.

Six drop groups, six colours each. Every category is independent — mix and match freely.
Install one colour per category.

![All six beam categories in game](images/beams_group.png)

Two files per pack: the texture, and the mesh. The mesh is my own work, built from scratch,
and the beam will not render without it — install both. The beam itself is pixel-identical
across every category and colour, so the whole set reads as one thing.

### Want everything one colour?

One download instead of six. Each bundle is every drop group in that colour — the same files
as the individual packs, just in one archive.

[**Void**](../../releases/latest/download/ROSE_AllBeams_Void.zip) ·
[**Crimson**](../../releases/latest/download/ROSE_AllBeams_Crimson.zip) ·
[**Verdigris**](../../releases/latest/download/ROSE_AllBeams_Verdigris.zip) ·
[**Moldie**](../../releases/latest/download/ROSE_AllBeams_Moldie.zip) ·
[**Lime**](../../releases/latest/download/ROSE_AllBeams_Lime.zip)

Prefer to mix — teal crystals but red ore? Use the individual packs below. Chem, Rune, Quartz,
Copper, Prism and Parchment each echo one drop's own original artwork, so they're single packs
only and aren't in any bundle.

### Zodiac & Rune Stone

A carved standing stone with a glowing rune on both faces.
*Dirty Zodiac Stone · Dirty Rune Stone*

| Void | Crimson | Verdigris | Moldie | Lime | Rune |
|---|---|---|---|---|---|
| ![](images/di22_void.png) | ![](images/di22_crimson.png) | ![](images/di22_verdigris.png) | ![](images/di22_moldie.png) | ![](images/di22_lime.png) | ![](images/di22_rune.png) |

[Void](../../releases/latest/download/ROSE_DI22_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_DI22_Crimson.zip) ·
[Verdigris](../../releases/latest/download/ROSE_DI22_Verdigris.zip) ·
[Moldie](../../releases/latest/download/ROSE_DI22_Moldie.zip) ·
[Lime](../../releases/latest/download/ROSE_DI22_Lime.zip) ·
[Rune](../../releases/latest/download/ROSE_DI22_Rune.zip)

### Dirty Crystal

A cluster of cut crystal shards, with the beam rising from the middle of them.
*Dirty Crystal*

| Void | Crimson | Verdigris | Moldie | Lime | Quartz |
|---|---|---|---|---|---|
| ![](images/di23_void.png) | ![](images/di23_crimson.png) | ![](images/di23_verdigris.png) | ![](images/di23_moldie.png) | ![](images/di23_lime.png) | ![](images/di23_quartz.png) |

[Void](../../releases/latest/download/ROSE_DI23_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_DI23_Crimson.zip) ·
[Verdigris](../../releases/latest/download/ROSE_DI23_Verdigris.zip) ·
[Moldie](../../releases/latest/download/ROSE_DI23_Moldie.zip) ·
[Lime](../../releases/latest/download/ROSE_DI23_Lime.zip) ·
[Quartz](../../releases/latest/download/ROSE_DI23_Quartz.zip)

### Dirty Ore & Dirty Stone

Broken rock veined with glowing ore.
*Dirty Ore · Dirty Stone*

| Void | Crimson | Verdigris | Moldie | Lime | Copper |
|---|---|---|---|---|---|
| ![](images/di55_void.png) | ![](images/di55_crimson.png) | ![](images/di55_verdigris.png) | ![](images/di55_moldie.png) | ![](images/di55_lime.png) | ![](images/di55_copper.png) |

[Void](../../releases/latest/download/ROSE_DI55_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_DI55_Crimson.zip) ·
[Verdigris](../../releases/latest/download/ROSE_DI55_Verdigris.zip) ·
[Moldie](../../releases/latest/download/ROSE_DI55_Moldie.zip) ·
[Lime](../../releases/latest/download/ROSE_DI55_Lime.zip) ·
[Copper](../../releases/latest/download/ROSE_DI55_Copper.zip)

### Spiritual & Heart Stone

A faceted gemstone heart on a small pedestal. The **Prism** version keeps the rainbow of
the original artwork — every facet a different hue, and the beam sweeps through the
spectrum as it rises.
*Dirty Spiritual Stone · Dirty Heart Stone*

| Void | Crimson | Verdigris | Moldie | Lime | Prism |
|---|---|---|---|---|---|
| ![](images/di10_void.png) | ![](images/di10_crimson.png) | ![](images/di10_verdigris.png) | ![](images/di10_moldie.png) | ![](images/di10_lime.png) | ![](images/di10_prism.png) |

[Void](../../releases/latest/download/ROSE_DI10_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_DI10_Crimson.zip) ·
[Verdigris](../../releases/latest/download/ROSE_DI10_Verdigris.zip) ·
[Moldie](../../releases/latest/download/ROSE_DI10_Moldie.zip) ·
[Lime](../../releases/latest/download/ROSE_DI10_Lime.zip) ·
[Prism](../../releases/latest/download/ROSE_DI10_Prism.zip)

### Scrolls & Event Drops

A bound roll of parchment. The paper takes the colour lightly, the cord takes it fully.
*Scrolls, dances, and event items — including this event's School Spirit.*

| Void | Crimson | Verdigris | Moldie | Lime | Parchment |
|---|---|---|---|---|---|
| ![](images/di50_void.png) | ![](images/di50_crimson.png) | ![](images/di50_verdigris.png) | ![](images/di50_moldie.png) | ![](images/di50_lime.png) | ![](images/di50_parchment.png) |

[Void](../../releases/latest/download/ROSE_DI50_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_DI50_Crimson.zip) ·
[Verdigris](../../releases/latest/download/ROSE_DI50_Verdigris.zip) ·
[Moldie](../../releases/latest/download/ROSE_DI50_Moldie.zip) ·
[Lime](../../releases/latest/download/ROSE_DI50_Lime.zip) ·
[Parchment](../../releases/latest/download/ROSE_DI50_Parchment.zip)

---

## Community Window

Your Friends window with three extra tabs. The friend and ignore lists are the game's own,
untouched — the rest is new.

| Notes | Checklist | Symbols |
|---|---|---|
| ![](images/community_notes.png) | ![](images/community_checklist.png) | ![](images/community_symbols.png) |

- **Notes** — a notepad. Also shows your zone, coordinates and server time.
- **Checklist** — eight tick-boxes, each with a quantity and a label. Use it for whatever you
  like: a farming run, a crafting list, a set you're collecting.
- **Symbols** — emoji you can copy and paste into chat.

Notes and Checklist keep what you type for as long as the client is running. Close the window,
reopen it, and it's still there. **It is not saved to disk** — everything clears when you close
the game.

One plain text file. Open it in Notepad and read it if you like; there's nothing else in the pack.

**Download:** [Community Window](../../releases/latest/download/ROSE_UI_CommunityWindow.zip)


---

## Installing

1. Close ROSE completely.
2. Copy the folders from the zip into your ROSE Online install folder, letting them merge.
   Usually `C:\Program Files\ROSE Online`.
3. Start the game.

Windows will ask you to confirm replacing files — that's expected, and you may get an
administrator prompt.

Only one UI theme at a time, and one colour per drop group at a time. To switch, install
another straight over the top. Every pack in a family ships an identical file list, so nothing
gets left behind.

Drop groups are independent of each other and of the UI themes — there is no wrong combination.

## Uninstalling

**Delete the files you copied in.** That's the whole process.

ROSE loads loose files on disk in preference to its packed archives, so installing these does
not modify or replace any original game data — it sits on top of it, and removing it falls
straight back to stock. Every pack contains a `FILE_LIST.txt` naming every file it installs,
so you always know exactly what to remove.

The original artwork lives inside the game's own packed archives and is never modified, so
deleting the files is a complete return to stock.

---

## Is this safe?

Fair question to ask of any mod. Here's what's checkable rather than just claimed:

- **There is no installer and no executable.** Every pack contains only `.dds` textures,
  `.zms` mesh geometry, `.cur` cursors, `.css` and `.html` (plain text you can open and read),
  and `.txt` readmes. No `.exe`, no `.dll`, no scripts. Nothing in these archives can run.
- **Everything is browsable right here.** The `packs/` folder in this repository is the exact
  contents of every download, unpacked. You can look before you download.
- **SHA-256 checksums** for every zip are in [CHECKSUMS.txt](CHECKSUMS.txt), with instructions
  for verifying them.
- **Uninstall is deleting files.** No uninstaller to trust, no registry, no leftovers.
- **Client-side only.** Nothing communicates with anything. No server-side component exists.

---

## Terms

Free to use. Please don't sell it or repackage it as your own. Credit is appreciated but not
required.

These are recolours of ROSE Online's own artwork, plus original work by me. All rights in the
underlying game assets belong to their owners; this is a fan modification, offered in the hope
it's useful and with no claim over anything that isn't mine.

## Known limits

Fonts, particle effects, nameplate health bars, and character-sheet stat numbers are
engine-side and can't be changed by a mod. They stay stock in every theme.

## Notes

Some windows cache their artwork. If part of the interface still looks unchanged after
installing, close and reopen that window, or restart the client.
