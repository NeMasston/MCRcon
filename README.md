# MCRcon VK
***
### 2 RCON бота:
- Для страницы `VK`
- Для группы `VK`
***
Настройка бота для `страницы`:

1. Открываем файл butty.yml.

2. Получаем Access Token вашей страницы `VK`.
Получить Токен, можно открыв [этот сервис](https://vkhost.github.io/) и нажать `VK API`.
В появившемся виджете, нажимаем кнопку `разрешить`.
У вас откроется страница из URL которой, нам нужно скопировать `Access Token`.
Но как понять где `Access Token`? Всё легко! В URL адресе есть access_token=СИМВОЛЫ&expires_in,
Вам нужно скопировать символы со знака `=` по знак `&`, это и есть наш `Токен`!

Вставляем токен в строку `token`.

3. Три друга: `VIP`, `BLACKLICK` и `ADMIN`.
- `VIP`: Вставляем в строку `VIP` ваш ID страницы `VK`, аналогично проделываем с `ADMIN`.
Это нужно для того, что бы бот понимал, что вы имеете права к консоли.
- `ADMIN`: Вставляем в строку ваш ID страницы.
- `BLACKLIST`: В эту строку, вставляем ID страницы `V`K того человека, которому бот не будет даже отвечать!
Сохраянем и выходим из файла.

4. Переходим в папку `/plugins/DustRCON`
5. Открываем файл `config.yml`. Там уже идут настройки по желанию, могу лишь отметить то, что
обязательным является вписать свой ID в строку `owners` и вписать `RCON ДАННЫЕ` от вашего сервера.
Сохраняем и выходим.
6. В корне запускаем start.bat для WINDOWS или st.sh для LINUX-подобных систем.
***
Настройка бота для `группы`:
1. Открываем файл config.yml.
2. В строку `id_token` вписываем ID вашей группы VK, к которой будет прикреплён бот.
3. Access Token:
- Переходим в настройки группы
- Открываем раздел `Работа с API`
- Нажимаем `Создать ключ`
- Отмечаем все галочки и нажимаем `создать`.
- Копируем ключ после его создания и вставляем в строку access_token.
4. `users_id` & `owners_id`:
- В обе строки вставляем ID вашей страницы и человека которому вы хотите дать доступ.
5. `rcons`: Тут уже настраивайте сами в зависимости от вашего сервера.
6. `messages`: Это настройка сообщений, изменяем по желанию.
7. Сохраняем файл и выходим.
***
На этом небольшой туториал по настройке ботов окончен.
- Специально для конфы `Азизыч` и паблика `MHC`
- Туториал: [Rowness/Masston](https://vk.com/masston)

# БОТ ДЛЯ СТРАНИЦЫ РАБОТАЕТ ЧАСТИЧНО! ОГРАНИЧЕНИЕ ВК 15 ФЕВРАЛЯ!
