# Гра "Tic-Tac-Toe"

## Опис гри
"Tic-Tac-Toe" — це логічна гра для двох гравців, яка проводиться на дошці розміром 3x3 клітинки. Один гравець ставить "X", а інший - "O". Гравці ходять по черзі, розміщуючи свій символ на вільній клітинці дошки. Гравець, який перший зможе утворити рядок, стовпчик або діагональ із трьох своїх символів, виграє гру.

### Правила гри

1. **Початок гри**: 
    - Перший гравець завжди грає "X", а другий гравець грає "O".
2. **Хід гравців**: 
    - Гравці ходять по черзі. Кожен гравець вказує номер клітинки на дошці, де він хоче поставити свій символ. 
    - Клітинка повинна бути вільною, тобто не містити символ "X" або "O".
3. **Переможець**: 
    - Гра завершується, коли один з гравців утворює рядок, стовпчик або діагональ із трьох своїх символів (або "X", або "O"). Цей гравець вважається переможцем.
4. **Нічия**: 
    - Якщо всі клітинки на дошці заповнені, а переможця не визначено (немає рядків, стовпців або діагоналей із трьох однакових символів), гра закінчується в нічию.

### Вимоги

- Компілятор C++

### Компіляція та запуск

1. Скомпілюйте програму за допомогою компілятора C++:
    ```sh
    g++ tictactoe.cpp -o tictactoe
    ```

2. Запустіть виконуваний файл:
    ```sh
    ./tictactoe
    ```

