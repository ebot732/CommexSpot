# CommexSpot
Trading bot for CommEX exchange.


Бот для спот торговли на криптобирже Commex (аналог BinSpot-20).

Запуск бота на VPS с ubuntu
1. Подключаемся к серверу и по умолчанию находимся в корневом каталоге.
2. Создаем новую папку (например, с именем CommexSpot) командой:  
mkdir CommexSpot
3. Создаём новую screen-сессию (назовем, например, тоже CommexSpot) для  бота командой:  
screen -S CommexSpot
4. Заходим в папку CommexSpot командой:  
cd CommexSpot
5. Скачиваем бота в папку CommexSpot командой:  
wget https://github.com/ebot732/CommexSpot/releases/download/CommexSpot-20/CommexSpot-20
6. Даём права на запуск бота командой:  
chmod 755 CommexSpot-20
7. Запускаем  бота командой:  
./CommexSpot-20  
и следуем подсказкам.
8. Выходим из работающего screen, не прерывая его работу, командой:  
ctrl+a, d (при нажатой ctrl жмем а, отпускаем их, и затем жмем d)

Далее, чтобы зайти в screen работающего бота, введите команду:  
screen -x CommexSpot  
То есть, второй раз вводить  
screen -S CommexSpot  
не нужно, а то создастся еще одна screen-сессия.
