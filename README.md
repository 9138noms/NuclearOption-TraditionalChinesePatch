# Nuclear Option — Traditional Chinese Localization Patch

Nuclear Option 繁體中文翻譯模組（BepInEx 外掛）。
Nuclear Option Traditional Chinese translation (BepInEx mod).

- **2,841 translated entries** covering UI, HUD, MFD, missions, scenarios, vehicles, weapons.
- Translation contributed by **4096** (community contributor).

## Requirements

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Early Access 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Installation

1. Install **BepInEx 5.x** into the game folder.
   ```
   e.g. C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```
2. Launch the game once, then quit. (BepInEx folder structure will be created.)
3. Copy all the files from this repo into:
   ```
   [Game Folder]\BepInEx\plugins\LocalizationPatch\
   ```
   (Create the `LocalizationPatch` folder if it doesn't exist.)
4. Set the language. Edit `BepInEx\config\com.noms.localizationpatch.cfg`:
   ```
   [General]
   Language = zh_tw
   ```
5. Launch the game — Traditional Chinese is applied automatically.

## Files

| File | Purpose |
|------|---------|
| `LocalizationPatch.dll` | The translation plugin |
| `LocalizationPatchDropdown.dll` | Dropdown / editor addon |
| `zh_tw.json` | Translation data (2,841 entries) |
| `NotoSansTC-VariableFont_wght.ttf` | Noto Sans TC font for Traditional Chinese rendering |

## Hotkeys

| Key | Action |
|-----|--------|
| `F10` | Toggle debug overlay |
| `Ctrl+F10` | Reload translation data (hot reload) |

## Notes

- Faction names (`PALA`, `BDF`, `BOSCALI`, `PRIMEVA`, `FFL`, `LMA`) and weapon / aircraft codenames (`Compass`, `Alkyon AB-4`, `FGA-57 Anvil`, `IRM-S2`, `LCV25`, `M12 Jackknife`, `NL-98`, `Eyeball Mk.II`, `GBM-500LR`, `GS25`, `GPO-N`, etc.) are kept in their original form.
- If anything looks broken, set `Language = zh_tw` manually in `BepInEx\config\com.noms.localizationpatch.cfg`.

## Credits

- Translation: **4096** (community contributor)
- Plugin: based on the shared [Nuclear Option Localization framework](https://github.com/9138noms/NuclearOption-TranslationToolkit)

## Font License

Noto Sans TC — [SIL Open Font License 1.1](https://github.com/notofonts/noto-cjk/blob/main/Sans/LICENSE)
Source: https://fonts.google.com/noto/specimen/Noto+Sans+TC

## Related projects

🇰🇷 [Korean](https://github.com/9138noms/NuclearOption-KoreanPatch) ·
🇷🇺 [Russian](https://github.com/9138noms/NuclearOption-RussianPatch) ·
🇺🇦 [Ukrainian](https://github.com/9138noms/NuclearOption-UkrainianPatch) ·
🇧🇾 [Belarusian](https://github.com/9138noms/NuclearOption-BelarusianPatch) ·
🇩🇪 [German](https://github.com/9138noms/NuclearOption-GermanPatch) ·
🇪🇸 [Spanish](https://github.com/9138noms/NuclearOption-SpanishPatch) ·
🇫🇷 [French](https://github.com/9138noms/NuclearOption-FrenchPatch) ·
🇧🇷 [Portuguese](https://github.com/9138noms/NuclearOption-PortuguesePatch) ·
🇳🇴 [Norwegian](https://github.com/9138noms/NuclearOption-NorwegianPatch)

Translation toolkit for making your own language patch:
https://github.com/9138noms/NuclearOption-TranslationToolkit
