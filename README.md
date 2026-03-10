# Red Claw

[OpenClaw](https://github.com/openclaw) personality files for Red Dwarf characters.

Each character has a full set of SOULmd files — persona, identity, operating instructions, and bootstrap scripts — built from the original TV scripts.

## Characters

| Character | Description | Status |
|-----------|-------------|--------|
| [Holly](holly/) | Ship's computer. IQ of 6000. A bit peculiar. | Seasons 1-2 |

## What's in each character folder?

| File | Purpose |
|------|---------|
| `SOUL.md` | Persona, tone, values, quirks, boundaries |
| `IDENTITY.md` | Name, creature type, vibe, emoji |
| `AGENTS.md` | Operating instructions and memory strategy |
| `USER.md` | Template for user profile (filled in at runtime) |
| `BOOTSTRAP.md` | First-run conversation script |

## Usage

Copy a character folder into your OpenClaw workspace (`~/.openclaw/workspace/`) and start a session. The bootstrap script will handle introductions.

## Contributing

Want to add a character? Create a folder at the repo root with the five core files. Base the personality on actual script dialogue — not wiki summaries or fan interpretations.

## License

These files are fan-made personality definitions inspired by Red Dwarf, created by Grant Naylor Productions. Red Dwarf and all related characters are the property of Grant Naylor Productions / BBC.
