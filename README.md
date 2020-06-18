МИНИСТЕРСТВО НАУКИ  И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ  

Федеральное государственное автономное образовательное учреждение высшего образования  

"КРЫМСКИЙ ФЕДЕРАЛЬНЫЙ УНИВЕРСИТЕТ им. В. И. ВЕРНАДСКОГО"  

ФИЗИКО-ТЕХНИЧЕСКИЙ ИНСТИТУТ  

Кафедра компьютерной инженерии и моделирования
<br/><br/>
### Отчёт по лабораторной работе № 7<br/> по дисциплине "Программирование"
<br/>
​Cтудента 1 курса группы ПИ-б-о-192(2)<br/>
Золотого Александра Витальевича<br/>
направления подготовки 09.03.04 "Программная инженерия"  
<br/>


<br/>
<table>

<tr><td>Научный руководитель<br/> старший преподаватель кафедры<br/> компьютерной инженерии и моделирования</td>

<td>(оценка)</td>

<td>Чабанов В.В.</td>

</tr>

</table>

<br/><br/>

​

Симферополь, 2020

<br/>

## Лабораторная работа №7.Изучение базовых возможностей IDE Qt Creator

***Цель :*** изучить основные возможности создания и отладки программ в IDE Qt Creator.

***Ход работы:***

------
**Как создать консольное приложение С++ в IDE Qt Creator без использования компонентов Qt?**
Во вкладке проекты нажимаем на создать.В появившемся окне выбираем "Проект без QT" и "Приложение на языке C++#.

