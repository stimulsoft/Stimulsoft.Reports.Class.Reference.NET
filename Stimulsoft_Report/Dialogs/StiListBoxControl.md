---
title: "StiListBoxControl Class"
---

## StiListBoxControl Class

**Namespace:** `Stimulsoft.Report.Dialogs`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiListBoxControl
```

### Inheritance

Inherits from: StiReportControl  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiListBoxControl()` | Creates a new StiListBoxControl. |
| `StiListBoxControl([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect)` | Creates a new StiListBoxControl. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Control** | ListBox |  |
| **ItemsBinding** | string |  |
| **SelectedIndexBinding** | string |  |
| **SelectedItemBinding** | string |  |
| **SelectedValueBinding** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | StiEvent | Gets default event for this report control. |
| **GetEvents** | [StiEventsCollection](../Events/StiEventsCollection.md) | Return events collection of this component; |
| **InvokeSelectedIndexChanged** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
