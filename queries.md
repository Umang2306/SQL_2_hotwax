QUERIES

1\. Check status of your order SELECT Order_Id, Status FROM Order;

2.find total amount of your order SELECT SUM(Total_Amount) AS
Total_Order_Amount FROM Order

3.update you city UPDATE User SET City = \'Mumbai\' WHERE State =\'MP\'
;

4\. change product description UPDATE Products SET Product_Description =
\'product description.\' WHERE Product Name = \'Air Jordans\';

5\. Display returnable products SELECT \* FROM Product WHERE Product
Returnable= \'Yes\' ;
