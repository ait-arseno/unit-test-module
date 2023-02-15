# Java Unit Test Module

## Tentang Unit Test Module ini
Module ini adalah sebuah module yang membantu kita membentuk unit test berdasarkan standar struktur project yang sudah ditentukan.

Sejauh ini (`0.0.4-SNAPSHOT`) module ini sudah bisa digunakan untuk membentuk unit test di komponen-komponen berikut:


- [x] DTO
- [x] Mapstruct Mapper
- [x] Service Internal
- [x] Service Delegate

## Instalasi

Untuk saat ini, clone repo git ini, dan selanjutnya dapat melakukan salah satu dari berikut:

-----
### A. Maven
untuk PC yang sudah di-install Maven, bisa dengan menjalankan command berikut di command line:
> `mvn clean install`

### B. IDE
buka project ini di IDE pilihan anda, lalu jalankan maven clean dan maven install sesuai IDE masing-masing

----
Setelah melakukan maven install, module ini dapat digunakan di project yang akan dibuat Unit Testnya, dengan menambahkan dependency berikut pada pom.xml

```

<dependency>   
    <groupId>org.ait.module.java</groupId>
    <artifactId>unit-test-module</artifactId>
    <version>0.0.4-SNAPSHOT</version>
</dependency>
```
Setelah menambahkan ke POM, reload project agar dapat langsung mengimport dari module ini

## Contoh penggunaan
Contoh penggunaan module ini bisa dilihat di repo git [java-unittest-example](https://github.com/ait-arseno/java-unittest-example)