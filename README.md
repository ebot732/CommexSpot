# CommexSpot
Trading bot for CommEX exchange.
( реф ссылка для регистрации: https://accounts.commex.com/en/register?ref=NUC4IQEU )

Бот для спот торговли на криптобирже Commex (аналог BinSpot-21).

Запуск бота на VPS с ubuntu
1. Подключаемся к серверу и по умолчанию находимся в корневом каталоге.
2. Создаем новую папку (например, с именем CommexSpot) командой:  
mkdir CommexSpot
3. Создаём новую screen-сессию (назовем, например, тоже CommexSpot) для  бота командой:  
screen -S CommexSpot
4. Заходим в папку CommexSpot командой:  
cd CommexSpot
5. Скачиваем бота в папку CommexSpot командой:  
wget https://github.com/ebot732/CommexSpot/releases/download/CommexSpot-21/CommexSpot-21
6. Даём права на запуск бота командой:  
chmod 755 CommexSpot-21
7. Запускаем  бота командой:  
./CommexSpot-21  
и следуем подсказкам.
8. Выходим из работающего screen, не прерывая его работу, командой:  
ctrl+a, d (при нажатой ctrl жмем а, отпускаем их, и затем жмем d)

Далее, чтобы зайти в screen работающего бота, введите команду:  
screen -x CommexSpot  
То есть, второй раз вводить  
screen -S CommexSpot  
не нужно, а то создастся еще одна screen-сессия.
