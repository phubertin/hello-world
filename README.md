# hello-world
--This is an example test. So, have a look.
--Voila je vous informe que ce processus est bel et bien en marche. Alors, prend soin de toi.

Create HumanResources.MyTeam:   
USE AdventureWorks;  
GO  
CREATE TABLE HumanResources.myTeam   
(EmployeeID smallint NOT NULL,  
Name nvarchar(50) NOT NULL,  
Title nvarchar(50) NULL,  
Background nvarchar(50) NOT NULL DEFAULT ''  
);  
GO  

USE AdventureWorks;  
GO  
INSERT INTO HumanResources.myTeam(EmployeeID,Name,Title,Background)  
   VALUES(77,'Mia Doppleganger','Administrative Assistant','Microsoft Office');  
GO  
INSERT INTO HumanResources.myTeam(EmployeeID,Name,Title,Background)  
   VALUES(49,'Hirum Mollicat','I.T. Specialist','Report Writing and Data Mining');  
GO  
