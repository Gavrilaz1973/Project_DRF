Задание 1
Для модели курса добавьте в сериализатор поле вывода количества уроков.

Задание 2
Добавьте новую модель «Платежи» со следующими полями:

пользователь,
дата оплаты,
оплаченный курс или урок,
сумма оплаты,
способ оплаты: наличные или перевод на счет.
Запишите в эту модель данные через инструмент фикстур или кастомную команду.

Задание 3
Для сериализатора модели курса реализуйте поле вывода уроков.

Задание 4
Настройте фильтрацию для эндпоинтов вывода списка платежей с возможностями:

менять порядок сортировки по дате оплаты,
фильтровать по курсу или уроку,
фильтровать по способу оплаты.
* Дополнительное задание
Для профиля пользователя сделайте вывод истории платежей, расширив сериализатор для вывода списка платежей.
Задание 1
Создайте новый Django-проект, подключите DRF и внесите все необходимые настройки.

Задание 2
Создайте следующие модели:

Пользователь:
все поля от обычного пользователя, но авторизацию заменить на email;
телефон;
город;
аватарка.
Курс:
название,
превью (картинка),
описание.
Урок:
название,
описание,
превью (картинка),
ссылка на видео.
Задание 3
Опишите CRUD для моделей курса и урока, но при этом для курса сделайте через ViewSets, а для урока — через Generic-классы.

Для работы контроллеров опишите простейшие сериализаторы.

Работу каждого эндпоинта необходимо проверять с помощью Postman.

Также на данном этапе работы мы не заботимся о безопасности и не закрываем от редактирования объекты и модели даже самой простой авторизацией.

* Дополнительное задание
Реализуйте эндпоинт для редактирования профиля любого пользователя на основе более привлекательного подхода для личного использования: Viewset или Generic.

Дополнительное задание, помеченное звездочкой, желательно, но не обязательно выполнять.
 
