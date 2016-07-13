# PSWM-Translate
Localization for Parzi's Star Wars Mod

## Steps to Help Translate
1. If a localization file (i.e. `en_US.lang` for American English) already exists, create a fork of the repository and edit the file. **Proceed to step 3.**
2. If a localization file does **NOT** already exist, create a fork of the repository and create a new file with a [filename that corresponds to your language](http://minecraft.gamepedia.com/Language). The file name *must* be the **locale code** of your language, plus `.lang` at the end. 
3. Edit the key/value pairs for the localized strings in your file. Keep in mind that the keys must remain the same (i.e. `item.starwarsmod.banthaHorn.name`) between _all_ localization files, but every value can be changed to suit your language.
4. If you come across `%s` in a translation, fear not. `%s` gets replaced ingame with other important information. For example, `Affiliation: %s` would be displayed ingame as `Affiliation: The Rebel Alliance` 
5. Create a pull request back to this repository
6. We will either accept or, under extreme circumstances, reject your pull request
7. The new language additions will appear in the next version of the mod

Happy translating!
