# 56-57-58-59

ПАРАГРАФ 56

1 Целочисленные типы данных
Дробные типы данных 
Символьные типы данных 
Логические типы данных 
Идентификационные типы данных

2 Во многих языках программирования есть несколько целочисленных и вещественных типов данных, потому что в современных компьютерах целые и вещественные числа представляются по-разному:

Целое число может быть представлено абсолютно точно, а вещественное — неизбежно с некоторой конечной погрешностью, которая определяется свойствами транслятора. 
Набор операций над целыми и вещественными числами различается. Например, операции сложения целых и вещественных чисел представляются разными машинными командами. 
Реализация операций над вещественными числами сложнее с аппаратной точки зрения, поэтому в ряде архитектур вещественные числа вообще могут отсутствовать.

3 Символьная переменная отличается от строковой тем, что символьная всегда содержит ровно один символ, а строковая содержит строку из нескольких символов. 

4 В логические переменные записываются данные, которые могут принимать только два значения: True (истина) и False (ложь).

5 Приоритет операций — формальное свойство операции, влияющее на очерёдность её выполнения в выражении с несколькими различными операторами при отсутствии явного (с помощью скобок) указания на порядок их вычисления. 

6 Если операции имеют одинаковый приоритет, то они выполняются по очереди слева направо.

7 Скобки в выражениях используются для того, чтобы установить очерёдность выполнения операций. Они показывают, что действия внутри них выполняются в первую очередь.

8 В выражении можно свободно смешивать два или более типа данных, при условии их совместимости друг с другом, иначе будет ошибка.

9 Я НЕ БУДУ ИЗУЧАТЬ ПАСКАЛЬ!!!!

10 Проблема вычисления остатка от деления в различных языках программирования заключается в том, что оператор вычисления остатка (например, %) действует верно для положительных значений аргумента, но для отрицательного делимого и положительного делителя он даёт отрицательный результат. 

Например, 17 % 5 == 2, но -17 % 5 == -2. Это может приводить к ошибкам при использовании оператора для вычисления хэшей, индексов в кольцевом буфере, а также для представления отношения эквивалентности.

11 Операция возведения в степень выполняется путём многократного умножения числа на себя. Нужно умножить число само на себя столько раз, сколько указано в показателе степени. В пайтоне - 2 ** 2 = 4,  2 ** 4 = 16

12 abs(x) — абсолютное значение x
sin(x) — синус x
cos(x) — косинус x
tg(x) — тангенс x

13 Чтобы выполнить округление к ближайшему целому в Python, можно использовать функцию round()

14 Случайные числа — это искусственно полученная последовательность реализаций случайной величины с заданным законом распределения.

15 К примеру подбросить монетку.

16 Отличие псевдослучайного числа от случайного состоит в том, что оно получено путём вычислений по некоторому алгоритму, как следствие, для генераторов псевдослучайных чисел возможно предсказать, какое число будет сгенерировано.

17 random.randint(a, b)  random.random()



ПАРАГРАФ 57


1 Основное отличие разветвляющихся алгоритмов от линейных заключается в том, что в разветвляющихся алгоритмах последовательность выполнения команд зависит от соответствия заявленному условию, а в линейных — все действия выполняются последовательно друг за другом.

2 Сложность задачи.
Нелинейные зависимости.
Ограничения линейных алгоритмов.
Неоднородные данные.

3 ХЗ

4 Тк значения вернутся обратно.

5 Полный - после проверки на True идет условие записанное после else, в неполной же форме действию переходит к следующему оператору.

6 В логическых выражениях обозначается как 0, 1 (True, False), в обычных = и !=
 
7 Сложное условие — это условие, состоящее из нескольких простых условий (отношений), связанных с помощью логических операций.
 
8 Порядок вычисления в сложном условии определяется следующим образом:

В выражениях со скобками первым выполняется действие в скобках, а затем действия вне скобок слева направо. 
В выражениях без скобок сначала выполняют по порядку слева направо умножение и деление, а лишь затем — сложение и вычитание. 
Если в выражение входит большое количество действий, то в нём выделяют блоки — части выражения между знаками сложения и вычитания, не входящими в скобки. Каждый блок решают отдельно, а затем выполняют сложение или вычитание слева направо. 

9 Операторы выбора позволяют принять программе решение, основываясь на истинности или ложности условия. 
 
10 неа 
  
11 Чтобы записать в операторе выбора на Python, что нужно делать, если ни один вариант не подошёл, можно использовать заключительный блок под оператором else. Если ни одно из условий для частей if и elif не выполняется, то срабатывает этот блок (если он существует). 
 
12 хз
