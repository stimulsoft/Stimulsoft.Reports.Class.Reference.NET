---
title: "MemoryTraceWriter Class"
---

## MemoryTraceWriter Class

**Namespace:** `Stimulsoft.Base.Json.Serialization`

Represents a trace writer that writes to memory. When the trace message limit is reached then old trace messages will be removed as new messages are added.

### Inheritance

Implements: [ITraceWriter](ITraceWriter.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **MemoryTraceWriter**() | Initializes a new instance of the MemoryTraceWriter class. |

**MemoryTraceWriter**()

Initializes a new instance of the MemoryTraceWriter class.


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

---

### Method Details

#### GetTraceMessages

**GetTraceMessages**(): IEnumerable<string>

Returns an enumeration of the most recent trace messages.

**Returns** IEnumerable<string> — An enumeration of the most recent trace messages.


---

#### ToString

**ToString**(): string

Returns a String of the most recent trace messages.

**Returns** string — A String of the most recent trace messages.


---

#### Trace

**Trace**(**level**: [TraceLevel](../TraceLevel.md), **message**: string, **ex**: Exception): void

Writes the specified trace level, message and optional exception.

**Parameters**

- **level** ([TraceLevel](../TraceLevel.md)) — The TraceLevel at which to write this trace.  
- **message** (string) — The trace message.  
- **ex** (Exception) — The trace exception. This parameter is optional.  

