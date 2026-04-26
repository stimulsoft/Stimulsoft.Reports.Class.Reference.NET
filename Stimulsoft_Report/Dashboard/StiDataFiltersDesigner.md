---
title: "StiDataFiltersDesigner Class"
---

## StiDataFiltersDesigner Class

**Namespace:** `Stimulsoft.Report.Dashboard`

This class describes the designer of the data filter for elements.

### Inheritance

Inherits from: [StiComponentDesigner](../Components/Design/StiComponentDesigner.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDataFiltersDesigner**([IStiDesignerBase](../Design/IStiDesignerBase.md) designer) |  |

**StiDataFiltersDesigner**(**designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md))

**Parameters**

- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataFiltersDesigner** `static` | [StiComponentDesigner](../Components/Design/StiComponentDesigner.md) | Returns a designer of the component. |
| **GetUserFiltersDesigner** `static` | [StiComponentDesigner](../Components/Design/StiComponentDesigner.md) | Returns a designer of the component. |

---

### Method Details

#### GetDataFiltersDesigner `static`

**GetDataFiltersDesigner**(**designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md), **componentType**: Type): [StiComponentDesigner](../Components/Design/StiComponentDesigner.md)

Returns a designer of the component.

**Parameters**

- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md)) — Report designer.  
- **componentType** (Type) — Component type.  

**Returns** [StiComponentDesigner](../Components/Design/StiComponentDesigner.md) — Component designer.


---

#### GetUserFiltersDesigner `static`

**GetUserFiltersDesigner**(**designer**: [IStiDesignerBase](../Design/IStiDesignerBase.md), **componentType**: Type): [StiComponentDesigner](../Components/Design/StiComponentDesigner.md)

Returns a designer of the component.

**Parameters**

- **designer** ([IStiDesignerBase](../Design/IStiDesignerBase.md)) — Report designer.  
- **componentType** (Type) — Component type.  

**Returns** [StiComponentDesigner](../Components/Design/StiComponentDesigner.md) — Component designer.

