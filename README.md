Soal 1, dan 2 Menggunakan PHP 

Soal 6a Query Untuk Menampilkan sesuai soal adalah 

SELECT c.name as cashier, p.name as product, g.name as category, p.price as price FROM product p join cashier c on p.id_cashier=c.id_cashier join category g on p.id_category=g.id_category

Soal 6b terdapat pada folder bootcamp-statis

Soal 6c terdapat pada folder bootcamp-dinamis disini saya menggunakan Framework CodeIgniter 3 dan Bootstrap 4 CDN.

Berikut ini langkah dalam menjalankan file :

1. Buka folder bootcamp-dinamis
2. Jalankan sistem menggunakan xampp
3. Maka akan tampil halaman utama (home) seperti gambar di bawah :

![image](https://user-images.githubusercontent.com/17777914/73129319-5900c380-4013-11ea-8a36-7dc03f49f52e.png)

Halaman ketika melakukan penambahan data :
![image](https://user-images.githubusercontent.com/17777914/73129330-92393380-4013-11ea-9613-6709eab0b460.png)

Halaman ketika berhasil melakukan penambahan data :
![image](https://user-images.githubusercontent.com/17777914/73129338-d3314800-4013-11ea-8ce2-1379c6689af2.png)
![image](https://user-images.githubusercontent.com/17777914/73129341-e512eb00-4013-11ea-9e5b-2baac3fcec21.png)

Halaman ketika melakukan ubah data :
![image](https://user-images.githubusercontent.com/17777914/73129345-0673d700-4014-11ea-9d02-e0d9e559609a.png)

Halaman ketika berhasil melakukan perubahan data :
![image](https://user-images.githubusercontent.com/17777914/73129351-1b506a80-4014-11ea-8841-214be665cdec.png)
![image](https://user-images.githubusercontent.com/17777914/73129354-328f5800-4014-11ea-9bac-dfd63cd7861e.png)

Halaman ketika melakukan hapus data :
![image](https://user-images.githubusercontent.com/17777914/73129360-4935af00-4014-11ea-93cb-b1c043439a0f.png)

Halaman ketika berhasil melakukan hapus data :
![image](https://user-images.githubusercontent.com/17777914/73129361-581c6180-4014-11ea-972b-7454a764a462.png)
![image](https://user-images.githubusercontent.com/17777914/73129364-6f5b4f00-4014-11ea-986d-755e074bcc61.png)
