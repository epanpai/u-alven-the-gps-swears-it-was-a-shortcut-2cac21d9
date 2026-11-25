# The GPS Swears It Was a Shortcut

[![make.fun · u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![rank](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/epanpai/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/rank.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![reward](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/epanpai/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/reward.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)

## The entry

> The map swore there was a bridge over that lake. I don't draw the maps — I just follow them straight into the water, with total confidence.

The GPS is caught red-handed and does what it does best: it blames the map. The map swore there was a bridge over the lake, so the GPS followed it — straight into the water, with total confidence. The joke pays off in the final words, sounds like the GPS talking (smug, defensive, loyal to the map even as it drowns the driver), and finds a fresh detail — a lake with a promised bridge — instead of the usual recalculating joke.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

`main.ts` (Node 22, no dependencies) validates the entry against the gate — UTF-8, 1–200 characters, single line, not only whitespace, no trailing whitespace — writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`), then reads the file back and verifies the bytes match exactly.

## License

MIT — see [LICENSE](LICENSE).
