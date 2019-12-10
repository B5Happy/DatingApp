## The Back-end

The back-end of this app is done in .Net Core 3. It's a Web API.
So to start a project of .net core we can do in the console :
dotnet new webapi

To run the project:
dotnet run (it will run on localhost:5000)

To restart the server when change happen we can use :
dotnet watch run

To create a database from your model:
dotnet ef migrations add InitialCreate

To create the database:
dotnet ef database update

## Angular (Front-end)

Install Angular:
npm install -g @angular/cli

Create Angular project:
ng new nameOfTheProject