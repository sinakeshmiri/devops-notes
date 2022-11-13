# Queries:

**Keywords:**

SELECT:
```
SELECT  name
FROM patrons;
```
![image](https://user-images.githubusercontent.com/72389059/201511390-243e403a-c15e-4047-9daf-3c353ed87fdc.png)

![image](https://user-images.githubusercontent.com/72389059/201511366-16a961a7-b5c8-45dc-829e-17797b5ffbf0.png)
![image](https://user-images.githubusercontent.com/72389059/201511412-3772cfae-8c75-4837-885f-41933885620f.png)

*select all fileds:*
```
SELECT *
FROM patrons;
```
AS:

Aliasing is used rename columns
```
SELECT name AS first_name ,  year_hired
FROM employees;
```
![image](https://user-images.githubusercontent.com/72389059/201511871-414bd63a-13bb-4d55-9118-f1e708e1e905.png)

DISTINCT:

output only unique values

```
SELECT DISTINCT year_hired
FROM  empoyees;
```

![image](https://user-images.githubusercontent.com/72389059/201512070-30cb528b-563b-47f2-9f21-e1c8d42f7a68.png)

*multiple fiels*

![image](https://user-images.githubusercontent.com/72389059/201512155-5a996eb7-4d19-47f3-b63a-a2dab2da3d83.png)
![image](https://user-images.githubusercontent.com/72389059/201512161-5459de17-b3c7-435c-9284-cc8a6593af71.png)


VIEW:

virtual table that is result of a saved SQL SELECT statement

* when accessed , automatically update in respone to updates in the underlying data *

```

CREATE VIEW employee_hire_years AS /* add this lien to  your quey to create a view*/
SELECT id , name , year_hired
FROM employees;
```
query a view:


![image](https://user-images.githubusercontent.com/72389059/201512360-3b370b8e-8418-4898-aa4a-03b86a4ae215.png)



