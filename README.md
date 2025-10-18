# Проект: разработка автотестов для поля name в запросе на создание набора.
 
- Перед запуском тестов необходимо удостовериться в наличии всех необходимых файлов:\
data.py, configuration.py, sender_stand_request.py и create_kit_name_kit_test.py
- Для запуска тестов должны быть установлены пакеты pytest и requests
- Запуск всех тестов выполняется командой pytest, а также запуском файла create_kit_name_kit_test.py в поддерживающей Python среде разработки

## Шаги для выполнения проекта:
1. Написать POST-запрос на создание нового пользователя и сохранение токена авторизации authToken.
2. Написать POST-запрос на создание личного набора для этого пользователя. Учесть передачу заголовка Authorization.
3. Написать функции для проверки позитивных и негативных сценариев чек-листа.
4. Запустить автотесты.
5. Упаковать папку с файлами configuration.py, data.py, sender_stand_request.py, create_kit_name_kit_test.py, README.md, .gitignore в ZIP-архив.

### Полезные ссылки
* [Документация к API Яндекс.Прилавок](https://e0865d98-579d-4b0d-9fd0-95393b047ff2.serverhub.praktikum-services.ru/docs/) (смотрим на адресс тестового сервера)

#### Автор проекта
[@aleksey-vysotsky](https://github.com/aleksey-vysotsky) \
va9105293171@yandex.ru
