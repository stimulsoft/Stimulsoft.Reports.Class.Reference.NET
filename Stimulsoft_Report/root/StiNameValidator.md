---
title: "StiNameValidator Class"
---

## StiNameValidator Class

**Namespace:** `Stimulsoft.Report`

The class serves to serialize into a code of a report.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CorrectBusinessObjectName** `static` *(+1 overloads)* | string |  |
| **CorrectName** `static` *(+2 overloads)* | string | Replaces incorrect symbols in the string on the symbol '_'. |

---

### Method Details

#### CorrectBusinessObjectName `static`

**CorrectBusinessObjectName**(**str**: string, **isDataExpression**: bool): string

**Parameters**

- **str** (string)  
- **isDataExpression** (bool)  

**Returns** string

---

**CorrectBusinessObjectName**(**str**: string, **report**: [StiReport](StiReport.md), **isDataExpression**: bool): string

**Parameters**

- **str** (string)  
- **report** ([StiReport](StiReport.md))  
- **isDataExpression** (bool)  

**Returns** string


---

#### CorrectName `static`

**CorrectName**(**str**: string, **isDataExpression**: bool): string

Replaces incorrect symbols in the string on the symbol '_'.

**Parameters**

- **str** (string) — String to change.  
- **isDataExpression** (bool)  

**Returns** string — Changed string.

---

**CorrectName**(**str**: string, **checkKeywords**: bool, **isDataExpression**: bool): string

Replaces incorrect symbols in the string on the symbol '_'.

**Parameters**

- **str** (string) — String to change.  
- **checkKeywords** (bool) — Check string for keywords  
- **isDataExpression** (bool)  

**Returns** string — Changed string.

---

**CorrectName**(**str**: string, **report**: [StiReport](StiReport.md), **isDataExpression**: bool): string

Replaces incorrect symbols in the string on the symbol '_'.

**Parameters**

- **str** (string) — String to change.  
- **report** ([StiReport](StiReport.md)) — Report to get ScriptLanguage info  
- **isDataExpression** (bool)  

**Returns** string — Changed string.

