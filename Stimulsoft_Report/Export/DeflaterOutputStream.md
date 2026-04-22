---
title: "DeflaterOutputStream Class"
---

## DeflaterOutputStream Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class DeflaterOutputStream
```

### Inheritance

Inherits from: Stream  

### Constructors

| Constructor | Description |
| --- | --- |
| **DeflaterOutputStream**(Stream baseOutputStream) |  |
| **DeflaterOutputStream**(Stream baseOutputStream, [Deflater](Deflater.md) defl) |  |
| **DeflaterOutputStream**(Stream baseOutputStream, [Deflater](Deflater.md) defl, int bufsize) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Close** | void |  |
| **Finish** | void |  |
| **Flush** | void |  |
| **Read** | int |  |
| **ReadByte** | int |  |
| **Seek** | long |  |
| **SetLength** | void |  |
| **Write** | void |  |
| **WriteByte** | void |  |
| **deflate** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **baseOutputStream** | Stream |  |
| **buf** | byte[] |  |
| **def** | [Deflater](Deflater.md) |  |
| **isStreamOwnerValue** | bool |  |
