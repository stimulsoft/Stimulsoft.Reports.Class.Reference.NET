---
title: "StiQuickButtonHelper Class"
---

## StiQuickButtonHelper Class

**Namespace:** `Stimulsoft.Report.QuickButtons`

Summary description for StiQuickButtonHelper.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CheckVisibleQuickButtons** `static` | bool | Checks visibility of the quick button rectangle. |
| **GetQuickButtonRect** `static` | [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) | Returns quick button rectangle. |
| **GetQuickButtons** `static` | [StiQuickButton](StiQuickButton.md)[] |  |

---

### Method Details

#### CheckVisibleQuickButtons `static`

**CheckVisibleQuickButtons**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): bool

Checks visibility of the quick button rectangle.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — A rectangle of the component.  

**Returns** bool


---

#### GetQuickButtonRect `static`

**GetQuickButtonRect**(****: StiQuickButtonbuttons, **buttonIndex**: int, **rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

Returns quick button rectangle.

**Parameters**

- **** (StiQuickButtonbuttons)  
- **buttonIndex** (int) — An index of the quick button.  
- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — A rectangle of the component.  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) — Returns a rectangle of the quick button.


---

#### GetQuickButtons `static`

**GetQuickButtons**(**type**: Type): [StiQuickButton](StiQuickButton.md)[]

**Parameters**

- **type** (Type)  

**Returns** [StiQuickButton](StiQuickButton.md)[]

