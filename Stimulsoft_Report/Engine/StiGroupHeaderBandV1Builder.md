---
title: "StiGroupHeaderBandV1Builder Class"
---

## StiGroupHeaderBandV1Builder Class

**Namespace:** `Stimulsoft.Report.Engine`

### Inheritance

Inherits from: [StiBandV1Builder](StiBandV1Builder.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetCurrentConditionValue** `static` | object | Returns the current value of a condition of grouping. |
| **GetCurrentSummaryExpressionValue** `static` | object | Returns the current value of a summary expression of grouping. |
| **Prepare** | void | Prepares a component for rendering. |
| **Render** | bool | Renders a component in the specified container with taking generation of events into consideration. The rendered component is returned in the renderedComponent argument. |

---

### Method Details

#### GetCurrentConditionValue `static`

**GetCurrentConditionValue**(**masterGroupHeaderBand**: StiGroupHeaderBand): object

Returns the current value of a condition of grouping.

**Parameters**

- **masterGroupHeaderBand** (StiGroupHeaderBand)  

**Returns** object


---

#### GetCurrentSummaryExpressionValue `static`

**GetCurrentSummaryExpressionValue**(**masterGroupHeaderBand**: StiGroupHeaderBand): object

Returns the current value of a summary expression of grouping.

**Parameters**

- **masterGroupHeaderBand** (StiGroupHeaderBand)  

**Returns** object


---

#### Prepare

**Prepare**(**masterComp**: StiComponent): void

Prepares a component for rendering.

**Parameters**

- **masterComp** (StiComponent)  


---

#### Render

**Render**(**masterComp**: StiComponent, **renderedComponent**: StiComponent, **outContainer**: StiContainer): bool

Renders a component in the specified container with taking generation of events into consideration. The rendered component is returned in the renderedComponent argument.

**Parameters**

- **masterComp** (StiComponent)  
- **renderedComponent** (StiComponent) — A component which is being rendered.  
- **outContainer** (StiContainer) — A container in which rendering will be done.  

**Returns** bool — A value which indicates whether rendering of a component is finished or not.

