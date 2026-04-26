---
title: "StiDoughnutAreaIndicatorGeom Class"
---

## StiDoughnutAreaIndicatorGeom Class

**Namespace:** `Stimulsoft.Report.Chart`

### Inheritance

Inherits from: StiCellGeom  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDoughnutAreaIndicatorGeom**(RectangleF clientRectangle, string valueText, string titleText, IStiDoughnutAreaIndicator indicator) |  |

**StiDoughnutAreaIndicatorGeom**(**clientRectangle**: RectangleF, **valueText**: string, **titleText**: string, **indicator**: IStiDoughnutAreaIndicator)

**Parameters**

- **clientRectangle** (RectangleF)  
- **valueText** (string)  
- **titleText** (string)  
- **indicator** (IStiDoughnutAreaIndicator)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Indicator** | IStiDoughnutAreaIndicator |  |
| **TitleText** | string |  |
| **ValueText** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Draw** | void | Draws doughnut area indicator geom object on spefied context. |
| **DrawText** | void |  |

---

### Method Details

#### Draw

**Draw**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md)): void

Draws doughnut area indicator geom object on spefied context.

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  


---

#### DrawText

**DrawText**(**context**: [StiContext](../Stimulsoft/Base/Context/StiContext.md), **text**: string, **color**: Color, **rect**: RectangleF, **font**: [Font](../../Stimulsoft_Drawing/root/Font.md)): void

**Parameters**

- **context** ([StiContext](../Stimulsoft/Base/Context/StiContext.md))  
- **text** (string)  
- **color** (Color)  
- **rect** (RectangleF)  
- **font** ([Font](../../Stimulsoft_Drawing/root/Font.md))  

