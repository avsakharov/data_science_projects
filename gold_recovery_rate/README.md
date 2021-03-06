# Оценка коэффициента восстановление золота из руды

## Данные

Для выполнения проекта были предоставлены несколько датафреймов. Названия признаков в датафреймах кодировались следующим образом: [этап].[тип_параметра].[название_параметра]. Этапы: флотация, первичная очистка, вторичная очистка, финальные характеристики. Типы параметров: сырье, продукт, текущее состояние, расчетная характеристика. Параметры: сырье, флотационные реагенты, отвальные хвосты, объем воздуха, уровень жидкости, размер гранул и т.д.

## Задача

Необходимо подготовить прототип модели машинного обучения по заказу компании, разрабатывающей решения для увеличения эффективности работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды, используя данные с параметрами добычи и очистки. Качество работы алгоритма определялось по метрике sMAPE.

## Используемые библиотеки
*pandas*, *numpy*, *sklearn*, *plotly*
