---
title: "StiTableOfContents Class"
---

## StiTableOfContents Class

**Namespace:** `Stimulsoft.Report.Components`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiTableOfContents
```

### Inheritance

Inherits from: StiDataBand  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTableOfContents**() | Creates a new StiTableOfContents. |
| **StiTableOfContents**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiTableOfContents. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Indent** | int |  |
| **Margins** | [StiMargins](StiMargins.md) |  |
| **ReportPointer** | string |  |
| **Styles** | StiStylesCollection |  |
| **WordWrap** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **GetHeaderText** | string | Returns the band header text. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
