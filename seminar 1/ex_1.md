## Задача 1

Вывести отсортированный в алфавитном порядке список имен пользователей в файле passwd (вам понадобится grep).

cat /etc/passwd | grep -o "^[^:]*" | sort

![image](https://github.com/user-attachments/assets/f3b8414d-2a9f-419a-a404-076426398e56)
