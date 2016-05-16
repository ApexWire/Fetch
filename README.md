Fetch
=====

**Fetch это библиотека для чтения электронной почты и вложений, по протоколам POP и IMAP.**

## Установка

Предпочтительный способ установки расширения через [composer](http://getcomposer.org/download/).

Запустить

```sh
php composer.phar require "apexwire/fetch" : "^0.9.0"
```

или добавить

```json
"apexwire/fetch": "^0.9.0"
```

в разделе "require" вашего composer.json

## Применение

Это лишь простой код, чтобы показать, как получить доступ к сообщениям с помощью Fetch. Он использует Fetch
собственный автозагрузка, но он может (и должен быть, если это применимо) заменяется генерируемому
композитором.

```php
    $server = new \Fetch\Server('imap.example.com', 993);
    $server->setAuthentication('dummy', 'dummy');

    $messages = $server->getMessages();
    /** @var $message \Fetch\Message */
    foreach ($messages as $message) {
        echo "Subject: {$message->getSubject()}\nBody: {$message->getMessageBody()}\n";
    }
```

## Лицензия

Этот проект был выпущен под лицензией [BSD-3-Clause](LICENSE).
Подробнее [тут](http://choosealicense.com/licenses/bsd-3-clause).

Copyright © 2016, ApexWire

## Выражение признательности

- Проект является форком [Fetch](https://github.com/tedious/Fetch).
