---
title: "StiUnit Class"
---

## StiUnit Class

**Namespace:** `Stimulsoft.Report.Units`

Report units.

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Factor** | double | Gets the ruler scale in hundredths of inch on the one step. |
| **RollerStep** | double | Gets ruler step. |
| **ShortName** | string | Gets the shor unit name. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertFromHInches** *(+5 overloads)* | double | Converts a value from hundredths of inch into units of this class. |
| **ConvertToHInches** *(+5 overloads)* | double | Converts a value from hundredths of inch into units of this class. |
| **GetUnitFromReportUnit** `static` | [StiUnit](StiUnit.md) |  |
| **LoadFromJsonObject** `static` | [StiUnit](StiUnit.md) |  |
| **SaveToJsonObject** `static` | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### ConvertFromHInches

**ConvertFromHInches**(**value**: double): double

Converts a value from hundredths of inch into units of this class.

**Parameters**

- **value** (double) — Value for conversion.  

**Returns** double — Converted value.

---

**ConvertFromHInches**(**value**: decimal): decimal

Converts a value from hundredths of inch into units of this class.

**Parameters**

- **value** (decimal) — Value for conversion.  

**Returns** decimal — Converted value.

---

**ConvertFromHInches**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

Converts a rectangle from hundredths of inch into units of this class.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — Rectangle for conversion.  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) — Converted rectangle.

---

**ConvertFromHInches**(**rect**: [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)): [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)

Converts a rectangle from hundredths of inch into units of this class.

**Parameters**

- **rect** ([RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)) — Rectangle for conversion.  

**Returns** [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md) — Converted rectangle.

---

**ConvertFromHInches**(**size**: [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

Converts a size from hundredths of inch into units of this class.

**Parameters**

- **size** ([SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)) — Size for conversion.  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) — Converted size.

---

**ConvertFromHInches**(**size**: [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md)): [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md)

Converts a size from hundredths of inch into units of this class.

**Parameters**

- **size** ([SizeM](../../Stimulsoft_Base/Drawing/SizeM.md)) — Size for conversion.  

**Returns** [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md) — Converted size.


---

#### ConvertToHInches

**ConvertToHInches**(**value**: double): double

Converts a value from hundredths of inch into units of this class.

**Parameters**

- **value** (double) — Value for conversion.  

**Returns** double — Converted value.

---

**ConvertToHInches**(**value**: decimal): decimal

Converts a value from hundredths of inch into units of this class.

**Parameters**

- **value** (decimal) — Value for conversion.  

**Returns** decimal — Converted value.

---

**ConvertToHInches**(**rect**: [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)): [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)

Converts a rectangle from units of this class into hundredths of inch.

**Parameters**

- **rect** ([RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md)) — Rectangle for conversion.  

**Returns** [RectangleD](../../Stimulsoft_Base/Drawing/RectangleD.md) — Converted rectangle.

---

**ConvertToHInches**(**rect**: [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)): [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)

Converts a rectangle from units of this class into hundredths of inch.

**Parameters**

- **rect** ([RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md)) — Rectangle for conversion.  

**Returns** [RectangleM](../../Stimulsoft_Base/Drawing/RectangleM.md) — Converted rectangle.

---

**ConvertToHInches**(**size**: [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)): [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)

Converts a size from units of this class into hundredths of inch.

**Parameters**

- **size** ([SizeD](../../Stimulsoft_Base/Drawing/SizeD.md)) — Size for conversion.  

**Returns** [SizeD](../../Stimulsoft_Base/Drawing/SizeD.md) — Converted size.

---

**ConvertToHInches**(**size**: [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md)): [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md)

Converts a size from units of this class into hundredths of inch.

**Parameters**

- **size** ([SizeM](../../Stimulsoft_Base/Drawing/SizeM.md)) — Size for conversion.  

**Returns** [SizeM](../../Stimulsoft_Base/Drawing/SizeM.md) — Converted size.


---

#### GetUnitFromReportUnit `static`

**GetUnitFromReportUnit**(**reportUnit**: [StiReportUnitType](../root/StiReportUnitType.md)): [StiUnit](StiUnit.md)

**Parameters**

- **reportUnit** ([StiReportUnitType](../root/StiReportUnitType.md))  

**Returns** [StiUnit](StiUnit.md)


---

#### LoadFromJsonObject `static`

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): [StiUnit](StiUnit.md)

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  

**Returns** [StiUnit](StiUnit.md)


---

#### SaveToJsonObject `static`

**SaveToJsonObject**(**unit**: [StiUnit](StiUnit.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **unit** ([StiUnit](StiUnit.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **Centimeters** | [StiCentimetersUnit](StiCentimetersUnit.md) |  |
| **HundredthsOfInch** | [StiHundredthsOfInchUnit](StiHundredthsOfInchUnit.md) |  |
| **Inches** | [StiInchesUnit](StiInchesUnit.md) |  |
| **Millimeters** | [StiMillimetersUnit](StiMillimetersUnit.md) |  |
