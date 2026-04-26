---
title: "StiXChartAxisTitle Class"
---

## StiXChartAxisTitle Class

**Namespace:** `Stimulsoft.Dashboard.Components.Chart`

### Inheritance

Inherits from: StiChartAxisTitle  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiXChartAxisTitle**() |  |
| **StiXChartAxisTitle**([Font](../../../Stimulsoft_Drawing/root/Font.md) font, string text, Color color, StringAlignment alignment, [StiDirection](../../../Stimulsoft_Report/Chart/StiDirection.md) direction, [StiTitlePosition](../../../Stimulsoft_Report/Chart/StiTitlePosition.md) position, bool visible) |  |

**StiXChartAxisTitle**()

---

**StiXChartAxisTitle**(**font**: [Font](../../../Stimulsoft_Drawing/root/Font.md), **text**: string, **color**: Color, **alignment**: StringAlignment, **direction**: [StiDirection](../../../Stimulsoft_Report/Chart/StiDirection.md), **position**: [StiTitlePosition](../../../Stimulsoft_Report/Chart/StiTitlePosition.md), **visible**: bool)

**Parameters**

- **font** ([Font](../../../Stimulsoft_Drawing/root/Font.md))  
- **text** (string)  
- **color** (Color)  
- **alignment** (StringAlignment)  
- **direction** ([StiDirection](../../../Stimulsoft_Report/Chart/StiDirection.md))  
- **position** ([StiTitlePosition](../../../Stimulsoft_Report/Chart/StiTitlePosition.md))  
- **visible** (bool)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Direction** | [StiDirection](../../../Stimulsoft_Report/Chart/StiDirection.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

