# Bugrock JSON UI Schemas

VSCode Settings Example
```json
"json.schemas": [
  {
    "url": "https://kalmemarq.github.io/Bugrock-JSON-UI-Schemas/ui.schema.json",
    "fileMatch": [
      "*.ui.json",
      "*.uidx",
      "ui/**/*.json",
      "!_global_variables.json",
      "!_ui_defs.json"
    ]
  },
  {
    "url": "https://kalmemarq.github.io/Bugrock-JSON-UI-Schemas/ui_defs.schema.json",
    "fileMatch": [
      "ui/_ui_defs.json"
    ]
  },
  {
    "url": "https://kalmemarq.github.io/Bugrock-JSON-UI-Schemas/global_variables.schema.json",
    "fileMatch": [
      "ui/_global_variables.json"
    ]
  }
]
```
