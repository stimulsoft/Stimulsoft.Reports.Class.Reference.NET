---
title: "StiCodeDomSerializator Class"
---

## StiCodeDomSerializator Class

**Namespace:** `Stimulsoft.Report.CodeDom`  
**Assembly:** `Stimulsoft.Report`

The class serves to serialize into a code of a report.

```csharp
public class StiCodeDomSerializator
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectAggregatesBeginEnd** | void | Connect the delayed collection of aggregate functions to the events on the begin and the end. |
| **ContainsRemittedComponentInLast** | bool | Tests whether the collection is located in the component which formation is delayed to the end. |
| **ConvertExpressionToString** `static` | string |  |
| **ConvertTypeToString** `static` | string |  |
| **GetCheckerInfoString** `static` | string |  |
| **ReplaceSymbols** `static` *(+2 overloads)* | string | Replaces impossible symbols in the string on the symbol '_'. |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **StiCheckerInfoString** | string |  |
| **StrGenCode** | string |  |
