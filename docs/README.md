![GitHub Release](https://img.shields.io/github/v/release/oleandrum/macos-iast-keyboard)
![GitHub License](https://img.shields.io/github/license/oleandrum/macos-iast-keyboard)

This repository provides a custom keyboard layout for macOS that enables easy
typing using the
[IAST](https://en.wikipedia.org/wiki/International_Alphabet_of_Sanskrit_Transliteration)
(International Alphabet of Sanskrit Transliteration) standard. The layout was
created using SIL Ukelele, a tool for building and editing macOS keyboard
layouts.

## Features

- Easy access to IAST diacritics using intuitive key combinations
- Fully compatible with macOS
- Lightweight and simple installation
- Designed for scholars, students, and enthusiasts of Sanskrit and Indic studies

## Installation

### 1. Download

Go to the
**[Releases](https://github.com/oleandrum/macos-iast-keyboard/releases)** page
of this repository and download the latest `IAST.bundle` file. Note that in the
macOS UI, the `.bundle` appears as a single file but is actually a folder.

### 2. Install on macOS

1. Copy the `IAST.bundle` to one of the following locations:

   - For current user only: `~/Library/Keyboard Layouts/`
   - For all users: `/Library/Keyboard Layouts/`

Alternatively, if you are comfortable with terminal and git commands, you can
execute the following to automate the process:

```bash
git clone https://github.com/oleandrum/macos-iast-keyboard.git \
    && cp -r ./macos-iast-keyboard/IAST.bundle \
    ~/Library/Keyboard\ Layouts/ && rm -rf ./macos-iast-keyboard/
```

2. Once completed, verify the `~/Library/Keyboard Layouts/` directory to confirm
   the layout files have been correctly copied.
3. Log out and log back in (or restart your Mac).

### 3. Enable the Keyboard

1. Go to **System Settings → Keyboard → Input Sources**
2. Click **Add Input Source**
3. Find and select **IAST Keyboard**
4. Add it to your list of input sources

## Usage

Once installed, you can switch to the IAST keyboard from the macOS input menu
and start typing transliterated text with diacritics.

### IAST Characters

| **Symbol** | **Key Combination** | **Unicode**     |
| ---------- | ------------------- | --------------- |
| ā          | `⌥ + a`             | U+0101          |
| Ā          | `⌥ + ⇧ + a`         | U+0100          |
| ḍ          | `⌥ + d`             | U+1E0D          |
| Ḍ          | `⌥ + ⇧ + d`         | U+1E0C          |
| ē          | `⌥ + e`             | U+0113          |
| Ē          | `⌥ + ⇧ + e`         | U+0112          |
| ḥ          | `⌥ + h`             | U+1E25          |
| Ḥ          | `⌥ + ⇧ + h`         | U+1E24          |
| ī          | `⌥ + i`             | U+012B          |
| Ī          | `⌥ + ⇧ + i`         | U+012A          |
| ñ          | `⌥ + j`             | U+00F1          |
| Ñ          | `⌥ + ⇧ + j`         | U+00D1          |
| ḷ          | `⌥ + k`             | U+1E37          |
| Ḹ          | `⌥ + ⇧ + k`         | U+1E38          |
| ḷ          | `⌥ + l`             | U+1E37          |
| Ḷ          | `⌥ + ⇧ + l`         | U+1E36          |
| l̤          | `⌥ + v`             | U+006C + U+0324 |
| L̤          | `⌥ + ⇧ + v`         | U+004C + U+0324 |
| ṃ          | `⌥ + m`             | U+1E43          |
| Ṃ          | `⌥ + ⇧ + m`         | U+1E42          |
| ṅ          | `⌥ + g`             | U+1E45          |
| Ṅ          | `⌥ + ⇧ + g`         | U+1E44          |
| ṇ          | `⌥ + n`             | U+1E47          |
| Ṇ          | `⌥ + ⇧ + n`         | U+1E46          |
| ō          | `⌥ + o`             | U+014D          |
| Ō          | `⌥ + ⇧ + o`         | U+014C          |
| ṛ          | `⌥ + r`             | U+1E5B          |
| Ṛ          | `⌥ + ⇧ + r`         | U+1E5A          |
| ṝ          | `⌥ + f`             | U+1E5D          |
| Ṝ          | `⌥ + ⇧ + f`         | U+1E5C          |
| ś          | `⌥ + s`             | U+015B          |
| Ś          | `⌥ + ⇧ + s`         | U+015A          |
| ṣ          | `⌥ + x`             | U+1E63          |
| Ṣ          | `⌥ + ⇧ + x`         | U+1E62          |
| ṭ          | `⌥ + t`             | U+1E6D          |
| Ṭ          | `⌥ + ⇧ + t`         | U+1E6C          |
| ū          | `⌥ + u`             | U+016B          |
| Ū          | `⌥ + ⇧ + u`         | U+016A          |

### Vedic Signs

| **Symbol** | **Key Combination** | **Unicode**              |
| ---------- | ------------------- | ------------------------ |
| ̐           | `⌥ + c`             | U+0310                   |
| ̐           | `⌥ + ⇧ + c`         | U+0310                   |
| ̍           | `⌥ + 1`             | U+030D                   |
| ̎           | `⌥ + 2`             | U+030E                   |
| ̱           | `⌥ + 3`             | U+0331                   |
| ḫ          | `⌥ + 4`             | U+1E2B                   |
| ẖ          | `⌥ + 5`             | U+1E96                   |
| gͫ          | `⌥ + 6`             | U+0067 + U+036B          |
| gͫ̄          | `⌥ + 7`             | U+0067 + U+036B + U+0304 |

### Punctuation

| **Symbol** | **Key Combination** | **Unicode** |
| ---------- | ------------------- | ----------- |
| …          | `⌥ + .`             | U+2026      |
| “          | `⌥ + '`             | U+201C      |
| ”          | `⌥ + ⇧ + '`         | U+201D      |
| —          | `⌥ + -`             | U+2014      |
| —          | `⌥ + ⇧ + -`         | U+2014      |
| ·          | `⌥ + ⇧ + .`         | U+00B7      |

## Contributing

Contributions, suggestions, and improvements are welcome! Feel free to
[open issues or submit bug](https://github.com/oleandrum/macos-iast-keyboard/issues).
I'll do my best to address them as quickly as possible.

## License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this keyboard layout, including for
commercial purposes, provided that the original license and copyright notice are
included.

## Acknowledgements

- [SIL Ukelele](https://software.sil.org/ukelele/) for providing the keyboard
  layout creation tool
- The academic community for standardizing IAST
