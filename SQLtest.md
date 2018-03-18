# 1: Query to fetch city, postal code and customer name  for the people from country germany

SELECT City,PostalCode,CustomerName,Country from Customers where Country = "Germany"

# 2: get all the customer whose name start with D
SELECT *from Customers where CustomerName LIKE 'D%'

        
# 3: Get the order id of all the customersselect Orders.CustomerID,Orders.OrderID,Customers.CustomerName,Customers.Address,Customers.CustomerID AS CUTOMERIDOF FROM Orders
INNER JOIN Customers on Orders.CustomerID = Customers.CustomerID

# 4: Get the order date and customer name and quantity for each order
select Orders.OrderDate, Customers.CustomerName, OrderDetails.Quantity FROM ((Orders inner join OrderDetails on Orders.OrderID = OrderDetails.OrderID) inner join Customers on Orders.CustomerID = Customers.CustomerID);
# 5:  Get the shipper name of each order
 select Shippers.ShipperName, Shippers.Phone, Orders.OrderID from Shippers inner join Orders on Shippers.ShipperID = Orders.ShipperID
 order by OrderID desc
# 6: Count the number of suppliers from city USA
SELECT Count(SupplierName) from Suppliers where Country = 'USA'

# 7: Print the unique countries in from supplier table
select distinct Country from Suppliers order by Country

# 8: Get All the orders between 1996-07-12 and 1996-07-18
select OrderID,OrderDate from Orders where OrderDate Between '1996-07-04' and '1996-07-08'
# 9:  Get the customer name and customer address , employee first name and notes and orderID, shipper name and shipper contact number
select Customers.CustomerName, Customers.Address, Employees.FirstName, Employees.Notes, Orders.OrderID, Shippers.ShipperName,Shippers.Phone
from (((Orders inner join Customers on Orders.CustomerID = Customers.CustomerID) inner join Employees on Orders.EmployeeID = Employees.EmployeeID)
inner join Shippers on Orders.ShipperID = Shippers.ShipperID)

# 10: print the name of costliest product details
SELECT ProductName,Price from Products order by Price desc limit 2
select Price from Products order by Price desc limit 1

#11: Print the total number of quantity  ordered tis date
SELECT SUM(Quantity) from OrderDetails
