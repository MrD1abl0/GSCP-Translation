English | [Русский](https://github.com/MrD1abl0/GSCP-Translation/blob/master/README-ru.md "Русский")
# Game Server Constrol Panel - Translation
<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/logo.png?raw=true" width="200">

This repository stores the [GSCP](https://play.google.com/store/apps/details?id=ru.air.gscp "GSCP") translation files.

------------

### Improving translations
If you want to add support for a new language or improve the having translation, send new files with translation through:
- [Pull request](https://github.com/MrD1abl0/GSCP-Translation/pulls "Pull request")
- Forums ([hlmod](https://hlmod.ru/threads/android-game-server-control-panel.48657/ "hlmod"), [devcs](https://dev-cs.ru/threads/6759/ "devcs"), [goldsrc](https://goldsrc.ru/threads/3948/ "goldsrc"))
- Messengers ([Telegram](https://t.me/MrD1ablo "Telegram"), [Steam](http://steamcommunity.com/id/wh40k/ "Steam"), [VK](http://vk.com/wh40k "VK"))
- Email (a.i.rekunov@gmail.com)

### Translation files structure
+ Folder name in the format: {Language} - {[Language Code](https://github.com/MrD1abl0/GSCP-Translation/blob/master/LOCALES-LIST.md "Language Code")}
	+ strings.xml (UI translation)
	+ strings-rate.xml (Rate dialog translation)
	+ strings-extra.xml (Extra translation)
	+ changelog.xml
	+ gplay-page.txt (Google Play description)

### Example of translatable strings
```xml
<!--String to translate-->
<string name="action_settings">Settings</string>  

<!--translatable="false" - No need to translate, you can delete-->
<string name="action_debug" translatable="false">Debug UI</string> 

<!--String array to translate-->
<string-array name="dialog_mute_type_text">
	<item>Both</item>
	<item>Voice</item>
	<item>Chat</item>
</string-array>

<!--translatable="false" - No need to translate, you can delete-->
<string-array name="srvedit_spn_apitype_text" translatable="false">
	<item>Myarena.ru</item>
</string-array>

<!--integer-array - No need to translate, you can delete-->
<integer-array name="srvedit_spn_apitype_value">
	<item>0</item>
</integer-array>
```

### Updating translations in the app
Adding translation changes in app occurs with publication of a major or minor update in Google Play.

### UI examples (Nexus One - 3,7" 480x800 hdpi)
<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/1.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/2.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/3.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/4.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/5.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/6.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/7.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/8.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/9.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/10.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/11.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/12.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/13.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/14.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/15.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/16.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/17.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/18.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/19.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/20.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/21.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/22.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/23.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/24.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/25.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/26.png?raw=true" width="280">