# Cars - тестовое задание для LevelApp


## Замечания разработчика

### Выделение предметной области (domain)

Так как приложение не имеет какой-либо логики, выделение предметной области усложнит понимание
кода

### Создание моделей данных, не зависимых от POJO

Создание таких моделей значительно повысит гибкость проекта и в большей степени
обезопасит его от изменение со стороны бэкенда. Однако здесь они не используются для экономии 
времени в краткосрочной перспективе

### Прямая зависимость от слоя данных на presentation

Наличие прямой зависимости от слоя данных легко устранить, перенеся в конструктор соответствующие
параметры и при желании подключив какой-либо DI фреймворк

### Внедрение зависимостей внутри ViewModels

Сделано для экономии времени. Чтобы избавиться от этого, можно выполнить то же, что было указано 
выше