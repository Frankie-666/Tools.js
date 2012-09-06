# Tools.js
Free jQuery tools for websites. <a href="http://ionden.com/tools/">Страница проекта</a>

## Возможности
* Работает на jQuery 1.7+
* Удобное решение повседневных рутинных задач
* Модульность, можно подключать компоненты на выбор
* Легкое подключение и использование
* Кроссбраузерность. IE 7.0+ и все современные браузеры.
* <a href="http://ionden.com/tools/license.html">Лицензия MIT</a>


## Компоненты
* tools.mobile - определяет мобильные браузеры
* tools.fuck - фильтр мата
* tools.pattern - проверяет тип полей на соответствие

## Tools.mobile
* содержит 2 переменные: <code>check</code> и <code>browser</code>
* tools.mobile.check - вернет <code>true</code>, если вы открыли страницу мобильным браузером (вроде Safari на iPhone и т.п.)
* tools.mobile.browser - вернет название мобильного устройства/браузера
* <a href="http://ionden.com/tools/#mobile">Демо</a>

## Tools.fuck
* Метод <code>tools.fuck.check(текст[, mask])</code> определяет матершину в словах и возвращает текст, где все матные слова заменены на звездочки
* Не обязательный аргумент <code>mask</code>: вы можете передать методу шаблон замены в виде строки, например "[censored]"
* <a href="http://ionden.com/tools/#fuck">Демо</a>

## Tools.pattern
* Метод <code>tools.pattern.check(текст, type)</code> проверяет текст на соответствие указанному типу
* Аргумент <code>type</code>: вы можете передавать методу названия шаблонов проверки. На данный момент их 3:
  * __text__ - проверяет отсутствие специальных символов в тексте, вроде <;
  * __email__ - проверяет текст на соответствие шаблону адреса: name@mail.com;
  * __phone__ - проверяет текст на соответствие шаблону телефона: +7(123)456-78-90 и подобным.


* <a href="http://ionden.com/tools/#pattern">Демо</a>