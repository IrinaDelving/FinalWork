В задаче требуется написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам.

Задаем первоначальный массив типа string с названием Array и размером - 5 элементов. Задаем новый массив типа string с названием newArray, в который мы поместим элементы, после выполнения проверки циклом. Выделяем память для первого и второго массива new string [5].

В метод ComparisonArray передаем оба массива и выполняем проверку условия: длина строки <=3. 
 Для этого перебираем каждый элемент массива array с помощью счетчика i. Если условие выполняется, помещаем элемент в переменную count нового массива (присваиваем элемент). После этого переменная count увеличивается на 1 и возвращается в цикл для проверки следующего элемента массива. Счетчик цикла i увеличивается на 1 итератором i++. Цикл повторяется до тех пор, пока не будет обработан (сравнен) последний элемент массива. 

В методе PrintArray выводим на консоль наш новый массив.