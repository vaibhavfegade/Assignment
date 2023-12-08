# Assignment

**Assignment.zip contains solution for C# Assignments**

**Solution for SQL Assignment:**

SELECT FirstName, LastName, ReportsTo, Position, Age,
CASE WHEN ReportsTo ='Jenny Richards' THEN 'CEO'
     Else 'NONE'
END
As "Boss Title" FROM maintable_7NQN3
Where ReportsTo = 'Jenny Richards' or ReportsTo is NULL
Order by Age
