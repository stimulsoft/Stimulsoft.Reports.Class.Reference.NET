---
title: "StiElementInteractionDesigner Class"
---

## StiElementInteractionDesigner Class

**Namespace:** `Stimulsoft.Report.Dashboard`

This class describes the designer of the element interaction.

### Inheritance

Inherits from: [StiComponentDesigner](../Components/Design/StiComponentDesigner.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiElementInteractionDesigner**([IStiDesignerBase](../Design/IStiDesignerBase.md) designer) |  |

**StiElementInteractionDesigner**(**designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md))

**Parameters**

- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDesigner** `static` | [StiComponentDesigner](../Components/Design/StiComponentDesigner.md) | Returns a designer of the component. |

---

### Method Details

#### GetDesigner `static`

**GetDesigner**(**designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md), **componentType**: Type): [StiComponentDesigner](../Components/Design/StiComponentDesigner.md)

Returns a designer of the component.

**Parameters**

- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md)) — Report designer.  
- **componentType** (Type) — Component type.  

**Returns** [StiComponentDesigner](../Components/Design/StiComponentDesigner.md) — Component designer.

