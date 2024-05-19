FIRST NORMAL FORM ORDER TABLE

CREATE CREATE TABLE Orders ( Order_ID VARCHAR(10) PRIMARY KEY,
First_Name VARCHAR(255), Last_Name VARCHAR(255), Product_Name
VARCHAR(255), Product_Description VARCHAR(255), Product_Reluma
VARCHAR(10), Seller_Name VARCHAR(255), Total_Price INT, Order_Date DATE,
Order_Status VARCHAR(255), Order_City VARCHAR(255), Order_State
VARCHAR(10), Pincode INT );

INSERT INSERT INTO Orders (Order_ID, First_Name, Last_Name,
Product_Name, Product_Description, Product_Reluma, Seller_Name,
Total_Price, Order_Date, Order_Status, Order_City, Order_State, Pincode)
VALUES (\'EILLIP\', \'John\', \'Doe\', \'One Plus Nord Phone\', \'Red
Mobile\', \'No\', \'Seller 2\', 20000, \'2002-08-15\', \'Approve\',
\'Indore\', \'MP\', 452001), (\'02\', \'John\', \'Doe\', \'Air Jorilares
Shoes\', \'\', \'Yes\', \'Niko\', 25000, \'2002-08-15\', \'Approve\',
\'Indore\', \'M.P.\', 457001), (\'00\', \'Mary\', \'Ann\', \'One Plus
Nord Phone\', \'Red Mobile\', \'No\', \'Seller 2\', 20000,
\'2002-08-15\', \'Approve\', \'Pune\', \'Mahara\', 410014);
