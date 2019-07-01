[English](https://github.com/MrD1abl0/GSCP-Translation "English") | Русский
# Game Server Constrol Panel - Перевод
<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/logo.png?raw=true" width="200">

В данном репозитории хранятся файлы перевода Android приложения [GSCP](https://play.google.com/store/apps/details?id=ru.air.gscp "GSCP").

------------

### Обновление доступных переводов
Если вы хотите добавить поддержку нового языка или улучшить имеющий перевод отправьте новые файлы с переводом через:
- [Pull request](https://github.com/MrD1abl0/GSCP-Translation/pulls "Pull request")
- Форумы ([hlmod](https://hlmod.ru/threads/android-game-server-control-panel.48657/ "hlmod"), [devcs](https://dev-cs.ru/threads/6759/ "devcs"), [goldsrc](https://goldsrc.ru/threads/3948/ "goldsrc"))
- Мессенджеры ([Telegram](https://t.me/MrD1ablo "Telegram"), [Steam](http://steamcommunity.com/id/wh40k/ "Steam"), [VK](http://vk.com/wh40k "VK"))
- Email (a.i.rekunov@gmail.com)

### Структура файлов перевода
+ Папка c названием в формате: {Язык} - {[Код языка](https://github.com/MrD1abl0/GSCP-Translation/blob/master/LOCALES-LIST.md "Код языка")}
	+ strings.xml (Перевод UI)
	+ strings-rate.xml (Перевод диалога с предложением оставить отзыв)
	+ strings-extra.xml (Дополнительные фразы для перевода)
	+ changelog.xml (Список изменений)
	+ gplay-page.txt (Описание приложения в Google Play)

### Пример переводимых строк
```xml
<!--Строка для перевода-->
<string name="action_settings">Settings</string>  

<!--translatable="false" - Переводить не нужно, можно удалить-->
<string name="action_debug" translatable="false">Debug UI</string> 

<!--Массив строк для перевода-->
<string-array name="dialog_mute_type_text">
	<item>Both</item>
	<item>Voice</item>
	<item>Chat</item>
</string-array>

<!--translatable="false" - Переводить не нужно, можно удалить-->
<string-array name="srvedit_spn_apitype_text" translatable="false">
	<item>Myarena.ru</item>
</string-array>

<!--integer-array - Переводить не нужно, можно удалить-->
<integer-array name="srvedit_spn_apitype_value">
	<item>0</item>
</integer-array>
```

### Обновление перевода в приложении
Добавление изменений перевода в приложение происходит вместе с публикацией крупного или мелкого обновления в Google Play.

### Примеры UI (Nexus One - 3,7" 480x800 hdpi)
<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/1.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/2.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/3.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/4.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/5.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/6.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/7.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/8.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/9.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/10.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/11.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/12.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/13.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/14.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/15.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/16.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/17.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/18.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/19.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/20.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/21.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/22.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/23.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/24.png?raw=true" width="280">

<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/25.png?raw=true" width="280"> <img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/26.png?raw=true" width="280">