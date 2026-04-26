---
title: "StiCheck Class"
---

## StiCheck Class

**Namespace:** `Stimulsoft.Report.Check`

### Inheritance

Implements: ICloneable  

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Element** | object |  |
| **ElementName** | string |  |
| **LongMessage** | string |  |
| **ObjectType** | [StiCheckObjectType](StiCheckObjectType.md) |  |
| **ShortMessage** | string |  |
| **Status** | [StiCheckStatus](StiCheckStatus.md) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** | object |  |
| **CreatePreviewImage** | void |  |
| **ProcessCheck** | object |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object


---

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

