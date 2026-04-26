---
title: "StiQuickButton Class"
---

## StiQuickButton Class

**Namespace:** `Stimulsoft.Report.QuickButtons`

The class describes the base type for the quick button.

### Inheritance

Implements: IDisposable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Image** | [Image](../../Stimulsoft_Drawing/root/Image.md) | Gets image of the quick button. |
| **IsSelected** | bool | Gets or sets value which indicates this quick button is selected. |
| **Name** | string | Gets name of the quick button. |
| **SelectedImage** | [Image](../../Stimulsoft_Drawing/root/Image.md) | Gets selected image of the quick button. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Dispose** | void | Dispose this quick button. |
| **OnClick** | void |  |

---

### Method Details

#### Dispose

**Dispose**(): void

Dispose this quick button.


---

#### OnClick

**OnClick**(**control**: Control, **pos**: Point, **component**: StiComponent, **designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md)): void

**Parameters**

- **control** (Control)  
- **pos** (Point)  
- **component** (StiComponent)  
- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md))  

