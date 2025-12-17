# winece
Cheat Engine for wine

Installs CE on the same prefix of your game (Steam games for now) and modifies the args to start with your game. (which is the reason most of times u cant just run CE directly.) An example;

 ` export WINEPREFIX=/home/{username}/.local/share/Steam/steamapps/compatdata/{GameID}/pfx`
 
 ` export STEAM_COMPAT_DATA_PATH=/home/{username}/.local/share/Steam/steamapps/compatdata/{GameID}`
 
 ` export WINEFSYNC=1`
 
 ` export PROTON_NO_ESYNC=0`
 
 ` export PROTON_NO_FSYNC=0`

  `~/.steam/steam/steamapps/common/Proton\ -\ Experimental/files/bin/wine \
      "/home/{username}/.local/share/Steam/steamapps/compatdata/3304105226/pfx/drive_c/Program Files/Cheat Engine/CheatEngine.exe"`

Im trying to make the same thing useful on every distro. From my experience it works best on Arch Linux.
