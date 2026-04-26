---
title: "StiComponentDesigner Class"
---

## StiComponentDesigner Class

**Namespace:** `Stimulsoft.Report.Components.Design`

Class describes base designer of components.

### Inheritance

Implements: [IStiComponentDesigner](../IStiComponentDesigner.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiComponentDesigner**([IStiDesignerBase](../../Design/IStiDesignerBase.md) designer) | Creates a new designer of the component. |

**StiComponentDesigner**(**designer**: [IStiDesignerBase](../../Design/IStiDesignerBase.md))

Creates a new designer of the component.

**Parameters**

- **designer** ([IStiDesignerBase](../../Design/IStiDesignerBase.md)) — Report designer.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Designer** | [IStiDesignerBase](../../Design/IStiDesignerBase.md) | Report designer. |
| **FirstRun** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateComponent** | StiComponent | Creates a component of the specified type. |
| **Design** | DialogResult | Calls the designer of the component. |
| **GetActionFromPoint** *(+1 overloads)* | [StiAction](../../../Stimulsoft_Report_Check/root/StiAction.md) |  |
| **GetComponentDesigner** `static` *(+1 overloads)* | [StiComponentDesigner](StiComponentDesigner.md) | Returns a designer of the component. |
| **OnDoubleClick** | void | Occurs when user DoubleClick on a the component in the designer. |
| **PointInRect** | [StiAction](../../../Stimulsoft_Report_Check/root/StiAction.md) | Returns the action fits to the position of a point in the specified rectangle. |

---

### Method Details

#### CreateComponent

**CreateComponent**(**componentType**: Type, **region**: [RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)): StiComponent

Creates a component of the specified type.

**Parameters**

- **componentType** (Type) — Type of conmponent being ceated.  
- **region** ([RectangleD](../../../Stimulsoft_Base/Drawing/RectangleD.md)) — The rectangle describes the component size.  

**Returns** StiComponent — Created component.


---

#### Design

**Design**(**component**: StiComponent): DialogResult

Calls the designer of the component.

**Parameters**

- **component** (StiComponent) — Component for edition.  

**Returns** DialogResult — Result of showing the component designer.


---

#### GetActionFromPoint

**GetActionFromPoint**(**x**: double, **y**: double, **component**: StiComponent): [StiAction](../../../Stimulsoft_Report_Check/root/StiAction.md)

**Parameters**

- **x** (double)  
- **y** (double)  
- **component** (StiComponent)  

**Returns** [StiAction](../../../Stimulsoft_Report_Check/root/StiAction.md)

---

**GetActionFromPoint**(**x**: double, **y**: double, **component**: StiComponent, **forGetDesigner**: bool): [StiAction](../../../Stimulsoft_Report_Check/root/StiAction.md)

Returns StiAction for specified component from point.

**Parameters**

- **x** (double) — x coordinate.  
- **y** (double) — y coordinate.  
- **component** (StiComponent) — Component for checking.  
- **forGetDesigner** (bool)  

**Returns** [StiAction](../../../Stimulsoft_Report_Check/root/StiAction.md) — Action for this point.


---

#### GetComponentDesigner `static`

**GetComponentDesigner**(**designer**: [IStiDesignerBase](../../Design/IStiDesignerBase.md), **componentType**: Type): [StiComponentDesigner](StiComponentDesigner.md)

Returns a designer of the component.

**Parameters**

- **designer** ([IStiDesignerBase](../../Design/IStiDesignerBase.md)) — Report designer.  
- **componentType** (Type) — Component type.  

**Returns** [StiComponentDesigner](StiComponentDesigner.md) — Component designer.

---

**GetComponentDesigner**(**designer**: [IStiDesignerBase](../../Design/IStiDesignerBase.md), **componentType**: Type, **guiMode**: [StiGuiMode](../../../Stimulsoft_Base/root/StiGuiMode.md)): [StiComponentDesigner](StiComponentDesigner.md)

Returns a designer of the component.

**Parameters**

- **designer** ([IStiDesignerBase](../../Design/IStiDesignerBase.md)) — Report designer.  
- **componentType** (Type) — Component type.  
- **guiMode** ([StiGuiMode](../../../Stimulsoft_Base/root/StiGuiMode.md))  

**Returns** [StiComponentDesigner](StiComponentDesigner.md) — Component designer.


---

#### OnDoubleClick

**OnDoubleClick**(**sender**: StiComponent): void

Occurs when user DoubleClick on a the component in the designer.

**Parameters**

- **sender** (StiComponent) — Component on what DoubleClick occured.  


---

#### PointInRect

**PointInRect**(**designer**: [IStiDesignerBase](../../Design/IStiDesignerBase.md), **comp**: StiComponent, **x**: int, **y**: int): [StiAction](../../../Stimulsoft_Report_Check/root/StiAction.md)

Returns the action fits to the position of a point in the specified rectangle.

**Parameters**

- **designer** ([IStiDesignerBase](../../Design/IStiDesignerBase.md))  
- **comp** (StiComponent)  
- **x** (int) — X point.  
- **y** (int) — Y point.  

**Returns** [StiAction](../../../Stimulsoft_Report_Check/root/StiAction.md) — Action.

