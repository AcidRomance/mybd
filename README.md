   Первая лабораторная:

1) Выберите из таблицы orders все заказы

   
![image](https://github.com/user-attachments/assets/ebdbfae2-ec2f-47eb-8656-98ed6774c9ab)

2) Выберите из таблицы orders все заказы кроме новых. 
У новых заказов status равен "new". Использовать in
   ![image](https://github.com/user-attachments/assets/a58f9a0d-4a17-4d46-a749-7d944637d798)

3) Выберите из таблицы orders все новые и отмененные заказы. У отмененных заказов status равен "cancelled". У новых заказов status равен "new".

  ![image](https://github.com/user-attachments/assets/cef07c92-d10f-488a-a2dd-0732f816b8a4)

4) Выберите из таблицы orders все заказы содержащие более 3 товаров (products_count).
Вывести нужно только номер (id) и сумму (sum) заказа.

![image](https://github.com/user-attachments/assets/11959c64-1e16-4d67-a962-0c5e45fe4714)



Вторая лабораторная:

1) Выберите из таблицы orders 3 самых дешевых заказа за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/ef4864c1-ccd4-4d9b-84df-cec5e0f6eee2)


2) Выберите из таблицы orders 2 самых дорогих заказов за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/6b7d7ed7-7168-441e-8674-a9dff5aa4457)


