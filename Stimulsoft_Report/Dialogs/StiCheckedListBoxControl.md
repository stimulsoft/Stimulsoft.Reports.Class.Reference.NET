---
title: "StiCheckedListBoxControl Class"
---

## StiCheckedListBoxControl Class

**Namespace:** `Stimulsoft.Report.Dialogs`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiCheckedListBoxControl
```

### Inheritance

Inherits from: StiReportControl  

### Constructors

| Constructor | Description |
| --- | --- |
| `StiCheckedListBoxControl()` | Creates a new StiCheckedListBoxControl. |
| `StiCheckedListBoxControl([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect)` | Creates a new StiCheckedListBoxControl. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Control** | CheckedListBox |  |
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
