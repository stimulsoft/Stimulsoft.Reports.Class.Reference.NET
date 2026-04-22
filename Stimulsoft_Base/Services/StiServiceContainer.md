---
title: "StiServiceContainer Class"
---

## StiServiceContainer Class

**Namespace:** `Stimulsoft.Base.Services`  
**Assembly:** `Stimulsoft.Base`

Describes class for access to container of services.

```csharp
public class StiServiceContainer
```

### Inheritance

Inherits from: CollectionBase  
Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiServiceContainer**() | Creates a new object of the type StiServiceContainer. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **StandardAssemblies** `static` | string[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** *(+1 overloads)* | void | Adds service to the container. |
| **AddRange** | void | Adds services to the container. |
| **Clear** | void | Clears all collection from service container. |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **Contains** *(+1 overloads)* | bool |  |
| **CreateService** `static` | [StiService](StiService.md) | Creates service. |
| **GetService** *(+2 overloads)* | [StiService](StiService.md) | Gets a service type. |
| **GetServices** *(+3 overloads)* | [StiServiceContainer](StiServiceContainer.md) | Gets all services of the type from the container. |
| **GetServicesFromAssembly** `static` *(+1 overloads)* | [StiServiceContainer](StiServiceContainer.md) | Returns services which are in the specified assembly. |
| **GetServicesNamesFromAssembly** `static` | ArrayList |  |
| **GetStandardServices** `static` | [StiServiceContainer](StiServiceContainer.md) | Gets a service container that contains all standard services. |
| **GetStandardServicesNames** `static` | ArrayList |  |
| **GetStringFromService** `static` *(+1 overloads)* | string | Returns string presentation of the service. |
| **IndexOf** | int |  |
| **Insert** | void |  |
| **Load** *(+2 overloads)* | void | Loads container of services. |
| **Remove** *(+2 overloads)* | void | Removes services of the type from the container. |
| **Save** *(+2 overloads)* | void | Saves container of services. |
| **ToArray** | [StiService](StiService.md)[] | Gets array of services, that contains in this service container. |
| **ToList** *(+1 overloads)* | List<T> |  |

### Events

| Event | Type | Description |
| --- | --- | --- |
| **BeforeGetService** | StiServiceActionHandler |  |
