---
title: "StiRangeSelectorHelper Class"
---

## StiRangeSelectorHelper Class

**Namespace:** `Stimulsoft.Dashboard.Components.RangeSelector`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CalculateAutoStep** `static` | decimal |  |
| **CalculateNiceTicks** `static` | List<decimal> |  |
| **FormatValue** `static` *(+2 overloads)* | string |  |
| **GetAutoRange** `static` | [DecimalRange](../../../Stimulsoft_Report/root/DecimalRange.md) |  |
| **GetRangeInitialValue** `static` | [DecimalRange](../../../Stimulsoft_Report/root/DecimalRange.md) |  |
| **IsArgumentDateTime** `static` | bool |  |
| **TryToNullableDecimal** `static` | decimal? |  |

---

### Method Details

#### CalculateAutoStep `static`

**CalculateAutoStep**(**min**: decimal, **max**: decimal, **isDateTime**: bool, **maxTicks**: int): decimal

**Parameters**

- **min** (decimal)  
- **max** (decimal)  
- **isDateTime** (bool)  
- **maxTicks** (int)  

**Returns** decimal


---

#### CalculateNiceTicks `static`

**CalculateNiceTicks**(**min**: decimal, **max**: decimal, **isDateTime**: bool, **maxTicks**: int): List<decimal>

**Parameters**

- **min** (decimal)  
- **max** (decimal)  
- **isDateTime** (bool)  
- **maxTicks** (int)  

**Returns** List<decimal>


---

#### FormatValue `static`

**FormatValue**(**element**: StiRangeSelectorElement, **value**: decimal): string

**Parameters**

- **element** (StiRangeSelectorElement)  
- **value** (decimal)  

**Returns** string

---

**FormatValue**(**element**: StiRangeSelectorElement, **value**: DateTime): string

**Parameters**

- **element** (StiRangeSelectorElement)  
- **value** (DateTime)  

**Returns** string

---

**FormatValue**(**element**: StiRangeSelectorElement, **value**: object): string

**Parameters**

- **element** (StiRangeSelectorElement)  
- **value** (object)  

**Returns** string


---

#### GetAutoRange `static`

**GetAutoRange**(**element**: StiRangeSelectorElement): [DecimalRange](../../../Stimulsoft_Report/root/DecimalRange.md)

**Parameters**

- **element** (StiRangeSelectorElement)  

**Returns** [DecimalRange](../../../Stimulsoft_Report/root/DecimalRange.md)


---

#### GetRangeInitialValue `static`

**GetRangeInitialValue**(**element**: StiRangeSelectorElement): [DecimalRange](../../../Stimulsoft_Report/root/DecimalRange.md)

**Parameters**

- **element** (StiRangeSelectorElement)  

**Returns** [DecimalRange](../../../Stimulsoft_Report/root/DecimalRange.md)


---

#### IsArgumentDateTime `static`

**IsArgumentDateTime**(**element**: StiRangeSelectorElement): bool

**Parameters**

- **element** (StiRangeSelectorElement)  

**Returns** bool


---

#### TryToNullableDecimal `static`

**TryToNullableDecimal**(**element**: StiRangeSelectorElement, **value**: object): decimal?

**Parameters**

- **element** (StiRangeSelectorElement)  
- **value** (object)  

**Returns** decimal?

