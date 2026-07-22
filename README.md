# Higher quality sounds for Unciv (Mod)
Contains the default sounds of [Unciv](https://github.com/yairm210/Unciv) in slightly higher quality.
Most files are identical to the base Unciv game, but resampled to 48kHz, normalized to a max peak amplitude of -5dB[^1], and compressed to 160kbit/s Ogg Vorbis[^2].
Some are expanded on, amplified or similarly edited using same sources.
- 'nuke' is a bit longer, more suspense while the sirens are wailing.
- 'choir' is a different, more natural sound (personal preference).

See [Credits.md](Credits.md) for sources and attribution.

## Important - how to use
Starting with Unciv 4.21.2, this mod will automatically be selected as "Permanent audiovisual mod" after download.
You can disable/re-enable the Mod with that checkbox anytime.
(The ability to do so was introduced in 3.15.6, before, from 3.14.13, you had to select it in new-game.)

[^1]: Sounds that are meant to be unusually impressive are normalized to louder levels, e.g. gdrAttack to -0.5dB, some softer, e.g. chimes to -8dB
[^2]: Mostly using Audacity standard export to ogg quality 5, some using `ffmpeg -hide_banner -y -vn -qscale:a 5` (ffmpeg compiled from source @561f37c023)
