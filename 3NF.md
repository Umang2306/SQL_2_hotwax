Third Normal form(3NF)

USER TABLE CREATE CREATE TABLE User ( User_Id VARCHAR(255) PRIMARY KEY,
First_Name VARCHAR(255) NOT NULL, Last_Name VARCHAR(255) NOT NULL,
Pin_Code INT NOT NULL );

INSERT INSERT INTO User (User_Id, First_Name, Last_Name, Pin_Code)
VALUES (\'U1\', \'John\', \'Doe\', 452001), (\'U2\', \'Mary\', \'Ann\',
410014);

ADDRESS TABLE CREATE CREATE TABLE Address ( Pin_Code INT PRIMARY KEY,
City VARCHAR(255) NOT NULL, State VARCHAR(255) NOT NULL, FOREIGN KEY
(Pin_Code) REFERENCES User(Pin_Code) );

INSERT INSERT INTO Address (Pin_Code, City, State) VALUES (452001,
\'Indore\', \'MP\'), (410014, \'Pune\', \'Maharashtra\');
