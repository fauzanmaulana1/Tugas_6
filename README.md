# Tugas_6
## Nama   : Fauzan Maulana
## NIM    : 312010115
## Kelas  : TI.20.D.1
## Matkul : Sistem Basis Data

- Masuk ke database nama_nim

![Untitled](https://user-images.githubusercontent.com/101807419/174796867-31764959-281f-48e8-8ebc-9596ee923b6e.png)

- Lakukan proses backup dan recovery dengan sql dari database tugas seblumnya !
Backup
![image](https://user-images.githubusercontent.com/101807419/174797226-644169f0-d91f-4284-b557-9e656783de92.png)

Jika proses backup berhasil maka akan muncul file backuppada direktori C:\xampp\mysql\data\nama database
![image](https://user-images.githubusercontent.com/101807419/174797417-a3e85804-d261-4bee-baca-50f882e37df3.png)

Recovery

Data yang telah di-backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan adalah LOAD DATA INFILE. Perintah yang dijalankan adalah

LOAD DATA INFILE ‘Nama_backup_file’ INTO TABLE nama_table ;
![image](https://user-images.githubusercontent.com/101807419/174799156-b0061c13-9b72-463b-a33f-3b4536289d9c.png)

- Lakukan proses backup dan recovery dengan sqldump dari database tugas seblumnya !
