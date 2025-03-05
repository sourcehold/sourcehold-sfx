# sourcehold-sfx
All about sound effects of Stronghold and Stronghold Crusader

## Playing .raw files
To play the raw PCM files from the game files, use `ffplay` and the following command (e.g. for file `suspense1b.raw`):
```bash
ffplay -f s16le -ar 16k -ch_layout mono -i suspense1b.raw
```

Use this command to convert it to a wav
```bash
ffmpeg -f s16le -ar 16k -ch_layout stereo -i suspense1b.raw suspense1b.wav
```
