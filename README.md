# tugas-database
Soal Nomor 1 : SELECT * FROM [Customers] WHERE country = "Germany" OR country = "Mexico";

Soal Nomor 2 : SELECT * FROM [Products] WHERE Price < 15

Soal Nomor 3 : SELECT * FROM [Products] WHERE Price BETWEEN 10 AND 30

Soal Nomor 4 : SELECT * FROM [Customers] WHERE NOT Country = 'Brazil' AND NOT Country = 'Argentina' AND NOT Country = 'Mexico' AND NOT Country = 'Canada' AND NOT Country = 'USA' AND NOT Country = 'Venezuela'

Soal Nomor 5 : SELECT COUNT (Orders.OrderID), Customers.CustomerName
FROM Orders
INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID
WHERE CustomerName = 'Rattlesnake Canyon Grocery'

Soal Nomor 6 : SELECT Orders.OrderID, Shippers.ShipperName, Orders.OrderDate
FROM ((Orders
INNER JOIN Shippers ON Orders.ShipperID = Shippers.ShipperID))
WHERE ShipperName = 'Federal Shipping' AND OrderDate < '1996-12-01'

Soal Nomor 7 : INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID)
INNER JOIN OrderDetails ON Orders.OrderID = OrderDetails.OrderID)
INNER JOIN Products ON OrderDetails.ProductID = Products.ProductID)
WHERE CustomerName = 'Save-a-lot Markets';

Soal Nomor 8 : 
