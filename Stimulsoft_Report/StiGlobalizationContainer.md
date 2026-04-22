---
title: "StiGlobalizationContainer Class"
---

## StiGlobalizationContainer Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiGlobalizationContainer
```

### Inheritance

Implements: [IStiJsonReportObject](../Stimulsoft_Base/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGlobalizationContainer**() |  |
| **StiGlobalizationContainer**(string cultureName) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **CultureName** | string |  |
| **Items** | [StiGlobalizationItemCollection](StiGlobalizationItemCollection.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FillItemsFromReport** | void |  |
| **GetAllStringsForReport** | Hashtable | Internal use only. |
| **LoadFromJsonObject** | void |  |
| **LocalizeReport** | void |  |
| **RemoveUnlocalizedItemsFromReport** | void |  |
| **SaveToJsonObject** | [JObject](../Stimulsoft_Base/Json/Linq/JObject.md) |  |
