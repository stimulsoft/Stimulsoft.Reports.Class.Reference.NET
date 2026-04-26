---
title: "StiCodeDomExpressionHelper Class"
---

## StiCodeDomExpressionHelper Class

**Namespace:** `Stimulsoft.Report.CodeDom`

Describes class which contains static methods which helps parse expressions.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetLexem** `static` | List<string> |  |
| **GetLexemFullRtf** `static` | List<string> | Breaks the text value to the script and text. |
| **GetLexemSimple** `static` | List<string> |  |
| **ReadString** `static` | void |  |

---

### Method Details

#### GetLexem `static`

**GetLexem**(**script**: string): List<string>

**Parameters**

- **script** (string)  

**Returns** List<string>


---

#### GetLexemFullRtf `static`

**GetLexemFullRtf**(**codeGenerator**: [StiCodeGenerator](StiCodeGenerator.md), **script**: string, **richText**: StiRichText): List<string>

Breaks the text value to the script and text.

**Parameters**

- **codeGenerator** ([StiCodeGenerator](StiCodeGenerator.md))  
- **script** (string)  
- **richText** (StiRichText)  

**Returns** List<string> — Array of lexems.


---

#### GetLexemSimple `static`

**GetLexemSimple**(**codeGenerator**: [StiCodeGenerator](StiCodeGenerator.md), **script**: string, **richText**: StiRichText): List<string>

**Parameters**

- **codeGenerator** ([StiCodeGenerator](StiCodeGenerator.md))  
- **script** (string)  
- **richText** (StiRichText)  

**Returns** List<string>


---

#### ReadString `static`

**ReadString**(**codeGenerator**: [StiCodeGenerator](StiCodeGenerator.md), **pos**: int, **lexem**: StringBuilder, **script**: string, **al**: List<string>, **isRichText**: bool, **fullRtf**: bool): void

**Parameters**

- **codeGenerator** ([StiCodeGenerator](StiCodeGenerator.md))  
- **pos** (int)  
- **lexem** (StringBuilder)  
- **script** (string)  
- **al** (List<string>)  
- **isRichText** (bool)  
- **fullRtf** (bool)  

