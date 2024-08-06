[English](https://github.com/MrD1abl0/GSCP-Translation "English") | Русский
# Game Server Constrol Panel - Перевод
<img src="https://github.com/MrD1abl0/GSCP-Translation/blob/master/images/logo.png?raw=true" width="200">

В данном репозитории хранятся файлы перевода Android приложения [GSCP](https://play.google.com/store/apps/details?id=ru.air.gscp "GSCP").

------------

### Обновление доступных переводов
Если вы хотите добавить поддержку нового языка или улучшить имеющийся перевод отправьте новые файлы с переводом через:
- [Pull request](https://github.com/MrD1abl0/GSCP-Translation/pulls "Pull request")
- Форумы ([csdevs](https://csdevs.net/threads/game-server-control-panel.1164/ "csdevs"), [hlmod](https://hlmod.ru/threads/android-game-server-control-panel.48657/ "hlmod"), [devcs](https://dev-cs.ru/threads/6759/ "devcs"), [goldsrc](https://goldsrc.ru/threads/3948/ "goldsrc"))
- Мессенджеры ([Telegram](https://t.me/airv00 "Telegram"), [Steam](http://steamcommunity.com/id/wh40k/ "Steam"), [VK](http://vk.com/wh40k "VK"))
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

### Примеры UI (Pixel - 5,0" 1080x1920 420dpi)
<img src="/images/1.webp?raw=true" width="204"> <img src="/images/2.webp?raw=true" width="204"> <img src="/images/3.webp?raw=true" width="204"> <img src="/images/4.webp?raw=true" width="204">

<img src="/images/5.webp?raw=true" width="204"> <img src="/images/6.webp?raw=true" width="204"> <img src="/images/7.webp?raw=true" width="204"> <img src="/images/8.webp?raw=true" width="204">

<img src="/images/9.webp?raw=true" width="204"> <img src="/images/10.webp?raw=true" width="204"> <img src="/images/11.webp?raw=true" width="204"> <img src="/images/12.webp?raw=true" width="204">

<img src="/images/13.webp?raw=true" width="204"> <img src="/images/14.webp?raw=true" width="204"> <img src="/images/15.webp?raw=true" width="204"> <img src="/images/16.webp?raw=true" width="204">

<img src="/images/17.webp?raw=true" width="204"> <img src="/images/18.webp?raw=true" width="204"> <img src="/images/19.webp?raw=true" width="204"> <img src="/images/20.webp?raw=true" width="204">

<img src="/images/21.webp?raw=true" width="204"> <img src="/images/22.webp?raw=true" width="204"> <img src="/images/23.webp?raw=true" width="204"> <img src="/images/24.webp?raw=true" width="204">

<img src="/images/25.webp?raw=true" width="204"> <img src="/images/26.webp?raw=true" width="204"> <img src="/images/27.webp?raw=true" width="204"> <img src="/images/28.webp?raw=true" width="204">

<img src="/images/29.webp?raw=true" width="204"> <img src="/images/30.webp?raw=true" width="204"> <img src="/images/31.webp?raw=true" width="204"> <img src="/images/32.webp?raw=true" width="204">

<img src="/images/33.webp?raw=true" width="204"> <img src="/images/34.webp?raw=true" width="204"> <img src="/images/35.webp?raw=true" width="204"> <img src="/images/36.webp?raw=true" width="204">

<img src="/images/37.webp?raw=true" width="204"> <img src="/images/38.webp?raw=true" width="204"> <img src="/images/39.webp?raw=true" width="204"> <img src="/images/40.webp?raw=true" width="204">