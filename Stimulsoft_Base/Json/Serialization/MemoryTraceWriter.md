---
title: "MemoryTraceWriter Class"
---

## MemoryTraceWriter Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Represents a trace writer that writes to memory. When the trace message limit is reached then old trace messages will be removed as new messages are added.

```csharp
public class MemoryTraceWriter
```

### Inheritance

Implements: [ITraceWriter](ITraceWriter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **MemoryTraceWriter**() | Initializes a new instance of the MemoryTraceWriter class. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LevelFilter** | [TraceLevel](../TraceLevel.md) | Gets the TraceLevel that will be used to filter the trace messages passed to the writer. For example a filter level of `Info` will exclude `Verbose` messages and include `Info`, `Warning` and `Error` messages. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetTraceMessages** | IEnumerable<string> | Returns an enumeration of the most recent trace messages. |
| **ToString** | string | Returns a String of the most recent trace messages. |
| **Trace** | void | Writes the specified trace level, message and optional exception. |
