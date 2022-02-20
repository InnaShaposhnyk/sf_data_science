# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](https://github.com/InnaShaposhnyk/sf_data_science/blob/main/project_0_guess_the_number/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/InnaShaposhnyk/sf_data_science/blob/main/project_0_guess_the_number/README.md#Какой-кейс-решаем)  
[3. Информация о программе](https://github.com/InnaShaposhnyk/sf_data_science/blob/main/project_0_guess_the_number/README.md#Информация-о-программе)  
[4. Результат](https://github.com/InnaShaposhnyk/sf_data_science/blob/main/project_0_guess_the_number/README.md#Результат)   

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](https://github.com/InnaShaposhnyk/sf_data_science/blob/main/project_0_guess_the_number/README.md#Оглавление)


### Какой кейс решаем?    
В рамках курса SkillFactory по Data Science нужно написать программу, которая угадывает число меньше чем за 20 попыток.

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

:arrow_up:[к оглавлению](https://github.com/InnaShaposhnyk/sf_data_science/blob/main/project_0_guess_the_number/README.md#Оглавление)


### Информация о программе
- Программа проверяет, относится ли загаданное число к первому десятку. Если да, угадывает число из диапазона чисел первого десятка.
- Если число не относится к первому десятку, программа проверяет равно ли загаданное число 100.
- Если нет, программа проверяет к какому десятку (от 2-го до 9-го) относится число. Затем угадывает число из диапазона чисел соответстующего десятка.
  
:arrow_up:[к оглавлению](https://github.com/InnaShaposhnyk/sf_data_science/blob/main/project_0_guess_the_number/README.md#Оглавление)


### Результат 
Программа угадывает загаданное компьютером число в среднем за 9-10 попыток.

:arrow_up:[к оглавлению](https://github.com/InnaShaposhnyk/sf_data_science/blob/main/project_0_guess_the_number/README.md#Оглавление)
