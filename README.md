Финальный проект "Инженер по тестированию плюс"

Автоматизация теста к API

Для запуска тестов должны быть установлены пакеты pytest и requests Для запуска теста необходимо в файл configuration скопировить актуальный URL, в файле sendor_stand_request нажать кнопку Run Автоматизация теста к API Необходимо автоматизировать сценарий:

Клиент создает заказ. Проверяется, что по треку заказа можно получить данные о заказе. Шаги автотеста: Выполнить запрос на создание заказа. Сохранить номер трека заказа. Выполнить запрос на получения заказа по треку заказа. Проверить, что код ответа равен 200.