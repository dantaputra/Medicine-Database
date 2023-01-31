# crud-go-typescript-mysql

Website sederhana untuk Create, Read, Update, dan Delete data MySQL dengan bahasa Go dan Typescript

Langkah-langkah:
- Buat database bernama go_db dan tabel di database mysql dengan nama tabel obat

```java
CREATE TABLE `obat` (
  `id_obat` int(11) NOT NULL primary key AUTO_INCREMENT,
  `kode_obat` varchar(10) DEFAULT NULL,
  `nama_obat` varchar(255) NOT NULL,
  `harga` varchar(255) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
```

- Lanjut ketikan perintah ini di terminal atau di git command
> git clone https://github.com/dantaputra/crud-go-typescript-mysql.git
- Terakhir, masuk ke dalam folder project go jalankan perintah
> go run main.go'
- Buka browser dan buka link berikut
> http://localhost:9000/
