# EXILIUM Tracker (i18n)

Deployed at https://exilium.xyz

This directory contains translations for the application in the following languages:

- Deutsch (German)
- English
- Español (Spanish)
- Français (French)
- 日本語 (Japanese)
- 한국어 (Korean)
- Português (Portuguese)
- ภาษาไทย (Thai)
- 简体中文 (Simplified Chinese)
- 繁體中文 (Traditional Chinese)

## Structure

```
├── de/
│ └── pages/
│   └── achievement.json
│   └── common.json
│   └── home.json
│   └── metadata.json
│   └── pull.json
│   └── setting.json
├── en/
│ └── pages/
│   └── achievement.json
│   └── common.json
│   └── home.json
│   └── metadata.json
│   └── pull.json
│   └── setting.json
└── ...
```

## Translation Guidelines

1. Find your language folder (e.g., \`ja\` for Japanese)
2. Navigate to the file you want to translate
3. Only translate the values, keep the keys unchanged

Example:

```json
{
  "title": "Translate this text",
  "description": "Translate this text too"
}
```

The English version (\`en\` folder) can be used as a reference for the original text.
