Create Database

```sql

CREATE DATABASE impactbyte;

CREATE TABLE products (
  id_products int PRIMARY KEY NOT NULL AUTO_INCREMENT,
  product_name VARCHAR,
  price int,
  stock int,
);

SHOW TABLE products;

INSERT INTO `products` (`id_products`, `product_name`, `price`, `stock`) 
VALUES (NULL, `tahu gejrot`, `15000`, `15`);
INSERT INTO `products` (`id_products`, `product_name`, `price`, `stock`) 
VALUES (NULL, `tempe mendoan`, `15000`, `13`);
INSERT INTO `products` (`id_products`, `product_name`, `price`, `stock`) 
VALUES (NULL, `ayam bakar`, `25000`, `11`);
INSERT INTO `products` (`id_products`, `product_name`, `price`, `stock`) 
VALUES (NULL, `es teh manis`, `5000`, `20`);
INSERT INTO `products` (`id_products`, `product_name`, `price`, `stock`) 
VALUES (NULL, `rujak cingur`, `20000`, `6`);

SHOW TABLE PRODUCTS




```