---
title: "ANTLRStringStream Class"
---

## ANTLRStringStream Class

**Namespace:** `Stimulsoft.Data.Expressions.Antlr.Runtime`  
**Assembly:** `Stimulsoft.Data`

```csharp
public class ANTLRStringStream
```

### Inheritance

Implements: [ICharStream](ICharStream.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| `ANTLRStringStream()` |  |
| `ANTLRStringStream(string input)` |  |
| `ANTLRStringStream(string input, string sourceName)` |  |
| `ANTLRStringStream(chardata , int numberOfActualCharsInArray)` |  |
| `ANTLRStringStream(chardata , int numberOfActualCharsInArray, string sourceName)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Consume** | void |  |
| **LA** | int |  |
| **LT** | int |  |
| **Mark** | int |  |
| **Release** | void |  |
| **Reset** | void |  |
| **Rewind** *(+1 overloads)* | void |  |
| **Seek** | void |  |
| **Substring** | string |  |
| **ToString** | string |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **data** | char[] |  |
| **lastMarker** | int |  |
| **markDepth** | int |  |
| **markers** | IList<[CharStreamState](CharStreamState.md)> |  |
| **n** | int |  |
| **name** | string |  |
| **p** | int |  |
