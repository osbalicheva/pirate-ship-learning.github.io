---
title: Cheat Sheet
permalink: /docs/python/cheetsheet/
---
Весь Python на одной странице

## Инструкции по установке на Windows 10

1. Скачиваем и устанавливаем [последнюю версию](https://www.python.org/downloads/)
2. Проверяем Python из командной строки
```
python
>>> print( "Halo worlt")
Halo worlt
```
3. Если файл запуска не добавлен в пути Windows и сообщение похоже на
```
'python' is not recognized as an internal or external command,
operable program or batch file.
```
то выполняем команду
```
setx /M path "%path%;C:\your\path\to\pyhon\"
```

Если во время установки у вас возникли пробелемы, то нужно обратиться к [официальной документации](https://docs.python.org/3/using/index.html).
