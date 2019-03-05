# Python

## Основы. Простейшая работа с данными

@snap[south]
Лекция 1.0
@snapend

---

Основные типы

+++

```Python
var_1 = 1
var_2 = True
var_3 = 0.5

var_4 = "Python"
var_5 = [1,2,3,4,5]
```

+++

Простейшие типы данных можно условно разбить на несколько данных.

+++

@snap[north]
Типы переменных
@snapend

@snap[west]
@ul[](false)
- __None__
- __Логический__ (Boolean type)
- __Числа__ (Numeric type)
	@ul[](false)
	- `Int` - целые числа
	- `float` - числа с плавающей точкой
	- `complex` - комплексные числа
	@ulend
@ulend
@snapend

+++

@snap[north]
Типы переменных
@snapend

@snap[west]
@ul[square-bullets](false)

* __Списки__ (Sequence Type)
	
	@ul[square-bullets](false)
	- `list` - список
	- `tuple` - кортеж
	- `range` - диапазон
	@ulend

* __Строки__ (Text sequence type)
	
	@ul[square-bullets](false)
	- `str` - строчный тип
	@ulend

* __Словари__ (Mapping Types)

	@ul[square-bullets](false)
	- `dict` - словарь
	@ulend

@ulend

@snapend

+++

@snap[north]
Типы переменных
@snapend

@snap[west]
@ul[](false)
- __Множества__ (Set Types)
	@ul[](false)
	- `set` - множество
	- `frozenset` - константное множество
	@ulend
- __Бинарные списки__ (Binary Sequence Types)
	@ul[](false)
	- `bytes` - байты
	- `bytearray` - массивы байт
	- `cmemoryview` – специальные объекты для доступа к внутренним данным объекта через protocol buffer
	@ulemd
@ulend

@snapend

+++

@snap[north]
Типы переменных
@snapend

@snap[west]



@snapend

+++

Списки

+++

@snap[north-west]
List
@snapend

@snap[west]
Списки - упорядоченные коллекции объектов произвольного типа. В программировании - это классичесткая __структура данных__. В Python - это самый доступный способ хранить объекты в упорядоченном виде
@snapend

+++

@snap[north-west]
Методы списка
@snapend

@snap[west]
@ol
- Метод `.append(x)` добавляет новый объект `x` в коллекцию в конец коллекции
- Метод `.remove(x)` удаляет из коллекции объект `x`
- Метод `.pop(i)` удаляет из списка элемент под номером `i` и возвращает этот объект
- Функция `len(l)` возвращает размер списка `l`
@olend
@snapend

+++

```Python
l = [] 

l.append(10)
l.append("banana")
l.append(True)
l.pop(0)
print(l)
# ['banana', True]
```
@[1](Создаем пустой список)
@[3-5](Добавляем в него элементы)
@[6](Удаляем из списка элемент с индексом 0 - первый элемент)

+++

@snap[north-west]
Работа с индексами
@snapend

@snap[west]
Индекс объекта в списке - его порядковый номер в списке. Обращение к элементам массива возможно через имя списка, в котором хранится объект, и его индексу. Индекс указывается в квадратных скобках `[` и `]`.
@snapend

+++

```Python
l = ["Hello", "my", "old", "friend"]

print(l[3])
#'friend'
```

---

Строки

+++

@snap[north-west]
Strings
@snapend

@snap[west]
__Строчки__ - простейший класс в Python для работы с символьными значениями. Грубо говоря это список символов. Этот класс имеет особое важное значение практически в любом ЯП
@snapend

+++

```Python
grettings = "Oh, hi Mark"

print(grettings[0])
# 'O'

print(len(greetings))
# 11
```

@[1](Создаем строчку с помощью литералов)
@[3](Можно обращаться к элементам строчки через индексы)
@[5](Длину строки можно определить как и для списков)

+++

@snap[north-west]
Методы строк
@snapend

@snap[west]
@ol
- `.replace(tmp, sub)` - Замена в строке шаблона `tmp` на `sub`
- `.split(div)` - Разделяет строку на подстроки по разделителю `div`
- `.find(s)` - возвращает индекс подстроки s в строке. Если такой подстроки нет - возвращает -1
@olend
@snapend


