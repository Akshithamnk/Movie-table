
BEGIN TRANSACTION;

/* Create a table called movies */
CREATE TABLE movies(Id integer PRIMARY KEY, Name text,Actor text,Actress text,Year integer,Director text);

/* Create few records in this table */
INSERT INTO movies VALUES(1,'Supreme','Sai Daram Tej','Rashi Khanna','2016','Anil ravipudi');
INSERT INTO movies VALUES(2,'Bahubali','Prabhas','Anushka Shetty','2015','S S Rajamouli');
INSERT INTO movies VALUES(3,'Fida','Varun Tej','Sai Pallavi','2017','Shekar Kammula');
INSERT INTO movies VALUES(4,'Arjun Suravaram','Nikhil','Lavanya','2019','Santhosh');
INSERT INTO movies VALUES(5,'Geetha Govindam','Vijay Devarakonda','Rashmika Mandanna','2018','Parasuram');
COMMIT;

/* Display all the records from the table */
SELECT * FROM movies;
