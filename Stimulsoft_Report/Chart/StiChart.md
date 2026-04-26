---
title: "StiChart Class"
---

## StiChart Class

**Namespace:** `Stimulsoft.Report.Chart`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ChartInfoV1** | [StiChartInfoV1](StiChartInfoV1.md) |  |
| **ChartInfoV2** | [StiChartInfoV2](StiChartInfoV2.md) |  |
| **Core** | StiChartCoreXF |  |
| **CustomStyleName** | string |  |
| **EditorType** | StiChartEditorType? |  |
| **IsAnimation** | bool |  |
| **PreviousAnimations** | List<[StiAnimation](../Stimulsoft/Base/Context/Animation/StiAnimation.md)> |  |
| **Rotation** | [StiImageRotation](../Components/StiImageRotation.md) |  |
| **SortAnimation** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawChart** *(+1 overloads)* | void |  |
| **RenderAtEnd** | void |  |

---

### Method Details

#### DrawChart

**DrawChart**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **useMargins**: bool, **useBackground**: bool): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **useMargins** (bool)  
- **useBackground** (bool)  

---

**DrawChart**(**g**: [Graphics](../../Stimulsoft_Drawing/root/Graphics.md), **rect**: RectangleF, **useMargins**: bool, **useBackground**: bool, **zoom**: double): void

**Parameters**

- **g** ([Graphics](../../Stimulsoft_Drawing/root/Graphics.md))  
- **rect** (RectangleF)  
- **useMargins** (bool)  
- **useBackground** (bool)  
- **zoom** (double)  


---

#### RenderAtEnd

**RenderAtEnd**(): void

