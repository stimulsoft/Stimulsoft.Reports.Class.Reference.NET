---
title: "StiValidationSettings Class"
---

## StiValidationSettings Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Expression** | string |  |
| **ExpressionLevel** | [StiValidationLevel](StiValidationLevel.md) |  |
| **ExpressionMessage** | string |  |
| **Max** | string |  |
| **Min** | string |  |
| **PatternLevel** | [StiValidationLevel](StiValidationLevel.md) |  |
| **PatternMessage** | string |  |
| **PatternRegex** | string |  |
| **PatternType** | [StiValidationPatternType](StiValidationPatternType.md) |  |
| **RangeLevel** | [StiValidationLevel](StiValidationLevel.md) |  |
| **RangeMessage** | string |  |
| **Required** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Parse** `static` | [StiValidationSettings](StiValidationSettings.md) |  |
| **ToString** `static` *(+1 overloads)* | string |  |
| **Validate** | [StiValidationResult](StiValidationResult.md) |  |

---

### Method Details

#### Parse `static`

**Parse**(**validationString**: string): [StiValidationSettings](StiValidationSettings.md)

**Parameters**

- **validationString** (string)  

**Returns** [StiValidationSettings](StiValidationSettings.md)


---

#### ToString `static`

**ToString**(**settings**: [StiValidationSettings](StiValidationSettings.md)): string

**Parameters**

- **settings** ([StiValidationSettings](StiValidationSettings.md))  

**Returns** string

---

**ToString**(): string

**Returns** string


---

#### Validate

**Validate**(**value**: object, **type**: Type, **report**: [StiReport](../root/StiReport.md), **variable**: StiVariable): [StiValidationResult](StiValidationResult.md)

**Parameters**

- **value** (object)  
- **type** (Type)  
- **report** ([StiReport](../root/StiReport.md))  
- **variable** (StiVariable)  

**Returns** [StiValidationResult](StiValidationResult.md)

