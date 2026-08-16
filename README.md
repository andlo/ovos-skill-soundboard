# SoundBoard

A sound-effects board for OVOS - 'play a drum roll', 'play applause', 'play an air horn'. Same bundled-CC0-sample pattern as ovos-skill-sound-like, but for stock sound effects rather than animal/object sounds. Could plausibly share infrastructure with ovos-skill-sound-like rather than being fully separate - worth revisiting once both exist.

> **This is a skeleton only - not implemented yet.** Repo, structure,
> and design notes are in place; the actual skill logic hasn't been
> written. See "Design notes" in [DEVELOPMENT.md](DEVELOPMENT.md).

## Why this exists

Nothing like this exists in the OVOS ecosystem yet, though ovos-skill-laugh is a narrow precedent (one sound, evil laugh). Architecturally close enough to ovos-skill-sound-like that it may be worth merging the two rather than building this as fully separate - a design question for before real implementation starts.

## Planned usage (not yet functional)
```
"play a drum roll"
"play applause"
"play an air horn"
```

## Install

Not yet published to PyPI.

## Development

See [DEVELOPMENT.md](DEVELOPMENT.md).

## Category
**Entertainment**

## Tags
#sound-effects #fun #soundboard
