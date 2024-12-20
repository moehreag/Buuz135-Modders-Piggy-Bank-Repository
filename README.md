# Modder's Piggy Bank Repository
The repository for Modder's Piggy Bank data. Modify only the `mod-authors.json` file.

## Json Format

If not specified, the field it is required

```
{
    "author": "Dummy", 
    "primary_color": "0x55FFFF", //Optional - Default 0x55FFFF (Aqua) - Must be a valid "Integer.decode()" value
    "secondary_color": "0x55FFFF", //Optional - Default 0x55FFFF (Aqua) - Must be a valid "Integer.decode()" value
    "alternate_attribution": [  //Optional - 
      "Dummy Mod Team"
    ],
    "links": [
      {
        "type": "type",
        "url": "url"
      }
    ]
  }
```

## Supported Link types

There isn't any link validation, types are used for the icon shown in game

* Ko-fi: `ko-fi`
* Github Sponsor: `github-sponsor`
* Patreon: `patreon`
* BuyMeACoffee: `buymeacoffee`
* Custom: `custom`
