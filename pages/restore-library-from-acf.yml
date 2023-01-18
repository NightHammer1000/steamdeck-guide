# Restore Library from .acf files

Open Steam Library folder.
Mark down all the Steam Game IDs from the .acf files.
Steam Game ID comes after appmanifest_
appmanifest_[STEAM APP ID].acf
Construct the Steam Launch command with a validation command for each acf File:

## Linux
**Make sure Steam is closed first!**
From everywhere

    steam -console +app_start_validation [STEAM APP ID]

repeat `+app_start_validation [STEAM APP ID]` for each acf file.

## Windows
**Make sure Steam is closed first!**
From the Root folder of your steam installation (usually `C:\Program Files (x86)\Steam`)

    steam.exe -forceservice -console +app_start_validation [STEAM APP ID]

repeat `+app_start_validation [STEAM APP ID]` for each acf file.

---
Steam should now validate, repair and redownload each game.
