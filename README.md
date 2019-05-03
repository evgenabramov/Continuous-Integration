# Описание запуска проекта

[![Build Status](https://travis-ci.com/evgenabramov/Continuous-Integration.svg?token=BTLs4oCWwqfaRL1pjb6t&branch=dev)](https://travis-ci.com/evgenabramov/Continuous-Integration)

***Внимание!*** Файл с описанием архитектуры проекта `Architecture.md` 
и файл с описанием игровой модели `GameModel.md` лежат в корневой папке.

Предполагается наличие у запускающего проект системы сборки `cmake`.

Скопируйте содержимое репозитория на свой компьютер.
Перейдите в корневую папку проекта в терминале и наберите следующие команды:

```
mkdir build
cd build
cmake ../
make
./run_unit_tests
```

В результате проект соберется и вы получите результат 
unit-тестирования компонентов проекта в терминале.

***Внимание!*** Весь код запускался и тестировался на macOS High Sierra 
10.13.6

В данном проекте используется система Continuous Integration на базе Travis-Ci.

