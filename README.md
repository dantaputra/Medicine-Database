# crud-go-typescript-mysql

Website sederhana untuk Create, Read, Update, dan Delete data MySQL dengan bahasa Go dan Typescript

- Buat database bernama go_db dan sebuah tabel di database mysql dengan nama tabel users

```java
CREATE TABLE `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `username` varchar(50) DEFAULT NULL,
  `first_name` varchar(200) NOT NULL,
  `last_name` varchar(200) NOT NULL,
  `password` varchar(120) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```

- lanjut ketikan perintah ini di terminal atau di git command
> git clone https://github.com/jadirullah/crud-dengan-go-mysql.git'
- terakhir, masuk ke dalam folder project go jalankan perintah
> go run main.go'
