---
title: "StiComponentDesigner Class"
---

## StiComponentDesigner Class

**Namespace:** `Stimulsoft.Report.Components.Design`  
**Assembly:** `Stimulsoft.Report`

Class describes base designer of components.

```csharp
public class StiComponentDesigner
```

### Inheritance

Implements: [IStiComponentDesigner](../IStiComponentDesigner.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiComponentDesigner**([IStiDesignerBase](../../Design/IStiDesignerBase.md) designer) | Creates a new designer of the component. |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Designer** | [IStiDesignerBase](../../Design/IStiDesignerBase.md) | Report designer. |
| **FirstRun** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateComponent** | StiComponent | Creates a component of the specified type. |
| **Design** | DialogResult | Calls the designer of the component. |
| **GetActionFromPoint** *(+1 overloads)* | [StiAction](../../../Stimulsoft_Report_Check/StiAction.md) |  |
| **GetComponentDesigner** `static` *(+1 overloads)* | [StiComponentDesigner](StiComponentDesigner.md) | Returns a designer of the component. |
| **OnDoubleClick** | void | Occurs when user DoubleClick on a the component in the designer. |
| **PointInRect** | [StiAction](../../../Stimulsoft_Report_Check/StiAction.md) | Returns the action fits to the position of a point in the specified rectangle. |
