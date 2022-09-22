# query-database
https://www.webfx.com/tools/emoji-cheat-sheet/

C:\laragon\bin
😄
mysql -u root -p

+ show databases
+ show tables;
+ desc tabel
+ Drop table tb_latihan;
+ Drop database db_gilacoding;

## query
```
insert into barang (id, barang, jumlah) values (1, "jambu", 3);
```

```
update barang set jumlah = 1 where barang = jambu;
```

```
select penjualan.id_jual,barang.id_barang,barang.nama_barang
,barang.harga,penjualan.jumlah from barang,penjualan where penjualan.id_barang=b
arang.id_barang;
```

```
DELETE FROM tb_latihan WHERE id_latihan = 1;
create table barang
    -> (id INT AUTO_INCREMENT
    -> title VARCHAR(50) NOT NULL);
```

```
select nama_barang, max(harga) 'Maksimam', min(harga)'Minimum', sum(harga
)'total', avg(harga)'Rata-Rata' from barang; 
```

semua dimunculkan dari huruf m
```
Select nama_barang from barang where nama_barang LIKE '%m%';
```
semua kata ketika huruf m dibelakang sendiri
```
Select nama_barang from barang where nama_barang LIKE '%m';
```
---
###
