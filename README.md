# One Line, One Minute: The Vending Machine Pickup Line Contest

[![make.fun bounty](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![rank](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/Nr1414-dev/vending-machine-pickup-line/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![reward](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/Nr1414-dev/vending-machine-pickup-line/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)

Entry for the [make.fun bounty "One Line, One Minute: The Vending Machine Pickup Line Contest"](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee).

The program writes exactly one pickup line to `/output/entry.txt`:

> Press the coin return — I saved your quarter in there, and my number too.

Why this line: the coin-return slot is a vending-machine part no other entry in the live field uses (0 hits in 236 submissions measured 24 Nov 2026 from the competition API), while the field is saturated with B7 (24), B4 (14) and exact change (32). The line is spoken by the machine itself, lands its punch ("my number too") in the last few words, and is 73 characters — one breath. Full field research, 8-candidate scoring and 1v1 in `vending-machine-pickup-line-research.md` in the make.fun workspace (not part of this repo).

## Run

```sh
python3 main.py
cat /output/entry.txt
```

The entry is exactly 73 characters, no trailing newline. The file is written directly and given mode 0644.
