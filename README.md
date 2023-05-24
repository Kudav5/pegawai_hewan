## **Tugas Praktikum (Pegawwai)**

### 1. Tampilkan pegawai yang gajinya bukan 2.000.000 dan 1.250.000 !

`select*from pegawai where gaji not in ('2000000','1250000');`

### 2. Tampilkan pegawai yang tunjangannya NULL

`select*from pegawai where tunjangan in ('NULL');`

### 3. Tampilkan pegawai yang tunjangannya tidak NULL!

`select*from pegawai where tunjangan not in ('NULL');`

### 4. Tampilkan hitung jumlah baris /record tabel pegawai!

### 5. Tampilkan hitung jumlah total gaji di tabel pegawai

`select sum(gaji) as jumlah from pegawai;`

### 6. Tampilkan hitung rata rata gaji pegawai

`select avg(gaji) as rerata from pegawai;`

### 7. Tampilkan gaji terkecil

`select min(gaji) as terkecil from pegawai;`

### 8. Tampilkan gaji terbesar

`select max(gaji) as terbesar from pegawai;`