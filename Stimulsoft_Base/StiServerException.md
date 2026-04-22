---
title: "StiServerException Class"
---

## StiServerException Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

This class describes base class of Stimulsoft Server exceptions.

```csharp
public class StiServerException
```

### Inheritance

Inherits from: Exception  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiServerException(Exception innerException)` |  |
| `StiServerException(string message, Exception innerException)` |  |
| `StiServerException([StiNoticeIdent](StiNoticeIdent.md) noticeIdent, Exception innerException)` |  |
| `StiServerException([StiNotice](StiNotice.md) notice, Exception innerException)` |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Notice** | [StiNotice](StiNotice.md) |  |
