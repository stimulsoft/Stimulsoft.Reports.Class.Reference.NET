---
title: "StiLanguage Class"
---

## StiLanguage Class

**Namespace:** `Stimulsoft.Report.CodeDom`

Base class for script languages description.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetGeneratedCode** `static` | string | Returns the automatically generated script from the text. |
| **GetGeneratedCodePos** `static` | void | Returns a position of the automatically generated script. |
| **GetProvider** | [StiCodeDomProvider](StiCodeDomProvider.md) | Returns a provider for this language. |
| **InsertGeneratedCode** `static` | string | Inserts the automatically generated script from the text. |
| **RemoveGeneratedCode** `static` | string | Removes the automatically generated script from the text. |
| **ReplaceGeneratedCode** `static` | string | Replace the automatically generated script for a new one. |

---

### Method Details

#### GetGeneratedCode `static`

**GetGeneratedCode**(**text**: string, **language**: [StiLanguage](StiLanguage.md)): string

Returns the automatically generated script from the text.

**Parameters**

- **text** (string) — Text contains script.  
- **language** ([StiLanguage](StiLanguage.md)) — Script language.  

**Returns** string — Script.


---

#### GetGeneratedCodePos `static`

**GetGeneratedCodePos**(**text**: string, **index**: int, **length**: int, **language**: [StiLanguage](StiLanguage.md)): void

Returns a position of the automatically generated script.

**Parameters**

- **text** (string) — Text contains script.  
- **index** (int) — Script position.  
- **length** (int) — Script length.  
- **language** ([StiLanguage](StiLanguage.md)) — Script language.  


---

#### GetProvider

**GetProvider**(): [StiCodeDomProvider](StiCodeDomProvider.md)

Returns a provider for this language.

**Returns** [StiCodeDomProvider](StiCodeDomProvider.md) — Provider.


---

#### InsertGeneratedCode `static`

**InsertGeneratedCode**(**text**: string, **script**: string, **language**: [StiLanguage](StiLanguage.md)): string

Inserts the automatically generated script from the text.

**Parameters**

- **text** (string) — The text which will be inserted into the script.  
- **script** (string) — Script for embedding.  
- **language** ([StiLanguage](StiLanguage.md)) — Script language.  

**Returns** string — Text with inserted script.


---

#### RemoveGeneratedCode `static`

**RemoveGeneratedCode**(**text**: string, **language**: [StiLanguage](StiLanguage.md)): string

Removes the automatically generated script from the text.

**Parameters**

- **text** (string) — Text contains script.  
- **language** ([StiLanguage](StiLanguage.md)) — Script language.  

**Returns** string — Text without script.


---

#### ReplaceGeneratedCode `static`

**ReplaceGeneratedCode**(**text**: string, **script**: string, **language**: [StiLanguage](StiLanguage.md)): string

Replace the automatically generated script for a new one.

**Parameters**

- **text** (string) — Text contains script.  
- **script** (string) — Script.  
- **language** ([StiLanguage](StiLanguage.md)) — Script language.  

**Returns** string — Text changed with script.

