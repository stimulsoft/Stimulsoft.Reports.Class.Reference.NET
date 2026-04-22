---
title: "DeflaterHuffman Class"
---

## DeflaterHuffman Class

**Namespace:** `Stimulsoft.Report.Export`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class DeflaterHuffman
```

### Constructors

| Constructor | Description |
| --- | --- |
| `DeflaterHuffman([DeflaterPending](DeflaterPending.md) pending)` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BitReverse** `static` | short |  |
| **CompressBlock** | void |  |
| **FlushBlock** | void |  |
| **FlushStoredBlock** | void |  |
| **IsFull** | bool |  |
| **Reset** | void |  |
| **SendAllTrees** | void |  |
| **TallyDist** | bool |  |
| **TallyLit** | bool |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **pending** | [DeflaterPending](DeflaterPending.md) |  |
