## Schema

```json
{
  "schemaVersion": 1,
  "modules": [
    {
      "id": "quest_settings_patcher",  // internal slug, any unique string
      "name": "Quest Settings Patcher",
      "description": "...",
      "author": "Lumince",
      "githubOwner": "Lumince",        // the module's OWN repo -- app resolves its latest release
      "githubRepo": "Quest-Settings-Patcher",
      "assetSuffix": ".apk",
      "deviceFilter": null,             // null, or a QuestDevice name
      "packageName": "com.lumi.settingspatcher"
    }
  ]
}
```
