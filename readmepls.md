Лабораторная работа №1
Слиозберг Владимир Владимирович 467498

1. Скачал homebrew с официального сайта

2. С помощью команды "brew install gedit" установил gedit

3. Создал файл "script.bash", используя команду "gedit script.bash"

4. В файле написал следующие две строки:
#!/bin/bash
echo "Welcome, Vasya Pupkin"

5. Теперь при вводе команды "bash script.bash" в терминале получаю вывод:
Welcome, Vasya Pupkin

6. Для того, чтобы при вводе команды "script.bash" в выводе я получал желаемое имя, я модифицировал файл следующим образом:
#!/bin/bash
echo "Welcome, %*"

7. Теперь при вводе имени "Alexander Alexandrovich Untila" после "bash script.bash" получаю в выводе:
Welcome, Alexander Alexandrovich Untila
