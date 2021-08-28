# Assessment

The assessment is done as two part 
front end:- angular
backend : rest api using springboot  
spring boot application port is 8180 and angular application port is 4200

Get All Employees:
HTTP Method: GET
http://localhost:8180/api/v1/employees
------------------------------------------------------
Get Employee By Id:
HTTP Method GET
http://localhost:8180/api/v1/employees/{id}
----------------------------------------------------------
Create Employee:
HTTP Method - POST
http://localhost:8180/api/v1/employees

RequestBody
{
   "id":1234567,
    "employeeName":"Manal",
	"dateOfJoining":"2017-09-14T23:28:56.782Z",
	"salary":130000,
	"department":"AD"
}
-------------------------------------------------------------------
Update Employee
HTTP Method - POST
http://localhost:8180/api/v1/employees/{id}

RequestBody
{
   "id":1234567,
    "employeeName":"Manal",
	"dateOfJoining":"2017-09-14T23:28:56.782Z",
	"salary":130000,
	"department":"AD"
}
-----------------------------------------------
Delete Employee By Id:
HTTP Method - DELETE
http://localhost:8180/api/v1/employees/{id}
--------------------------------------------------------------
Search with employeeNumber and employee name
HTTP Method - GET
http://localhost:8180/api/v1/employees/{id}/{employeeName}











