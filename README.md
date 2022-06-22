# Bugrock JSON UI Schemas

VSCode Settings Example
```json
"json.schemas": [
  {
    "url": "https://github.com/KalmeMarq/Bugrock-JSON-UI-Schemas/raw/main/ui.schema.json",
    "fileMatch": [
      "*.ui.json",
      "*.uidx",
      "ui/**/*.json",
      "!_global_variables.json",
      "!_ui_defs.json"
    ]
  },
  {
    "url": "https://github.com/KalmeMarq/Bugrock-JSON-UI-Schemas/raw/main/ui_defs.schema.json",
    "fileMatch": [
      "ui/_ui_defs.json"
    ]
  },
  {
    "url": "https://github.com/KalmeMarq/Bugrock-JSON-UI-Schemas/raw/main/global_variables.schema.json",
    "fileMatch": [
      "ui/_global_variables.json"
    ]
  }
]
```