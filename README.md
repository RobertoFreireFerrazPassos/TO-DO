# TO-DO

## Platform

https://github.com/RobertoFreireFerrazPassos/Platform

- Create simple Angular
- User can customize a form (list of basic fields such as text and boolean)
- User can attach javascript to it, so it can use the form information to run inside this javascript in the backend

## Observability

https://github.com/RobertoFreireFerrazPassos/Observability

- Create UserApi and communicate with OrderApi via gRPC to get a user data. OrderApi will add this user data to the orderDto.
- Pass the traceKey header via gRPC message to UserAPI be used as distributed trace log like all the others apis.
- Understand and see how implement Circuit breaker or retry policy with Polly (https://makolyte.com/csharp-circuit-breaker-with-polly/)
- remove any object type if possible to avoid boxing

Serialization

- Understand serialization: serializable, Datamember, dataContract using system.runtime.Serialization, Client with jsonconvert.deserializeObject from newtonsoft

https://docs.microsoft.com/pt-br/dotnet/csharp/programming-guide/concepts/serialization/

https://docs.microsoft.com/pt-br/dotnet/api/system.serializableattribute?view=net-6.0

## Design-Patterns

https://github.com/RobertoFreireFerrazPassos/Design-Patterns

- Finish read the book Head First Design Patterns: A Brain-Friendly Guid.
- Continue from chapter 4. the Factory Pattern.

## dotNet-OOP

https://github.com/RobertoFreireFerrazPassos/dotNet-OOP

- Review everything to fix any mistake. Do this by testing in visual studio.
- Try to explain better.
- Complete any pending topic.

## Security

https://github.com/RobertoFreireFerrazPassos/Security

- Complete all pending topics.

## EventSourcing-and-Cqrs

https://github.com/RobertoFreireFerrazPassos/EventSourcing-and-Cqrs

- "This project uses" readme topic, add docker and authentication via JWT and identity to list
- Verify if it keeps order while sending and receiving events via rabbitmq. if not, it must implement to do so.
- Try to improve the repositories. Search for: "// TO DO"
- Fix bug: It is duplicating menu items in database
- Implement logic to avoid duplicate events in receiptapi when the kitchen api cannot save in outbox table after sending event

Docker

- Set all backend apis to run inside docker

Front End

- Create simple Front End using Angular
- Run project using docker
- remove "Steps to test" readme topic since it won't be necessary anymore
 
Auth

- Create User Authentication Api to login and logout
- Users will be set via migration
- Return JWT Token so each user can access allowed api 
- Add identity in each api

Receipt implementation

- Endpoint to calculate receipt from order events is not finished
- Use price property from inventory api
- Review and update databse schema if necessary

## Entity-Framework-Core

https://github.com/RobertoFreireFerrazPassos/Entity-Framework-Core

- Generate classes from Database-First approach using the schooldb
- use Fluent API
- Use transactions to update reports tables as well and roll back if necessary
- Create Repository Layer
- Use Sorting, Filtering and Paging
- Work with ChangeTracking in EF Core
- Work with Shadow Property in EF Core
- Add Logging in EF Core 
- Create procedures and call them using EF Core
- Use Linq
- Create mock test for the repository
- Create real data test in schooldb (Integration Test)
- Resolve N + 1 issue

## Algorithms_Data_Structures

https://github.com/RobertoFreireFerrazPassos/Algorithms_Data_Structures

- Add more Algorithms examples
- Add more Data Structures
- Review and complete Tree example
- For each Sort Algorithms, explain performance and Big O Notation

## Clean-Code-and-Refactoring

https://github.com/RobertoFreireFerrazPassos/Clean-Code-and-Refactoring

- Review  everything
- Try to add more topics

## Concurrent-and-Parallel-in-DotNet

https://github.com/RobertoFreireFerrazPassos/Concurrent-and-Parallel-in-DotNet

- Read Book Parallel Programming and Concurrency with C# 10 and .NET 6: A modern approach to building faster, more responsive, and asynchronous .NET applications using C#
- Update project while reading the book
