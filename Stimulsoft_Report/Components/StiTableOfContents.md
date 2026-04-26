---
title: "StiTableOfContents Class"
---

## StiTableOfContents Class

**Namespace:** `Stimulsoft.Report.Components`

### Inheritance

Inherits from: StiDataBand  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTableOfContents**() | Creates a new StiTableOfContents. |
| **StiTableOfContents**([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) rect) | Creates a new StiTableOfContents. |

**StiTableOfContents**()

Creates a new StiTableOfContents.

---

**StiTableOfContents**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md))

Creates a new StiTableOfContents.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes sizes and position of the component.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Indent** | int |  |
| **Margins** | [StiMargins](StiMargins.md) |  |
| **ReportPointer** | string |  |
| **Styles** | StiStylesCollection |  |
| **WordWrap** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object | Creates a new object that is a copy of the current instance. |
| **GetHeaderText** | string | Returns the band header text. |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(**cloneProperties**: bool): object

Creates a new object that is a copy of the current instance.

**Parameters**

- **cloneProperties** (bool)  

**Returns** object — A new object that is a copy of this instance.


---

#### GetHeaderText

**GetHeaderText**(): string

Returns the band header text.

**Returns** string — Band header text.


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

