# JavaWeb-based-Online-Shopping-System-Development

## Here's an example and the steps to develop a basic JavaWeb online shopping system.

 To develop a JavaWeb online shopping system, we can use technologies such as **Java**, **Spring**, **Spring MVC**, **Hibernate**, etc.

### 1. Database design
First, we need to design and create the database structure for the shopping system. 
Here I choose the **MySQL** database.

And design the database structure as follows:
 - goods: id, name, description, price, image, category.
 - category: id, name.
 - user: id, username, password, address, phone, email.
 - order: id, orderNUM, userid, totalprice, orderstatus, order_time.
 - orderdetail: id, orderid, goods_id, quantity.
