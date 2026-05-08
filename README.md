# VORTEX

VORTEX is a KSL mod for CarX Drift Racing Online focused on suspension tuning, telemetry, and adaptive damping.

It reads suspension data, builds dynostand setups, and adjusts damping live while the car is on track.

## Current features

- Suspension calibration and dynostand setup application
- Adaptive suspension and helper modes during live driving
- Car info and suspension telemetry panels
- Built-in theme catalog plus custom user themes
- EN/RU localization
- In-game Settings actions for refreshing local themes and opening the theme folder
- `F8` toggles the main window

## Theme support

- Built-in themes are packaged with the mod
- Custom themes are plain JSON files in `data/themes/user/*.json`
- `template.json` is included as a starter template and is ignored by the theme catalog
- Copy `template.json` to a new file, edit `id`, `name`, and `palette`, then use `Settings -> Refresh local themes`

## Requirements

- CarX Drift Racing Online
- KSL Mod Loader

## Install

1. Download the latest release from [Releases](https://github.com/Dranser/VORTEX/releases)
2. Install it using your KSL setup
3. Launch the game and press `F8` to open VORTEX

## Development

- Build from source with `dotnet build VORTEX.sln`

## Notes

- UI text is localized in English and Russian
- The theme folder can be opened directly from `Settings -> Open themes folder`
