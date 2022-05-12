SELECT CustomerID, SiteID, Status, LastName, FirstName, Mid, Address1, Ssn, Grade, RecordCode, AttendanceStatus

FROM Customers

WHERE RecordCode  = 'active'

ORDER BY LastName, firstname, Mid# ActiveStudentListByName
