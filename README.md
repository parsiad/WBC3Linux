# WBC3Linux

WBC3Linux is a native x86_64 Linux port of Warlords Battlecry III based on the 1.03.23 source code.

To play, you need a legally obtained copy of the game and must point the app at that installation on first run.

WBC3Linux is released as a Flatpak containing a stripped binary.
The port source code is derived from the original confidential source code and hence cannot be released publicly.

![](https://raw.githubusercontent.com/parsiad/WBC3Linux/refs/heads/main/screenshot.png)

## Install

If you do not already have Flatpak installed, follow the [official Flatpak setup instructions](https://flatpak.org/setup/) for your distribution first.

```bash
curl --fail --location --remote-name \
	https://github.com/parsiad/WBC3Linux/raw/refs/heads/main/io.github.parsiad.WBC3Linux.flatpak && \
	flatpak install --user ./io.github.parsiad.WBC3Linux.flatpak
```

## Run

If your desktop environment has an application launcher, Warlords Battlecry III should be accessible from there after the install.
Otherwise, run:

```bash
flatpak run io.github.parsiad.WBC3Linux
```

On first launch, choose the directory containing the original Warlords Battlecry III data files when prompted.

## Disclaimer

WBC3Linux is distributed for end-user play only.
It does not grant permission to redistribute, decompile, modify, or create derivative works from the original or ported game code.

