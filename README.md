# Беларускі пераклад Stardew Valley

**Belarusizatar Stardew Valley** — поўны пераклад гульні Stardew Valley на беларускую мову.  

Аўтары перакладу:   
Перакладнікі: Ueschar & dymniška  
Рэдактар: Cactusovič  

Асаблівая падзяка <span style="color:#ff0000"><3</span>  
observr - Помач з перакладам, пруфрыдынг, іншае меркаванне  
dziaǔčo - Помач з тэставаннем перакладу  
Danielle Tłumač - аўтарка папраўленага шрыфту  

---
![App Platorm](https://i.imgur.com/n6u630Y.png)

## Інструкцыя ўсталявання


### 1. Неабходныя файлы

Каб гульня замяніла арыгінальны тэкст беларускім перакладам, вам спатрэбяцца:
  - Беларусізатар
  - [SMAPI installer](https://smapi.io/)
  - [ContentPatcher](https://www.nexusmods.com/stardewvalley/mods/1915)
  - [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098)

---

### 2.1 Усталяванне праз менеджар модаў для Windows (рэкамендуецца)
1. Усталюйце [Vortex](https://www.nexusmods.com/site/mods/1?tab=files) ці іншы менеджар модаў для Nexusmods. Запусціце гэту праграму.

2. Увайдзіце на свой уліковы запіс Nexusmods
3. У спісе гульняў (укладка Games з левага боку) выберыце Stardew Valley
4. Вам павінна паказацца паведамленне з прапановай усталяваць Smapi. Націсніце "Install" (усталяваць)
5. Спампуйце **Content Patcher**, **Generic Mod Config Menu** і **Беларусізатар**, націскаючы ў раздзеле спамповак "Mod manager download" (Спампаваць праз менеджар модаў) Зірніце ва ўкладку "Mods" вашага менеджара модаў, каб упэўніцца, што ўсе патрэбныя мадыфікацыі ўсталяваны і ўключаны.
6. Запусціце Stardew Valley праз менеджар модаў

---

### 2.2 Усталяванне ўласнаруч
<details>
  <summary>Windows</summary>


1. Распакуйце архіў "SMAPI installer" у зручнае месца на вашым камп'ютары.  
Унутры будуць некалькі файлаў для ўсталявання на розных сістэмах. Вам патрэбны наступны:  
>install on Windows.bat 
 
2. Адкрыецца кансоль з выбарам шляху да папкі з гульнёй. Выберыце адзін з паказаных варыянтаў, увядзіце адпаведны нумар у кансоль і націсніце Enter.

> Where do you want to add or remove SMAPI?  
> [1] C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

3) Далей вам прапаноўваецца ўсталяваць або выдаліць SMAPI. Увядзіце "1" і націсніце Enter для ўсталявання

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

3) Праверка ўсталявання - Калі ўсё прайшла паспяхова, вы ўбачыце наступнае паведамленне:

> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install):  
>     "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%  
> If you don't use Steam, launch StardewModdingAPI.exe in your game folder to play with mods.

<span style="color:#ffff00">[!] Калі ў вас Steam версія гульні, рэкамендуем скапіяваць тэкст з другой лінейкі. Мае выглядаць падобным чынам:</span>

> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%

<span style="color:#ffff00">Гэта вам спатрэбіцца пазней, каб уключыць магчымасць атрымоўваць дасягненні ў Steam.</span>

4. Распакуйце архівы з мадыфікацыямі **Content Patcher**, **Generic Mod Config Menu** і **Беларусізатарам** у папку Mods у каранёвым каталогу гульні. Звычайна гэта будзе:  
> C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\Mods


### Версія без Steam

5. Запускайце гульню праз файл "StardewModdingAPI.exe" замест звычайнага "Stardew Valley.exe". Гэты файл мае быць у каранёвай тэчцы з гульнёй, напрыклад:

> C:\Games\Stardew Valley

Рэкамендуем стварыць ярлык для гэтага файла, каб было зручней запускаць гульню.

### Версія для Steam (Запуск праз бібліятэку Steam і атрыманне дасягненняў)

5. Скапіюйце каманду з усталявальніка SMAPI, якая з'яўляецца пасля паведамлення:

> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install)

Звычайна каманда выглядае так:

> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%

