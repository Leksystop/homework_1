# Инструкция для работы с Marckdown

## Выделение текста 

Чтобы выделить текст курсивом необходимо обрамить его звездочками(*) или знаком нижнего подчеркивания(_) Например, *вот так* или _вот так_

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками(** ) или двойным знаком нижнего подчеркивания.Например, **Вот так** или __вот так__.

Альтернативные способы выделения текста жирным или курсивом, нужны для того чтобы мы могли совмещать оба эти способа. Например, _текст может быть выделен курмивом и при это быть **полужирным**_.

## Списки 
Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+). Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пунскту просто пронумеровать.Например, вот так:
1. Первый пункт.
2. Второй пункт.

## Работа с изображениями 
Чтобы добавить картинку в текст необходимо использовать следующий синтаксис - ставим восклицательный знак, потом в квадратных скобках указываем текст, а в круглых - адрес файла с картинкой. Адрес относительный или абсолютный. Например, вот так:
! [привет, это крэш!](411px-Crash.png)

## Работа с ссылками 
Подразумевается, что по URL-адресу не существует ссылки еще на текст. Он следует в квадратные скобки. Для создания внутритекстовой гиперссылки необходимо использовать круглые скобки сразу после закрывающей квадратной. Внутри них необходимо указать URL-адрес. В них же возможно утвердить название, Назначение в кавычки, которое будет назначено назначением, но этот пункт не является обязательным.

  (https://github.com/Leksystop) или [мой гитхаб](https://github.com/Leksystop)
## Работа с таблицами 
Таблицы не являются частью Markdown, но многие обработчики, например Markdown Here и Github, имеют их. Они позволяют легко добавить таблицу в электронное письмо -- в других случаях для этого необходимо скопировать их из другого приложения.

Вертикальные линии обозначают столбцы.

| Таблицы       | Это                | Круто |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    | $1600 |
| столбец 2     | выровнен по центру |   $12 |
| зебра-строки  | прикольные         |    $1 |

Внешние вертикальные линии (|) не обязательны и нужны только, чтобы сам код Markdown выглядел красиво. Тот же код можно записать так:

Markdown | не такой | красивый
--- | --- | ---
*Но выводится* | `так же` | **клево**
1 | 2 | 3

## Цитаты 
Для цитирования в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой абзаца. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитаты). Для их использования используются дополнительные уровни цитирования («>»). Цитаты в Markdown могут привести к обнаружению множественных элементов. Цитаты на языке Markdown :

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.
>Второй параграф.
## Вложение цитаты в цитату

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
>
>Первый уровень цитирования

## Заключение 
