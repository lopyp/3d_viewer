﻿# 3d Viewer

 ## Возможности

- Просмотр объектов в формате .obj
- Отображение основных характеристик модели
- Вариативные параметры отображения модели
- Сохранение отобажаемого вида в форматах .bmp, jpeg, gif

## Установка

Перед началом установки убедитесь что у вас установлены следующие пакеты

> Требуется: `GCC` `G++` `MAKE` `CMAKE` `QT6` `lcov`
 
- Из папки SRC выполните следующую команду 
```sh
make install
```
> Исполняемый файл будет находится в папке:
MACOS: s21_viewer/3D_Viewer.app/Contents/MacOS
LINUX: s21_viewer/

## Тестирование
> Перед запуском убедитесь, что математическая составляющая программы работает корректно
- Из папки SRC выполните следующую команду 
```sh
make test
```
- Чтобы проверить покрытие тестами
```sh
make gcov_report
```
## Запуск

- Из папки SRC выполните следующую команду 
```sh
make launch
```

## Архивация

- Из папки SRC выполните следующую команду
```sh
make dist
```

## Удаление

- Из папки SRC выполните следующую команду
```sh
make uninstall
```
