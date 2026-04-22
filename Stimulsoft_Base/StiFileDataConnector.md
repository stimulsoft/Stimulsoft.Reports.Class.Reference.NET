---
title: "StiFileDataConnector Class"
---

## StiFileDataConnector Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public abstract class StiFileDataConnector
```

### Inheritance

Inherits from: [StiDataConnector](StiDataConnector.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **FileType** | [StiFileType](StiFileType.md) | A type of the file which can be processed with this connection helper. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [StiFileDataConnector](StiFileDataConnector.md) |  |
| **GetDataSet** | DataSet | Returns DataSet based on specified options. |
| **RetrieveSchema** | [StiDataSchema](StiDataSchema.md) | Returns schema object which contains information about structure of the database. Schema returned start at specified root element (if it applicable). |
| **TestConnection** | [StiTestConnectionResult](StiTestConnectionResult.md) | Returns StiTestConnectionResult that is the information of whether the connection string specified in this class is correct. |
