# Noto Sans Full for Firestorm

This is a definition file that changes the Noto font of [Firestorm Viewer](https://www.firestormviewer.org/), a third-party viewer for SecondLife, from [Noto Sans CJK](https://github.com/notofonts/noto-cjk) etc., which contains kanji characters such as Japanese, to the font settings equivalent to [Alchemy Viewer](https://alchemyviewer.org/).

Before:
![Before](img/before.webp)

After:
![After](img/after.webp)

The current settings use the OS font, which causes the typeface and size to change depending on the environment, making it difficult to read. By using this patch, fonts for all languages ​​will be unified to the Noto font family.

## Install

Add the following files from this repository to your Firestorm `fonts` directory (`C:\Program Files\Firestorm-Releasex64\fonts` on Windows):

- fonts_noto_sans_full.xml
- NotoSans-Bold.otf
- NotoSans-BoldItalic.otf
- NotoSans-Italic.otf
- NotoSans-Regular.otf
- NotoSansCJK-Bold.ttc
- NotoSansCJK-Regular.ttc
- NotoSansDevanagariUI-Bold.otf
- NotoSansDevanagariUI-Regular.otf
- NotoSansEgyptianHieroglyphs-Regular.otf
- NotoSansKannadaUI-Bold.otf
- NotoSansKannadaUI-Regular.otf
- NotoSansMath-Regular.otf
- NotoSansMath-Regular.ttf
- NotoSansMono-Bold.otf
- NotoSansMono-Regular.otf
- NotoSansOriya-Bold.otf
- NotoSansOriya-Regular.otf
- NotoSansSymbols-Bold.otf
- NotoSansSymbols-Regular.otf
- NotoSansSymbols2-Regular.otf
- NotoSansTamilUI-Bold.otf
- NotoSansTamilUI-Regular.otf
- NotoSansThai-Bold.otf
- NotoSansThai-Regular.otf

![環境設定](img/font-config.webp)

Next, start Firestorm and select `Noto sans full` from the UI font settings.

Set Font Adjustment to -1.0.

## Lisence

&copy; 2023,2025 by Logue, Licensed under the GNU LESSER GENERAL PUBLIC LICENSE.

- [Noto Sans CJK and Mono License](./NotoSans-LICENSE.txt)