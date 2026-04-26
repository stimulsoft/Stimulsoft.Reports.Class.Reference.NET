---
title: "DiagnosticsTraceWriter Class"
---

## DiagnosticsTraceWriter Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Represents a trace writer that writes to the application's TraceListener instances.

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

---

### Method Details

#### Trace

**Trace**(**level**: [TraceLevel](../TraceLevel.md), **message**: string, **ex**: Exception): void

Writes the specified trace level, message and optional exception.

**Parameters**

- **level** ([TraceLevel](../TraceLevel.md)) — The TraceLevel at which to write this trace.  
- **message** (string) — The trace message.  
- **ex** (Exception) — The trace exception. This parameter is optional.  

