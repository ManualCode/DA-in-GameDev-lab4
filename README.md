# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
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
### Должна ли величина loss стремиться к нулю при изменении исходных данных? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ.

1
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/69ca3a81-38cb-440b-9e12-c61f3b973d93)

2
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/a5c541a4-c52d-4ac7-b89d-7016fe2623f9)

3
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/f9057b84-6518-48b5-b757-720dec2f9e0e)

4
![image](https://github.com/ManualCode/DA-in-GameDev-lab4/assets/120582775/10a39ef5-f540-4f6a-88d8-bfb961f473b3)





## Задание 3
### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.

- Перечисленные в этом туториале действия могут быть выполнены запуском на исполнение скрипт-файла, доступного [в репозитории](https://github.com/Den1sovDm1triy/hfss-scripting/blob/main/ScreatingSphereInAEDT.py).
- Для запуска скрипт-файла откройте Ansys Electronics Desktop. Перейдите во вкладку [Automation] - [Run Script] - [Выберите файл с именем ScreatingSphereInAEDT.py из репозитория].

```py

import ScriptEnv
ScriptEnv.Initialize("Ansoft.ElectronicsDesktop")
oDesktop.RestoreWindow()
oProject = oDesktop.NewProject()
oProject.Rename("C:/Users/denisov.dv/Documents/Ansoft/SphereDIffraction.aedt", True)
oProject.InsertDesign("HFSS", "HFSSDesign1", "HFSS Terminal Network", "")
oDesign = oProject.SetActiveDesign("HFSSDesign1")
oEditor = oDesign.SetActiveEditor("3D Modeler")
oEditor.CreateSphere(
	[
		"NAME:SphereParameters",
		"XCenter:="		, "0mm",
		"YCenter:="		, "0mm",
		"ZCenter:="		, "0mm",
		"Radius:="		, "1.0770329614269mm"
	], 
)

```

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
