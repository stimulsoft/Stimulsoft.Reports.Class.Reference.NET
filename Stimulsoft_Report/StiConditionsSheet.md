---
title: "StiConditionsSheet Class"
---

## StiConditionsSheet Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

This class describes a list of conditions.

```csharp
public class StiConditionsSheet
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiConditionsSheet(StiConditionsCollection conditions)` | Creates a new object of the type StiConditionsSheet. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Conditions** | StiConditionsCollection |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** *(+1 overloads)* | void | Loads a list of conditionss from the stream. |
| **LoadFromJsonFile** | void | Loads a list of conditions from a json file. |
| **LoadFromString** | void | Loads conditions from a string. |
| **Save** *(+1 overloads)* | void | Saves a list of conditions in the stream. |
| **SaveToString** | string | Saves to a string this conditions. |
