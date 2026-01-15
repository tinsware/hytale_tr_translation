# Turkish Character Conversion Notice

## Overview
Due to display compatibility issues with Turkish characters in Hytale, all Turkish special characters have been temporarily converted to their ASCII equivalents.

## Character Mapping
The following Turkish characters were replaced:

| Original | Replacement | Unicode |
|----------|-------------|---------|
| Ş        | S          | U+015E |
| ş        | s          | U+015F |
| İ        | I          | U+0130 |
| ı        | i          | U+0131 |
| Ğ        | G          | U+011E |
| ğ        | g          | U+011F |
| Ü        | U          | U+00DC |
| ü        | u          | U+00FC |
| Ö        | O          | U+00D6 |
| ö        | o          | U+00F6 |
| Ç        | C          | U+00C7 |
| ç        | c          | U+00E7 |

## Impact
- **Total replacements**: 1,570 instances in client.lang
- **Languages affected**: Turkish (tr-TR)
- **Files modified**: `client.lang` (server.lang pending)

## Future Plans
This is a temporary solution until properly supports Unicode Turkish characters. Once the game engine is updated to handle UTF-8 Turkish characters correctly, the translations will be reverted to their proper Turkish form.

## Examples
- "Birinci Şahıs" → "Birinci Sahis" (First Person)
- "Çoğalt" → "Cogalt" (Duplicate)
- "Değişiklikleri At" → "Degisiklikleri At" (Discard Changes)

## Technical Notes
- Font support: Noto fonts include all Turkish characters
- File encoding: UTF-8
- Issue: Game rendering limitation, not font or file encoding problem