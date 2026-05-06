# Nuclear Option — 繁體中文翻譯模組 (Localization Patch)

Nuclear Option 繁體中文翻譯模組。以 BepInEx 外掛形式運作，翻譯介面、HUD、MFD、任務、情境、載具與武器等共 **2,841 條目**。

## 系統需求

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Early Access 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## 安裝方法

1. 將 **BepInEx 5.x** 安裝到遊戲資料夾。
   ```
   範例：C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. 啟動遊戲**一次**後關閉。(這會建立 BepInEx 資料夾結構)

3. 將本資料夾的所有檔案複製到下列路徑:
   ```
   [遊戲資料夾]\BepInEx\plugins\LocalizationPatch\
   ```
   > 若 `LocalizationPatch` 資料夾不存在，請手動建立。

4. 編輯 `BepInEx\config\com.noms.localizationpatch.cfg`,設定:
   ```
   [General]
   Language = zh_tw
   ```

5. 啟動遊戲，繁體中文翻譯會自動套用。

### 一鍵安裝程式 (替代方案)

https://github.com/9138noms/NuclearOption-LocalizationInstaller/releases/latest

## 內含檔案

| 檔案 | 用途 |
|------|------|
| `LocalizationPatch.dll` | 翻譯外掛 |
| `LocalizationPatchDropdown.dll` | 下拉選單外掛 |
| `zh_tw.json` | 繁體中文翻譯資料 (2,841 條目) |
| `NotoSansTC-VariableFont_wght.ttf` | 繁體中文顯示字型 |

## 遊戲內快速鍵

| 按鍵 | 功能 |
|------|------|
| `F10` | 切換除錯面板顯示 |
| `Ctrl+F10` | 重新載入翻譯資料 (熱重載) |

## 注意事項

- 陣營名稱 (PALA、BDF、BOSCALI、PRIMEVA、FFL、LMA) 與載具 / 武器代號 (Compass、Alkyon AB-4、FGA-57 Anvil、IRM-S2 等) 保持原文。
- 若出現問題，可在 `BepInEx\config\com.noms.localizationpatch.cfg` 中手動設定 `Language = zh_tw`。

## 翻譯貢獻者

- 翻譯：**4096** (社群貢獻)
- 外掛 / 框架：https://github.com/9138noms/NuclearOption-TranslationToolkit

## 字型授權

Noto Sans TC — [SIL Open Font License 1.1](https://github.com/notofonts/noto-cjk/blob/main/Sans/LICENSE)
資料來源：https://fonts.google.com/noto/specimen/Noto+Sans+TC

## 相關專案

🇰🇷 [Korean](https://github.com/9138noms/NuclearOption-KoreanPatch) ·
🇷🇺 [Russian](https://github.com/9138noms/NuclearOption-RussianPatch) ·
🇺🇦 [Ukrainian](https://github.com/9138noms/NuclearOption-UkrainianPatch) ·
🇧🇾 [Belarusian](https://github.com/9138noms/NuclearOption-BelarusianPatch) ·
🇩🇪 [German](https://github.com/9138noms/NuclearOption-GermanPatch) ·
🇪🇸 [Spanish](https://github.com/9138noms/NuclearOption-SpanishPatch) ·
🇫🇷 [French](https://github.com/9138noms/NuclearOption-FrenchPatch) ·
🇧🇷 [Portuguese](https://github.com/9138noms/NuclearOption-PortuguesePatch) ·
🇳🇴 [Norwegian](https://github.com/9138noms/NuclearOption-NorwegianPatch)

翻譯工具包 (製作您自己的語言補丁):
https://github.com/9138noms/NuclearOption-TranslationToolkit
