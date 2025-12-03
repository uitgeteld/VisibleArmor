# Visible Armor

A client-side Minecraft mod that displays a colored armor HUD based on the armor material you're wearing!

## Features

- **Material-Based Colors**: The armor bar changes color depending on your armor material:
  - **Diamond** - Cyan/Aqua blue
  - **Netherite** - Dark gray/black
  - **Iron** - Light gray
  - **Gold** - Golden yellow
  - **Chainmail** - Steel gray
  - **Leather** - Brown
  - **Turtle** - Green
  - **Mod armors** - Automatically detects common mod materials (emerald, ruby, sapphire, amethyst)

- **Client-Side Only**: No server installation required!

- **Configurable**: Edit the config file to customize:
  - Enable/disable the custom armor HUD
  - Enable/disable color tinting

## Installation

1. Download the latest release from the releases page
2. Place the `.jar` file in your Minecraft `mods` folder
3. Launch Minecraft with Forge 1.20.1

## How It Works

The mod determines your "dominant" armor material by checking all equipped armor pieces. When you wear diamond armor, the armor bar displays in cyan blue. Mix-and-match armor sets will show the color of whichever material you're wearing the most pieces of.

## Building from Source

```bash
./gradlew build
```

The built jar will be in `build/libs/`

## License

Apache 2.0

## Credits

Created by uitgeteld

