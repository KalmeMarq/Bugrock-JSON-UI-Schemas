# Bugrock JSON UI Schemas

VSCode settings
```json
"json.schemas": [
  {
    "fileMatch": [
      "**/*.ui.json",
      "*/ui/realmsPlus_sections/*.json",
      "*/ui/*.json",
      "*/ui/settings_sections/*.json",
      "!*/ui/_global_variables.json",
      "!*/ui/_ui_defs.json",
      "*/ui/ui_*_screen.json",
      "*/ui/ui_*.json",
      "*/ui/xbl_*.json"
      "*/ui/storage_management*.json"
      "*/ui/realms_*.json"
    ],
    "url": "{Path to ui.schema.json}"
  },
  {
    "fileMatch": [
      "*/ui/_ui_defs.json"
    ],
    "url": "{Path to ui_defs.schema.json}"
  }
]
```