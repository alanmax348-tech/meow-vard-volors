# meow-vard-volors

Card text colors for the MazenFCM Cards Bot (FC Mobile `/ocard`).

`card_text_colors.json` maps each card-background stem to the exact
in-game text colors (`ovr`, `position`, `name`) as hex strings, e.g.

```json
{"27_RIVALS27_ENGLAND_ICON": {"ovr": "#0D1B55", "position": "#0D1B55", "name": "#0D1B55"}}
```

Updated weekly by an automated job: new designs get their colors from
RenderZ (the bot's host cannot reach RenderZ, so this file is the
bridge). The bot fetches this file from the raw URL at runtime -- no
file upload needed.

Source of colors: RenderZ player-info `animation.colors`.
