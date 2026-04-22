---
title: "StiRuntimeVariables Class"
---

## StiRuntimeVariables Class

**Namespace:** `Stimulsoft.Report`  
**Assembly:** `Stimulsoft.Report`

Describes the class which allows to save and restore variables of a report.

```csharp
public class StiRuntimeVariables
```

### Inheritance

Implements: ICloneable  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiRuntimeVariables([StiReport](StiReport.md) report)` | Creates a new instance of the StiRuntimeVariables class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Column** | int |  |
| **DataSourcesPosition** | Hashtable |  |
| **Line** | int |  |
| **LineThrough** | int |  |
| **Page** | StiPage |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **SetVariables** | void | Sets runtime-variables to the specified report. |
