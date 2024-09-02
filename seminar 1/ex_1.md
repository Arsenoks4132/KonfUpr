## Задача 1

Вывести отсортированный в алфавитном порядке список имен пользователей в файле passwd (вам понадобится grep).

cat /etc/passwd | grep -o "^[^:]*" | sort

![image](https://github.com/user-attachments/assets/f3b8414d-2a9f-419a-a404-076426398e56)

## Задача 2

Вывести данные /etc/protocols в отформатированном и отсортированном порядке для 5 наибольших портов, как показано в примере ниже:

```
[root@localhost etc]# cat /etc/protocols ...
142 rohc
141 wesp
140 shim6
139 hip
138 manet
```

![image](https://github.com/user-attachments/assets/722552ed-33d9-402e-9395-5f9a947d98c6)
