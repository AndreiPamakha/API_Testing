# API_Testing
Модуль посвящен тестированию API

# Практическое задание 7. Создание коллекции в Postman и кейсы для API

### Задание 1

В рамках задания вам необходимо протестировать все методы, которые представлены для сервиса https://petstore.swagger.io/ в Postman и создать соответствующие коллекции.

Документация формируется автоматически в инструменте Swagger, и очень часто именно такой формат используют на проекте. Ее создают backend-разработчики. Если на проекте документации нет, то вы можете предложить это сделать, потому что тестирование API лучше подключать еще до тестирования GUI, и на интеграционном уровне можно найти довольно критические баги.

Если вы захотите отправлять запросы в самом Swagger, то вам необходимо настроить авторизацию. Необходимо нажать кнопку Authorize и ввести в поле client_id значение тест. Также необходимо проставить чек-боксы для просмотра и редактирования домашних питомцев.

Обязательно используйте переменные для упрощения своей работы в Postman, например, для базового URL.

Обратите внимание на статус-коды, которые должны приходить в тестовой документации, на обязательные атрибуты, на особенности формата тела запроса. Мельчайшая неточность и ваш запрос вернется с ошибкой.

Помимо создания коллекции по всем методам вам также вам необходимо:

Написать тест, который проверяет статус код после удаления домашнего животного из базы
Создать несколько юзеров, используя метод createdWithArray
В теле запроса для создания питомца сделать динамические значения, которые будут автоматически генерироваться при отправке
Ссылку на коллекцию и выполненные задания пришлите в форме ниже. Не забудьте сделать коллекцию публичной и видимой для всего интернета

### Задание 2

Используя рекомендации из шаблона, напишите тестовые кейсы для тестирования запросов коллекции для 4 методов из блока store. Не забывайте, что проверки могут быть позитивные и негативные.
Используя следующую WSDL  создайте рабочую коллекцию в Postman, с помощью которых можно определить: валюту страны, полную информацию о стране и информацию о языке конкретной страны. Для быстрой работы с методами установите расширение Wizdler для браузера.

Проверьте следующий файл XML на наличие ошибок

<?xml version="1.0" encoding="UTF-8"?>
<note date="12/05/2022">
<to><name>Alena</to></name>
<lastname>Petrova</lastname>
<from>Alex</From>
<update=12/05/2022><update>
</note>

Решение оформите в гугл-таблице. Отдельная вкладка для каждого задания

## Решение 

1. Коллекция PetStore: https://www.postman.com/whitespar/workspace/petstore-swagger/collection/26532598-72d29882-a1a0-4e57-817a-17eb8810bc8b?action=share&creator=26532598
2. Тест-кейсы и проверка XML: https://docs.google.com/spreadsheets/d/1p8nwC3EKufEaYVg1FSqjpa3b7WVT7hpqkva0meT82w4/edit#gid=1982309468
 https://docs.google.com/spreadsheets/d/1p8nwC3EKufEaYVg1FSqjpa3b7WVT7hpqkva0meT82w4/edit#gid=1220596673


