---
title: "StiV2Builder Class"
---

## StiV2Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiBuilder](StiBuilder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetBuilder** `static` | [StiV2Builder](StiV2Builder.md) |  |
| **InternalRender** | StiComponent | Renders a component. Does not call events of a component while rendering. |
| **Prepare** | void | Prepares a component for rendering. |
| **Render** | StiComponent | Renders a component with calling an event. A method is used with InternalRender for the component rendering. |
| **SetReportVariables** | void | Sets system variables which are specific for the specified component. |
| **UnPrepare** | void | Clears a component for rendering. |

---

### Method Details

#### GetBuilder `static`

**GetBuilder**(**componentType**: Type): [StiV2Builder](StiV2Builder.md)

**Parameters**

- **componentType** (Type)  

**Returns** [StiV2Builder](StiV2Builder.md)


---

#### InternalRender

**InternalRender**(**masterComp**: StiComponent): StiComponent

Renders a component. Does not call events of a component while rendering.

**Parameters**

- **masterComp** (StiComponent)  

**Returns** StiComponent


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

Prepares a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  


---

#### Render

**Render**(**masterComp**: StiComponent): StiComponent

Renders a component with calling an event. A method is used with InternalRender for the component rendering.

**Parameters**

- **masterComp** (StiComponent)  

**Returns** StiComponent


---

#### SetReportVariables

**SetReportVariables**(**masterComp**: StiComponent): void

Sets system variables which are specific for the specified component.

**Parameters**

- **masterComp** (StiComponent)  


---

#### UnPrepare

**UnPrepare**(**masterComp**: StiComponent): void

Clears a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  