3) Добавьте в таблицу orders данные о новом заказе стоимостью 8000 рублей. В заказе 4 товара (products).

   ![image](https://github.com/user-attachments/assets/f0b7fe57-6c94-441e-9ff2-91ee55aec109)

![image](https://github.com/user-attachments/assets/cb894435-f384-49df-9a1a-35296fff1a52)


4) Добавьте в таблицу products новый товар — «VR-очки», стоимостью 70000 рублей в количестве (count) 2 штук.

   ![image](https://github.com/user-attachments/assets/b9d23143-30df-4c85-8e4a-1ba151d82b4f)

![image](https://github.com/user-attachments/assets/83cdec71-1cbc-4171-98df-3f4edd185509)

5) В таблицу products внесли данные с ошибкой, вместо "PS5" в наименовании написали IMAC. Исправьте ошибку.

   ![image](https://github.com/user-attachments/assets/f903e5f0-fe00-4fc5-846d-8d425beb2343)

   ![image](https://github.com/user-attachments/assets/267b0963-015c-47ea-b9c4-fa411901e773)

   Задание3
![image](https://github.com/user-attachments/assets/3a05abfe-d76b-4957-85f9-26d34c9bc8ea)
![image](https://github.com/user-attachments/assets/1b7815ed-4c25-4943-8d98-527bcf59682f

Задание4 
BD4
Создайте таблицу users для хранения информации о пользователях сайта. В таблице должны быть следующие поля:
id – идентификатор, целое положительное; email – адрес электронной почты, строка не более 100 символов; date_joined – дата регистрации (достаточно хранить дату, без времени) last_activity – дата и время последней активности (с точностью до секунд).
￼ первый
Создайте таблицу calendar для хранения календаря посетителей. В таблице должны быть следующие поля:
id – идентификатор записи в календаре, целое положительное; user_id – идентификатор пользователя, целое положительное; doctor_id – идентификатор доктора, целое положительное; visit_date – дата и время визита (точность до секунд).
￼ второй
Создайте таблицу users , в которой будут следующие поля:
id — идентификатор, целые положительные числа. first_name— имя, строки до 50 символов. last_name — фамилия, строки до 60 символов. bio — биография, текст до 65000 символов.
￼3скрин
По obj смотри, где скрины стоят
![image](https://github.com/user-attachments/assets/f11dbcae-7890-4e6e-8ad3-64b502b290d0)
![image](https://github.com/user-attachments/assets/62219ec3-d21d-47f1-99ea-1cd6a7931539)

задание5
# BD5

1) Выберите из таблицы orders 4 самых дорогих заказов за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

![image](https://github.com/user-attachments/assets/38ad58ad-f585-47f4-8167-ee188795af1f)

2) Выберите из таблицы products название и цены четырех самых дешевых товаров, которые есть на складе.

![image](https://github.com/user-attachments/assets/c8909f9f-c702-4df0-a05a-75fa01e0a1c4)

3) Выберите из таблицы orders три последних заказа (по дате date) стоимостью от 3200 рублей и выше.
Данные отсортируйте по дате в обратном порядке.

![image](https://github.com/user-attachments/assets/18a8a1e3-c1d4-4933-ad54-56010f93ddce)

4) Создайте данную таблицу:

![image](https://github.com/user-attachments/assets/fc4930ec-aa95-43a8-b1ed-239c35a63fd0)

5) Из этой таблицы сделать выборку на основе задания: Сайт выводит товары по 5 штук. Выберите из таблицы products товары, которые пользователи увидят на 3 странице каталога при сортировке в порядке возрастания цены (price).

![image](https://github.com/user-attachments/assets/f2489fb6-d218-45ac-8429-fa4f62036538)

# BD6
1)Создайте таблицу orders для хранения списка заказов:

id — идентификатор, целое положительное. user_id — идентификатор пользователя, который оформил заказ. Целое положительное, NULL запрещен. amount — стоимость заказа. Целое положительное число не более 1 млн. NULL запрещен, по умолчанию 0. created — дата и время создания заказа. NULL запрещен. state — статус заказа. Выбор из new, cancelled, in_progress, delivered, completed. Можно выбрать только один вариант. NULL запрещен. По умолчанию должен стоять new. Добавьте 3 записи так, чтобы получалась таблица ниже:

CREATE table orders (id INT UNSIGNED, user_id INT UNSIGNED NOT null, amount mediumint unsigned NOT NULL DEFAULT 0, created DATETIME NOT NULL, state ENUM ('NEW', 'cancelled', 'in_progress', 'delivered', 'completed') NOT NULL DEFAULT 'new'); INSERT INTO orders (id, user_id, amount, created, state) VALUES (1, 56, 5400, '2018-02-01 17:46:59', DEFAULT), (2, 90, 249, '2018-02-01 19:13:04', DEFAULT), (3, 78, 2200, '2018-02-01 22:43:09', DEFAULT);

![image](https://github.com/user-attachments/assets/eea19cb7-8f42-44de-935c-9014df8a19c2)

2)Создайте таблицу users для хранения списка пользователей сайта:

id — идентификатор, целое положительное. first_name — имя, строка до 20 символов. NULL запрещен. last_name — фамилия, строка до 20 символов. NULL запрещен. patronymic — отчество, строка до 20 символов. NULL запрещен, по умолчанию пустая строка. is_active — отметка об активности пользователя. Логическое поле, по умолчанию TRUE. is_superuser — отметка администратора. Логическое поле, по умолчанию FALSE. Добавьте 3 записи так, чтобы получалась таблица ниже:

CREATE table users (id INT UNSIGNED, first_name VARCHAR(20) NOT NULL, last_name VARCHAR(20) NOT NULL, patronymic VARCHAR(20) NOT NULL DEFAULT '', is_active BOOLEAN DEFAULT TRUE, is_superuser BOOLEAN DEFAULT FALSE); INSERT INTO users (id, first_name, last_name, patronymic, is_active, is_superuser) VALUES (1, 'Дмитрий', 'Иванов', DEFAULT, DEFAULT, DEFAULT), (2, 'Анатолий', 'Белый', 'Сергеевич', DEFAULT, TRUE), (3, 'Андрей', 'Крючков', DEFAULT, FALSE, DEFAULT); SELECT * FROM users;

![image](https://github.com/user-attachments/assets/1c1853ae-2dfd-4fe7-9459-3e3702168c8a)

3)Создайте таблицу products для хранения товаров в интернет магазине:

id — идентификатор, целое положительное. category_id — категория, целое положительное. Может принимать NULL. По умолчанию NULL. name — название, строка до 100 символов. NULL запрещен. count — количество, целое положительное до 255. NULL запрещен, по умолчанию 0. price — цена типа DECIMAL с 10 знаками, 2 из которых выделены для копеек. NULL запрещен, по умолчанию 0.00. Добавьте 3 записи так, чтобы получалась таблица ниже:

CREATE table products (id INT UNSIGNED, category_id INT DEFAULT NULL, name VARCHAR(100) NOT null, count TINYINT unsigned NOT NULL DEFAULT 0, price DECIMAL (10, 2) NOT NULL DEFAULT 0.00); INSERT INTO products (id, category_id, name, count, price) VALUES (1, 1, 'Кружка', 5, 45.90), (2, 17, 'Фломастеры', DEFAULT, 78.00), (3, NULL, 'Сникерс', 12, 50.80);

![image](https://github.com/user-attachments/assets/5bb7c855-3c22-47d4-a627-26ff330508d3)



Шпоры: 
INSERT INTO table (column1, column2) VALUES (value1, value2);
 Добавление одной записи
 
INSERT INTO table (column1, column2) VALUES (value11, value12), (value21, value22), ...
 Добавление нескольких записей
 
INSERT INTO table1 (column1, column2) SELECT (col1, col2) FROM table2;
 Добавление записей из другой таблицы
 
UPDATE table1 SET column1 = new value;
 Обновление поля во всех записях
 
UPDATE table1 SET column1=new_value column2=new_value WHERE condition;
 Обновление поля во записях, соответствующих условию
 
 DELETE FROM table; Удаление всех записей
 
 DELETE FROM table WHERE condition; Удаление записей, соответствующих условию
