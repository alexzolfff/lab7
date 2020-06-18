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

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_1.png)

Рисунок 1. Выбор настроуки шаблона нового проекта.

Далее даем название проекту и указываем его рассположение.Путь к проекту не должен содержать русских символов, т.к. это может привести к ошибкам во время сборки.

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_2.png)

Рисунок 2. Размещение проекта
      
Во вкладке " Система сборки" оставляем настройки по-умолчанию.

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_3.png)

Рисунок 3. Настройка системы сборки

Так же поступаем и во вкладках " Выбор комплекта" и "Управление проектом"

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_4.png)

Рисунок 4. Выбор комплекта

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_5.png)

Рисунок 4. Управление проектом

В-конце концов,проект создан.

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_6.png)

Рисунок 5. Проект

**Как изменить цветовую схему (оформление) среды?**

В верхней строке выбираем "Инструменты" и в них параметры.Откроется следующее окно:

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_1.1.png)

Рисунок 6. Параметры

Во вкладке "Среда" настраиваем нужные парвметры.

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_2.1.png)

Рисунок 7. Изменение оформления среды

**Как закомментировать/раскомментировать блок кода средствами Qt Creator?**   

Чтобы закомментировать/раскомментировать блок кода средствами Qt Creator нужно:     
1 способ: выделить нужный блок и нажать Ctrl+/; 
2 способ: выделить нужный блок и нажать  правую кнопку мыши; в открвшемся окне выбираем нужный параметр.

**Как открыть в проводнике Windows папку с проектом средствами Qt Creator?**

1 способ: в QT Creator нажать Ctrl+O;
2 способ:  верхней строке выбираем "Файл" и в нем нажимаем на "Открыть файл или проект...".
Откроется следующее окно:

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/Screenshot_4.1.png)

Рисунок 8. Список вкладок "Файл"

**Какое расширение файла-проекта используется Qt Creator?**

В Qt Creator используется расширение ".pro" для файла-проекта.

**Как запустить код без отладки?**

1 способ: сочетание клавиш
2 способ: нажать на зеленую треугольную кнопку в левом нижнем углу

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/9.png)

Рисунок 9. Кнопка запуска без отладки

**Как запустить код в режиме отладки?**

1 способ: сочетание клавиш
2 способ:нажать на зеленую треугольную кнопку с "жучком"  в левом нижнем углу

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/9.png)

Рисунок 10. Кнопка запуска с отладки
**Как установить/убрать точку останова (breakpoint)?**

1 способ: нажать F9;
2 способ: нажать павой кнопкой мыши на нужную строчку и выбрать нужный параметр.

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/11.jpg)

Рисунок 11. Установка точки установа


**Создаем программу с следующим кодом:**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D0%BA%D0%BE%D0%B4.png)

Рисунок 12. Код программы

**Переключаемся в конфигурацию сборки «Отладка»;**
**Устанавливаем breakpoint на 5, 6 и 7 строках;**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D0%BA%D0%BE%D0%B4%20%D1%81%20%D1%82%D0%BE%D1%87%D0%BA%D0%B0%D0%BC%D0%B8.png)

Рисунок 13.Установка точек останова.

**Запускаем приложение щелкнув по кнопке с изображением жука .**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/1%20%D1%82%D0%BE%D1%87%D0%BA%D0%B0.png)

Рисунок 14. Первая точка останова

**Используем эту же кнопку для перехода к следующей точке останова;**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/2%20%D1%82%D0%BE%D1%87%D0%BA%D0%B0.png)

Рисунок 15. Вторая точка останова

**Какое значение содержит переменная i в 5й строке?**

5

**Какое значение содержит переменная d в 6й строке?**

9.2671142210660936e-317

**Какие значение содержатся в переменных i и  d в 7й строке?**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D0%B2%207%20%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B5.png)

Рисунок 16. Значение аеременных в  7 строке

**Совпадают ли эти значения с теми, что вы получали в MSVS для соответствующих типов?**

Значения совпадают.

**Закрываем проект и переходим на вкладку «Начало» => «Примеры»;**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80%D1%8B.png)

Рисунок 17. Вкладка Начало

**Выбераем проект «Calculator Form Example».**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D0%BA%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80.png)

Рисунок 18.Проект «Calculator Form Example»

**Изучаем описание проекта в открывшемся окне;**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D0%B8%D0%B7%D1%83%D1%87%D0%B8%D1%82%D0%B5.png)

Рисунок 19. Проект в открывшемся окне

**Переходим на вкладку «Редактор» и запускаем сборку проекта;**

В инспекторе проекта выберите файл «main.cpp».

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/show.png)

Рисунок 20. Выбераем файл «main.cpp».

В этом файле устанавливаем курсор на слово «show» в строке calculator.show(); и нажмаем F1.

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D1%81%D0%BF%D1%80%D0%B0%D0%B2%D0%BA%D0%B0.png)

Рисунок 21. Вывод справки

**В инспекторе проекта выбераем файл «Формы» => «calculatorform.ui» ;**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D0%B4%D0%B8%D0%B7%D0%B0%D0%B9%D0%BD.png)

Рисунок 22. Вкладка Дизайн

**На форме заменяем английский текст на русский. Пересобираем проект.**

![](https://github.com/MiladaKrapivina/LabWorks/blob/master/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%207/SkreenShot/%D0%BA%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80%20%D0%BF%D0%B5%D1%80%D0%B5%D1%81%D0%B1%D0%BE%D1%80.png)

Рисунок 23. Пересобранный проект

***Вывод:*** в ходе лабораторной работы я ознакомился сосновными возможностями QT Creator, c понятием точки останова и научился ими пользоваться.Кроме того я научился пользоваться отладкой в данной среде.
