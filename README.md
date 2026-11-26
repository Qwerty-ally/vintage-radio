# Vintage Radio

A radio station for Finn Shapiro's Vintage album. Everyone who tunes in hears the same song at the same moment, like a real station. It loops the 12 songs in album order, all day.

- **The look** changes with every song: the dial glow, the "radio" title, the background and the listings take their colors from that song's cover. The colors are in `COLORS` in `index.html`.
- **Songs** are in `media/vintage/`, and covers are in `media/vintage/covers/` (from music-site). Left out on purpose: Tisket Tasket, So What and Not What I Want.
- **The switch:** at **12:00 PM Eastern on Sunday, Feb 28, 2027** (`SWITCH_AT`) the radio turns into **PK Radio** with a burst of static, in the Pretty Killer pink/black style, starting on track 1.
  - **Before then, copy the PK mp3s into `media/pk/`** (the file names are listed under `pk` in `STATIONS`, the same as in pk-rhythm/songs). They are left out for now so nobody can find them early.
- **Testing:** type `pk` anywhere to preview the PK side, `vintage` to go back, and `auto` to follow the date again.
- If you change a song file, update its `len` (its length in seconds) so everyone stays in sync.
