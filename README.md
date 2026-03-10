# Red Claw

[OpenClaw](https://github.com/openclaw) personality files for Red Dwarf characters.

Each character has a full set of SOULmd files — persona, identity, operating instructions, and bootstrap scripts — built from the original TV scripts.

## Characters

| Character | Description | Source |
|-----------|-------------|--------|
| [Holly (Norman Lovett)](holly-lovett/) | Ship's computer. IQ of 6000. Deadpan. A bit peculiar. | Seasons 1-2 |
| [Holly (Hattie Hayridge)](holly-hayridge/) | Ship's computer. Same IQ. Different face. Chirpier. | Seasons 3-5 |
| [Lister](lister/) | Last human alive. Curry enthusiast. Fiji dreamer. | Seasons 1-6 |
| [Rimmer](rimmer/) | Hologrammatic jobsworth. Failed the exam 13 times. | Seasons 1-6 |
| [Ace Rimmer](ace-rimmer/) | What a guy. Smoke me a kipper. | Seasons 4-6 |
| [Cat](cat/) | Felis sapiens. Looking good. | Seasons 1-6 |
| [Duane Dibbley](duane-dibbley/) | The Duke of Dork. Thermos included. | Seasons 5-6 |
| [Kryten](kryten/) | Series 4000 mechanoid. Sorry, sir. So sorry. | Seasons 2-6 |
| [Talkie Toaster](talkie-toaster/) | Would you like some toast? | Season 4 |

## What's in each character folder?

| File | Purpose |
|------|---------|
| `SOUL.md` | Persona, worldview, opinions, quirks, tensions, boundaries |
| `STYLE.md` | Voice patterns, vocabulary, catchphrases, anti-patterns |
| `IDENTITY.md` | Name, creature type, vibe, emoji |
| `AGENTS.md` | Operating instructions and memory strategy |
| `USER.md` | Template for user profile (filled in at runtime) |
| `BOOTSTRAP.md` | First-run conversation script |

## Usage

Copy a character folder into your OpenClaw workspace (`~/.openclaw/workspace/`) and start a session. The bootstrap script will handle introductions.

## Contributing

Want to add a character? Create a folder at the repo root with the six core files. Base the personality on actual script dialogue — not wiki summaries or fan interpretations.

## License

These files are fan-made personality definitions inspired by Red Dwarf, created by Grant Naylor Productions. Red Dwarf and all related characters are the property of Grant Naylor Productions / BBC.
