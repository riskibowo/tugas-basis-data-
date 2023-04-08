# tugas basis data
### 1.Membuat data base latihan2
```
CRATE DATABASE Latihan2
```
![image](https://user-images.githubusercontent.com/115862112/230727331-95d36346-69e2-428c-a44b-dab6c34cdc07.png)
### menampilkan daftar basisdata
![image](https://user-images.githubusercontent.com/115862112/230727398-d6243cb4-380a-44f6-9e2b-eee022dad27e.png)

### 2.Membuat tabel biodata di dalam database latihan2
```
USE latihan2; CREATE TABLE biodata (nama VARCHAR(15),alamat VARCHAR(15));
```
![image](https://user-images.githubusercontent.com/115862112/230727493-b303606c-5588-4cc7-b623-8b1479dec6be.png)
### 3.Menambahkan kolom keterangan
```
 ALTER TABLE biodata ADD keterangan VARCHAR(15);
```
![229923774-aafc34d6-1d18-4739-ab69-d0216d5387ee](https://user-images.githubusercontent.com/115862112/230727709-cc161916-45d5-4c2f-8d06-735e6b7f600f.png)


### 4.Menambahkan kolom id di awal:
```
ALTER TABLE biodata ADD id INT(11) FIRST;
```
![229924635-f622f0ac-7525-4aa3-9d5e-c40585641669](https://user-images.githubusercontent.com/115862112/230727783-493d870c-b6f2-4f58-b23b-fa0a2607d7a8.png)
### 5.Menambahkan kolom phone setelah kolom alamat:
```
 ALTER TABLE biodata ADD phone VARCHAR(15) AFTER alamat;
```
![229924689-57741e36-0215-4408-a0d3-e3a5429f353b](https://user-images.githubusercontent.com/115862112/230727875-b41bcea8-43d3-4f7e-9247-8ef87932a978.png)
### 6.Mengubah tipe data kolom id menjadi char(11):
```
ALTER TABLE biodata MODIFY id CHAR(11);
```
![image](https://user-images.githubusercontent.com/115862112/230728053-0136d156-72fa-4b20-b87f-a81659be8290.png)
### 7.Mengubah nama kolom phone menjadi hp (varchar 20):
```
 ALTER TABLE biodata CHANGE phone hp VARCHAR(20);
```
![image](https://user-images.githubusercontent.com/115862112/230728096-20526d0e-002c-4fba-963a-240dcd2b9541.png)
### 8.Menambahkan kolom email setelah kolom hp:
```
ALTER TABLE biodata ADD email VARCHAR(15) AFTER hp;
```
![image](https://user-images.githubusercontent.com/115862112/230728163-a9246061-fb1e-4a4e-b453-7080d156b432.png)
### 

