# Brainwave_Matrix_Intern_Task2

𝗗𝗮𝘁𝗮𝗯𝗮𝘀𝗲 𝗠𝗮𝗻𝗮𝗴𝗲𝗺𝗲𝗻𝘁 𝗜𝗻𝘁𝗲𝗿𝗻

I have completed my given task by Brainwave Matrix Solutions.

Task Name : Develop a database for any entity you like i.e hospital ,library, school, movie rental, online store. This project involves more queries and database design. Write some SQL Queries.

I created a OnlineBookStore Database.In this Database I have created total 7 tables(entity) whiich contain different attributes and different values.

TABLES:

1] AUTHORS TABLE:

  1] author_id : This is the primary key in these table and datatype is int.

  2] Author_Name : The datatype is the varchar and these consist of the name of the author.

2] BOOKS TABLE :

  1] bookid : These is the primary keuy in this table and the datatype is int.These contain unique id of the book.

  2] bookName : Contains name of the book and the datatype is varchar.

  3] author_id : Contains id of the author and the datatype is int.These is the foreign key in these table which references authors.

  4] genre_id :  Contains id of the genre and the datatype is int.These is the foreign key in these table which references genre.

  5] isbn : Isbn stands for the 'international standard book number' and datatype is varchar.

  6] price : These attributes indicates the price of the book and the datatype of these attribute is float.

  7] stockquantity : Indicates the quantity of particular book available in store and datatype is int.

  8] publicationyear : Indicates the year of publication of particular book available in store and datatype is int.

3] CUSTOMER TABLE : 

  1] CUSTOMERID : These is the primary key in these table and the datatype is int.Contains unique id of the customer.

  2] Customer_Name : Contains name of the customer and the datatype is varchar.

  3] Address : Contains address of the customer and the datatype is varchar.

  4] mobileno : Contains mobile number of the customer and the datatype is varchar.

4] GENRE TABLE :

  1] genre_id : These is the primary key in these table and the datatype is int.Contains unique id of the genre.

  2] genre_name : Contains name/type of the genre and the datatype is varchar.

5] ORDERS TABLE :

  1] orderid : These is the primary key in these table and the datatype is int.Contains unique id of the genre.

  2] customerid : These is the foreign key in these table references customer and datatype is int.Contains unique id of the customer.

  3] orderdate : Contains date of the order when book is ordered and datatype is varchar.

  4] totalamount : Indicates total amount of the order and datatype is int.

  5] shipping_address : Indicates the shipping address where to delivered and datatype is varchar.

  6] orderstatus : These indicates order status and the datatype is varchar.

6] ORDERITEMS TABLE :

  1] orderitemid : Indicates id of the ordered item and the datatype is int.These is the primary key in these table.

  2] orderid : Indicates id of the order and the datatype is int.These is the foreign key in this table references orders.

  3] bookid : Indicates id of the book and the datatype is int.These is the foreign key in this table references books.

  4] quantity : Indicates quantity of the book which is order and the datatype is int.

  5] price : Indicates price and the datatype is int.

7] PAYMENT TABLE :

  1] PaymentId : Indicates unique id of the payment and the datatype is int.This is the primary key in these table.

  2] orderid : Indicates unique id of the order and the datatype is int.This is the foreign key references orders.

  3] paymentdate : Indicates date when the payment is done and the datatype should be varchar/date/datetime.

  4] paymentmethod : Indicates method of payment like by cash,upi etc and the datatype is varchar.

  5] amount : Indicates amount and the datatype is float.

  6] transactionid : Indicates id of the transaction and the datatype is varchar.

I also make the ER (Entity Relationship) Diagram .

And some basic queries  like insert,alter and update etc and some aggregate functions like max etc.

