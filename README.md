# Описание разметки файла README.md
Файл README.md рекомендовано использовать для описания проектов на GitHub. Пишется он на языке разметки **markdown**. 

Markdown – это облегченный язык разметки, который является инструментом преобразования кода в HTML. Главной особенностью данного языка является максимально простой синтаксис, который служит для упрощения написания и чтения кода разметки, что, в свою очередь, позволяет легко его корректировать. 
Теперь рассмотрим более подробно функции языка разметки Markdown.

1. [Горизонтальная линия/Разделительная черта](#Горизонтальная-линия)
2. [Заголовки](#Заголовки)
3. [Выделение текста](#Работа-с-выделением-текста)
4. [Цитирование в тексте](#Цитирование-в-тексте)
5. [Подсветка кода](#Подсветка-кода)
6. [Списки](#Списки)
7. [Ссылки](#Ссылки)
8. [Изображения](#Изображения)

    
## Горизонтальная линия
Для того чтобы создать горизонтальную линию, необходимо поместить три (или более) дефиса или звездочки на отдельной строке текста. Между ними возможно располагать пробелы. Горизонтальные линии в Markdown выглядят следующим образом:
```
Текст, который надо разделить
--- или ***
Текст, который надо разделить
```
В результате на экран выводится следующее:

Текст, который надо разделить

---------

Текст, который надо разделить

## Заголовки

Всего существует шесть уровней заголовков. Для того, чтобы создать заголовок, необходимо в начале строки добавить символы `#`, в количестве равном его уровню.
```
#  Заголовок первого уровня
### Заголовок третьего уровня
###### Заголовок шестого уровня
```
В результате на экран выводится следующее:

#  Заголовок первого уровня
### Заголовок третьего уровня
###### Заголовок шестого уровня

## Работа с выделением текста

```
~~Зачеркнутый текст~~
```
~~Зачеркнутый текст (Strikethrough)~~

Для выделения текста **`жирным`** или *`наклонным`* и их сочетания можно использовать комбинации `*` или `_`

```
**Жирный текст (bold)**
```
**Жирный текст (bold)**

```
*Наклонный текст (italic)*
```
*Наклонный текст (italic)*

```
***Жирный наклонный текст (bold italic)***
```
***Жирный наклонный текст (bold italic)***

```
__Жирный текст (bold)__
```
__Жирный текст (bold)__

```
_Наклонный текст (italic)_
```
_Наклонный текст (italic)_

```
___Жирный наклонный текст (bold italic)___
```
___Жирный наклонный текст (bold italic)___

```
~~*__Тут странный текст__*~~
```
~~*__Тут странный текст__*~~
    
## Цитирование в тексте
```
> Цитата (уровень 1)    
> > Вложенная цитата (уровень 2)    
> > > Вложенная цитата (уровень 3)    

```
В результате на экране отображается слндующее:

> Цитата (уровень 1)    
> > Вложенная цитата (уровень 2)    
> > > Вложенная цитата (уровень 3)    

> > Продолжение цитаты (уровень 2)    

> Продолжение цитаты (уровень 1)    

Внешний вид, конечно, не очень, но может и пригодиться.

## Подсветка кода

Чтобы отметить фрагмент строки, выделить слово или фразу внутри строки, необходимо окружить его одинарными обратными апострофами «`». 
В отличие от блоков кода, кодовый фрагмент позволяет поместить код внутрь обычного абзаца текста.

 Это `слово` будет выделено
 
Для выделения в блоки - тройные:
```
Здесь может быть
Ваша реклама
```

Дополнительно можно задавать язык кода внутри блока, указав его после первых трех кавычек:

    ```html
        <input type="text">
    ```

    ```css
        body {
            margin: 0;
            padding: 0;
        }
    ```

    ```Python
        from timeit import Time
    ```

## Списки
Markdown поддерживает упорядоченные (нумерованные) и неупорядоченные (маркированные) списки.
Задать **маркированный** список можно несколькими символами `-`, `+` или `*`. 
```
- Уровень списка 1. Пункт 1.
- Уровень списка 1. Пункт 2.
- Уровень списка 1. Пункт 3.
```
- Уровень списка 1. Пункт 1.
- Уровень списка 1. Пункт 2.
- Уровень списка 1. Пункт 3.

Можно создавать многоуровневые списки. Каждый уровень отделяется **четырьмя** или **двумя** пробелами:
```
- Уровень списка 1. Пункт 3.
    - Уровень списка 2. Пункт 1.
        - Уровень списка 3. Пункт 1.
        - Уровень списка 3. Пункт 2.
           - Уровень списка 4. Пункт 1.
```
- Уровень списка 1. Пункт 3.
    - Уровень списка 2. Пункт 1.
      - Уровень списка 3. Пункт 1.
      - Уровень списка 3. Пункт 2.
         - Уровень списка 4. Пункт 1.
         
Для формирования **нумерованных** списков в качестве маркеров используются числа с точкой. 
`
1. Первый уровень списка 1.
2. Второй уровень списка 1.
3. Третий уровень списка 1.
`
## Ссылки
Либо просто вставить ссылку, либо дополнительно задать текст ссылки (пробела между скобками быть не должно):
```
Первый вариант вставки ссылок - это просто написать адрес сайта http://github.com
```
Первый вариант вставки ссылок - это просто написать адрес сайта http://github.com

Второй вариант записывается так: `[текст ссылки](адрес ссылки)`
```
[github.com](http://github.com)
```
[github.com](http://github.com)
    
[github(DOT)com]:http://github.com    
    
[:arrow_up:Оглавление](#Оглавление)
____


[:arrow_up:Оглавление](#Оглавление) 
