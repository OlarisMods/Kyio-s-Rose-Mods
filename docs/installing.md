# Installing, uninstalling, and what is in these packs

## Installing

1. Close ROSE completely.
2. Copy the folders from the zip into your ROSE Online install folder, letting them merge.
   Usually `C:\Program Files\ROSE Online`.
3. Start the game.

Windows will ask you to confirm replacing files — that's expected, and you may get an
administrator prompt.

Only one UI theme at a time, and one color per drop group at a time. To switch, install
another straight over the top. Every pack in a family ships an identical file list, so nothing
gets left behind.

Drop groups are independent of each other and of the UI themes — there is no wrong combination.

### Updating a UI theme from before 16 October 2026

Delete this one file from your ROSE folder before installing, if it is there:

    data\ui\themes\rose\styles\spritesheet_glassui.css

Every UI theme made before the 16 October 2026 patch shipped a copy of it. After the patch,
an old copy hides the game's new buttons: the group manager button becomes a **white square**,
and some icons go missing. No current pack ships it, so once it is gone it stays gone.
[ROSE UI Editor](https://github.com/OlarisMods/ROSE_UI_Editor) removes it for you.

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

- **There is no installer and no executable.** Every pack contains only `.dds`
  textures, `.zms` mesh geometry, `.zmo` motion data, `.ptl` particle
  definitions, `.eft` effect definitions, `.cur` cursors, a `.pal` colour
  palette and an `.ico` window icon, `.css` and `.html` (plain text you can open and
  read), a `manifest.json`, and `.txt` readmes. No `.exe`, no `.dll`, no
  scripts. Nothing in these archives can run.
- **Everything is browsable right here.** [packs/CONTENTS.md](../packs/CONTENTS.md)
  lists every file in all 126 packs, generated straight from the archives
  themselves. You can look before you download.
- **SHA-256 checksums** for every zip are in [CHECKSUMS.txt](../CHECKSUMS.txt), with instructions
  for verifying them.
- **Uninstall is deleting files.** No uninstaller to trust, no registry, no leftovers.
- **Client-side only.** Nothing communicates with anything. No server-side component exists.

---

## Known limits

Fonts and character-sheet stat numbers are engine-side and can't be changed by a mod. They
stay stock in every theme. (Nameplate health bars could not be changed either until the
16 October 2026 patch; they now follow the bar colours of whichever theme you use.)

## Notes

Some windows cache their artwork. If part of the interface still looks unchanged after
installing, close and reopen that window, or restart the client.

## Terms

Free to use. Please don't sell it or repackage it as your own. Credit is appreciated but not
required.

These are recolors of ROSE Online's own artwork, plus original work by me. All rights in the
underlying game assets belong to their owners; this is a fan modification, offered in the hope
it's useful and with no claim over anything that isn't mine.
