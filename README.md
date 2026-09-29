# api-course-work

WEB 4 =  5
Web 5 
Количество объектов: 3  
ID каждого объекта: 1, 2, 3
Web 6 = Количество ответов при postId=3: 5 Количество ответов при postId=4: 6
web 3 Web3
Метод GET  
Статус 200 OK  
Content-Type application/json; charset=utf-8  
Пользователей 10  
Запрос со статусом = 200 нет 
web 7 
Количество при _limit=2: 2  
Количество при _limit=7: 7
web 8 
1 Адрес: https://jsonplaceholder.typicode.com/comments?postId=7&_limit=4  
Порт: подразумевается 443 *(https)*  
Путь: /comments  
Query-параметры: postId=7&_limit=4

2 Адрес: http://localhost:8080/tasks?page=2&sort=date  
Порт: 8080 *(указан явно)*  
Путь: /tasks  
Query-параметры: page=2&sort=date

3 Адрес: https://api.example.com:3000/users/42/posts?status=active  
*Важный нюанс:* число `42` — это часть пути, а не порт! Порт всегда стоит между хостом и первым слэшем (`:`).  
Порт: 3000 *(указан явно)*  
Путь: /users/42/posts  
Query-параметры: status=active
Web 9 одни и теже по 10 с postid_2

WEB 10.

query ломает запрос

WEB 11.

Content-Type     application/json; charset=utf-8
Content-Length   1847

Content-Type     nosniff

WEB 12.
5 объектов
"id": 1,
"id": 2,
"id": 3,
"id": 4,
"id": 5,

5 объектов
"id": 6,
"id": 7,
"id": 8,
"id": 9,
"id": 10,

_page отвечает за пагинацию