![](https://github.com/alexzolfff/lab7/blob/master/img/Screenshot_1.png?raw=true)

Рисунок 1. Выбор настроуки шаблона нового проекта.

Далее даем название проекту и указываем его рассположение.Путь к проекту не должен содержать русских символов, т.к. это может привести к ошибкам во время сборки.

![](https://github.com/alexzolfff/lab7/blob/master/img/Screenshot_2.png?raw=true)

Рисунок 2. Размещение проекта
      
Во вкладке " Система сборки" оставляем настройки по-умолчанию.

![](https://github.com/alexzolfff/lab7/blob/master/img/Screenshot_3.png?raw=true)

Рисунок 3. Настройка системы сборки

Так же поступаем и во вкладках " Выбор комплекта" и "Управление проектом"

![](https://github.com/alexzolfff/lab7/blob/master/img/Screenshot_4.png?raw=true)

Рисунок 4. Выбор комплекта

![](https://github.com/alexzolfff/lab7/blob/master/img/Screenshot_5.png?raw=true)

Рисунок 4. Управление проектом

В-конце концов,проект создан.

![](https://github.com/alexzolfff/lab7/blob/master/img/Screenshot_6.png?raw=true)

Рисунок 5. Проект

**Как изменить цветовую схему (оформление) среды?**

В верхней строке выбираем "Инструменты" и в них параметры.Откроется следующее окно:

![](https://github.com/alexzolfff/lab7/blob/master/img/Screenshot_1.1.png?raw=true)

Рисунок 6. Параметры

Во вкладке "Среда" настраиваем нужные парвметры.

![](https://github.com/alexzolfff/lab7/blob/master/img/Screenshot_2.1.png?raw=true)

Рисунок 7. Изменение оформления среды

**Как закомментировать/раскомментировать блок кода средствами Qt Creator?**   

Чтобы закомментировать/раскомментировать блок кода средствами Qt Creator нужно:     
1 способ: выделить нужный блок и нажать Ctrl+/; 
2 способ: выделить нужный блок и нажать  правую кнопку мыши; в открвшемся окне выбираем нужный параметр.

**Как открыть в проводнике Windows папку с проектом средствами Qt Creator?**

1 способ: в QT Creator нажать Ctrl+O;
2 способ:  верхней строке выбираем "Файл" и в нем нажимаем на "Открыть файл или проект...".
Откроется следующее окно:

![](https://github.com/alexzolfff/lab7/blob/master/img/scr4.png?raw=true)

Рисунок 8. Список вкладок "Файл"

**Какое расширение файла-проекта используется Qt Creator?**

В Qt Creator используется расширение ".pro" для файла-проекта.

**Как запустить код без отладки?**

1 способ: сочетание клавиш
2 способ: нажать на зеленую треугольную кнопку в левом нижнем углу

![](https://github.com/alexzolfff/lab7/blob/master/img/9.png?raw=true)

Рисунок 9. Кнопка запуска без отладки

**Как запустить код в режиме отладки?**

1 способ: сочетание клавиш
2 способ:нажать на зеленую треугольную кнопку с "жучком"  в левом нижнем углу

![](https://github.com/alexzolfff/lab7/blob/master/img/9.png?raw=true)

Рисунок 10. Кнопка запуска с отладки
**Как установить/убрать точку останова (breakpoint)?**

1 способ: нажать F9;
2 способ: нажать павой кнопкой мыши на нужную строчку и выбрать нужный параметр.

![](https://github.com/alexzolfff/lab7/blob/master/img/11.jpg?raw=true)

Рисунок 11. Установка точки установа


**Создаем программу с следующим кодом:**

![](https://github.com/alexzolfff/lab7/blob/master/img/код.png?raw=true)

Рисунок 12. Код программы

**Переключаемся в конфигурацию сборки «Отладка»;**
**Устанавливаем breakpoint на 5, 6 и 7 строках;**

![](https://github.com/alexzolfff/lab7/blob/master/img/код%20с%20точками.png?raw=true)

Рисунок 13.Установка точек останова.

**Запускаем приложение щелкнув по кнопке с изображением жука .**

![](https://github.com/alexzolfff/lab7/blob/master/img/1%20точка.png?raw=true)

Рисунок 14. Первая точка останова

**Используем эту же кнопку для перехода к следующей точке останова;**

![](https://github.com/alexzolfff/lab7/blob/master/img/2%20точка.png?raw=true)

Рисунок 15. Вторая точка останова

**Какое значение содержит переменная i в 5й строке?**

5

**Какое значение содержит переменная d в 6й строке?**

9.2671142210660936e-317

**Какие значение содержатся в переменных i и  d в 7й строке?**

![](https://github.com/alexzolfff/lab7/blob/master/img/в%207%20строке.png?raw=true)

Рисунок 16. Значение аеременных в  7 строке

**Совпадают ли эти значения с теми, что вы получали в MSVS для соответствующих типов?**

Значения совпадают.

**Закрываем проект и переходим на вкладку «Начало» => «Примеры»;**

![](https://github.com/alexzolfff/lab7/blob/master/img/примеры.png?raw=true)

Рисунок 17. Вкладка Начало

**Выбераем проект «Calculator Form Example».**

![](https://github.com/alexzolfff/lab7/blob/master/img/калькулятор.png?raw=true)

Рисунок 18.Проект «Calculator Form Example»

**Изучаем описание проекта в открывшемся окне;**

![](https://github.com/alexzolfff/lab7/blob/master/img/изучите.png?raw=true)

Рисунок 19. Проект в открывшемся окне

**Переходим на вкладку «Редактор» и запускаем сборку проекта;**

В инспекторе проекта выберите файл «main.cpp».

![](https://github.com/alexzolfff/lab7/blob/master/img/show.png?raw=true)

Рисунок 20. Выбераем файл «main.cpp».

В этом файле устанавливаем курсор на слово «show» в строке calculator.show(); и нажмаем F1.

![](https://github.com/alexzolfff/lab7/blob/master/img/справка.png?raw=true)

Рисунок 21. Вывод справки

**В инспекторе проекта выбераем файл «Формы» => «calculatorform.ui» ;**

![](https://github.com/alexzolfff/lab7/blob/master/img/дизайн.png?raw=true)

Рисунок 22. Вкладка Дизайн

**На форме заменяем английский текст на русский. Пересобираем проект.**

![](https://github.com/alexzolfff/lab7/blob/master/img/калькулятор%20пересбор.png?raw=true)

Рисунок 23. Пересобранный проект

***Вывод:*** в ходе лабораторной работы я ознакомился сосновными возможностями QT Creator, c понятием точки останова и научился ими пользоваться.Кроме того я научился пользоваться отладкой в данной среде.
