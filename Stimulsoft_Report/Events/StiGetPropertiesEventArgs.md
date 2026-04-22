---
title: "StiGetPropertiesEventArgs Class"
---

## StiGetPropertiesEventArgs Class

**Namespace:** `Stimulsoft.Report.Events`  
**Assembly:** `Stimulsoft.Report`

Describes an argument for the event GetProperties.

```csharp
public class StiGetPropertiesEventArgs
```

### Inheritance

Inherits from: EventArgs  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiGetPropertiesEventArgs**(objectselectedObjects , PropertyDescriptorCollection properties, System.Windows.Forms.PropertySort propertySort, Base.StiGuiMode guiMode) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **GuiMode** | Base.StiGuiMode |  |
| **Properties** | PropertyDescriptorCollection |  |
| **PropertySort** | System.Windows.Forms.PropertySort |  |
| **SelectedObjects** | object[] |  |
