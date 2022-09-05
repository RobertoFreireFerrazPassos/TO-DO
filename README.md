# TO-DO


## Observability

https://github.com/RobertoFreireFerrazPassos/Observability

- Create UserApi and communicate with OrderApi via gRPC to get a user data. OrderApi will add this user data to the orderDto.
- Pass the traceKey header via gRPC message to UserAPI be used as distributed trace log like all the others apis.
- Understand and see how implement Circuit breaker or retry policy with Polly (https://makolyte.com/csharp-circuit-breaker-with-polly/)

## Design-Patterns

https://github.com/RobertoFreireFerrazPassos/Design-Patterns

- Finish read the book Book Head First Design Patterns: A Brain-Friendly Guid.
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

- Implement Endpoint to calculate receipt from order events
- Verify if it keeps order while sending and receiving events via rabbitmq. if not, it must implement to do so.
- Try to improve the repositories. Search for: "// TO DO"
- Fix bug: It is duplicating menu items in database
- Implement logic to avoid duplicate events in receiptapi when the kitchen api cannot save in outbox table after sending event

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

N + 1 issue
https://www.brentozar.com/archive/2018/07/common-entity-framework-problems-n-1/
