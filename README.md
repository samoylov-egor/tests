# Rick Roll Rockstar Program

Программа на языке Rockstar, которая анализирует входную строку и выводит соответствующие фразы.

## Описание

Программа принимает строку на вход и проверяет точное совпадение:

- Если Input = "Rick" → выводит "Never gonna give you up!"
- Если Input = "Roll" → выводит "Never gonna let you down!"
- Если Input = "Rick Roll" → выводит "Never gonna give you up!" затем "Never gonna let you down!"
- Если Input = "Roll Rick" → выводит "Never gonna let you down!" затем "Never gonna give you up!"
- Если Input не совпадает ни с одним из вышеперечисленных → выводит "Silence...."

## Использование

1. Запустите интерпретатор Rockstar
2. Загрузите файл `rickroll.rock`
3. Введите строку в stdin (программа использует `Listen to Input` для получения ввода)
4. Получите результат

## Тестовые случаи

Смотрите файл `test_cases.txt` для примеров входных данных.

## Файлы

- `rickroll.rock` - основная программа на Rockstar
- `test_cases.txt` - примеры тестовых данных
- `README.md` - этот файл с инструкциями
