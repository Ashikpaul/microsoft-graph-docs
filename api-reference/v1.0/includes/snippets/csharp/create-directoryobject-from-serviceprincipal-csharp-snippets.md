---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var directoryObject = new DirectoryObject
{
	Id = "{id}"
};

await graphClient.ServicePrincipals["{id}"].Owners.References
	.Request()
	.AddAsync(directoryObject);

```