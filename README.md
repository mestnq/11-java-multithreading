# Задание 1:
Программа при каждом запуске выводит разные результаты, необходимо разобраться из-за чего это происходит и исправить программу так, чтобы она выводила правильный результат.
Убедитесь, что потоки работают параллельно и блокируют друг друга минимально возможное время.

# Задание 2:
Эта программа предназначена для того, чтобы выполнить 30 долгих и ресурсоемких задач. Для ускорения процесса программист использовал ThreadPoolExecutor. Так как данные для каждой задачи занимают много оперативной памяти, он ограничил количество задач в очереди до 3. Но что-то пошло не так, и программа отказывается выполнять все задачи. Исправьте код так, чтобы все 30 задач выполнились в 3 потока, и цикл создания задач не переполнял очередь задач.
Выложите исправленный код.
