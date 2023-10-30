*Membuat Tabel Mahasiswa pada Database polban*

1. Buka SQL lalu login .
2. Lalu Buat Database dengan syntax : CREATE DATABASE polban.
3. Selanjutnya connect dengan Database tersebut dengan syntax : \c polban.
4. Lalu buat tabel sesuai dengan yang ditugaskan dengan syntax : CREATE TABLE mahasiswa (NIM int , Nama varchar(30) , Gender varchar(30) , alamat varchar(100) , kotaasal varchar(30) , tanggallahir varchar(30) , tahunmasuk varchar(30) , No Hp decimal);
5. Lalu masukan data mahsiswa kedalam tabel dengan syntax : INSERT INTO mahasiswa (nim , nama , gender , alamat , kotaasal ,tanggallahir , tahunmasuk , nomorhp ) VALUES (221331040 , 'Dikri Nugraha' , 'Laki - Laki' , 'Jalan Jendral Sudriman' , 'Cimahi' , '26/Mei/2004' , '2022' , '0881023421454');
6. Untuk mengecek pada SQL data teresbut sudah masuk kita bisa menggunakan syntax : SELECT * FROM mahasiswa;![image](https://github.com/dikrinugraha/pertemuan2-basis-data/assets/148309578/a5eabf0a-0b9b-4f64-943a-8c5353e10ade)
7. Lalu cek di Dbeaver : ![image](https://github.com/dikrinugraha/pertemuan2-basis-data/assets/148309578/b69c3e7b-2cd6-4778-bfbe-c76a58dcb075) ![image](https://github.com/dikrinugraha/pertemuan2-basis-data/assets/148309578/c5e01e0f-f0d7-4427-9d28-1de7c03ffe44)


 
