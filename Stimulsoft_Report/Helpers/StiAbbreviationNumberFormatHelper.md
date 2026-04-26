---
title: "StiAbbreviationNumberFormatHelper Class"
---

## StiAbbreviationNumberFormatHelper Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Format** `static` *(+2 overloads)* | string |  |
| **GetPostfixes** `static` | string[] |  |
| **GetThresholds** `static` | int[] |  |
| **SimpleAbbreviateNumber** `static` | string |  |

---

### Method Details

#### Format `static`

**Format**(**value**: double, **reportCulture**: string): string

**Parameters**

- **value** (double)  
- **reportCulture** (string)  

**Returns** string

---

**Format**(**value**: decimal, **reportCulture**: string): string

**Parameters**

- **value** (decimal)  
- **reportCulture** (string)  

**Returns** string

---

**Format**(**value**: decimal, **postfix**: string, **reportCulture**: string, **decimalDigits**: int, **totalNumberCapacity**: int?): decimal

**Parameters**

- **value** (decimal)  
- **postfix** (string)  
- **reportCulture** (string)  
- **decimalDigits** (int)  
- **totalNumberCapacity** (int?)  

**Returns** decimal


---

#### GetPostfixes `static`

**GetPostfixes**(**reportCulture**: string): string[]

**Parameters**

- **reportCulture** (string)  

**Returns** string[]


---

#### GetThresholds `static`

**GetThresholds**(): int[]

**Returns** int[]


---

#### SimpleAbbreviateNumber `static`

**SimpleAbbreviateNumber**(**number**: double): string

**Parameters**

- **number** (double)  

**Returns** string

