# Modding notes

Things worth knowing if you are editing these files yourself.

## The buff filenames do not match the buffs

They went from Korean into English through a dictionary, and a fair few landed on
the wrong word:

| Buff | The file that draws it |
|---|---|
| Attack power up | `attackup_01.ptl` |
| **Attack speed up** | **`defendup_01.ptl`** |
| Critical rate up | `criticalup_01.ptl` |
| Accuracy up | `hitup_01.ptl` |
| Dodge up | `shirkup_01.ptl` |
| Damage up | `damage_up01.ptl` |
| Move speed up | `smoke_07.ptl` |
| **Magic defence up** | **`_horsepower_02.ptl`** |
| Defence up | an effect *mesh*, not a particle file — `EffectMesh\defend_01\` |

Attack speed lives in a file called *defendup*. Magic defence lives in one
called *horsepower* — 마력 means both *magical power* and *horsepower*, and the
dictionary picked the wrong one.

So searching for the stat name will not find these. Search for what an effect
**draws** instead of what it is called.

And one of them is not a particle file at all: defence up is drawn by an effect
mesh with its own textures, which is why replacing a `.ptl` for it does nothing.
