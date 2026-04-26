---
title: "StiValidationResult Class"
---

## StiValidationResult Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **IsValid** | bool |  |
| **Level** | [StiValidationLevel](StiValidationLevel.md) |  |
| **Message** | string |  |
| **PropertyName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Fail** `static` | [StiValidationResult](StiValidationResult.md) |  |
| **Success** `static` | [StiValidationResult](StiValidationResult.md) |  |
| **Warning** `static` | [StiValidationResult](StiValidationResult.md) |  |

---

### Method Details

#### Fail `static`

**Fail**(**message**: string, **level**: [StiValidationLevel](StiValidationLevel.md)): [StiValidationResult](StiValidationResult.md)

**Parameters**

- **message** (string)  
- **level** ([StiValidationLevel](StiValidationLevel.md))  

**Returns** [StiValidationResult](StiValidationResult.md)


---

#### Success `static`

**Success**(): [StiValidationResult](StiValidationResult.md)

**Returns** [StiValidationResult](StiValidationResult.md)


---

#### Warning `static`

**Warning**(**message**: string): [StiValidationResult](StiValidationResult.md)

**Parameters**

- **message** (string)  

**Returns** [StiValidationResult](StiValidationResult.md)

