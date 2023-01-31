# crud-go-typescript-mysql

Website sederhana untuk Create, Read, Update, dan Delete data MySQL dengan bahasa Go dan Typescript

Langkah-langkah:
- Buat database bernama 'gosql' dan tabel di database mysql dengan nama tabel 'obat'

```java
DROP TABLE IF EXISTS `obat`;
CREATE TABLE `obat` (
  `id_obat` int(6) unsigned NOT NULL AUTO_INCREMENT,
  `kode_obat` varchar(30) NOT NULL,
  `nama_obat` varchar(30) NOT NULL,
  `harga` varchar(30) NOT NULL,
  PRIMARY KEY (`id_obat`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;
```

- Lanjut ketikan perintah ini di terminal atau di git command
> git clone https://github.com/dantaputra/crud-go-typescript-mysql.git
- Terakhir, masuk ke dalam folder project go jalankan perintah
> go run main.go
- Buka browser dan buka link berikut
> http://localhost:9000/
