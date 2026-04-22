---
title: "JsonContainerAttribute Class"
---

## JsonContainerAttribute Class

**Namespace:** `Stimulsoft.Base.Json`  
**Assembly:** `Stimulsoft.Base`

```csharp
public abstract class JsonContainerAttribute
```

### Inheritance

Inherits from: Attribute  

### Constructors

| Constructor | Description |
| --- | --- |
| **JsonContainerAttribute**() | Initializes a new instance of the JsonContainerAttribute class. |
| **JsonContainerAttribute**(string id) | Initializes a new instance of the JsonContainerAttribute class with the specified container Id. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Description** | string | Gets or sets the description. |
| **Id** | string | Gets or sets the id. |
| **ItemConverterParameters** | object[] | The parameter list to use when constructing the JsonConverter described by ItemConverterType. If null, the default constructor is used. When non-null, there must be a constructor defined in the JsonConverter that exactly matches the number, order, and type of these parameters. |
| **ItemConverterType** | Type | Gets the collection's items converter. |
| **Title** | string | Gets or sets the title. |
