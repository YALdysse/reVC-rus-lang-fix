<img src="https://github.com/mrxenginner/reVC/blob/miami/res/images/logo_1024.png?raw=true" alt="reVC logo" width="200">

# [Рус] Исправление русской локализация для reVC (reverse engineered GTA: Vice City)

Проект реверс-инжиниринга GTA: Vice City, reVC, включал в себя русскую локализацию от 1С, однако из-за остановки разработки проекта русская локализация не была полностью завершена — в игре остались немало непереведенных новых строк. Этот репозиторий имеет целью завершить русскую локализацию проекта reVC.

## Компиляция

Чтобы скомпилировать текст в gxt, вам необходимо воспользоваться инструментом [«GXT Compiller»](https://github.com/Sergeanur/GXT-compiler) от Sergeanur.
Пример команды для компиляции текста:
> gxt.exe -i ".\txt\russian_utf-8-BOM.txt" -o ".\build\russian.gxt" -t ".\tables\vc_table_rus_1c.txt"

## Декомпиляция

## Установка

Просто скопируйте файл `russian.gxt` в каталог с игрой `./text` с заменой исходного файла. Вот и все! Наслаждайтесь!

