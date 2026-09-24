# Combat Text

Just the floating combat numbers, for anyone who wants a clearer damage readout without
changing their whole interface. 13 files.

![Combat text in a real fight](../images/combat_text_ingame.png)

![Combat text, every damage type](../images/combat_text_all_themes.png)

**Download:**
[Void](../../releases/latest/download/ROSE_CombatText_Void.zip) ·
[Crimson](../../releases/latest/download/ROSE_CombatText_Crimson.zip) ·
[Moldie](../../releases/latest/download/ROSE_CombatText_Moldie.zip) ·
[Ancient](../../releases/latest/download/ROSE_CombatText_Ancient.zip)

## Large

The same four themes with the numbers drawn as large as the game allows — about **36% taller**.

The original artwork leaves roughly a third of each number's space empty, so at any distance
you're reading smaller digits than you need to be. This fills that space. Same colors, same
behaviour, same everything else.

[Void](../../releases/latest/download/ROSE_CombatText_Void_Large.zip) ·
[Crimson](../../releases/latest/download/ROSE_CombatText_Crimson_Large.zip) ·
[Moldie](../../releases/latest/download/ROSE_CombatText_Moldie_Large.zip) ·
[Ancient](../../releases/latest/download/ROSE_CombatText_Ancient_Large.zip)

The size the game draws these at lives in the effect definition, which a mod can't reach — so
36% is the whole of what the artwork can give. The digits now stop one pixel short of their
neighbours; any larger and they'd run together.

## Which colour means what

Damage types are told apart by color, so each one is assigned rather than everything being
tinted the same way:

- **damage you deal** — the theme's color
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
