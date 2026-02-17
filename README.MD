<img src="https://github.com/mrxenginner/reVC/blob/miami/res/images/logo_1024.png?raw=true" alt="reVC logo" width="200">

# [Рус] Исправление русской локализации для reVC (reverse engineered GTA: Vice City)

Проект реверс-инжиниринга GTA: Vice City, reVC, включал в себя русскую локализацию от 1С, однако из-за остановки разработки проекта русская локализация не была полностью завершена — в игре остались немало непереведенных новых строк. Этот репозиторий имеет целью завершить русскую локализацию проекта reVC.

## Компиляция

Чтобы скомпилировать текст в gxt, вам необходимо воспользоваться инструментом [«GXT Compiller»](https://github.com/Sergeanur/GXT-compiler) от Sergeanur.
Пример команды для компиляции текста:
> gxt.exe -i ".\txt\russian_utf-8-BOM.txt" -o ".\build\russian.gxt" -t ".\tables\vc_table_rus_1c.txt"

## Декомпиляция

## Установка

Просто скопируйте файл `russian.gxt` в каталог с игрой `./text` с заменой исходного файла. Вот и все! Наслаждайтесь!

___

# [Eng] Fix for Russian localisation for reVC (reverse engineered GTA: Vice City)

The GTA: Vice City reverse engineering project, reVC, included Russian localisation from 1C, but due to the project's development being halted, the Russian localisation was not fully completed — quite a few new lines remained untranslated in the game. The purpose of this repository is to complete the Russian localisation of the reVC project.

## Compilation

To compile text in gxt, you need to use the [GXT Compiler](https://github.com/Sergeanur/GXT-compiler) tool from Sergeanur.
Example command for compiling text:
> gxt.exe -i ".\txt\russian_utf-8-BOM.txt" -o ".\build\russian.gxt" -t ".\tables\vc_table_rus_1c.txt"

## Decompilation

## Installation

Simply copy the `russian.gxt` file to the game directory `./text`, replacing the original file. That's it! Enjoy!
