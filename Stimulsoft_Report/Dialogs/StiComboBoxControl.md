---
title: "StiComboBoxControl Class"
---

## StiComboBoxControl Class

**Namespace:** `Stimulsoft.Report.Dialogs`  
**Assembly:** `Stimulsoft.Report`

```csharp
public class StiComboBoxControl
```

### Inheritance

Inherits from: StiReportControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiComboBoxControl**() | Creates a new StiComboBoxControl. |
| **StiComboBoxControl**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiComboBoxControl. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Control** | ComboBox |  |
| **ItemsBinding** | string |  |
| **SelectedItemBinding** | string |  |
| **SelectedValueBinding** | string |  |
| **TextBinding** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefaultEvent** | StiEvent | Gets default event for this report control. |
| **GetEvents** | [StiEventsCollection](../Events/StiEventsCollection.md) | Return events collection of this component; |
| **InvokeSelectedIndexChanged** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |
