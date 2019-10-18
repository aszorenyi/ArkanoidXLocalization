# ArkanoidX - Localization
This repository is for the translation of [ArkanoidX](https://play.google.com/store/apps/details?id=com.szorenyiadam.android.arkanoidx) and [ArkanoidX - Donate Version](https://play.google.com/store/apps/details?id=com.szorenyiadam.android.arkanoidx.donate).

English (base language) and Hungarian will be updated and maintained by me. Other languages are maintained in this repository by the community.

Changes in this repository will be merged and published in the next version of the game.

### Contribute
To contribute to the translation of ArkanoidX, you will need to fork this repository. This allows you to edit and push changes of files to your fork, then you can open a pull request.
For more information, read Github's official [forking guide](https://guides.github.com/activities/forking/).

### Adding a new language
If you want to begin translating ArkanoidX for a new language, create a new folder named `values-xx` where `xx` is the correct [two letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes#Partial_ISO_639_table). Alternatively you can add the [country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Decoding_table) as well. In this case the folder name format will be `values-xx_yy` where `xx` is the language code and `yy` is the country code (e.g. `values-pt_BR` for Portuguese (Brazilian).

In this folder create a file named `strings.xml`, then copy and paste the contents of the [English](https://github.com/aszorenyi/ArkanoidXLocalization/blob/master/values/strings.xml) file into it and start translating the strings.

Language files contains the translators name (`translated_by` key), e-mail address (`translator_email` key) and website (`translator_website` key). These strings are shown in the About menu on Translation tab. If you don't want to make them public, just leave these keys empty, or use a dash.

### Play Store descriptions
Google Play Store descriptions are located in the [play-store](https://github.com/aszorenyi/ArkanoidXLocalization/blob/master/play-store/) folder. File name format is `xx_playstore_description.txt` for the Free version and `xx_playstore_donate_description.txt` for the Donate version where `xx` is the correct [two letter language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes#Partial_ISO_639_table).