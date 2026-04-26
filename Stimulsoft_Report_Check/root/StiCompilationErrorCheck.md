---
title: "StiCompilationErrorCheck Class"
---

## StiCompilationErrorCheck Class

**Namespace:** `Stimulsoft.Report.Check`

### Inheritance

Inherits from: [StiReportCheck](StiReportCheck.md)  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ComponentName** | string |  |
| **Error** | CompilerError |  |
| **PropertyName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreatePreviewImage** | void |  |
| **ProcessCheck** | object |  |

---

### Method Details

#### CreatePreviewImage

**CreatePreviewImage**(**elementImage**: [Image](../../Stimulsoft_Drawing/root/Image.md), **highlightedElementImage**: [Image](../../Stimulsoft_Drawing/root/Image.md), **useScale**: bool): void

**Parameters**

- **elementImage** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **highlightedElementImage** ([Image](../../Stimulsoft_Drawing/root/Image.md))  
- **useScale** (bool)  


---

#### ProcessCheck

**ProcessCheck**(**report**: [StiReport](../../Stimulsoft_Report/root/StiReport.md), **obj**: object): object

**Parameters**

- **report** ([StiReport](../../Stimulsoft_Report/root/StiReport.md))  
- **obj** (object)  

**Returns** object

