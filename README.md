# osu! package manager
A simple tool that allows you to backup your beatmaplist into a file and restore them.

## Warning: This tool assumes that the install folder for osu! is at ``` /Appdata/Local/osu!/```, the program will prompt you to enter in your custom Osu! install folder when running for the first time

You can change the install location anytime in ```osu.conf``` by editing it with InstallLocation=[OsuInstallPath]

## Main Features
- Export your current beatmap list to share with people without having to zip up your songs folder
- Downloads all the beatmaps from a given beatmap list
- No login - osuppkg will use your main browser to download songs (Just be sure to be logged into osu! on it)
- Optimisations - osuppkg will only download missing beatmaps

## Download
[https://github.com/sfook/osu-pkg/releases](https://github.com/sfook/osu-pkg/releases)

### Commands Usage
- ``` -h ``` or ```--help``` 
    - Displays available commands
- ``` -q ``` or ```--query```
    - Lists all beatmaps installed
- ``` -d ``` or ```--download```
    - Downloads the beatmap using the list of beatmaps provided

### Note that downloading beatmaps requires you to be logged into osu! on your main browser
