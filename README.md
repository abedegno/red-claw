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

## Disclaimer

This is an unofficial fan project. It is not affiliated with, endorsed by, or connected to Grant Naylor Productions, BBC, or any of the creators, writers, or performers of Red Dwarf.

Red Dwarf and all related characters, names, and catchphrases are the intellectual property of Grant Naylor Productions / BBC. These files are fan-made personality definitions created for personal and non-commercial use.

No original scripts, episodes, or copyrighted content are distributed in this repository. If the rights holders have any concerns, please open an issue and we will respond promptly.
