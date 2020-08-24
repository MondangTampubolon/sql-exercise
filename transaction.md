Create table TRANSACTION

```sql
 
 create table transactions(
        id_transaction int primary key auto_increment,
        id_product int,
        id_customer int,
        foreign key (id_product) references products(id_product),
        foreign key (id_customer) references customers(id_customer)
    );
  insert into transactions(id_product, id_customer)
  value(NULL, 3,5);
  insert into transactions(id_product, id_customer)
  value(NULL, 3,2);
  

       

```