# german-epic-characters-DB

В этом проекте с помощью графовой базы данных Neo4j собраны персонажи из трёх немецких эпических текстов. Пары встречасемости были изначально в формате .csv эти файлы мы превратили в базу данных.
Поскольку у нас встречаемость персонажей, о хранить мы будет максимально простую структуру (данных не очень много у нас):

1. Узлы Character (Персонаж) с атрибутами: name (имя персонажа) и text (название произведения).
2. Отношения INTERACTS (Встречаемость) с атрибутом weight (количество встречаемости в тексте рядом)

Для чего это вообще нужно? Для анализа сети персонажей. Это намного ужобнее хранитиь, чем кучу файлов .csv. Плюс, можно проводить операции над графами намного проще и не использовать что-то типо виснущего gephi.


Поиск элемента в базе данных
Сортировка или группировка или агрегация
Кроме этого 3 балла дают:

Какая-нибудь фишка вашей базы или Вам что-то понравилось на курсе
Например, Redis -- работа с разными типами данных значений, RediStack Mongo -- связь коллекций через ObjectId, полнотекстовый поиск Neo4j -- нахождение не только ближайшего соседа, нахождение кратчайшего пути до элемента, graph data science и т.д.

ИЛИ

Прикручиваете какой-нибудь сервис к своей базе: сайт, графики, интеграция с другими хранилищами, стриминг и т.д.
Оформление даёт дополнительный балл. Если вы выполнили всё в тетрадке .ipynb с использованием python-коннектора и тетрадка полностью рабочая или вы собрали ваш проект в проекте poetry или контейнеризации docker, в вашем проекте есть тестовые данные -- балл Ваш.
