**Политика очистки** данных в базе-приемнике перед переносом:

* `Disabled` — не очищать.

  Выберите эту опцию, если будет производиться только репликация без копирования данных.

* `Drop` — полное удаление таблиц, участвующих в трансфере (вариант по умолчанию).

  Используйте эту опцию, чтобы при любой активации трансфера в эндпоинт-приемник всегда передавалась самая последняя версия схемы таблиц из источника.

* `Truncate` — удалить только данные из таблиц, участвующих в трансфере, но оставить схему.

  Используйте эту опцию, если схема в эндпоинте-приемнике отличается от той, которая была бы перенесена из источника при трансфере.