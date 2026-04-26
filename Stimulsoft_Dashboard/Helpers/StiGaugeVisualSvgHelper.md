---
title: "StiGaugeVisualSvgHelper Class"
---

## StiGaugeVisualSvgHelper Class

**Namespace:** `Stimulsoft.Dashboard.Helpers`

This class helps to work with gauge visual object though SVG format.

### Inheritance

Implements: [IStiGaugeVisualSvgHelper](../../Stimulsoft_Report/Dashboard/Visuals/IStiGaugeVisualSvgHelper.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetEmptyDataGauge** | StiGauge |  |
| **WriteGauge** *(+1 overloads)* | void |  |

---

### Method Details

#### GetEmptyDataGauge

**GetEmptyDataGauge**(**gaugeElement**: StiGaugeElement): StiGauge

**Parameters**

- **gaugeElement** (StiGaugeElement)  

**Returns** StiGauge


---

#### WriteGauge

**WriteGauge**(**writer**: XmlTextWriter, **svgData**: [StiSvgData](../../Stimulsoft_Report/Export/StiSvgData.md), **needAnimation**: bool, **needToVertScroll**: bool, **contentHeight**: int, **isStyleSample**: bool): void

**Parameters**

- **writer** (XmlTextWriter)  
- **svgData** ([StiSvgData](../../Stimulsoft_Report/Export/StiSvgData.md))  
- **needAnimation** (bool)  
- **needToVertScroll** (bool)  
- **contentHeight** (int)  
- **isStyleSample** (bool)  

---

**WriteGauge**(**writer**: XmlTextWriter, **svgData**: [StiSvgData](../../Stimulsoft_Report/Export/StiSvgData.md), **needAnimation**: bool, **isStyleSample**: bool): void

**Parameters**

- **writer** (XmlTextWriter)  
- **svgData** ([StiSvgData](../../Stimulsoft_Report/Export/StiSvgData.md))  
- **needAnimation** (bool)  
- **isStyleSample** (bool)  

