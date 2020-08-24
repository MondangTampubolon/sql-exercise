Create table CUSTOMERS

```sql

CREATE DATABASE impactbyte;

CREATE TABLE customers (
  id_customer int PRIMARY KEY NOT NULL AUTO_INCREMENT,
  full_name VARCHAR (20),
  username VARCHAR (10),
  email VARCHAR (20),
  no_HP VARCHAR ,
  address VARCHAR (30)
);

SHOW TABLE customers;

INSERT INTO `customers` (`id_customers`, `full_name`, `username`, `email`, `no_HP`, `address`) VALUES (NULL, `Harry Style`, `Harry`, `harryganteng@gmail.com`, `081234567899`, `Jl. merah merona`);
INSERT INTO `customers` (`id_customers`, `full_name`, `username`, `email`, `no_HP`, `address`) VALUES (NULL, `Taylor Swift`, `Tay Tay`, `taytaycuit@gmail.com`, `081235667856`, `Jl. pilu membiru`);
INSERT INTO `customers` (`id_customers`, `full_name`, `username`, `email`, `no_HP`, `address`) VALUES (NULL, `Dedi Dores`, `Dedi`, `dedidedi@gmail.com`, `081389767899`, `Jl. janur kuning`);
INSERT INTO `customers` (`id_customers`, `full_name`, `username`, `email`, `no_HP`, `address`) VALUES (NULL, `Patric Sandy`, `sandy`, `sandypatric@gmail.com`, `08123433899`, `Jl. hitam pekat`);
INSERT INTO `customers` (`id_customers`, `full_name`, `username`, `email`, `no_HP`, `address`) VALUES (NULL, `Juno Ali`, `juno`, `junoali@gmail.com`, `083123467899`, `Jl. putih bersih`);

SELECT * FROM customers;

```