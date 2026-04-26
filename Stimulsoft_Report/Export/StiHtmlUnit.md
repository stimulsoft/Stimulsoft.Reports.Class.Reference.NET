---
title: "StiHtmlUnit Class"
---

## StiHtmlUnit Class

**Namespace:** `Stimulsoft.Report.Export`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **IsNullOrZero** `static` | bool |  |
| **NewUnit** `static` *(+2 overloads)* | [StiHtmlUnit](StiHtmlUnit.md) |  |
| **ToPixelString** `static` | string |  |
| **ToString** | string |  |

---

### Method Details

#### IsNullOrZero `static`

**IsNullOrZero**(**unit**: [StiHtmlUnit](StiHtmlUnit.md)): bool

**Parameters**

- **unit** ([StiHtmlUnit](StiHtmlUnit.md))  

**Returns** bool


---

#### NewUnit `static`

**NewUnit**(**value**: double): [StiHtmlUnit](StiHtmlUnit.md)

**Parameters**

- **value** (double)  

**Returns** [StiHtmlUnit](StiHtmlUnit.md)

---

**NewUnit**(**value**: double, **unitType**: StiHtmlUnitType): [StiHtmlUnit](StiHtmlUnit.md)

**Parameters**

- **value** (double)  
- **unitType** (StiHtmlUnitType)  

**Returns** [StiHtmlUnit](StiHtmlUnit.md)

---

**NewUnit**(**value**: double, **usePoints**: bool): [StiHtmlUnit](StiHtmlUnit.md)

**Parameters**

- **value** (double)  
- **usePoints** (bool)  

**Returns** [StiHtmlUnit](StiHtmlUnit.md)


---

#### ToPixelString `static`

**ToPixelString**(**value**: int): string

**Parameters**

- **value** (int)  

**Returns** string


---

#### ToString

**ToString**(): string

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **UnitType** | StiHtmlUnitType |  |
| **Value** | double |  |
