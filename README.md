# Игра морской бой

## Требования:
* GUI
* + Выполнение правил игры 
* + Компьютер-оппонент
* + Hot seat - авто настройки по умолчанию
* + Случайная расстановка кораблей
* + Возможность расстановки кораблей игроком(-ами)
* + Параметризация поля (размеры, типы и количество кораблей)
* + 2 уровня AI: рандом + более умный
* + Угловые корабли
* Загрузка/сохранение игры
* Игра на время (в режиме hot seat)

Право выбора 
    настройки по умолчанию: да / нет
        если да, то такие:
            игра на время
            размер поля 10х10
            прямые корабли
            игра с ботом 
            легкий уровень сложности
            автоматическая расстановка кораблей
            игра без времени
        если нет, то настройка игры:
            размер поля: 10 / 15 / 20
            корабли: прямые / угловые
            игра с: бот / человек
                если игра с ботом, то сложность: рандом / умная
            заполнение поля игрока: в ручную / автоматически

нечего тестировать в:
    в папке gui нет логики, только формирование окон
    класс Save логика взята из класса player/playerField
    класс Info хранилище полей


