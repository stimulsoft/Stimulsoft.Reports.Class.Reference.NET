---
title: "StiSerializeTypes Enum"
---

## StiSerializeTypes Enum

**Namespace:** `Stimulsoft.Base.Serializing`  
**Assembly:** `Stimulsoft.Base`

```csharp
public enum StiSerializeTypes
```

### Members

| Member | Value | Description |
| --- | --- | --- |
| **SerializeToAll** | 15 | Serialize for all variations. |
| **SerializeToCode** | 1 | Serialize in the code only. |
| **SerializeToDesigner** | 2 | Serialize for the designer only. |
| **SerializeToSaveLoad** | 4 | Serialize for save or load only. |
| **SerializeToDocument** | 8 | Serialize for document only. |
| **SerializeToAllExceptCode** | SerializeToDesigner \| SerializeToSaveLoad \| SerializeToDocument | Serialize for all variations except code |
| **SerializeToAllExceptDocument** | SerializeToDesigner \| SerializeToSaveLoad \| SerializeToCode | Serialize for all variations except document |
