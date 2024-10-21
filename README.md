# ML
## Guideline for git

   1. Форкаем данный репозиторий (В github)
   2. Клонируем данный репозиторий на ваш ПК (git clone https://github.com/TevenixLevelUps/ML)
   2. Жестко чет пишем
   3. Добавляем изменения в staging (git add .)
   4. Фиксируем прибыль (изменения) (git commit -m "Some title for commit.")
   5. Отправляем изменения в удаленный репозиторий (git push -u https://github.com/TevenixLevelUps/ML)
   6. Создаем PR в вашем удаленном github репозитории. Укажите ФИО и ссылку на ТГ.
   Будут вопросы - обращайтесь в группу левелапов дабы избежать повторяющихся вопросов. Стесняетесь - @ffandorin

## Task 1

Реализовать алгоритмы градинетного спуска (полный, стохастический, батчевый), протестировать их на нескольких моделях регрессии и сравнить результаты.

В качестве данных для обучения используйте какой-нибдуь небольшой датасет, типа California House Pricing или load_iris. Не забудьте разделить его данные на тренировочные и тестовые.

Поэксперементируйте с настройками. Протестируйте алгоритмы с различными значениями гиперпараметра (величины шага спуска), количествами итераций или критериями остановки, величинами батча.

Продемонстрируйте результаты работы с алгоритмами, например, путем оценки моделей с помощью метрик, построением графиков зависимости значеня функции потерь от количества итераций или количества итераций алгоритма перед срабатыванием критерия остановки и т.д.
