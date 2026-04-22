---
title: "DiagnosticsTraceWriter Class"
---

## DiagnosticsTraceWriter Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`  
**Assembly:** `Stimulsoft.Base`

Represents a trace writer that writes to the application's TraceListener instances.

```csharp
public class DiagnosticsTraceWriter
```

### Inheritance

Implements: [ITraceWriter](ITraceWriter.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **LevelFilter** | [TraceLevel](../TraceLevel.md) | Gets the TraceLevel that will be used to filter the trace messages passed to the writer. For example a filter level of `Info` will exclude `Verbose` messages and include `Info`, `Warning` and `Error` messages. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Trace** | void | Writes the specified trace level, message and optional exception. |
