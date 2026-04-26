---
title: "StiComponentV1Builder Class"
---

## StiComponentV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiV1Builder](StiV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **InternalRender** | bool | Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument. |
| **Prepare** | void | Prepares a component for rendering. |
| **Render** *(+1 overloads)* | bool | Renders a component in the specified container with taking events generation into consideration. A rendered component is returned in the renderedComponent argument. |
| **UnPrepare** | void | Clears a component after rendering. |

---

### Method Details

#### InternalRender

**InternalRender**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container without taking generation of BeforePrintEvent and AfterPrintEvent into consideration and without taking Conditions into consideration. A rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — Rendered component.  
- **outContainer** (StiContainer) — Panel in which rendering will be done.  

**Returns** bool — Is rendering finished or not.


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

Prepares a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  


---

#### Render

**Render**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container with taking events generation into consideration. A rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A component which is being rendered.  
- **outContainer** (StiContainer) — A container in which rendering will be done.  

**Returns** bool — A value which indicates whether rendering of the component is finished or not.

---

**Render**(**masterComp**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container with taking events generation into consideration.

**Parameters**

- **masterComp** (StiComponent)  
- **outContainer** (StiContainer) — A Panel in which rendering will be done.  

**Returns** bool — A value which indicates whether rendering is finished or not.


---

#### UnPrepare

**UnPrepare**(**masterComp**: StiComponent): void

Clears a component after rendering.

**Parameters**

- **masterComp** (StiComponent)  

