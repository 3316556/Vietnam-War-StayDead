# Configure StayDead

No MelonPreferences config is required. The mod stores save-state data through Unity PlayerPrefs/Windows registry keys prefixed with SD_. Do not delete those keys if you want persisted battlefield state to remain.

## MelonPreferences

Most mods create preferences automatically only if they need them. If this mod uses MelonPreferences, the settings will appear after the game has launched once with the mod installed.

Preference file location:

`	ext
VietnamWar\UserData\MelonPreferences.cfg
`

Do not ship a pre-filled MelonPreferences.cfg to users; it can overwrite settings from other mods.
