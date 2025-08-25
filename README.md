## Nextbots
## File sys
addons # 3d-party code and content.
content # fonts, themes, animations, sounds and e.t.c.
globals # global scenes and code (singleton).
scripts # source code.
shaders # shader source code.
scenes # scenes, packed scene, scene resources.


## File formats
png # texture, sprite and alpha channel support
jpeg # big texture no alpha support
wav # audio files short 3.5 seconds.
mp3 # all audio files 3.5 upper seconds, all voice line and simple sounds.
.cfg # configuration files, archive user data.
.json # archive all other data.
! prefer selected file format better .tres (.anim, .theme, е.t.c.) but prefer usage .tres format better .res binary format.


## Recomendations
• minimum _process() and strong math in functions.
• cashing all links with @onready.
• preloaded shadows better dynamic lights.
• minimum physics collable and math.
• minimum shader using.
• one pixel = one triangle.
• use jolt physics engine and 32 ticks server.
• minimum server math and data usage
• prefer usage non archived resources.
• 1 pixel = 1 triangle.
• in this project usage jolt physics and 32 physics tickrate
• minimum server math and data usage.
• use light resources.
• use UNDERSTATABLE NAMES for files..


1) PLAYER CONTROLLER
• Игрок
• Ходьба
• осмотр по сторонам
• падение
• ускорение при движении
• хп

2) HUD
• прицел
• показ хп

2) TOUCH CONTROLL
• джойстик
• ограничение на зону ввода поворота камеры правой стороны экрана.
• кнопка паузы

2) TEST MAP
• Простая платформа

3) NEXTBOT
• Nextbot
• Машина состоний
• Состояние поиска игрока
• состояние преследования
• поиск игрока
• ускорение при движении
• падение скорости при повороте
• преследоыаник игрока
• урон игроку от прикосновения по некстботу.
• ярость
• накопление ярости
• использование ярости

4) MENU
• стартовый экран
• главное меню
• профиль
• настройки
• выход из игры
• пауза
• о разработчиках
• список серверов
• создание сервера
• вернуться в игру
• уведомление о получении достижения
• экран окончания бенчмарка
• show FPS

5) BENCHMARK

6) LAN GAME?ное меню
• профиль
• настройки
• выход из игры
• пауза
• о разработчиках
• список серверов
• создание сервера
• вернуться в игру

5) BENCHMARK

6) LAN GAME?
