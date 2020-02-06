
Мониторинг серверов с ОС Windows
================================



Проверка журнала system
-----------------------

Для включения проверки используется тэг **sys_log**. Для изменения настроек выполняемой проверки используется текстовая строка в формате JSON. Пример тэга **sys_log**:
``sys_log={"severity":"warning","notification":{"mail":{"send_recovery":false,"users":["SungurovDV"]}}}``

Для повышения наглядности, строку выше можно разбить на несколько строк.

.. code-block:: python

sys_log={
  "severity":"warning",
  "check_interval":"120",
  "past_hours":"1",
  "notification":{
    "mail":{
      "send_recovery":false,
      "users":["SungurovDV"]
    }
  }
}



Проверка журнала application
----------------------------



