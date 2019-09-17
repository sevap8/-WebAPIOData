# -WebAPIOData
How to Use Web API OData to Build an OData V4 Service without Entity Framework.
In this article, we will show how to build an OData service using in-memory data as data source and with basic function.
Service document

http://localhost:[portNumber]/

Service metadata

http://localhost:[portNumber]/$metadata

Get People

http://localhost:[portNumber]/People

Queries

http://localhost:[portNumber]/People?$filter=contains(Description,'Lorem')

http://localhost:[portNumber]/People?$select=Name

http://localhost:[portNumber]/People?$expand=Trips
