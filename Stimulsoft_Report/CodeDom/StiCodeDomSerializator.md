---
title: "StiCodeDomSerializator Class"
---

## StiCodeDomSerializator Class

**Namespace:** `Stimulsoft.Report.CodeDom`

The class serves to serialize into a code of a report.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConnectAggregatesBeginEnd** | void | Connect the delayed collection of aggregate functions to the events on the begin and the end. |
| **ContainsRemittedComponentInLast** | bool | Tests whether the collection is located in the component which formation is delayed to the end. |
| **ConvertExpressionToString** `static` | string |  |
| **ConvertTypeToString** `static` | string |  |
| **GetCheckerInfoString** `static` | string |  |
| **ReplaceSymbols** `static` *(+2 overloads)* | string | Replaces impossible symbols in the string on the symbol '_'. |

---

### Method Details

#### ConnectAggregatesBeginEnd

**ConnectAggregatesBeginEnd**(): void

Connect the delayed collection of aggregate functions to the events on the begin and the end.


---

#### ContainsRemittedComponentInLast

**ContainsRemittedComponentInLast**(**comp**: StiComponent): bool

Tests whether the collection is located in the component which formation is delayed to the end.

**Parameters**

- **comp** (StiComponent) — Component.  

**Returns** bool — Test results.


---

#### ConvertExpressionToString `static`

**ConvertExpressionToString**(**generator**: [StiCodeGenerator](StiCodeGenerator.md), **expression**: CodeExpression): string

**Parameters**

- **generator** ([StiCodeGenerator](StiCodeGenerator.md))  
- **expression** (CodeExpression)  

**Returns** string


---

#### ConvertTypeToString `static`

**ConvertTypeToString**(**type**: Type, **language**: [StiReportLanguageType](../root/StiReportLanguageType.md)): string

**Parameters**

- **type** (Type)  
- **language** ([StiReportLanguageType](../root/StiReportLanguageType.md))  

**Returns** string


---

#### GetCheckerInfoString `static`

**GetCheckerInfoString**(**componentName**: string, **propertyName**: string): string

**Parameters**

- **componentName** (string)  
- **propertyName** (string)  

**Returns** string


---

#### ReplaceSymbols `static`

**ReplaceSymbols**(**str**: string): string

Replaces impossible symbols in the string on the symbol '_'.

**Parameters**

- **str** (string) — String to change.  

**Returns** string — Changed string.

---

**ReplaceSymbols**(**str**: string, **report**: [StiReport](../root/StiReport.md)): string

**Parameters**

- **str** (string)  
- **report** ([StiReport](../root/StiReport.md))  

**Returns** string

---

**ReplaceSymbols**(**str**: string, **checkKeywords**: bool, **report**: [StiReport](../root/StiReport.md)): string

Replaces impossible symbols in the string on the symbol '_'.

**Parameters**

- **str** (string) — String to change.  
- **checkKeywords** (bool)  
- **report** ([StiReport](../root/StiReport.md))  

**Returns** string — Changed string.


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **StiCheckerInfoString** | string |  |
| **StrGenCode** | string |  |
