![OR](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/04dd4e15-3b93-4afb-9fec-57210f3b43f2)# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
- Тимохов Кирилл Александрович
- РИ220910
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Изучение модели работы перцептрона посредством использования Unity.

## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления:
### OR | дать комментарии о корректности работы
### AND | дать комментарии о корректности работы
### NAND | дать комментарии о корректности работы
### XOR | дать комментарии о корректности работы
Ход работы:
- Создал проект Unity, добавил скрипт Perceptron на пустой GameObject и просмотрел, что выводит Console.
1. OR. Работает корректно, необходимо 3-4 эпохи, чтобы перцептрон работал без ошибок.
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/423f2dde-cf04-422a-bc36-d6b6a52e66ba2)
2. AND. Работает корректно, необходимо 5-6 эпох, чтобы перцептрон работал без ошибок.
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/1c75371f-94bf-4a2b-9878-0ce5dd97640b)
3. NAND. Работает корректно, необходимо 5-6 эпох, чтобы перцептрон работал без ошибок.
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/2a114c48-6c38-47fc-bdf6-8a178c8df8a4)
4. XOR. Работает некорректно, т.к. XOR - нелинейная функция, перцептрон может решать задачи только линейной классификации.
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/8d7ef6fa-a944-4cc4-8fd1-c7fd82dc7199)

## Задание 2
### Построить графики зависимости количества эпох от ошибки обучения. Указать от чего зависит необходимое количество эпох обучения.

Ход работы:
- Я заполнил Google-Таблицу данными об эпохах и визуализировал их с помощью графиков.

1. OR (Логическое сложение(ИЛИ)):
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/69ca3a81-38cb-440b-9e12-c61f3b973d93)

2. AND (Логическое умножение(И)):
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/a5c541a4-c52d-4ac7-b89d-7016fe2623f9)

3. NAND (Инвертированное Логическое умножение(НЕ И)):
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/f9057b84-6518-48b5-b757-720dec2f9e0e)

4. XOR (Исключающая Логическая сумма((ИЛИ) и (НЕ И))):
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/10a39ef5-f540-4f6a-88d8-bfb961f473b3)

## Задание 3
### Визуализировать работу персептрона с помощью физуальной модели на сцене Unity.

1. Тест OR:

![OR](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/201545aa-2a14-4136-b887-c24cb088c3b0)
2. Тест AND:

![AND](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/1fa95746-eee5-4957-bfc8-5d5b36d85221)
3. Тест NAND:

![NAND](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/fb3609c4-7fa5-46b9-ad6a-adc901f25f61)
4. Тест XOR:

![XOR](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/b71e1e83-3ad5-4ab6-b1ad-38363766f873)

## Выводы

Абзац умных слов о том, что было сделано и что было узнано.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
