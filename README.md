# planuml-diagram
diagram for muiv practice

# mkdocs-adding
1. Установка .py
2. Добавление через терминал пакета mkdocs
pip install mkdocs-material
3. Создание папок ru/en, добавление в них файла index.md с описанием процецссов

@startuml
Пользователь -> Разработчик: Создание заявки на изменение типового маршрута в СервисДеске
Разработчик --> Пользователь: Сообщение о принятии заявки в работу
Разработчик -> Пользователь: Внесение изменений и ожидание прохождения тестирования пользователем
Пользователь -> Разработчик: Сообщение о принятии выполненной работы, либо просьба о доработке
@enduml