# Instructions
## Existing code was given

1. Open the departments and employees SQL script and copy it into Azure Data Studio. Select the entire contents of the file and run it. This will create the database, and the tables, and insert some data.
1. In Visual Studio, create a new console application called DepartmentsEmployees.
1. In your terminal, navigate to the directory where you created your project. The directory will have a DepartmentsEmployees.sln file in it.
1. Run the following commands. This imports the required package needed to have your C# code connect to a SQL Server database.
```dotnet add package System.Data.SqlClient```
```dotnet restore```
1. Create or update the *.cs files with the code found below.
1. Run the application, fix any compiler errors (if any).
1. In Program.cs, complete the PrintDepartmentReport(string title, List<Department> departments).
1. Run the application, note the printed reports.
1. In Program.cs, complete the PrintEmployeeReport(string title, List<Employee> employees).
1. Run the application, note the printed reports.
1. Review the methods in Repository.cs.
1. Complete the unfinished methods in Repository.cs. Remember to test your work along the way!