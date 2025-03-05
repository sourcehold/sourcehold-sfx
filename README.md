# sourcehold-sfx
All about sound effects of Stronghold and Stronghold Crusader

## Playing .raw files
To play the raw PCM files from the game files, use `ffplay` and the following command:
```bash
ffplay -f s16le -ar 16k -ch_layout mono suspense1b.raw
```
