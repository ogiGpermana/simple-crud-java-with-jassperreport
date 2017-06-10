## Simple CRUD java with jasperreport 

![alt text][logo]: https://lh3.googleusercontent.com/15diMXb1Pml866jcKj_0zDA3G5YT1XhTwbEQ5VfDSKMOePhJ5cO4BKbveAYZw1k2k7djp4Q0sI8tHO7p3EeS-Amuu84r60EsyLErpbCE1Eg4x3uqO6PQETH7v3BzeBA-n85uGg "crud jasperreport"

Untuk menjalankan aplikasi sederhana ini cukup mudah, yang harus dilakukan adalah :
    - Clone atau unduh zip file masternya dari link github ini
    - Buat database dengan nama terserah disesuaikan saja
    - Setting username dan password sesuai dengan yang ada di lingkungan local server
    - Buat tabel person seperti dibawah ini
    - Run Project selesai

```sql
CREATE SCHEMA `javalat` ;

CREATE TABLE `javalat`.`employees` (
  `employee_id` INT NOT NULL AUTO_INCREMENT,
  `full_name` VARCHAR(75) NULL,
  `gender` VARCHAR(45) NULL,
  `department` VARCHAR(45) NULL,
  `position` VARCHAR(45) NULL,
  `salary` DOUBLE NULL,
  PRIMARY KEY (`employee_id`));
```
