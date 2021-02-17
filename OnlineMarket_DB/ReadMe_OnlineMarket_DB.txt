-----Online Market_DB-----

1.)	This is a complete website for online market, which is connected to SQL sever with UI handling the CURD operations.

2.)	Product code is used as string as provided,and not a int sequence number in database.

3.)	Table was created with the below scripts

	Create Table Products(
	Productcode varchar(100) Primary Key,
	Name Varchar(100) Not Null,
	Price varchar(100) Not Null
	);



