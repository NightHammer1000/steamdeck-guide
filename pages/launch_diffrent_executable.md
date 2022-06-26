# Launch Steam Games with a diffrent Executeable

## Native Games

For native games, you have to put the following in the Game Settings under "Launch Arguments" (Replace `<NEW EXECUTEABLE>` with the new Executeable Filename):

`<NEW EXECUTEABLE> # %command%`


## Windows Games

For Windows games, you have to put the following in the Game Settings under "Launch Arguments" (Replace `<NEW EXECUTEABLE>` with the new Executeable Filename):

`$(echo %command% | sed -r "s/proton waitforexitandrun .*/proton waitforexitandrun/") "$STEAM_COMPAT_INSTALL_PATH/<NEW EXECUTEABLE>"`
