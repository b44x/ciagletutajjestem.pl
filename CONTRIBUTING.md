# 🌍 Dodaj tłumaczenie / Add a translation

Dziękujemy, że chcesz pomóc! / Thank you for wanting to help!

This song is about a child fighting cancer for the third time. Help the world understand its message by adding a translation in your language.

---

## How to add a translation (5 minutes)

1. **Fork** this repository
2. **Copy** `translations/template.json` → `translations/XX.json`  
   (replace `XX` with your [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes), e.g. `de`, `fr`, `ua`, `es`)
3. **Fill in** all the fields:
   - `"lang"` – your ISO code (e.g. `"de"`)
   - `"name"` – language name in your language (e.g. `"Deutsch"`)
   - `"flag"` – flag emoji (e.g. `"🇩🇪"`)
   - `"contributor"` – your GitHub handle (e.g. `"@yourname"`)
   - `"blocks"` – translate every `"tx"` field, **keep all `"t"` timestamps unchanged**
4. **Open a Pull Request** – title: `Add [Language name] translation`

The translation will appear automatically on the site after merge. ✨

---

## Format reference

```json
{
  "lang": "de",
  "name": "Deutsch",
  "flag": "🇩🇪",
  "contributor": "@yourname",
  "blocks": [
    {
      "tag": "Intro",
      "type": "intro",
      "lines": [
        { "t": 0, "tx": "YOUR TRANSLATION HERE" },
        { "t": 3, "tx": "ANOTHER LINE" }
      ]
    }
  ]
}
```

**Rules:**
- ✅ Translate only the `"tx"` values
- ✅ Keep `"t"` timestamps exactly as-is (they sync with the music)
- ✅ Keep `"type"` values as-is (`intro`, `verse`, `chorus`, `bridge`, `outro`)
- ✅ Keep all blocks and lines in order
- ❌ Don't change the JSON structure
- ❌ Don't rename files other than the language code

---

## Available translations

| Language | Code | File | Contributor |
|----------|------|------|-------------|
| Polski (original) | `pl` | `translations/pl.json` | original |
| English | `en` | `translations/en.json` | machine-translated |

*Add your language and update this table in your PR!*

---

## Questions?

Open an issue or tag [@b44x](https://github.com/b44x) in your PR.

---

## About the song

**"Ciągle tutaj jestem" (Still Here)** is a diss track against cancer by:
- 🎤 **Maja Mecan** – a child fighting her 3rd cancer relapse
- 🎤 **Bedoes 2115** – Polish rapper
- ❤️ **Cancer Fighters** – Polish foundation supporting children with cancer

102+ million views. Donate: [siepomaga.pl/latwogang](https://www.siepomaga.pl/latwogang) · [pomagam.cancerfighters.pl](https://pomagam.cancerfighters.pl/o-nas/)
