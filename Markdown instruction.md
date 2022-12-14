# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить тектс курсивом необходимо обрамить его звездочками (*) или нижним подчеркиванием (_). Например, *вот так* или _вот так_

Чтобы выделить текст полужирным - обрамляем двойными звездочками (**) или двойным нижним подверкиванием (__). Например, **вот так** или __вот так__

Альтернативные способы выделения текста полужирным или курсивом, чтобы мы могли совмещать оба способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком плюс (+). Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4
+ Элемент 5

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать. Например, вот так: 
1. Первый пункт
2. Второй пункт
3. Третий пункт

## Работа с изображениями
Чтобы вставить изображение в текст, достаточно написать следующее:
![Символ мира](mir.jpg)

## Работа с таблицами
При работе с таблицами используем вертикальный слеш (|). Для выделения шапки таблицы второй строкой необходимо использовать (--|--).

 Автоматически наименование заголовков выравнивается полевому краю. Чтобы изменить оформление вносим символы во второй сроке под ибозначением именования столбцов. 
 
 Выровнять по центру используем двоеточие (:):
 - по центру (|:---:|)
 - по правому краю (|---:)
 
№| to do | status| executor
--|-------|:-----:|----:
1| creat new start-up|in progress| Rybkin| 
2| find new staff| in progress|Gochyan
3| fix last changes in b-plan|done|Lehanov


## Цытаты
Для добавления цитат используем знак (>). Если хотим добавать вложеную цтату добавлем количество стрелок (>>)
> Сожалеть - лишь попусту тратить время
>> Tomas Crown (c)

## _ДОМАШНЕЕ ЗАДАНИЕ 2_
```
Продолжить работу с файлом, начатую на Семинаре 1. Создать и слить как минимум 4 ветки. Обязательно создать конфликт и разрешить его. Архив с репозиторием и проделанной работой приложить к уроку.
```


### ВЫПОЛНЕНИЕ:
1. добавлены 2 ветки: tables, quotes
2. в tables внесена информация по оформлению таблиц. Прописана инфо о ДЗ, которая не была указана в ветке master. отражено исполнение
3. Дополнительно в ветке master внесена инфо по ДЗ с сайта - для создания конфликта
4. Созданы еще 2 ветки: HomeTask, Result
5. В ветке quotes внесена инфо по оформлению. Ветка залита без конфликтов.
6. в ветке hometask продублирована инфо по ДЗ. таким образом получится конфликт в трех ветках. Сначала залита ветка hometask, при решении конфликта приняты изменения из этой ветки.
7. Залита ветка tables. Конфликт. При решении конфликта частичное удаление текста из заливаемой ветки - не принят текст с детализацией ДЗ и по выполнению.
8. залита ветка results. Конфликт - совпадение первых пунктов. Принята последняя версия из ветки Result. При решении конфликта полная замена текста.

### Трудности при выполнении задания:
* при слиянии веток делала не по порядку разделов (например, сначала таблицы, после цитаты...), а в разнобой. поэтому несколько раз раздел цитаты исчезал из чистовика. по этой причине делалось несколько раз слияние quotes, hometask.