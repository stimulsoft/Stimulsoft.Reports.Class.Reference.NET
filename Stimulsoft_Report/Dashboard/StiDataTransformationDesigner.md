---
title: "StiDataTransformationDesigner Class"
---

## StiDataTransformationDesigner Class

**Namespace:** `Stimulsoft.Report.Dashboard`

This class describes the designer of the data transformation for elements.

### Inheritance

Inherits from: [StiComponentDesigner](../Components/Design/StiComponentDesigner.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataTransformationDesigner**([IStiDesignerBase](../Design/IStiDesignerBase.md) designer) |  |

**StiDataTransformationDesigner**(**designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md))

**Parameters**

- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetTransformationDesigner** `static` | [StiComponentDesigner](../Components/Design/StiComponentDesigner.md) | Returns a designer of the component. |

---

### Method Details

#### GetTransformationDesigner `static`

**GetTransformationDesigner**(**designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md), **componentType**: Type): [StiComponentDesigner](../Components/Design/StiComponentDesigner.md)

Returns a designer of the component.

**Parameters**

- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md)) — Report designer.  
- **componentType** (Type) — Component type.  

**Returns** [StiComponentDesigner](../Components/Design/StiComponentDesigner.md) — Component designer.