6. Адкрыйце Steam, зайдзіце ва **ўласцівасці** Stardew Valley (пстрык ПКМ на гульню ў бібліятэцы -> Properties), і ўстаўце каманду ў радок **LAUNCH OPTIONS** на першай укладцы **General**.

7. Усталяванне завершана, можаце запускаць гульню як звычайна


</details>
<details>
  <summary>MacOS</summary>

1. Увайдзіце ў *Сістэмныя налады > Прыватнасць і бяспека (System Settings > Privacy and Security)*.
2. Праверце, ці відаць *Налады распрацоўшчыка (Developer Tools)*. Калі іх няма, запусціце тэрмінал праз Spotlight і ўвядзіце каманду:  
   > spctl developer-mode enable-terminal
3. Націсніце *Налады распрацоўшчыка (Developer Tools)*.
4. Дадайце тэрмінал у спіс ([скрыншот](https://stardewvalleywiki.com/File:Fix_macOS_security_permissions_2.png)).
5. Перазапусціце камп'ютар.

6. Распакуйце архіў "SMAPI installer" у зручнае месца на вашым камп'ютары.  
Унутры будуць некалькі файлаў для ўсталявання на розных сістэмах. Вам патрэбны наступны:  
> iinstall on macOS.command 
 
3. Адкрыецца кансоль з выбарам шляху да папкі з гульнёй. Выберыце адзін з паказаных варыянтаў, увядзіце адпаведны нумар у кансоль і націсніце Enter.

> Where do you want to add or remove SMAPI?  
> [1] C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

4. Далей вам прапаноўваецца ўсталяваць або выдаліць SMAPI. Увядзіце "1" і націсніце Enter для ўсталявання

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

5. Праверка ўсталявання - Калі ўсё прайшла паспяхова, вы ўбачыце наступнае паведамленне:

> SMAPI is installed! Launch the game the same way as before to play with mods.

6. Распакуйце архівы з мадыфікацыямі **Content Patcher**, **Generic Mod Config Menu** і **Беларусізатарам** у папку Mods у каранёвым каталогу гульні. Звычайна гэта будзе:  
> ~/.steam/steam/steamapps/common/Stardew Valley/Mods

7. Усталяванне завершана, можаце запускаць гульню як звычайна 

</details>
<details>
  <summary>Android</summary>

1. Спампуйце [SMAPI Launcher APK](https://github.com/NRTnarathip/SMAPILoader/releases) (файл мусіць называцца прыкладна так: ***SMAPI.Launcher.vx.x.x.apk***)
2. [Усталюйце спампаваны лаўнчар](https://www.greenbot.com/article/2452614/how-to-sideload-an-app-onto-your-android-phone-or-tablet.html)
3. Спампуйце [SMAPI](https://github.com/NRTnarathip/SMAPI-Android-1.6/releases) (файл мусіць называцца прыкладна так: ***SMAPI.4.x.x-xxxx.zip***)
4. Запусціце лаўнчар SMAPI. Націсніце кнопку "Install SMAPI From Zip" (Усталяваць SMAPI з ZIP архіву)
5. Выберыце спампаваны файл SMAPІ. Пачакайце, пакуль лаўнчар не паведаміць, што SMAPI паспяхова ўсталяваны.
6. Націсніце "Start Game" (Пачаць гульню). Цяпер запускаць Stardew Valley трэба будзе пра гэты лаўнчар.
7. Больш дакладную інструкцыю можна прачытаць на афіцыяльнай [wiki](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Android).
</details>
<details>
  <summary>Linux</summary>

1. Усталюйце эмулятар тэрмінала xterm (Яго не трэба рабіць асноўным ці прадвызначаным)

2. Распакуйце архіў "SMAPI installer" у зручнае месца на вашым камп'ютары.  
Унутры будуць некалькі файлаў для ўсталявання на розных сістэмах. Вам патрэбны наступны:  
> install on Linux.sh 
 
3. Адкрыецца кансоль з выбарам шляху да папкі з гульнёй. Выберыце адзін з паказаных варыянтаў, увядзіце адпаведны нумар у кансоль і націсніце Enter.

> Where do you want to add or remove SMAPI?  
> [1] /home/karystalnik/.steam/steam/steamapps/common/Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

4. Далей вам прапаноўваецца ўсталяваць або выдаліць SMAPI. Увядзіце "1" і націсніце Enter для ўсталявання

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

5. Праверка ўсталявання - Калі ўсё прайшла паспяхова, вы ўбачыце наступнае паведамленне:

> SMAPI is installed! Launch the game the same way as before to play with mods.

6. Распакуйце архівы з мадыфікацыямі **Content Patcher**, **Generic Mod Config Menu** і **Беларусізатарам** у папку Mods у каранёвым каталогу гульні. Звычайна гэта будзе:  
> ~/.steam/steam/steamapps/common/Stardew Valley/Mods

7. Усталяванне завершана, можаце запускаць гульню як звычайна 

</details>
<details>
  <summary>Steam deck</summary>

2. Распакуйце архіў "SMAPI installer" у зручнае месца на вашай прыладзе  
Унутры будуць некалькі файлаў для ўсталявання на розных сістэмах. Вам патрэбны наступны:  
> install on Linux.sh 
 
3. Адкрыецца кансоль з выбарам шляху да папкі з гульнёй. Выберыце адзін з паказаных варыянтаў, увядзіце адпаведны нумар у кансоль і націсніце Enter.

> Where do you want to add or remove SMAPI?  
> [1] /home/karystalnik/.steam/steam/steamapps/common/Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

4. Далей вам прапаноўваецца ўсталяваць або выдаліць SMAPI. Увядзіце "1" і націсніце Enter для ўсталявання

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

5. Праверка ўсталявання - Калі ўсё прайшла паспяхова, вы ўбачыце наступнае паведамленне:

> SMAPI is installed! Launch the game the same way as before to play with mods.

6. Распакуйце архівы з мадыфікацыямі **Content Patcher**, **Generic Mod Config Menu** і **Беларусізатарам** у папку Mods у каранёвым каталогу гульні. Звычайна гэта будзе:  
> ~/.steam/steam/steamapps/common/Stardew Valley/Mods

7. Усталяванне завершана, можаце запускаць гульню як звычайна 
</details>

---
### 3. Змена правапісу і шрыфтоў

У меню гульні можна выбраць афіцыйны ці клясычны(БКП-2005) правапіс, а таксама 1 з 3 шрыфтоў. Каб усё адпаведна працавала, упэўніцеся, што ўсталявалі [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098).  

У левым ніжнім куце экрану будзе кнопка з значком "хэштэга", якая адкрывае меню модаў, улучаючы Беларусізатар (гл. Скрыншоты). Там трэба выбраць мод, што нас цікавіць (Stardew Valley Belarusian). Пасля змены правапісу ці шрыфту перазапусціце гульню.

---

### Тэлеграм аўтараў:
[Ueschar](https://t.me/Ueschar)  
[dymniska](https://t.me/dymniska)

### Таксама варта зірнуць:
[Тэлеграм-канал з навінамі аб перакладзе](https://t.me/trojantranslation)  
[Твітар з навінамі аб перакладзе](https://x.com/lokar_lak)  
[Дыскорд сервер беларускай супольнасці](https://discord.gg/wCPEK5kFUj)

---

# Белорусский перевод Stardew Valley

**Belarusizator Stardew Valley** — полный перевод игры Stardew Valley на белорусский язык.

Авторы перевода:  
Переводчики:    
Ueschar & dymniška  
Редактор: Cactusovič

Особая благодарность <span style="color:#ff0000"><3</span>  
observr - Помощь с переводом, proofreading, другое мнение  
dziaǔčo - Помощь с тестированием перевода  
Danielle Tłumač - авторка исправленного шрифта

---

![App Platorm](https://i.imgur.com/n6u630Y.png)
## Инструкция по установке
### 1. Необходимые файлы
Чтобы игра заменила оригинальный текст белорусским переводом, вам понадобятся:
- Belarusizator
- [SMAPI installer](https://smapi.io/)
- [ContentPatcher](https://www.nexusmods.com/stardewvalley/mods/1915)
- [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098)
---
### 2.1 Установка через менеджер модов для Windows (рекомендуется)
1. Установите [Vortex](https://www.nexusmods.com/site/mods/1?tab=files) или другой менеджер модов для Nexusmods. Запустите эту программу.
2. Войдите в свой аккаунт Nexusmods
3. В списке игр (вкладка Games слева) выберите Stardew Valley
4. Вам должно показаться сообщение с предложением установить Smapi. Нажмите "Install" (установить)
5. Скачайте **Content Patcher**, **Generic Mod Config Menu** и **Belarusizator**, нажимая в разделе скачиваний "Mod manager download" (Скачать через менеджер модов) Посмотрите во вкладку "Mods" вашего менеджера модов, чтобы убедиться, что все необходимые модификации установлены и включены.
6. Запустите Stardew Valley через менеджер модов

---

### 2.2 Установка вручную

<details>
<summary>Windows</summary>

1. Распакуйте архив "SMAPI installer" в удобное место на вашем компьютере.
Внутри будут несколько файлов для установки на разных системах. Вам нужен следующий:
>install on Windows.bat

2. Откроется консоль с выбором пути к папке с игрой. Выберите один из показанных вариантов, введите соответствующий номер в консоль и нажмите Enter.
> Where do you want to add or remove SMAPI?  
> [1] C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.
3) Далее вам предлагается установить или удалить SMAPI. Введите "1" и нажмите Enter для установки
> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.
3) Проверка установки - Если всё прошло успешно, вы увидите следующее сообщение:

> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install):  
>     "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%  
> If you don't use Steam, launch StardewModdingAPI.exe in your game folder to play with mods.

<span style="color:#ffff00">[!] Если у вас Steam версия игры, рекомендуем скопировать текст со второй строки. Должен выглядеть примерно так:</span>
> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%

<span style="color:#ffff00">Это вам понадобится позже, чтобы включить возможность получать достижения в Steam.</span>

4. Распакуйте архивы с модификациями **Content Patcher**, **Generic Mod Config Menu** и **Belarusizator** в папку Mods в корневом каталоге игры. Обычно это будет:
> C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\Mods
### Версия без Steam
5. Запускайте игру через файл "StardewModdingAPI.exe" вместо обычного "Stardew Valley.exe". Этот файл должен быть в корневой папке с игрой, например:
> C:\Games\Stardew Valley

Рекомендуем создать ярлык для этого файла, чтобы было удобнее запускать игру.
### Версия для Steam (Запуск через библиотеку Steam и получение достижений)
5. Скопируйте команду из установщика SMAPI, которая появляется после сообщения:
> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install)

Обычно команда выглядит так:
> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%
6. Откройте Steam, зайдите в **свойства** Stardew Valley (щелкните ПКМ на игру в библиотеке -> Properties), и вставьте команду в строку **LAUNCH OPTIONS** на первой вкладке **General**.
7. Установка завершена, можете запускать игру как обычно
</details>

<details>
<summary>MacOS</summary>

1. Войдите в *Системные настройки > Приватность и безопасность (System Settings > Privacy and Security)*.
2. Проверьте, виден ли *Настройки разработчика (Developer Tools)*. Если их нет, запустите терминал через Spotlight и введите команду:
> spctl developer-mode enable-terminal
3. Нажмите *Настройки разработчика (Developer Tools)*.
4. Добавьте терминал в список [](https://stardewvalleywiki.com/File:Fix_macOS_security_permissions_2.png).
5. Перезагрузите компьютер.
6. Распакуйте архив "SMAPI installer" в удобное место на вашем компьютере.
Внутри будут несколько файлов для установки на разных системах. Вам нужен следующий:
> install on macOS.command
3. Откроется консоль с выбором пути к папке с игрой. Выберите один из показанных вариантов, введите соответствующий номер в консоль и нажмите Enter.
> Where do you want to add or remove SMAPI?  
> [1] C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.
4. Далее вам предлагается установить или удалить SMAPI. Введите "1" и нажмите Enter для установки
> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.
5. Проверка установки - Если всё прошло успешно, вы увидите следующее сообщение:
> SMAPI is installed! Launch the game the same way as before to play with mods.
6. Распакуйте архивы с модификациями **Content Patcher**, **Generic Mod Config Menu** и **Belarusizator** в папку Mods в корневом каталоге игры. Обычно это будет:
> ~/.steam/steam/steamapps/common/Stardew Valley/Mods
7. Установка завершена, можете запускать игру как обычно
</details>

<details>
<summary>Android</summary>

1. Скачайте [SMAPI Launcher APK](https://github.com/NRTnarathip/SMAPILoader/releases) (файл должен называться примерно так: ***SMAPI.Launcher.vx.x.x.apk***)
2. [Установите скачанный лаунчер](https://www.greenbot.com/article/2452614/how-to-sideload-an-app-onto-your-android-phone-or-tablet.html)
3. Скачайте [SMAPI](https://github.com/NRTnarathip/SMAPI-Android-1.6/releases) (файл должен называться примерно так: ***SMAPI.4.x.x-xxxx.zip***)
4. Запустите лаунчер SMAPI. Нажмите кнопку "Install SMAPI From Zip" (Установить SMAPI из ZIP архива)
5. Выберите скачанный файл SMAPI. Подождите, пока лаунчер не сообщит, что SMAPI успешно установлен.
6. Нажмите "Start Game" (Начать игру). Теперь запускать Stardew Valley нужно будет через этот лаунчер.
7. Более подробную инструкцию можно прочитать на официальной [wiki](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Android).
</details>

<details>
<summary>Linux</summary>

1. Установите эмулятор терминала xterm (Его не нужно делать основным или предопределенным)
2. Распакуйте архив "SMAPI installer" в удобное место на вашем компьютере.
Внутри будут несколько файлов для установки на разных системах. Вам нужен следующий:
> install on Linux.sh
3. Откроется консоль с выбором пути к папке с игрой. Выберите один из показанных вариантов, введите соответствующий номер в консоль и нажмите Enter.
> Where do you want to add or remove SMAPI?  
> [1] /home/karystalnik/.steam/steam/steamapps/common/Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.
4. Далее вам предлагается установить или удалить SMAPI. Введите "1" и нажмите Enter для установки
> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.
5. Проверка установки - Если всё прошло успешно, вы увидите следующее сообщение:
> SMAPI is installed! Launch the game the same way as before to play with mods.
6. Распакуйте архивы с модификациями **Content Patcher**, **Generic Mod Config Menu** и **Belarusizator** в папку Mods в корневом каталоге игры. Обычно это будет:
> ~/.steam/steam/steamapps/common/Stardew Valley/Mods
7. Установка завершена, можете запускать игру как обычно
</details>

<details>
<summary>Steam Deck</summary>

1. Распакуйте архив "SMAPI installer" в удобное место на вашем устройстве
Внутри будут несколько файлов для установки на разных системах. Вам нужен следующий:
> install on Linux.sh
2. Откроется консоль с выбором пути к папке с игрой. Выберите один из показанных вариантов, введите соответствующий номер в консоль и нажмите Enter.
> Where do you want to add or remove SMAPI?  
> [1] /home/karystalnik/.steam/steam/steamapps/common/Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.
3. Далее вам предлагается установить или удалить SMAPI. Введите "1" и нажмите Enter для установки
> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.
4. Проверка установки - Если всё прошло успешно, вы увидите следующее сообщение:
> SMAPI is installed! Launch the game the same way as before to play with mods.
5. Распакуйте архивы с модификациями **Content Patcher**, **Generic Mod Config Menu** и **Belarusizator** в папку Mods в корневом каталоге игры. Обычно это будет:
> ~/.steam/steam/steamapps/common/Stardew Valley/Mods
6. Установка завершена, можете запускать игру как обычно
</details>

---

### 3. Изменение правописания и шрифтов

В меню игры можно выбрать официальное или классическое (БКП-2005) правописание, а также 1 из 3 шрифтов. Чтобы всё работало правильно, убедитесь, что установили [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098).

В левом нижнем углу экрана будет кнопка с значком "хэштега", которая открывает меню модов, включая Belarusizator (см. Скриншоты). Там нужно выбрать мод, который нас интересует (Stardew Valley Belarusian). После изменения правописания или шрифта перезапустите игру.

---

### Телеграм авторов:
[Ueschar](https://t.me/Ueschar)  
[dymniska](https://t.me/dymniska)
### Также стоит посмотреть:
[Телеграм-канал с новостями о переводе](https://t.me/trojantranslation)  
[Твиттер с новостями о переводе](https://x.com/lokar_lak)  
[Дискорд сервер белорусского сообщества](https://discord.gg/wCPEK5kFUj)

---

# Belarusian Translation of Stardew Valley
**Belarusizer Stardew Valley** — a complete translation of the game Stardew Valley into Belarusian.

Authors of the translation:  
Translators: Ueschar & dymniška  
Editor: Cactusovič  

Special thanks <span style="color:#ff0000"><3</span>  
observr - Help with translation, proofreading, other opinions  
dziaǔčo - Help with testing the translation  
Danielle Tłumač - author of the corrected font

---

![App Platorm](https://i.imgur.com/n6u630Y.png)
## Installation Instructions
### 1. Necessary Files
To have the game replace the original text with the Belarusian translation, you will need:
- Bielarusizatar
- [SMAPI installer](https://smapi.io/)
- [ContentPatcher](https://www.nexusmods.com/stardewvalley/mods/1915)
- [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098)

---

### 2.1 Installation via Mod Manager for Windows (recommended)

1. Install [Vortex](https://www.nexusmods.com/site/mods/1?tab=files) or another mod manager for Nexusmods. Launch this program.

2. Log in to your Nexusmods account
3. In the list of games (Games tab on the left), select Stardew Valley
4. You should see a message suggesting to install Smapi. Click "Install"
5. Download **Content Patcher**, **Generic Mod Config Menu** and **Belarusizer**, by clicking in the downloads section "Mod manager download" (Download via mod manager) Look at the "Mods" tab of your mod manager to make sure all necessary modifications are installed and enabled.
6. Launch Stardew Valley via the mod manager

---

### 2.2 Manual Installation
<details>
<summary>Windows</summary>

1. Unzip the "SMAPI installer" archive to a convenient place on your computer.
Inside there will be several files for installation on different systems. You need the following:
>install on Windows.bat

2. A console will open with a choice of path to the game folder. Select one of the shown options, enter the corresponding number in the console and press Enter.

> Where do you want to add or remove SMAPI?  
> [1] C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

3. Next, you will be prompted to install or uninstall SMAPI. Enter "1" and press Enter to install
> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

4. Installation check - If everything went successfully, you will see the following message:

> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install):
>     "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%  
> If you don't use Steam, launch StardewModdingAPI.exe in your game folder to play with mods.

<span style="color:#ffff00">[!] If you have the Steam version of the game, we recommend copying the text from the second line. It should look something like this:</span>

> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%

<span style="color:#ffff00">You will need this later to enable receiving achievements in Steam.</span>

5. Unzip the archives with modifications **Content Patcher**, **Generic Mod Config Menu** and **Belarusizer** into the Mods folder in the root directory of the game. Usually it will be:

> C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\Mods
### Non-Steam Version

6. Launch the game via the "StardewModdingAPI.exe" file instead of the usual "Stardew Valley.exe". This file should be in the root game folder, for example:
> C:\Games\Stardew Valley

We recommend creating a shortcut for this file for easier launching.

### Steam Version (Launch via Steam library and receiving achievements)
6. Copy the command from the SMAPI installer that appears after the message:
> SMAPI is installed! If you use Steam, set your launch options to enable achievements (see smapi.io/install)

Usually the command looks like this:
> "C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley\StardewModdingAPI.exe" %command%
7. Open Steam, go to **Properties** of Stardew Valley (right-click on the game in the library -> Properties), and paste the command into the **LAUNCH OPTIONS** line on the first **General** tab.
7. Installation is complete, you can launch the game as usual
</details>
<details>
<summary>MacOS</summary>

1. Go to *System Settings > Privacy and Security*.
2. Check if *Developer Tools* is visible. If not, launch the terminal via Spotlight and enter the command:

> spctl developer-mode enable-terminal

3. Click *Developer Tools*.
4. Add the terminal to the list [](https://stardewvalleywiki.com/File:Fix_macOS_security_permissions_2.png).
5. Restart the computer.
6. Unzip the "SMAPI installer" archive to a convenient place on your computer.
Inside there will be several files for installation on different systems. You need the following:

> install on macOS.command

3. A console will open with a choice of path to the game folder. Select one of the shown options, enter the corresponding number in the console and press Enter.

> Where do you want to add or remove SMAPI?  
> [1] C:\Program Files (x86)\Steam\steamapps\common\Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

4. Next, you will be prompted to install or uninstall SMAPI. Enter "1" and press Enter to install

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

5. Installation check - If everything went successfully, you will see the following message:

> SMAPI is installed! Launch the game the same way as before to play with mods.

6. Unzip the archives with modifications **Content Patcher**, **Generic Mod Config Menu** and **Belarusizer** into the Mods folder in the root directory of the game. Usually it will be:
> ~/.steam/steam/steamapps/common/Stardew Valley/Mods
7. Installation is complete, you can launch the game as usual
</details>
<details>
  <summary>Android</summary>

1. Download [SMAPI Launcher APK](https://github.com/NRTnarathip/SMAPILoader/releases) (the file should be named something like: ***SMAPI.Launcher.vx.x.x.apk***)

2. [Install the downloaded launcher](https://www.greenbot.com/article/2452614/how-to-sideload-an-app-onto-your-android-phone-or-tablet.html)
3. Download [SMAPI](https://github.com/NRTnarathip/SMAPI-Android-1.6/releases) (the file should be named something like: ***SMAPI.4.x.x-xxxx.zip***)
4. Launch the SMAPI launcher. Click the "Install SMAPI From Zip" button (Install SMAPI from ZIP archive)
5. Select the downloaded SMAPI file. Wait until the launcher reports that SMAPI is successfully installed.
6. Click "Start Game" (Start the game). Now you need to launch Stardew Valley through this launcher.
7. A more detailed guide can be found on the official [wiki](https://stardewvalleywiki.com/Modding:Installing_SMAPI_on_Android).

</details>
<details>
<summary>Linux</summary>

1. Install the xterm terminal emulator (It doesn't need to be made the main or default)
2. Unzip the "SMAPI installer" archive to a convenient place on your computer.
Inside there will be several files for installation on different systems. You need the following:

> install on Linux.sh

3. A console will open with a choice of path to the game folder. Select one of the shown options, enter the corresponding number in the console and press Enter.

> Where do you want to add or remove SMAPI?  
> [1] /home/karystalnik/.steam/steam/steamapps/common/Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.  

4. Next, you will be prompted to install or uninstall SMAPI. Enter "1" and press Enter to install

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.  

5. Installation check - If everything went successfully, you will see the following message:
> SMAPI is installed! Launch the game the same way as before to play with mods.
6. Unzip the archives with modifications **Content Patcher**, **Generic Mod Config Menu** and **Belarusizer** into the Mods folder in the root directory of the game. Usually it will be:
> ~/.steam/steam/steamapps/common/Stardew Valley/Mods
7. Installation is complete, you can launch the game as usual
</details>
<details>
<summary>Steam Deck</summary>

2. Unzip the "SMAPI installer" archive to a convenient place on your device
Inside there will be several files for installation on different systems. You need the following:

> install on Linux.sh

3. A console will open with a choice of path to the game folder. Select one of the shown options, enter the corresponding number in the console and press Enter.

> Where do you want to add or remove SMAPI?  
> [1] /home/karystalnik/.steam/steam/steamapps/common/Stardew Valley  
> [2] Enter a custom game path.  
> Type the number next to your choice, then press enter.

4. Next, you will be prompted to install or uninstall SMAPI. Enter "1" and press Enter to install

> What do you want to do?  
> [1] Install SMAPI.  
> [2] Uninstall SMAPI.  
> Type 1 or 2, then press enter.

5. Installation check - If everything went successfully, you will see the following message:

> SMAPI is installed! Launch the game the same way as before to play with mods.

6. Unzip the archives with modifications **Content Patcher**, **Generic Mod Config Menu** and **Belarusizer** into the Mods folder in the root directory of the game. Usually it will be:

> ~/.steam/steam/steamapps/common/Stardew Valley/Mods

7. Installation is complete, you can launch the game as usual
</details>

---

### 3. Changing Spelling and Fonts

In the game menu, you can choose official or classic (BKP-2005) spelling, as well as 1 of 3 fonts. To make everything work correctly, make sure you have installed [Generic Mod Config Menu](https://www.nexusmods.com/stardewvalley/mods/5098).

In the lower left corner of the screen, there will be a button with a "hashtag" icon that opens the mods menu, including the Belarusizer (see Screenshots). There you need to select the mod we are interested in (Stardew Valley Belarusian). After changing the spelling or font, restart the game.

---
### Authors' Telegram:
[Ueschar](https://t.me/Ueschar)  
[dymniska](https://t.me/dymniska)
### Also worth checking out:
[Telegram channel with translation news](https://t.me/trojantranslation)  
[Twitter with translation news](https://x.com/lokar_lak)  
[Belarusian community Discord server](https://discord.gg/wCPEK5kFUj)

