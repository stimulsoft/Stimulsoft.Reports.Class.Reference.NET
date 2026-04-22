---
title: "StiType Class"
---

## StiType Class

**Namespace:** `Stimulsoft.Report.Dictionary`  
**Assembly:** `Stimulsoft.Report`

This class describes wrapper for type registered in dictionary data.

```csharp
public class StiType
```

### Constructors

| Constructor | Description |
| --- | --- |
| **StiType**(string name, Type type) | Creates a new object of the type StiType. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Name** | string | Gets or sets name of type. |
| **Type** | Type | Gets or sets the registered type. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBaseTypes** `static` | [StiTypesCollection](StiTypesCollection.md) | Returns the collection of all base registered types in dictionary data. |
| **GetTypeFromTypeMode** `static` | Type |  |
| **GetTypeModeFromType** `static` | Type |  |
| **GetTypes** `static` | [StiTypesCollection](StiTypesCollection.md) | Returns the collection of all registered types in dictionary data. |
| **IsDateTimeType** `static` | bool |  |
| **IsFloatType** `static` | bool |  |
| **IsIntegerType** `static` | bool |  |
| **ToString** | string |  |
