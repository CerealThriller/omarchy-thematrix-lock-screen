# TheMatrix Live Lock Screen for Omarchy

A live, animated lock screen design for the
[Lock Screen Explorer](https://github.com/SirJul1337/omarchy-lock-explorer)
plugin: real falling code behind a retro CRT terminal card (boot text,
blinking cursor, your username, password field), all colored from your
current theme's palette automatically.

Made as a companion to the
[TheMatrix Omarchy theme](https://github.com/CerealThriller/omarchy-the-matrix-theme),
but it works with any theme.

## Installation

Requires the Lock Screen Explorer plugin.

```bash
mkdir -p ~/.config/omarchy/lock-designs
curl -o ~/.config/omarchy/lock-designs/TheMatrixTerminal.qml \
  https://raw.githubusercontent.com/CerealThriller/omarchy-thematrix-lock-screen/main/TheMatrixTerminal.qml
omarchy-shell lock rescanDesigns
omarchy-shell lock setDesign my-thematrixterminal
```

## Credits

The falling-code canvas is adapted from the "Rain" design built into
[Lock Screen Explorer](https://github.com/SirJul1337/omarchy-lock-explorer)
by SirJul1337 (MIT licensed). The CRT terminal card built on top of it is
original.

## License

MIT
