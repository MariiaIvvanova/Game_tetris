# Tetris Game

## Описание

Тетрис — классическая аркадная игра, в которой игроки управляют падающими тетромино и пытаются заполить горизонтальные линии, чтобы они исчезли. Цель игры — не дать тетромино достичь верхней части экрана.

## Требования

Перед тем как начать, убедитесь, что у вас установлены следующие инструменты:

- **Python** версии 3.8 или выше
- **pip** — менеджер пакетов Python
- **pipenv** — для управления виртуальными окружениями

## Установка

1. Клонируйте репозиторий:

    ```bash
    git clone https://github.com/MariiaIvvanova/Game_tetris.git
    cd Game_tetris
    ```

2. Установите зависимости с помощью pipenv:

    ```bash
    pipenv install
    ```

    Это создаст виртуальное окружение и установит все необходимые зависимости.

3. Активируйте виртуальное окружение:

    ```bash
    pipenv shell
    ```

4. Для запуска игры используйте команду:

    ```bash
    python main.py
    ```
 
## Управление

- Стрелка вверх — вращение тетромино.  
- Стрелка вниз — ускоренное падение тетромино.  
- Стрелка влево — перемещение тетромино влево.  
- Стрелка вправо — перемещение тетромино вправо.
- Пробел — начать игру сначала или после проигрыша
