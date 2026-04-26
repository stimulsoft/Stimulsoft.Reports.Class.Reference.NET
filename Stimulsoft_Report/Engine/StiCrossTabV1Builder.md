---
title: "StiCrossTabV1Builder Class"
---

## StiCrossTabV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiContainerV1Builder](StiContainerV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Prepare** | void | Prepares a component for rendering. |
| **Render** | bool | Renders a component in the specified container with taking events generation into consideration. A rendered component is returned in the renderedComponent argument. |

---

### Method Details

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
- **renderedComponent** (StiComponent) — A component what is being rendered.  
- **outContainer** (StiContainer) — A container in what rendering will be done.  

**Returns** bool — A value that indicates whether rendering of a component is finished or not.

