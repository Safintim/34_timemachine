# Таймер для веб сайтов, которые крадут ваше время

Скрипт помогает контролировать время нахождения на сайте. Требуется специальное расширение для Хрома.

После истечения таймера, каждые 30 секунд показывается сообщение о том, что пора работать.

## Как установить

Установить расширение для Хрома [Custom JavaScript for websites](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija).

Открыть расширение [cjs](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija) на сайте, который хотите контроллировать. Нажмите на ссылку "ваши собственные внешние скрипты", добавьте путь. Например, https://github.com/Safintim/34_timemachine/blob/master/index.js

Не забудьте нажать "Включить cjs для этого хоста", чтобы включить пользовательский JS.


Выглядит вот так:

![alt text](http://ipic.su/img/img7/fs/timemachine.1564308380.png)


Для более быстрой разработки вы можете использовать JS-код, размещенный на локальном хосте. Простой веб-сервер может быть использован для этого, запустите:

```sh
python3 -m http.server
```

Добавьте путь `http://localhost:8000/index.js` в расширение [cjs](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija)


## Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке - [DEVMAN.org](https://devman.org)
