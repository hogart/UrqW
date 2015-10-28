## Интерпретатор urq-квестов на языке js с открытым исходным кодом.
Кратко о:
Веб-урка это не онлайн урка. Её можно скачать и запускать, например, с флешки без интернета.
Можно разместить на своём сайте (пока только в отдельной подпапке), добавить в список свои игры и давать друзьм ссылку чтобы они поиграли.
Когда вы загружаете игру в веб урку (даже в моей онлайн-версии) никому ничего не отправляется. Загрузка и прогрывание происходит локально в браузере. Все сохранения браузер также держит локально.
https://github.com/narmiel/UrqW/archive/gh-pages.zip - по этой ссылке можно загрузить уже собранную версию сразу с bootstrap и jquery чтобы не ставить ничего дополнительно. Там сразу есть добавленые игры.

### Онлайн версия:
 * http://narmiel.github.io/UrqW/

### Установка:
* Вариант 1 (простой): скачать собранную версию отсюда https://github.com/narmiel/UrqW/archive/gh-pages.zip (игры что в онлайн версии там есть)
* Вариант 2: скачать с зип с ветки "мастер" и добавить в проект сторонние библиотеки jQuery, Boostrap, jszip и 
jszip-utils, которые не хранятся в репозитории вручную или через bower. С веткой "мастер" не идут в комплекте игры.

### Текущая цель:
 * ~~совместимость с большинством игр под досурку~~ (выполнено)
 * добавлять и тестировать новые игры

### FAQ:
 * Как закачать игру в онлайн каталог?
 * Прислать мне её на почту, akela88 [@] bk.ru, я её добавлю. Если речь идёт о том, как добавить игру в репозиторий на своём сайте, то нужно положить квест в папку quests и отредактировать файл games.json (смотрите примеры тут https://github.com/narmiel/UrqW/archive/gh-pages.zip)
 
### Чем помочь проекту?
 * issue с описанием найденых багов
 * добавление протестированых игр в репозиторий (с согласия автора, лол)
 * пул реквесты с исправлениями

### Документация:
 * http://narmiel.github.io/UrqW/docs/urql.html - описание urq language

### Ссылки:
 * http://telegram.me/narmiel - быстрая связь с разработчиком
 * http://urq.plut.info/ - сайт urq
 * http://forum.ifiction.ru/viewtopic.php?id=2138 - тема на форуме иффикшн про UrqW
 * http://urq.borda.ru/?1-0-0-00000495-000-0-0-1444755056 - тема на форуме urq про UrqW
 * http://rilarhiv.ru/urq.htm - библиотека urq игр
 * https://client01.chat.mibbit.com/?url=irc%3A%2F%2Firc.forestnet.org%3A6662%2F%23urq - чат об urq и не только, где ответят на любые ваши вопросы
 * https://github.com/narmiel/UrqW/issues - сюда писать о ошибках и пожеланиях
