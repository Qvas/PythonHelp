fffffffff# #################################  Типы данных  ##################################
# int (Числа)
number = 22

# float (Дробные числа)
fnumber = 5.7

# str (Текст)
name = "Pavel"

# bool (True или False)
status= True

# #################################  Импорт  ##################################
# Импорт можно писать только в начале кода
# Для импорта используйте import, пример:
import math

# #################################  Вывод на экран  ##################################
# Экранирование
print("Текст \"который\" выводится")  # где \" - экранирование, используется в основном для кавычек

# Перевод строки
print('Привет \n мир') # где \n - спец. символ для переноса строки

# Конкатенация
print("Привет, меня зовут " + name + "!")
print ( "Мне " + str(number) + " года!") # где str() обязательное значение для того чтобы не возникало ошибок с типами значений
#Для функций f и range результат равнозначен применению str():
print(f"Привет {name}!")

# Функция input
name = input("Введите своё имя: ") # Где input вопрос к пользователю, ответ которого он введёт на клавиатуре
age = input("Введите свой возраст: ") # В переменную age записывается число введённое пользователем
print("Привет, " + name + "!")
print("Тебе уже " + age + " лет!") # Обратите внимание, тут не нужно было вводить str(), потому что всё что пишет пользователь в input строка возврощает

# ################################# Цыфры  ##################################
# умножение - "*"
# деление - "/"
# плюс - "+"
# минус - "-"
# возведение в степень - "**"
# деление по модулю - "%"
# унарный минус - меняет знак числа, пример: "a = -a" то есть если a будет ровно 10, на экране выведется -10
# округление - "round", пример: 
    ########################
    a = 5.65
    print(round(a))
    ########################
#   Есть ещё 2 функции округления, но они требуют импортировать math, Пример:
#   первая это "floor" - Это принудительно в меньшую сторону
#   вторая это "ceil" - Это принудительно в большую сторону сторону
#
# вычисления числа Пи возможно только с импортом math
print(math.pi) # Где мы обращаемся к math с помощью math и просим число Пи с помощь pi
# 
# #################################  Разбор калькулятора  ##################################
# Для примера напишем код калькулятора
what = input("Что делаем? (+,-): ") # Задаём вопросы пользователю

a = float(input ("Введите первое число: "))
b = float(input ("Введите второе число: "))

# Обращаю внимание, всё что находится под if(под условием) должно быть под Tab'ом
# "if" - означает условие
# "elif" - второе условие, если первое не подошло
# "else" - Выполнить, если не одно из условий не подошло

if what == "+": # Где "==" проверка ровняется ли значение таковым
# Если проверка проходит успешно то выполняем код
    c = a + b 

elif what == "-": # Где "==" проверка ровняется ли значение таковым
    c = a - b

else: print("Ошибка, выбрана неверная операция") 

print("Результат: " + c)
##################################
# 
Со временем список будет дополнятся

