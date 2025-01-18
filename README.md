# OpenPaster i18n

The internationalization (i18n) module for OpenPaster, used to manage multilingual support.

## Directory Structure

```
.
├── README.md
├── scheme.json
├── en-US.json
├── zh-CN.json
└── ...
```

## Language Pack Structure

Language packs must comply with the JSON Schema specification defined in `scheme.json`.

## Adding New Languages

1. Copy `en-US.json` and rename it to the corresponding language code (e.g., `zh-CN.json`)
2. Modify the file content to the target language
3. Ensure the new language pack fully complies with the `scheme.json` specification

## Development Notes

- All language packs must use UTF-8 encoding
- Language pack filenames should use standard language codes (e.g., en-US, zh-CN, etc.)
- When adding new translation items, remember to update `scheme.json` accordingly
