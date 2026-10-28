# Documentation for flags used in data.json

## CurrentModVersion
The current format for the menu to use. Currently unused but may be useful in the future if a V4 format comes out.

## ModMenuVersion
The current version expected for the menu. If the attribute on the mod menu indicating version does not match this value, then the menu will send out a notification alerting that the menu is either outdated or supersedes the maximum expected version.

## DefaultPathLists
A list of default paths the mod will check for. This includes common names for mods, used so that the user does not need to input a custom path for the menu. If you would like a new name added to this list please submit a pull request adding it.

## ModMenuTheme
Determines the setup for the theme of the menu. "V2" is the new standard and makes the menu load a fallback UI for those without local mods installed. Previously, "Default" was used. Setting it back to "Default" will result in the fallback UI not being loaded.

## ShowMenuCredit
Toggles the display of the credit topbar image on the menu.

## ShowMenuValidator
Toggles the display of the menu validator image on the topbar.

## CheckForSkinsMoreThan14
Allows the menu to check for 100 skins instead of 100. When tested, the menu can take longer to switch between mods as a result of this being enabled.

## ShowAnimationsTab
Toggles the display of the animations tab on the menu.

## AllowStringAssets
Enables the custom path function of the menu. This allows for loading custom paths for local mods, and allows for loading online mods (if AllowAssetLoading is also enabled).

## AllowV2Format
Allows for V2 Format mods to load onto the menu. In Mod Menu V4, this is unsupported hence why the flag is disabled by default.

## AllowAssetLoading
Allows for Roblox Model IDs to be input into the custom path feature.

## UseNotificationService
Use the Notification Service instead of the Top OOD TextLabel on the menu.


# Legacy (Removed) Flags
## DataJSONVersion
Used to determine the format of the data.json file. It never had any technical use and as such has been removed.
