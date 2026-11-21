# Anime Pixel Arena: assets

Extracted, ready-to-use fan sprite data for [anime-pixel-arena](https://github.com/adelro-git/anime-pixel-arena), so work sessions don't have to re-download multi-GB packs. Fan-made MUGEN characters, unmodified, credited to their creators below. Not affiliated with any rights holder; characters belong to their respective owners.

## Layout

- `mugen/chars/<Character>/`: the character's MUGEN folder as shipped (`.def`, `.sff` sprites, `.air` animations, `.act` palettes, `.cns`/`.cmd` logic, `.snd` sounds). Read it with `prototypes/sprite-extract/sff.py` in the main repo.
- `CREDITS.md`: who made each character and where it came from.

## Adding a character

Copy the folder unchanged into `mugen/chars/`, drop `Thumbs.db`, and add a row to `CREDITS.md` with the `.def` author line, any credit text file in the folder, and the source pack and URL.
