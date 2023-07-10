Обо мне
Привет! Меня зовут Лена, я начинающий аналитик данных. В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

Навыки и технологии
Инструменты анализа данных: SQL, Excel
Системы управления базами данных: PostgreSQL


Проекты

Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра

Что нужно было сделать:

Задача №1 Проанализировать основные метрики кинотеатра и сделать выводы о предоставленных для анализа данных
Задача №2. Создать калькулятор юнит-экономики и понять, насколько оптимальной является текущая модель работы кинотеатра.
Как решала(-а):
1. На основ полученных данных были построены сводные таблицы в Excel с основными показателями (динамика кол-ва подписчиков и просмотров, распределение дат первых просмотров), также полученные данные были визуализированы
2. Был построен калькулятр юнит-экономики, при помощи которого была рассчитана эюнит-экономика при текущей схеме работы кинотеатра, а также расчитана модель to-be для мыхода на 25% маржинальность.

[Проект 1. Онлайн-кинотеатр.xlsx](https://github.com/Elena1Prokopeva/Portfolio/files/12006076/1.-.xlsx)

Выводы (итоги):

Итог №1 Первый и последний месяцы данных являются нерелевантными для анализа, так как содержат информацию только за несколько дней этих месяцев. Наибольшую активность пользователи показывают в летний период.
Итог №2 Текущая модель работы онлайн-кинотеатра неэффективна (маржинальность -94%). Для выхода на 25% маржинальность необходимо минимизировать объем скидок, пересмотреть цену подписки в большую сторону, а также снизить расхоы на привлечение новых подписок



Проект 2: Моделирование изменения балансов студентов

Что нужно было сделать:

Задача №1 Построить на основее хранящихся в разных БД данных движение балансов уроков студентов онлайн-школы и на основе первых 1000 результатов проверить валидность данных
Задача №2 Создать визуализацию данных по изменеию балансов студентов в течение года и сделать на ее основе выводы
Как решала(-а): 
Были предоставлены отдельные базы с данными по проведенным урокам и данными по платежам студентов. При помощи запоосов SQL были выделены данные о всех пополнениях балансов уроков учениками и всех списаниях с баланса учеников уроков по дням. На каждый день был выведен баланс уроков как разница между накопленными на дату пополнениями и списанием. На промежуточном этапе были выведены и проанализированы 1000 первых строк в разрезе учеников и дат для анализа корректности данных и на основе этого подготовлены вопросы к дата-инженерам. По итоговым данным в разрезе только дат была построена визуализации, отражающая динамику пополнений, списания и балансов всех учеников за год.

[Проект 2. Онлайн-школа.xlsx](https://github.com/Elena1Prokopeva/Portfolio/files/12006231/2.-.xlsx)

Выводы (итоги):

Итог №1 По некоторым пользователям были выявлены даты, в которые у них наблдался отрицательный баланс. Были сформулированы вопросы к дата-инженерам о корреектности отображения данных в БД
Итог №2 На основе анализа получившейся визуализации было выявлено, что накопленная сумма пополнений баланса, и накопленная сумма списания уроков постепенно увеличивались в течение 2016 года. За счет того, что увеличение накопленной суммы пополнений баланса происходило в большей степени, чем изменение количества списанных уроков, общая сумма баланса уроков также постепенно увеличивалась в течение года. Также суммарный баланс всегда был положительным, что говорит о том, что выявленные по отдельным пользователям отрицательные балансы в некоторые даты не носят массового критичного характера.

Контактная информация
Email: lena.pr96@gmail.com
