## Нетология. Введение в Android. Урок 10 (Базовые списки). Задача 2. Взаимодействие со списком

### [Задание](https://github.com/netology-code/and-homeworks/tree/master/4.1.listview/4.1.2):

В домашнем задании продолжим работать с приложением из [задачи 1](https://github.com/Yoji-kms/ListDisplay).

Пошаговый план действий:

- Сохранить данные в SharedPreferences во время первого запуска приложения. В последующие разы получать их из SharedPreferences.
- Добавить OnItemClickListener так, чтобы при клике на строку она удалялась из интерфейса.
- Добавить swipe to refresh.
- При использовании swipe to refresh обновлять содержимое списка из SharedPreferences так, чтобы список приходил в первоначальный вид.