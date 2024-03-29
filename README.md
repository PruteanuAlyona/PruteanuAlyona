# Итоговая контрольная работа

**ЗАДАЧА**
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

*АЛГОРИТМ РЕШЕНИЯ ЗАДАЧИ*
1. Делаем перебор значений из исходного массива
2. Проверяем каждое значение из массива на соответствие условию: длина строки меньше или равна трем.
3. Если строка удовлетворяет условию кладем значение в новый массив.
4. Повторяем пункты 2 и 3 до тех пор, пока не достигнем конца исходного массива.
5. Возвращаем новый заполненый массив как результат.

![Блок-схема алгоритма](Blok-shema.jmg)

*Как работать?*
* Для запуска программы перейдите в папку Control work, выберите файл Program.cs и запустите команду через терминал:

_dotnet run_

* Затем введите значение через пробел, например:

_[“Hello”, “2”, “world”, “:-)”]_

* Пример вывода программы будет выглядеть так:

_[“2”, “:-)”]_
