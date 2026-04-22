---
title: "StiExcelHelper Class"
---

## StiExcelHelper Class

**Namespace:** `Stimulsoft.Base.Excel`  
**Assembly:** `Stimulsoft.Base`

```csharp
public static class StiExcelHelper
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowCache** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CleanCache** `static` | void |  |
| **GetDataSetFromExcelDocument** `static` | DataSet |  |
| **GetDataSetFromXlsWithoutTypes** `static` | DataSet | Convert a stream with an XLS file to a DataSet without taking into account the types (converted to String). |
| **GetDataSetFromXlsxWithoutTypes** `static` | DataSet | Convert a stream with an XLSX file to a DataSet without taking into account types (cast to String). |
