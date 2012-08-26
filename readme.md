# Tools.js
Free jQuery tools for websites

## Возможности
* Работает на jQuery 1.7+
* Удобное решение повседневных рутинных задач
* Модульность, можно подключать компоненты на выбор
* Легкое подключение и использование
* Кроссбраузерность. IE 7.0+ и все современные браузеры.
* Лицензия MIT


## Компоненты
* tools.mobile - определяет мобильные браузеры
* tools.fuck - фильтр мата

## Tools.mobile
<p>Булева переменная <code>tools.mobile</code> возвращает значение <code>true</code>, если страница открыта мобильным браузером (вроде Safari на iPhone и т.п.)</p>

## Tools.fuck
* Метод <code>tools.fuck.check(текст[, bool])</code> определяет матершину в словах и возвращает текст, где все матные слова заменены на звездочки
* Не обязательная переменная <code>bool</code>. Если <code>true</code>, то в ответе, каждая буква мата будет заменена на звездочку, если <code>false</code>, то все слово будет заменено на 1 звездочку.