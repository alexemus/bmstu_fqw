# bmstu_fqw
## Final Qualification Work of BMSTU DS Course
## Выпускная квалификационная работа по курсу "DataScience" образовательного центра МГТУ им. Н.Э. Баумана 
## Слушатель Александр Минин


Задачи:
* Изучить теоретические основы и методы решения поставленной задачи.
* Провести разведочный анализ предложенных данных. Необходимо нарисовать гистограммы распределения каждой из переменной, диаграммы ящика с усами, попарные графики рассеяния точек. Необходимо также для каждой колонке получить среднее, медианное значение, провести анализ и исключение выбросов, проверить наличие пропусков.
* Провести предобработку данных (удаление шумов, нормализация и т.д.).
* Обучить нескольких моделей для прогноза модуля упругости при растяжении и прочности при растяжении. При построении модели необходимо 30% данных оставить на тестирование модели, на остальных происходит обучение моделей. При построении моделей провести поиск гиперпараметров модели с помощью поиска по сетке с перекрестной проверкой, количество блоков равно 10.
* Написать нейронную сеть, которая будет рекомендовать соотношение матрица-наполнитель.
* Разработать приложение с графическим интерфейсом или интерфейсом командной строки, которое будет выдавать прогноз, полученный в задании 4 или 5 (один или два прогноза, на выбор учащегося).
* Оценить точность модели на тренировочном и тестовом датасете.
* Создать репозиторий в GitHub / GitLab и разместить там код исследования. Оформить файл README.


Тема: **Прогнозирование конечных свойств новых материалов (композиционных материалов).**

> Описание: 
> Композиционные материалы — это искусственно созданные материалы, состоящие из нескольких других с четкой границей между ними. 
> 
> Прогнозирование конечных свойств новых материалов - это процесс использования вычислительных методов и алгоритмов для оценки и предсказания свойств >материалов, которые могут быть использованы в различных отраслях промышленности.
>
>В последние годы прогресс в области компьютерного моделирования и анализа данных позволил значительно ускорить и улучшить процесс разработки новых >материалов. С помощью компьютерных моделей можно изучать физические и химические свойства материалов на микро- и макроуровнях, а также оценивать их >поведение в различных условиях.
>
>Для прогнозирования свойств новых материалов используются различные вычислительные методы, такие как методы молекулярной динамики, методы первых принципов и методы машинного обучения. Эти методы позволяют изучать и предсказывать такие свойства материалов, как механические свойства, теплопроводность, >проводимость и магнитные свойства.
>
>Прогнозирование конечных свойств новых материалов имеет большое значение для промышленности, поскольку позволяет значительно сократить время и затраты на  разработку новых материалов. Благодаря этому можно получить материалы с оптимальными свойствами, которые будут использоваться в различных отраслях >промышленности, таких как авиационная, энергетическая, медицинская и другие.
> 
> Даже если мы знаем характеристики исходных компонентов, определить характеристики композита, состоящего из этих компонентов, достаточно проблематично. Для решения этой проблемы есть два пути: физические испытания образцов материалов, или прогнозирование характеристик. Суть прогнозирования заключается в >симуляции представительного элемента объема композита, на основе данных о характеристиках входящих компонентов (связующего и армирующего компонента). Созданные прогнозные модели помогут сократить количество проводимых испытаний, а также пополнить базу данных материалов возможными новыми характеристиками >материалов, и цифровыми двойниками новых композитов.
