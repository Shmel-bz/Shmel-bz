Перекрестила экран перед отправкой
# Шмелева Оксана, 22-я когорта — Финальный проект. Инженер по тестированию плюс
# Привет, я Шмелева Оксана Олеговна 22 когорта. Вторая часть дипломного проекта
нашла публичный ключ, вставила, обновила урл, логины пароли и поехали запросы (кони чуть было не двинула пока вспоминала где этот ключ и с чем его едят)
# Задание 1 и 2 работа с БД
 Задание1. смотрим что там у курьера, сколько заказов(для этого я пересоздала курьера и оформила заказ в постман)
 Задание2. проверим статусы заказов (Из за бага, который дублирует наши заказы при принятии его курьером, мы видим один и тот айди заказа дважды. Наплодим заказы через Постман (шт3-4). Проверяем статусы, пока заказ не принят 0 (и айди не задваевается), принял курьер 1 (задвоение+увидим увеличение rows) и удаление\отмена заказа -1 (не задваевается) и завершаем 2 (все ок) )
 

# Автотест 
Шаги автотеста:
Выполнить запрос на создание заказа.
Сохранить номер трека заказа.
Выполнить запрос на получения заказа по треку заказа.
Проверить, что код ответа равен 200
Shmel-bz/Shmel-bz is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->