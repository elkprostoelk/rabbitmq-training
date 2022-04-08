# rabbitmq-training
RabbitMQ tasks<br>
Tasks are made using .NET Core 5 + RabbitMQ + Docker<br>
To run projects you need to have .NET 5 SDK and Docker Desktop installed (if rabbit is dockerized)<br>
Run <code>docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management</code><br>
Each solution has 2 projects: producer and consumer; they should be launched separately, using <code>dotnet run</code> in the each project's folder.
