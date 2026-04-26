---
title: "StiTextInCells Class"
---

## StiTextInCells Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiText  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTextInCells**() | Creates a new StiTextInCells. |
| **StiTextInCells**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiTextInCells. |
| **StiTextInCells**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect, string text) | Creates a new StiTextInCells. |

**StiTextInCells**()

Creates a new StiTextInCells.

---

**StiTextInCells**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiTextInCells.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes size and position of the component.  

---

**StiTextInCells**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md), **text**: string)

Creates a new StiTextInCells.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes sizes and position of the component.  
- **text** (string) — Text expression.  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Convert** | void | Converts a component out of one unit into another. |
| **GetActualSize** | [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) |  |
| **IsExportAsImage** | bool |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Convert

**Convert**(**oldUnit**: [StiUnit](../Units/StiUnit.md), **newUnit**: [StiUnit](../Units/StiUnit.md), **isReportSnapshot**: bool): void

Converts a component out of one unit into another.

**Parameters**

- **oldUnit** ([StiUnit](../Units/StiUnit.md)) — Old units.  
- **newUnit** ([StiUnit](../Units/StiUnit.md)) — New units.  
- **isReportSnapshot** (bool)  


---

#### GetActualSize

**GetActualSize**(): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)


---

#### IsExportAsImage

**IsExportAsImage**(**format**: [StiExportFormat](../root/StiExportFormat.md)): bool

**Parameters**

- **format** ([StiExportFormat](../root/StiExportFormat.md))  

**Returns** bool


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **PropertyCellHeight** | object |  |
| **PropertyCellWidth** | object |  |
| **PropertyContinuousText** | object |  |
| **PropertyHorSpacing** | object |  |
| **PropertyVertSpacing** | object |  |
