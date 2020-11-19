[Example](database/climate/atmosphere/atmospheric-co2.json)

```json
{
  "path": "climate/atmosphere/atmospheric-co2.json", // may be necessary depending on implementation
  "label": "Atmospheric co2", // see path name
  "description": "Increased carbon dioxide released into the atmosphere",
  "relationships": [
    {
      "path": "./atmospheric-pollution.json", // "./" denotes relative path
      "type": "causes",
      "description": "Dramatic changes to air composition"
    },
    {
      "path": "./atmospheric-temperature.json",
      "type": "causes",
      "description": "" // can be left empty
    },
    {
      "path": "../../energy/hydrocarbon-combustion.json", // "../" denotes traversing to a higher folder
      "type": "caused by",
      "description": "Unsustainable energy production"
    }
  ],
  "metadata": {
    "categories": ["ecological instability", "climate change", "chemistry"]
    // users may want to be able to append arbitrary data here
  }
}
```
