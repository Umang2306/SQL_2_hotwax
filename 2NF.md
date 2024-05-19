Second Normal Form (2NF)

ORDER TABLE CREATE CREATE TABLE Order ( Order_Id INT PRIMARY KEY,
Total_Amount INT NOT NULL, Date DATE NOT NULL, Status VARCHAR(255) NOT
NULL );

INSERT INSERT INTO Order (Order_Id, Total_Amount, Date, Status) VALUES
(1, 20000, \'2022-08-15\', \'Approved\'), (2, 25000, \'2022-08-15\',
\'Pending\'), (3, 20000, \'2022-08-17\', \'Shipped\');

USER TABLE CREATE CREATE TABLE User ( FirstName VARCHAR(255) NOT NULL,
LastName VARCHAR(255) NOT NULL, PinCode INT NOT NULL, City VARCHAR(255)
NOT NULL, State VARCHAR(255) NOT NULL );

INSERT INSERT INTO User (FirstName, LastName, PinCode, City, State)
VALUES (\'John\', \'Does\', 452001, \'Indore\', \'MP\'), (\'Mary\',
\'Ann\', 410014, \'Pune\', \'Maharashtra\');

PRODUCT TABLE CREATE

CREATE TABLE Products ( FirstName VARCHAR(255) NOT NULL, LastName
VARCHAR(255) NOT NULL, Product_Name VARCHAR(255) NOT NULL,
Product_Description VARCHAR(255), Retumable VARCHAR(255), Seller
VARCHAR(255), City VARCHAR(255) NOT NULL, State VARCHAR(255) NOT NULL,
PinCode INT NOT NULL );

INSERT

INSERT INTO Products (FirstName, LastName, Product_Name,
Product_Description, Retumable, Seller, City, State, PinCode) VALUES
(\'John\', \'Doe\', \'One Plus Nord\', \'Red Mobile Phone\', \'No\',
\'Seller Z\', \'Indore\', \'MP\', 452001), (\'John\', \'Doe\', \'Air
Jordans\', \'Shoes\', \'Yes\', \'Nike\', \'Indore\', \'M.P.\', 452001),
(\'Mary\', \'Ann\', \'One Plus Nord\', \'Red Mobile Phone\', \'No\',
\'Seller Z\', \'Pune\', \'Maharashtra\', 410014);
