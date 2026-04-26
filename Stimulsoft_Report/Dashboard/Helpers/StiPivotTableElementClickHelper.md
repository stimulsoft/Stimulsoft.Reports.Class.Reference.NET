---
title: "StiPivotTableElementClickHelper Class"
---

## StiPivotTableElementClickHelper Class

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

**GetPointClick**(**table**: IStiPivotTableElement): PointD?

**Parameters**

- **table** (IStiPivotTableElement)  

**Returns** PointD?


---

#### InvokeTableHeaderClick `static`

**InvokeTableHeaderClick**(**table**: IStiPivotTableElement, **meterKey**: string): void

**Parameters**

- **table** (IStiPivotTableElement)  
- **meterKey** (string)  


---

#### ResetClick `static`

**ResetClick**(**table**: IStiPivotTableElement): void

**Parameters**

- **table** (IStiPivotTableElement)  


---

#### SetPointClick `static`

**SetPointClick**(**table**: IStiElement, **point**: [PointD](../../../Stimulsoft_Base/Drawing/PointD.md)): void

**Parameters**

- **table** (IStiElement)  
- **point** ([PointD](../../../Stimulsoft_Base/Drawing/PointD.md))  


### Events

| Event | Type | Description |
| --- | --- | --- |
| **TableHeaderClick** | StiPivotTableElementClickEventHandler |  |
