Для запуска приложения используется Apache с сервером на СУБД MySQL. Необходимо создать базу данных XO и таблицу к ней со следующим SQL кодом:
CREATE TABLE `users` (
  `email` varchar(100) DEFAULT NULL,
  `password` varchar(100) DEFAULT NULL,
  `name` varchar(100) DEFAULT NULL,
  `surname` varchar(100) DEFAULT NULL,
  `lastname` varchar(100) DEFAULT NULL
)

При подключении используется пользователь root с паролем root, подключение через localhost
