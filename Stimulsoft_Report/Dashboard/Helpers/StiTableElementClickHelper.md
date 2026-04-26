---
title: "StiTableElementClickHelper Class"
---

## StiTableElementClickHelper Class

**Namespace:** `Stimulsoft.Report.Dashboard.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetPointClick** `static` | PointD? |  |
| **InvokeTableHeaderClick** `static` | void |  |
| **ResetClick** `static` | void |  |
| **SetPointClick** `static` | void |  |

---

### Method Details

#### GetPointClick `static`

**GetPointClick**(**table**: IStiTableElement): PointD?

**Parameters**

- **table** (IStiTableElement)  

**Returns** PointD?


---

#### InvokeTableHeaderClick `static`

**InvokeTableHeaderClick**(**table**: IStiTableElement, **dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md), **columnKey**: string, **rect**: [RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)): void

**Parameters**

- **table** (IStiTableElement)  
- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **columnKey** (string)  
- **rect** ([RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md))  


---

#### ResetClick `static`

**ResetClick**(**table**: IStiTableElement): void

**Parameters**

- **table** (IStiTableElement)  


---

#### SetPointClick `static`

**SetPointClick**(**table**: IStiElement, **point**: [PointD](../../../Stimulsoft_Base/Drawing/PointD.md)): void

**Parameters**

- **table** (IStiElement)  
- **point** ([PointD](../../../Stimulsoft_Base/Drawing/PointD.md))  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **TableHeaderClick** | StiTableElementClickEventHandler |  |
