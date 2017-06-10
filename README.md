## Simple CRUD java with jasperreport 

Untuk menjalankan aplikasi sederhana ini cukup mudah, yang harus dilakukan adalah :
    - Clone atau unduh zip file masternya dari link github ini
    - Buat database dengan nama terserah disesuaikan saja
    - Setting username dan password sesuai dengan yang ada di lingkungan local server
    - Buat tabel person seperti dibawah ini
    - Run Project selesai

```sql
CREATE TABLE Person(
   personId int (30) NOT NULL,
   firstName varchar (30) NOT NULL,
   middleName varchar (30) NOT NULL,
   lastName varchar (30) NOT NULL,
   email varchar (30) NOT NULL,
   phone varchar (30) NOT NULL,
   PRIMARY KEY (personId)
);
```
