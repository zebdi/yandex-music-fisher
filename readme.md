#Yandex Music Fisher (1.3.1)

Расширение для загрузки музыки с сервиса [Яндекс.Музыка](http://music.yandex.ru/).

Можно скачивать отдельные треки, плейлисты, альбомы и дискографии.
Расширение самостоятельно устанавливает ID3 тег (включая обложку).
При прерывании загрузки есть возможность возобновить её.

[Список изменений](https://github.com/egoroof/yandex-music-fisher/releases)

### Зеркала

При блокировке одного из репозиториев другие продолжат работать. Сейчас доступны:

- [GitHub](https://github.com/egoroof/yandex-music-fisher)
- [Bitbucket](https://bitbucket.org/egoroof/yandex-music-fisher)

### Требование

Необходим браузер на базе Chromium:
[Chrome](https://www.google.com/chrome) (рекомендуется),
[Яндекс.Браузер](https://browser.yandex.ru),
[Opera](http://www.opera.com/),
[Iron](https://www.srware.net/ru/software_srware_iron.php),
[Coc Coc](https://coccoc.com/en) или подобный

### Установка

[Скачайте архив по этой ссылке](https://github.com/egoroof/yandex-music-fisher/releases/download/v1.3.1/yandex-music-fisher_1.3.1.zip),
извлеките в текущую папку, откройте страницу расширений в браузере и перенесите туда мышкой извлечённую папку __yandex-music-fisher__,
после чего в браузере появится новое расширение:

![Установка](/publish/install.gif "Установка")

Обновляется расширение аналогичным способом.
Когда выйдет новая версия, расширение оповестит вас.

### Условия использования сервиса Яндекс.Музыка

Используя расширение Yandex Music Fisher (далее - Расширение), вы считаетесь принявшим [условиями использования сервиса Яндекс.Музыка](https://legal.yandex.ru/music_termsofuse/) (далее – Условия).
В случае несогласия с какими-либо из положений указанных в Условиях, вы не вправе использовать сервис Яндекс.Музыка.
Разработчики Расширения не несут ответственность за нарушения Условий, поэтому используйте Расширение на свой страх и риск.

### Как пользоваться

Откройте страницу на [Яндекс.Музыка](http://music.yandex.ru/) с нужным ![blue](/publish/blue.png) треком,
![yellow](/publish/yellow.png) альбомом или ![green](/publish/green.png) плейлистом - иконка изменит цвет в зависимости
от открытой страницы. Нажав на неё откроется всплывающее окно с информацией о загрузке и кнопкой для начала скачивания.

![Использование](/publish/usage.gif "Использование")

После нажатия на кнопку скачивания, загрузка появится на вкладке "Загрузки":

![Загрузки](/publish/loader.png)

Далее пойдёт автоматический процесс скачивания. Можно покинуть сайт Яндекс Музыки.
Кроме того, со страницы исполнителя можно скачать дискографию:

![Дискография](/publish/discography.png)

### Пути сохранения

- Все загрузки сохраняются в папку, которая указана в настройке браузера "__Расположение загружаемых файлов__".
- Для __дискографии__ создаётся отдельная папка с именем исполнителя, в которую сохраняются альбомы.
- Для __альбома__ / __плейлиста__ создаётся отдельная папка с именем исполнителя и названием альбома / плейлиста.
- Если __альбом__ состоит из нескольких дисков, то создаются соответствующие папки.

### Ограничения

Поскольку __сервис Яндекс.Музыка позволяет слушать музыку только пользователям из России, Украины, Беларуси и
Казахстана__, то и скачивать музыку с помощью этого расширения возможно только из этих стран.

С недавних пор __сервис Яндекс.Музыка начал выводить капчу__ и таким способом противодействовать скачиванию треков.
При этом расширение покажет ошибку, а для дальнейшего скачивания нужно перейти на любую страницу Яндекс.Музыки и
ввести капчу. После чего можно возобновить скачивание через расширение. Однако на данный момент капча появляется постоянно,
что сильно тормозит скачивание больших коллекций треков. В будущих версиях расширения будут попытки свести к минимуму,
либо вообще избежать появления капчи. Тем не менее, теперь скорость скачивания сильно ограничена.

### Поддержка

По всем вопросам можете писать на kukukov.kuku@gmail.com.
Если треки не получается скачать, обязательно добавьте в письмо ссылку на страницу, с которой
пытаетесь скачать, версию расширения, а так же название и версию браузера.

Но лучше всего описывать проблему в
[трекере GitHub](https://github.com/egoroof/yandex-music-fisher/issues/new)
(требуется регистрация).
