Sample from : https://docs.microsoft.com/en-us/aspnet/core/tutorials/web-api-vsc

mkdir TodoApi
cd TodoApi
dotnet new webapi

1) Add a model class. TodoItem
2) Create the database context. TodoContext
3) Register a MemoryDatabase context with DI
4) Add a Empty controller. TodoController
5) Adding two GET methods into controller
    - GetAll()          GET /api/todo      http://localhost:5000/api/todo
    - GetById(long id)  GET /api/todo/{id}  http://localhost:5000/api/todo/1
6) Adding Create method