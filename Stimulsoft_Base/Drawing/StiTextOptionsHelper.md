---
title: "StiTextOptionsHelper Class"
---

## StiTextOptionsHelper Class

**Namespace:** `Stimulsoft.Base.Drawing`

### Inheritance

Inherits from: TypeConverter  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertStringToTextOptions** `static` | StiTextOptions |  |
| **ConvertTextOptionsToLocalizedString** `static` *(+1 overloads)* | string |  |
| **ConvertTextOptionsToString** `static` | string |  |

---

### Method Details

#### ConvertStringToTextOptions `static`

**ConvertStringToTextOptions**(**str**: string, **separator**: char): StiTextOptions

**Parameters**

- **str** (string)  
- **separator** (char)  

**Returns** StiTextOptions


---

#### ConvertTextOptionsToLocalizedString `static`

**ConvertTextOptionsToLocalizedString**(**op**: StiTextOptions, **wordWrap**: bool): string

**Parameters**

- **op** (StiTextOptions)  
- **wordWrap** (bool)  

**Returns** string

---

**ConvertTextOptionsToLocalizedString**(**op**: StiTextOptions, **separator**: char, **wordWrap**: bool): string

**Parameters**

- **op** (StiTextOptions)  
- **separator** (char)  
- **wordWrap** (bool)  

**Returns** string


---

#### ConvertTextOptionsToString `static`

**ConvertTextOptionsToString**(**op**: StiTextOptions, **separator**: char): string

**Parameters**

- **op** (StiTextOptions)  
- **separator** (char)  

**Returns** string

